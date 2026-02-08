# Stable Diffusion (PyTorch)

An implementation of a Stable Diffusion–style text-to-image pipeline built in PyTorch.

The project recreates the core components of latent diffusion models:

- CLIP text encoder for prompt embeddings  
- VAE encoder/decoder for latent image representation  
- U-Net diffusion model  
- DDPM sampler for iterative denoising  
- Support for text-to-image and image-to-image generation  


---

## Features

- Text → image generation from prompts  
- Image → image transformation with strength control  
- Classifier-free guidance (CFG)  
- Reproducible sampling with seeds  
- Modular model design  

---z

## Project Structure
- clip.py — text encoder
- encoder.py — VAE encoder
- decoder.py — VAE decoder
- diffusion.py — UNet + sampling logic
- ddpm.py — DDPM sampler
- pipeline.py — generation pipeline


## Requirements


- torch
- numpy
- tqdm
- transformers
- lightning
- pillow

---

## Installation

```bash
pip install torch numpy tqdm pillow transformers




