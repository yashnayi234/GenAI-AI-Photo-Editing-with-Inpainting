# GenAI-AI-Photo-Editing-with-Inpainting

## 🖼️ AI Photo Editing with SAM and Diffusion Inpainting

This project is a fun and creative AI-powered image editing tool that lets you **change the background or the subject of any image** using simple clicks and text prompts. Built using the **Segment Anything Model (SAM)** by Meta AI and Hugging Face's **Diffusion Inpainting**, the app combines cutting-edge segmentation and generative models for seamless visual manipulation.

## 🚀 Features

- ✅ Upload an image and click to select the subject
- 🪄 Automatically generate a precise mask using SAM
- 🎨 Replace the background with a custom AI-generated scene via text prompt
- 🔄 Or swap the subject while keeping the background
- ⚙️ Modify parameters like guidance scale and random seed for fine control
- 💻 Try it interactively using the integrated Gradio UI

## 🧠 Tech Stack

- 🤖 **Segment Anything Model (SAM)** – for subject segmentation
- 🌈 **Diffusers AutoPipelineForInpainting** – for background/subject inpainting using text prompts
- 🎛️ **Gradio** – for building the interactive UI
- ⚡ **PyTorch** – for GPU-accelerated deep learning
- 🐍 Jupyter Notebook – for development & experimentation

## 🛠️ How It Works

1. **Upload an Image** – Choose your photo.
2. **Click on the Subject** – Use point-based selection with SAM to generate a mask.
3. **Edit with Text** – Describe the new background or subject.
4. **Generate** – The inpainting model fills in the masked region with your prompt.
5. **Download the Result** – Or run further edits!

## 📸 Examples

| Original | Mask | Edited |
|---------|------|--------|
| <img width="379" alt="Screenshot 2025-04-01 at 1 26 06 PM" src="https://github.com/user-attachments/assets/fb52df50-ebfd-4fd8-a503-b3f6c2708718" />| <img width="372" alt="Screenshot 2025-04-01 at 1 26 20 PM" src="https://github.com/user-attachments/assets/de2a35d2-bff2-4609-b73c-be177804730a" /> | <img width="372" alt="Screenshot 2025-04-01 at 1 26 28 PM" src="https://github.com/user-attachments/assets/1d37ed59-bfa6-4daf-9862-ce03d392877d" /> |

## 📁 Project Structure
📦 AI-Photo-Editor 
  ├── starter.ipynb 
  ├── app.py
  ├── img
  ├── README.md 
  └── img
## ✨ Tips to Explore

- Use **prompt engineering** to generate highly specific scenes.
- Try different **Classifier-Free Guidance Scale** values for creative variations.
- **Iterative editing**: run the output through the app again for complex edits.

## 🧪 Requirements

Install all dependencies (if not using the pre-configured environment):

```bash
pip install torch torchvision
pip install git+https://github.com/facebookresearch/segment-anything.git
pip install diffusers transformers accelerate
pip install gradio
```


📎 Credits
### Meta AI - Segment Anything
### Hugging Face Diffusers
### Gradio for the easy-to-use UI
