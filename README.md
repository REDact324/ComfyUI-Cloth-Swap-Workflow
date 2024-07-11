# ComfyUI-Cloth-Swap-Workflow
[ComfyUI](https://github.com/comfyanonymous/ComfyUI) workflow for cloth-swapping. 

Utilize SAM models to segment the clothing in model image, and IP-Adapter for image-to-image conditioning.

![Screenshot of overall workflow](./workflow.png)

### Some results
<img src="./samples/zly/zly3.jpeg" width="25%"> <img src="./samples/zly/cloth3.png" width="25%"> <img src="./samples/zly/out3.png" width="25%">

<img src="./samples/zly/zly2.jpg" width="25%"> <img src="./samples/zly/cloth2.png" width="25%"> <img src="./samples/zly/out2.png" width="25%">

<img src="./samples/image_2/model-2.jpg" width="25%"> <img src="./samples/image_2/cloth-2.jpg" width="25%"> <img src="./samples/image_2/out-2.png" width="25%">

## Required Costum Nodes
- [ComfyUI_IPAdapter_plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
- [segment anything](https://github.com/storyicon/comfyui_segment_anything)
- [ComfyUI Impact Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack)
- [comfyui-art-venture](https://github.com/sipherxyz/comfyui-art-venture)

## Model Used
- [AlbedobaseXL v2.1](https://civitai.com/models/140737/albedobase-xl) for inpainting
- [epiCPhotoGasm Ultimate Fidelity](https://civitai.com/models/132632?modelVersionId=429454) for detail refining

Please share any models you found with better results🤗

## Limitation
- The input clothing style should be similar to the input character clothing.
- The clothing with ornate design may look different on the person after swapping.
- LoRAs and ControlNets are not specifically trained according to any fashion brand. (If you tried any well-performed ones, feel free to share!)

