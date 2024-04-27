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
- **GPU Requirement**: Due to the intensive computational requirements, ensure your setup includes a GPU. If you don't have a GPU on your personal laptop: Find an alternative computer with a GPU.
- **webui-user.bat was named as webui-user, so took some time to figure out that**
- **It may take some time to set up and fine-tune the parameters for generating images using Stable Diffusion Inpainting**.
### Text Prompts used:
- A subtle metallic sheen that suggests sophistication and high-quality, suitable for high-end grooming products
- A patterned background with a retro feel, using colors and designs from the mid-20th century for a nostalgic appeal
- A vintage-style background with elements like classic barber poles, old-fashioned razors, and brushes, invoking a sense of tradition and quality in grooming.
- A warm wooden plank texture that gives a masculine and earthy vibe, suitable for products targeting men
- A sophisticated combination of leather textures and polished wood, suggesting the interior of a high-end barbershop from the past, where attention to detail and quality are paramount.
- A background with a luxurious velvet texture in a deep burgundy or royal blue to contrast and elevate the ring's features
- A subtle bokeh light effect in gold and silver tones, reminiscent of elegant evening events, to add a magical and high-end atmosphere
- A soft-focus image of delicate white flowers or rose petals that adds a romantic and refined touch to the product display
- Smooth silk fabric in a gentle wave pattern, conveying a sense of softness and luxury that pairs well with fine jewelry
- A classic white marble background with subtle gray veining, a timeless and elegant backdrop that conveys sophistication
- A wash of pastel watercolor hues that blend seamlessly, offering a dreamy and artistic setting for the ring
- A dark, starry sky background that suggests the ring is as timeless and endless as the night sky.
- A smooth gradient from dark brown to light beige, mirroring the color palette of the bottle for a cohesive look
- A high-quality satin fabric background in a solid, neutral color like charcoal or cream, adding a subtle texture
- The look of frosted glass to convey a feeling of freshness and cleanliness, with a blur effect to keep the focus on the product
- A light wooden table with fine grain details providing a natural and clean setting without drawing attention away from the product
- A canvas texture in a single dark tone that complements the color of the liquid and the label of the bottle
- A matte finish surface in a deep brown color that matches the bottle, offering a sophisticated and modern vibe
- A background of high-quality linen fabric in a muted color that adds a hint of sophistication
- A deep, dark brown wooden surface with a subtle sheen, reflecting the bottle's base. The lighting is from above, casting a soft, realistic shadow that trails off gently
- A darkened room backdrop with a spotlight effect that highlights the aftershave bottle, creating a natural shadow to one side and a muted reflection beneath, simulating a photographic studio setting.
- A background that mimics a high-end marble, with veins of dark gray on black, polished to show the bottle's reflection and shadow, conveying sophistication and class
- A luxurious black marble base with subtle white veining, polished to perfection to allow for a muted reflection of the shoes, exuding exclusivity.
- A simple yet classy matte black surface that provides a soft reflection, ensuring the shoes remain the center of focus against the subtle backdrop
-  minimalist concrete floor with a glossy seal, providing a modern industrial look that contrasts with the classic style of the shoes while offering a faint reflection.
-  A smooth, jet-black onyx surface with a mirror finish for a striking reflection that enhances the contours and craftsmanship of the shoes.
-  A softly illuminated black marble surface that reflects the vintage camera, with a diffused light creating a clear but soft-edged reflection beneath the camera
-  A dark anthracite floor with a lacquered finish, reflecting the vintage camera with a soft glow, and ensuring the camera appears anchored and three-dimensional.
-  An image of a vintage camera on a reflective obsidian surface under a gentle overhead light, casting a realistic shadow and reflection that looks naturally integrated
-  A vintage camera set against a muted charcoal background with a glass-like polished finish, offering a subtle and true-to-life reflection that mimics a high-end product showcase
-  A smooth, dark, metallic surface with a slight patina that reflects the vintage camera, blending the reflection seamlessly with the surrounding area
-  A matte black surface that mimics the look of a high-end, polished stone, reflecting the shaving soap's packaging, and providing a simple yet elegant contrast.
-  Design a background that suggests a luxurious bathroom countertop, with a reflective marble surface in a dark hue, on which the shaving soap sits, reflecting its shape and details
These were some of the prompts used and I took help of chatgpt to frame them in proper grammar so I can get maximum generation out of the stable diffusion model 



