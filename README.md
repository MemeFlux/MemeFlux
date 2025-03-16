# MemeFlux: Multi-Instance Diffusion for Single Image to 3D Scene Generation

## 🏠 [Project Page](https://your-project-page.com) | [Paper](https://arxiv.org/abs/2412.03558) | [Model](https://huggingface.co/YourOrg/MemeFlux-3D) | [Online Demo](https://huggingface.co/spaces/YourOrg/MemeFlux-3D)

![teaser](assets/doc/teaser.png)

MemeFlux is a 3D generative model designed to create compositional 3D scenes from a single image. Unlike existing approaches that rely on reconstruction, retrieval, or multi-stage object generation, MemeFlux extends pre-trained image-to-3D object generation models into multi-instance diffusion models. This allows for the simultaneous creation of multiple, high-quality 3D elements with accurate spatial relationships and robust generalizability.

## 🌟 Key Features

*   **High Quality:** Generates diverse 3D scenes with intricate and detailed shapes.
*   **Broad Generalizability:** Successfully adapts to real-world and stylized image inputs, even when trained primarily on synthetic data.
*   **Efficient Generation:** Creates 3D scenes from segmented instance images, avoiding complex steps or time-consuming per-scene optimizations.

## 🔥 Recent Updates

*   [2025-03] Released model weights, Gradio demo, and inference scripts for MemeFlux-3D.

## 🔨 Installation

First, clone the repository:

