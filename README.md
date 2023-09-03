# Texture Atlas Compression Based on Repeated Content Removal

## Abstract
Optimizing the memory footprint of 3D models can have a major impact on the user experiences during real-time rendering and streaming visualization, where the major memory overhead lies in the high-resolution texture data. In this work, we propose a robust and automatic pipeline to content-aware, lossy compression for texture atlas. The design of our solution lies in two observations: 1) mapping multiple surface patches to the same texture region is seamlessly compatible with the standard rendering pipeline, requiring no decompression before any usage; 2) a texture image has background regions and salient structural features, which can be handled separately to achieve a high compression rate. Accordingly, our method contains \revise{joint operations of image segmentation, re-meshing, UV unwrapping, and texture baking.} To evaluate the efficacy of our approach, we batch-processed a dataset containing 100 models collected online. On average, our method achieves a texture atlas compression ratio of 81.41\% with an averaged PSNR and MS-SSIM scores of 40.90 and 0.98, a marginal error in visual appearance. 

## Code and Dataset
To be updated.

## License
To be updated.
