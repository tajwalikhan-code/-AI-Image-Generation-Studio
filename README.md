# 🎨 AI Image Generation Studio
### Multimodal Image Generation using Stable Diffusion v1.5

> Generate high-quality AI images from natural language prompts using Stable Diffusion, Hugging Face Diffusers, and Google Colab — completely free with GPU acceleration.

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Stable Diffusion](https://img.shields.io/badge/Stable_Diffusion-v1.5-purple)
![Diffusers](https://img.shields.io/badge/HuggingFace-Diffusers-yellow)
![Google Colab](https://img.shields.io/badge/Google-Colab-orange?logo=googlecolab)
![GPU](https://img.shields.io/badge/T4-GPU-success)
![License](https://img.shields.io/badge/License-MIT-blue)

</p>

---

# 📖 Project Overview

**AI Image Generation Studio** is a Generative AI application that transforms natural language prompts into high-quality images using **Stable Diffusion v1.5**.

The project is built entirely with **free and open-source technologies**, allowing users to generate professional AI artwork without requiring paid APIs.

It demonstrates the complete image generation workflow, from prompt validation and GPU inference to safety filtering, image verification, and interactive visualization.

Developed as part of the **Decode Labs Generative AI Internship**, this project also follows industry best practices for modular AI application development.

---

# ✨ Features

## 🖼 AI Image Generation

Generate images from simple text prompts.

Example:

> "A futuristic smart city at sunset"

↓

AI Generated Image

---

## 🎯 Prompt Engineering

Generate images using natural language descriptions.

Supports:

- Detailed prompts
- Creative prompts
- Cinematic prompts
- Realistic prompts
- Artistic prompts

---

## 🖥 Interactive Image Studio

Simple user interface built with **ipywidgets**

Users can:

- Enter prompt
- Select aspect ratio
- Generate image
- View results instantly

---

## 📐 Multiple Aspect Ratios

Supports

- Square (512×512)
- Portrait (512×768)
- Landscape (768×512)

---

## ⚙ Adjustable Generation Settings

Customize:

- Number of images
- Random seed
- Guidance Scale
- Inference Steps
- Aspect Ratio

---

## 🛡 Built-in Safety System

Includes two-layer safety protection.

### Input Safety

✔ Prompt validation

✔ Keyword filtering

✔ Empty prompt detection

✔ Maximum prompt length validation

---

### Output Safety

✔ NSFW Image Detection

✔ Unsafe image rejection

✔ Secure image generation

---

## 📂 Automatic Image Saving

Generated images are automatically stored inside

```
generated_images/
```

Each image is saved with a unique filename.

---

## 🔍 Image Integrity Verification

Before saving,

every generated image is checked to ensure

✔ File exists

✔ Image is valid

✔ No corruption occurred

---

## 🚀 GPU Optimized

Uses

- CUDA
- Float16 Precision
- Attention Slicing

to reduce memory usage while improving performance.

---

# 🏗 Project Workflow

```
User Prompt
      │
      ▼
Prompt Validation
      │
      ▼
Stable Diffusion Pipeline
      │
      ▼
GPU Image Generation
      │
      ▼
NSFW Safety Check
      │
      ▼
Image Integrity Verification
      │
      ▼
Save Image
      │
      ▼
Display Result
```

---

# 📂 Project Structure

```
AI_Image_Generation_Studio/

│

├── Project3_Image_Generation_Studio.ipynb

├── generated_images/

├── assets/

├── screenshots/

├── README.md

├── requirements.txt

└── LICENSE

```

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Stable Diffusion v1.5 | AI Image Generation |
| Hugging Face Diffusers | Diffusion Framework |
| Transformers | Model Loading |
| Accelerate | GPU Optimization |
| PyTorch | Deep Learning |
| CUDA | GPU Acceleration |
| Pillow | Image Processing |
| ipywidgets | Interactive UI |
| Google Colab | Development Platform |

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/AI_Image_Generation_Studio.git

cd AI_Image_Generation_Studio
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶ Running the Project

Open the notebook in **Google Colab**.

Enable GPU

```
Runtime

↓

Change Runtime Type

↓

T4 GPU

↓

Run All Cells
```

The application will automatically load Stable Diffusion and allow image generation.

---

# 💻 Example Prompt

```
A futuristic Pakistani smart city at sunset,
ultra realistic,
8K,
cinematic lighting,
highly detailed,
professional photography
```

---

# 📸 Example Output

| Prompt | Generated Image |
|---------|----------------|
| Futuristic City | screenshots/output1.png |
| Mountain Landscape | screenshots/output2.png |
| Cyberpunk Street | screenshots/output3.png |

*(Replace with your own screenshots.)*

---

# ⚙ Adjustable Parameters

| Parameter | Description |
|------------|-------------|
| Prompt | Image description |
| Aspect Ratio | Image dimensions |
| Guidance Scale | Prompt adherence |
| Seed | Reproducible generation |
| Steps | Image quality |
| Number of Images | Batch generation |

---

# 📚 Learning Outcomes

This project helped me gain practical experience in:

- Generative AI
- Stable Diffusion
- Diffusion Models
- Hugging Face Diffusers
- Prompt Engineering
- GPU Computing
- CUDA Optimization
- Image Processing
- Safety AI
- AI Deployment
- Python Programming

---

# 🚀 Future Improvements

- Image-to-Image Generation
- Negative Prompt Support
- Style Presets
- Batch Image Generation
- Download All Images
- AI Upscaling
- LoRA Support
- SDXL Integration
- Background Removal
- Prompt History
- Image Gallery
- Hugging Face Deployment
- Streamlit Web App

---

# 🎯 Skills Demonstrated

- Python Programming
- Generative AI
- Stable Diffusion
- Prompt Engineering
- Computer Vision
- Image Processing
- GPU Computing
- Deep Learning
- Hugging Face
- AI Application Development

---

# 👨‍💻 Developer

## Taj Wali Khan

**Artificial Intelligence Enthusiast | Python Developer | AI Automation for Business | BCS AI Student at Abdul Wali Khan University Mardan | Exploring Emerging Technologies**

---

# 🌐 Connect With Me

## LinkedIn

www.linkedin.com/in/taj-wali-khan-03a7693aa

## GitHub

https://github.com/tajwalikhan-code

---

# 🙏 Acknowledgements

Special thanks to:

- Decode Labs
- Hugging Face
- Stability AI
- Google Colab
- PyTorch Team
- Open Source AI Community

for providing amazing learning resources and open-source technologies.

---

# 📄 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project helpful,

⭐ Star this repository

🍴 Fork it

💬 Share your feedback

---

# 💡 Quote

> **"Every great AI-generated image begins with a single idea—and the right prompt brings it to life."**

---

<p align="center">

### ⭐ If you like this project, don't forget to Star this Repository ⭐

Made with ❤️ by **Taj Wali Khan**

</p>
