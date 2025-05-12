# SD webui txt2img script, adjusted for Forge

This script is updated for Forge -> https://github.com/lllyasviel/stable-diffusion-webui-forge

Im using the AMD version of https://github.com/lshqqytiger/stable-diffusion-webui-amdgpu-forge

Install via Forge-UI, Extensions, URL for extension's git repository and Github-adress, then reload the webui to access the script in the txt2img section.

Drag and drop or upload image files to modify a prompt and override default settings to modify images.

This file is specifically meant for a batch process of image files with metadata applicable to the txt2img section
of the webui. Allows user to easily use the hires fix upscale to get better images instead of img2img upscale.

overall features include:
  - upload multiple files to process
  - add/delete tags from a positive prompt
  - override default generation settings with image metadata

### script interface
![alt text](https://github.com/Nekuro25/SD-webui-txt2img-script/blob/main/ui.png?raw=true)

source references this discussion -> https://github.com/AUTOMATIC1111/stable-diffusion-webui/discussions/4938

made this script through feature request issue #7462 -> https://github.com/AUTOMATIC1111/stable-diffusion-webui/issues/7462

### known issues
Forge special flags like latent_modifier_enabled: True are not supported yet. 