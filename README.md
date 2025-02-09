## Introduction

This extension provides two nodes to use with my experimental ip-adapter finetune for NoobAI-XL. [Here](https://github.com/vahlok-alunmid/reForge-preprocessor_bigG_448) is the counterpart extension for Reforge WebUI.

- Extend Clip Vision Input Size: Interpolate PE for the loaded clip-v model to make it able to accept images of a different size. One can use it to extend the original clip-v's input size from 224. (My finetune was trained on 448.)
- IPAdapter Advanced (Clip Size Aware): A modified version of the original ip-adapter node (credits to the author of [ComfyUI-IPAdapter-Plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)), instead of using a pre-defined value for image preprocessing, resizes the input to the actual clip-v input size. 
