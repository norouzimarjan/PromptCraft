# PromptCraft

A powerful and user-friendly web-based image generator leveraging [Stable Diffusion 1.5](https://huggingface.co/runwayml/stable-diffusion-v1-5) and [Stable Diffusion XL (SDXL)](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0), built with 🤗 Diffusers and Gradio for seamless, interactive prompt-to-image generation.

This app allows users to input a text prompt and generate beautiful images in various styles such as cyberpunk, watercolor, anime, and photo-realistic. It also supports customization through CFG scale and selectable image resolutions.

---

##  Features

-  Choose between **Stable Diffusion v1.5** and **SDXL**.
-  Select from multiple artistic styles.
-  Customize CFG scale and image resolution.
-  Optional negative prompt to exclude unwanted elements.
-  View previously generated images in a scrollable gallery.
-  Built with Gradio for fast and interactive demos.

---

##  Demo Preview

### Live Demo (GIF)

[![demo-gif.gif](https://i.postimg.cc/kg43XpZw/demo-gif.gif)](https://postimg.cc/N5WPdpQr)

### Screenshot

![demo_Screenshot](https://github.com/user-attachments/assets/4cd26f2e-bd31-4c05-b996-1710f5191db4)


---

##  Requirements

Make sure you have the following installed:

- Python 3.9+
- CUDA-compatible GPU (for optimal performance)
- torch
- diffusers
- accelerate
- transformers
- gradio

You can install them using pip:

```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install diffusers accelerate transformers gradio
```

--- 
##  Example Prompts

- `a futuristic city skyline at night`
- `a cat wearing a space suit, cyberpunk style`
- `watercolor painting of a fantasy forest`
- `photo-realistic portrait of a young woman in the snow`
- `anime-style dragon flying over mountains`
---
##  Notes

- **CFG Scale** controls how strictly the model follows your text prompt. Values between `6` and `9` usually work best.
- **SDXL** produces higher-quality images but requires more GPU memory.
- For more detailed images, especially in SDXL, choose larger image sizes like `768x512`.
- The history panel on the right lets you keep track of previously generated images.

---

##  Credits

Created with 💜 as part of a Computer Vision course project.

- Models:
  - [Stable Diffusion v1.5 – RunwayML](https://huggingface.co/runwayml/stable-diffusion-v1-5)
  - [Stable Diffusion XL – StabilityAI](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)

- UI Framework:
  - [Gradio](https://gradio.app/)

