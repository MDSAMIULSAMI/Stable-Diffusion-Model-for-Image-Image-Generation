# Stable Diffusion Model for Image to Image Generation

This repository contains a Kaggle notebook implementation of a lightweight Stable Diffusion model for image-to-image generation using the Hugging Face Diffusers library. The notebook demonstrates how to generate stylized images based on input images and text prompts efficiently using a pre-trained pipeline.

Features

	•	Image-to-Image Transformation: Generate new images by applying creative modifications to input images.
	•	Pre-trained Model: Uses the lightweight runwayml/stable-diffusion-v1-5 model from Hugging Face.
	•	Kaggle Notebook Compatible: Optimized for GPU usage on Kaggle.
	•	Customizable Parameters: Modify strength and guidance_scale to control output.

Requirements

	•	pip install diffusers==0.17.0 transformers accelerate torch torchvision pillow

The Kaggle notebook setup automatically installs these dependencies.
