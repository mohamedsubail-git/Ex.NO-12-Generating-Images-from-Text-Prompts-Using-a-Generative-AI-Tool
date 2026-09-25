# Ex.NO-12 – Generating Images from Text Prompts Using a Generative AI Tool

## AIM

To understand how text-to-image generative AI works and to generate and refine sample images from text prompts using a generative AI model in Google Colab.

## WHAT IS TEXT-TO-IMAGE GENERATIVE AI?

Text-to-image generative AI converts a written description, called a **prompt**, into a newly generated image.

The AI model interprets different elements in the prompt, such as:

- Subject
- Environment
- Style
- Lighting
- Colour
- Mood
- Camera angle
- Level of detail

The quality of the generated image depends greatly on how clearly and specifically the prompt is written.

## TOOLS REQUIRED

- Google Colab
- Python
- Stable Diffusion
- Hugging Face Diffusers
- Transformers
- Accelerate
- Safetensors
- PyTorch
- GPU runtime such as T4 GPU
- Web browser

## PROCEDURE

### Step 1: Open Google Colab

Open Google Colab and create a new notebook.

### Step 2: Enable GPU Runtime

Select:

**Runtime → Change runtime type → T4 GPU**

A GPU is recommended because image generation requires significant computational resources.

### Step 3: Install Required Libraries

Install the required Python libraries using `pip`.

The experiment uses:

- Diffusers
- Transformers
- Accelerate
- Safetensors
- PyTorch

### Step 4: Load the Text-to-Image Model

The Stable Diffusion model is loaded using the Diffusers library.

The model converts the user's text prompt into an image.

### Step 5: Enter the First Prompt

The user enters a text prompt interactively.

Example:

> A futuristic classroom with college students learning with AI robots, modern digital screens, colorful technology, warm lighting, wide angle view, highly detailed digital art

### Step 6: Generate Images

The program generates two different images from the same prompt.

The generated images are displayed directly in Google Colab.

### Step 7: Save the First Images

The generated images are saved as:

- `first_image_1.png`
- `first_image_2.png`

### Step 8: Refine the Prompt

A second prompt is entered with additional descriptive details.

Example:

> smart car

### Step 9: Generate Refined Images

The refined prompt is processed by the same AI model to generate two new images.

### Step 10: Save the Final Image

One of the refined images is selected as the final output and saved as:

`final_ai_generated_image.png`

## SYSTEM WORKFLOW
```text
**Text Prompt**  
↓  
**Stable Diffusion Model**  
↓  
**Prompt Interpretation**  
↓  
**Image Generation**  
↓  
**Two Generated Images**  
↓  
**Review Images**  
↓  
**Refine Prompt**  
↓  
**Generate Refined Images**  
↓  
**Select Final Image**  
↓  
**Save Final Image**
```
## PROGRAM
```python

```

## SAMPLE PROMPT

### First Prompt

> A futuristic classroom with college students learning with AI robots, modern digital screens, colorful technology, warm lighting, wide angle view, highly detailed digital art

### Refined Prompt

> smart car

## OUTPUT


### First Generation

<img width="1689" height="940" alt="image" src="https://github.com/user-attachments/assets/fd87cb43-408a-4c02-afb5-25e11a9ab3fa" />

<img width="868" height="691" alt="image" src="https://github.com/user-attachments/assets/47f449c8-6106-499d-b358-03548077a96c" />

### Refined Generation

<img width="757" height="783" alt="image" src="https://github.com/user-attachments/assets/bbd571d3-aa39-4925-87fb-d7105bbf0934" />


<img width="689" height="746" alt="image" src="https://github.com/user-attachments/assets/946e2f03-a760-467e-8b27-7e4dda27bcc1" />

## GENERATED FILES

The program generates and saves the following files:

- `first_image_1.png`
- `first_image_2.png`
- `refined_image_1.png`
- `refined_image_2.png`
- `final_ai_generated_image.png`

## OBSERVATION

The experiment demonstrates that changing the wording and adding descriptive details to a text prompt can produce different visual results. The refined prompt provides additional information about the environment, colours, lighting, technology, and composition.

## RESULT

Text-to-image generative AI was successfully implemented in Google Colab. Two images were generated from the initial text prompt, the prompt was refined, and two additional images were generated from the refined prompt. The final generated image was successfully saved.

## CONCLUSION

The experiment demonstrates how text descriptions can be converted into visual content using generative AI. Prompt refinement plays an important role in controlling the subject, style, lighting, environment, and overall appearance of the generated image. This experiment also provides a practical understanding of how generative AI can be used for creative image generation.
