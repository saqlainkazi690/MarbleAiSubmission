# MarbleAiSubmission
This repository contains all the required files for Marble AI's internship assignment 
Project Title : Stable Diffusion Inpainting WEBUI
Setup:
Installed PYthon 3.10.6
Installed Git
Downloaded the stable diffusion Inpainting webui repository by running: "git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git"
The github link of the stable diffusion webui Automatic1111 is "https://github.com/AUTOMATIC1111/stable-diffusion-webui"
Then from the stable diffusion webui folder installed on the device, ran webui-user.bat
The stable diffusion webui is lanched after downloading all the necessary libraries including torch.
In the stable diffusion webui:
Used img2img generation
In img2img generation used inpaint
Sampling method used was - Euler a
Sampling steps was changed to 85
Used Soft Inpainting
Used masking 
Set CFG Scale at 6 through out for generating images
Set denoising strength through out as 0.99 as the background for the images was needed to be added from nothing but plain white
Set seed as -1
Set batch size as 1
Challenges faced through out:
Did'nt have access to GPU in personal laptop so UI could'nt work so had to use a laptop with GPU.
Took some time to setup an dtune the parameters for generating the images using stable diffusion inpainting
