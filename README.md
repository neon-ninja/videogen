# Simple video generation frontends

### Running the backends

### Hunyuan

`docker run -d --gpus all -p 8188:8188 -p 3000:3000 --name comfy saladtechnologies/comfyui:comfy0.3.12-api1.8.1-hunyuanvideo-fp16`

### Wan

`git clone https://github.com/replicate/cog-wan-2.1.git`  
`cog build`  
`docker run --name wan -d -p 5000:5000 --gpus all cog-wan-21`  

### LTXV

`docker run -d -p 5001:5000 --gpus=all r8.im/lightricks/ltx-video@sha256:8c47da666861d081eeb4d1261853087de23923a268a69b63febdf5dc1dee08e4`
