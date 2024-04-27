# Stable Diffusion Inpainting WEBUI

This repository contains all the necessary files for the Marble AI's internship assignment.

## Project Title
**Stable Diffusion Inpainting WEBUI**

## Setup Instructions
Follow these steps to set up and run the project:

### Prerequisites
- Python 3.10.6
- Git

### Installation
 Clone the Stable Diffusion Inpainting WEBUI repository:
- GitHub repository: [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

### Running the Application
1. Navigate to the `stable-diffusion-webui` folder.
2. Execute `webui-user.bat` to start the application.
3. The application will download all necessary libraries, including `torch`.

## Using the WEBUI
- **Inpainting with img2img**: 
- Navigate to the img2img generation section and select `inpaint`.
- **Sampling Method**: Euler a
- **Sampling Steps**: Set to 85
- **Inpainting Type**: Soft Inpainting
- Use masking techniques.
- **CFG Scale**: Set at 6
- **Denoising Strength**: Set at 0.99 (especially useful when adding backgrounds to plain white areas)

### Challenges Faced 
- **GPU Requirement**: Due to the intensive computational requirements, ensure your setup includes a GPU. If you don't have a GPU on your personal laptop:
- Find an alternative computer with a GPU.
-**webui-user.bat was named as webui-user, so took some time to figure out that**
-**It may take some time to set up and fine-tune the parameters for generating images using Stable Diffusion Inpainting**.



