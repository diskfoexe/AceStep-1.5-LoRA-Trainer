# AceStep 1.5 LoRA Trainer (Standalone)

This repository contains the core logic for training LoRA adapters on the AceStep 1.5 DiT model. 
Designed for efficient training in Google Colab using QLoRA.

## Features
- **Auto-Labeling**: Uses Qwen3-Embedding for audio captioning.
- **Fast Preprocessing**: Encodes audio to tensors once to save VRAM.
- **QLoRA Support**: Train on T4 GPUs with 4-bit/8-bit quantization.

## Usage in Colab
1. Clone this repo: `!git clone <your-repo-url>`
2. Install deps: `!pip install -r requirements.txt`
3. Upload audio to `my_audio/` folder.
4. Run the training script.
