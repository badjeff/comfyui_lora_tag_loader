LoRA Tag Loader for ComfyUI
=======
### A <a href="https://github.com/comfyanonymous/ComfyUI" >ComfyUI</a> custom node to read LoRA tag(s) from text and load it into checkpoint model.


## **Examples:**
  
- The custom node shall extract "_**&lt;lora:CroissantStyle:0.8&gt;**_" from positive prompt and output a merged checkpoint model to sampler. The lora tag(s) shall be stripped from output STRING, which can be forwarded to CLIP Text Encoder.

<img src="https://github.com/badjeff/comfyui_lora_tag_loader/blob/master/workflows/workflow_sample.png" width="720">

## **Install:**
To install, drop the "_**comfyui_lora_tag_loader**_" folder into the "_**...\ComfyUI\ComfyUI\custom_nodes**_" directory and restart UI.
