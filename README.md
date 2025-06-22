# Text-to-Image Generation with Stable Diffusion

This project demonstrates text-to-image generation using Stable Diffusion and Hugging Face's Diffusers library, implemented in a Google Colab notebook. The notebook leverages PyTorch for GPU-accelerated inference, making it accessible for users with free Colab resources.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Running the Notebook](#running-the-notebook)
- [Sample Outputs](#sample-outputs)
- [Contributing](#contributing)

## Project Overview

This repository contains a Google Colab notebook (`Image_generation_using_LLM_with_hugging_face.ipynb`) that showcases how to generate high-quality images from text prompts using Stable Diffusion. The notebook is designed to run seamlessly in Colab with GPU support.

## Features
- Text-to-image generation with Stable Diffusion.
- GPU acceleration via PyTorch in Google Colab.
- Clear documentation and example prompts.
- Sample output images included.

## Running the Notebook

To run the notebook, follow these steps:

1. **Open the notebook in Google Colab:**
   - [Image_generation_using_LLM_with_hugging_face.ipynb](#)

2. **Enable GPU acceleration:**
   - Go to `Runtime > Change runtime type`.
   - Select `GPU` (e.g., T4 GPU) and save.

3. **Run all cells sequentially:**
   - This will install dependencies and generate images.

4. **Modify the text prompt to create custom images:**
   - Example: `"A futuristic cityscape at sunset, digital art style"`

**Note:** Dependencies are installed automatically via `!pip install` commands in the notebook.

## Sample Outputs
![Sample Image 1](outputs/HFImg1.png)
*Caption for Sample Image 1*

![Sample Image 2](outputs/HFImg2.png)
*Caption for Sample Image 2*

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

