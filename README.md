# Creator Prompt Edit
Curation of some of my favorite prompts to generate high-fashion editorial-looking portraits using ChatGPT! Try it out here: https://ramakronym.github.io/creator-prompt-edit/


# Background & Context
As a fashion creator who runs my page as team of 1, while also working full-time in tech, I often do not have the luxury of planning extensive photoshoots, hiring photographers and investing $$$ to create an scale content. One incredibly compelling use-case of multi-model AI is creating high-fidelity images within minutes with a few simple prompts. Over the course of the last few months, I've compiled a list of my top favorite prompts that I use to enhance pictures I take on a regular smartphone to look more polished and editorial, while also creating new high-fashion images from scratch.

# How to use
Pick a photo in the style you like, copy the prompt and use it on your own image in ChatGPT. I recommend using a high-resolution headshot where your facial features are clearly visible so the model has all the context needed to render your updated portraits realistically.

# Behind the scenes - how image generation models work

Here's a high-level overview of what actually happens behind the scenes to enable this type of image creation. ChatGPT’s image models are trained to understand relationships between visual patterns and language - for example, what soft window light, silk fabric, or a vintage film aesthetic might look like. When you provide a prompt, the model uses those instructions to generate an image. If you also upload a photo, it can use that image as a reference while applying requested changes to the lighting, background, clothing, or style. An image model turns your prompt and any uploaded photos into numerical representations, then uses patterns learned during training to generate an image that fits those inputs.

During training, an image model learns statistical relationships among images, visual features, and language. It learns these patterns in its model weights—parameters adjusted during training. It isn’t simply looking up a matching photo and placing it into your result. The result can look highly realistic because the model has learned how many visual details tend to appear together: the way light falls across skin, how jewelry catches highlights, and how fabric creases around a pose. 

# How the model turns prompts into images and what to watch for 

There are often two popular approaches behind image generation models: Diffusion models & Auto-regressive models. 

Diffusion models, used by many image generators, generally learn to create images by progressively refining a noisy visual representation. The prompt guides that refinement toward an image matching the requested concepts.

Autoregressive models generate a sequence of visual information conditioned on the prompt and context. OpenAI has said that GPT-4o’s native image generation uses an autoregressive approach, typically.

When providing prompts, attention mechanisms help the model relate parts of the instructions and visual information to what it is generating. Research on Stable Diffusion, for example, has found different roles for cross-attention and self-attention in text-guided editing and preservation of visual structure. Language requirements may also sometimes compete - so while drafting prompts, make sure there are unique descriptions to specific attributes of the image (like background, color grading, lighting, etc.) to achieve high precision results.

I've also noticed that sometimes the model may mess up your facial features even when you prompt it to say "keep facial features INTACT". This happens because image reconstruction can sometimes introduce drift. The model may generate a new interpretation of your face instead of copying the original face pixel for pixel. Even a small change in eye spacing, lip shape, or jaw contour can make a familiar face feel different. For this, I would also suggest going into ChatGPT settings --> Personalization --> Reference Photos and adding your best reference images to improve facial feature context.

<img width="603" height="1311" alt="IMG_7385" src="https://github.com/user-attachments/assets/141e24eb-9ef2-482e-88f3-f535b94fb1c3" />
<img width="603" height="1311" alt="IMG_7384" src="https://github.com/user-attachments/assets/f35f3e3b-dfaf-4885-8be8-89d5d2981aa6" />







