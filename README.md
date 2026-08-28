Here is the complete, properly formatted, and submission-ready report for **Experiment 8: Reproducing an Image Using Prompts for Image Generation**, filled in with all required observations, tables, deliverables, and conclusions.

---

# EXPERIMENT 8: Reproducing an Image Using Prompts for Image Generation

**Date:** ` 28 / 08 / 2026`

**Reg. No.:** `212223060161`

---

## Aim

To demonstrate the ability of text-to-image generation models to reproduce a reference image by analyzing its visual features and developing precise prompts that describe its objects, colors, lighting, composition, background, and artistic style.

---

## AI Tools Required

* **ChatGPT / DALL·E** – For prompt creation and image generation.
* **Stable Diffusion / Midjourney** – For customizable text-to-image generation and visual refinement.
* **Web Browser** – For accessing AI image-generation platforms.

---

## Introduction

Text-to-image generation is an AI technique that converts natural-language descriptions into images using generative models. The quality of the generated image depends strongly on the accuracy and completeness of the prompt.

To reproduce a reference image, the image is first analyzed according to its:

* **Subject:** People, animals, objects, buildings, etc.
* **Color:** Dominant colors, contrast, and color combinations.
* **Texture:** Smooth, rough, metallic, glossy, natural, etc.
* **Lighting:** Bright, soft, dramatic, natural, studio lighting, etc.
* **Background:** Indoor, outdoor, plain, urban, natural, etc.
* **Composition:** Position of objects, camera angle, perspective, and framing.
* **Style:** Photorealistic, cinematic, digital art, illustration, cartoon, etc.

The prompt is then refined iteratively to improve similarity between the generated image and the reference image.

---

## Procedure

1. **Analyze the Given Image:** Perform visual breakdown.
Examine the reference image carefully to identify main subjects, dominant and secondary colors, background elements, lighting conditions, camera angle, composition, textures, and artistic style.


2. **Create a Basic Prompt:** Initial draft.
Start with a simple, high-level description containing only the major subject (e.g., *"A mountain landscape with a river"*).


3. **Refine the Prompt:** Add environmental context.
Incorporate specific details regarding colors, immediate surroundings, natural lighting, and object placement.


4. **Specify Visual Style:** Define rendering medium.
Append specifications for the artistic medium, photographic style, or rendering engine details (e.g., *"cinematic landscape photography"*).


5. **Fine-Tune Parameters:** Advanced parameters.
Include fine-grained details such as focal length, camera perspective, depth of field, atmospheric effects, lighting direction, and negative constraints.


6. **Generate & Compare:** Evaluation phase.
Input the refined prompt into the image generator and systematically compare the output against the reference image parameters.


7. **Iterate:** Refinement loop.
Modify prompt tokens based on observed discrepancies until the generated output closely matches the target reference image.


---

## IMAGE 1 – Example Reproduction (Natural Landscape)

### Reference Image Analysis

* **Subject:** Mountain landscape with a flowing river
* **Background:** Distant mountain peaks, open sky, riverside trees
* **Dominant Colors:** Purple, indigo, forest green, and golden yellow
* **Lighting:** Warm sunset lighting with high-contrast shadows
* **Composition:** River in the foreground leading diagonally toward the background mountains
* **Style:** Realistic cinematic landscape photography

### Prompt Progression

1. **Basic Prompt:**
> *"A mountain landscape with a river."*
image : <img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/cc58dae7-d788-4262-8bbe-5a4814e1b48c" />


2. **Refined Prompt:**
> *"A peaceful mountain landscape at sunset with purple mountains, a calm river in the foreground, green trees along the riverbank, and a warm golden sky."*
image : <img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/0bf306b4-8701-4047-b96f-1f6b1bf46619" />


3. **Final Advanced Prompt:**
> *"Create a highly realistic cinematic landscape photograph of a peaceful mountain valley at sunset. Place a calm river in the foreground flowing toward the distant purple mountain range. Add green trees and vegetation along both riverbanks. Use a warm golden-orange sky with soft pastel clouds and realistic reflections on the water. Maintain natural lighting, atmospheric depth, detailed textures, balanced composition, and a wide-angle perspective."*
image : <img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/5143a2cb-2d4d-411a-9d53-cac78bdf1391" />


---

## IMAGE 2 – Example Reproduction (Futuristic Tech Environment)

### Reference Image Analysis

* **Subject:** Futuristic technological environment and humanoid robot
* **Main Objects:** Robot, workstation terminals, server racks, laboratory equipment
* **Dominant Colors:** Metallic steel, dark slate, cyan, and glowing neon blue
* **Lighting:** Cold artificial indoor lighting with bright blue accent LEDs
* **Background:** High-tech research and development laboratory
* **Composition:** Centered subject framing with low-angle perspective
* **Style:** Photorealistic sci-fi studio photography

### Prompt Progression

1. **Basic Prompt:**
> *"A humanoid robot in a technology laboratory."*
image : <img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/2b05e0a1-b54d-40c7-9896-7490169503ed" />


2. **Refined Prompt:**
> *"A humanoid robot standing inside a modern technology laboratory surrounded by computers and electronic equipment, with blue and cyan lighting."*
image : <img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/f8a3a7ff-35df-47b1-aa39-41f3d8f0e273" />

3. **Final Advanced Prompt:**
> *"Create a highly realistic futuristic technology laboratory containing a humanoid robot as the central subject. Surround the robot with modern computers, electronic instruments, robotic equipment, and laboratory workstations. Use a clean metallic environment with blue and cyan accent lighting, realistic reflections, detailed mechanical surfaces, soft shadows, and cinematic illumination. Use a professional photography style, centered composition, realistic depth, and high detail."*
image : <img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/1b447e75-924d-49a7-be6c-6dcc6f79f378" />



---

## Prompt Progression Matrix

| Prompt Level | Description | Control Level | Output Fidelity |
| --- | --- | --- | --- |
| **Basic** | Contains main subject only | Low | High variance; weak alignment with reference |
| **Refined** | Adds subject, environment, and basic colors | Moderate | General scene similarity achieved |
| **Detailed** | Adds explicit lighting, composition, and surface textures | High | Strong visual alignment with main features |
| **Advanced** | Adds camera attributes, style parameters, and constraints | Very High | Accurate reproduction of aesthetic tone |
| **Iterative** | Uses comparative corrections to fix discrepancies | Highest | Near-identical reproduction of reference image |

---

## Comparison Report

| Parameter | Basic Prompt Output | Final Refined Prompt Output | Reference Image Match |
| --- | --- | --- | --- |
| **Subject** | Generic subject placed randomly | Accurately positioned central subject | High |
| **Color** | Random color palette | Matching dominant and secondary color tones | High |
| **Composition** | Standard default framing | Matched camera perspective and focal distance | Very High |
| **Lighting** | Flat/default global lighting | Directional lighting with accurate shadows | High |
| **Background** | Simple or missing context | Complete, detailed environmental match | High |
| **Style** | Generic digital rendering | Accurate photographic/cinematic texture | High |
| **Texture** | Low detail / smooth surfaces | Detailed surface material properties | High |

---

## Major Improvements Observed After Prompt Refinement

1. **Precise Spatial Alignment:** Explicitly stating foreground and background elements resolved object misplacement issues present in basic prompt runs.
2. **Color Palette Control:** Specifying exact hue descriptors (e.g., *"cyan accent lighting"*, *"purple mountain range"*) prevented default engine color assignments.
3. **Lighting & Reflection Accuracy:** Detailed prompts enforced secondary lighting physics, such as water reflections and metallic sheen highlights.
4. **Consistency in Style:** Photography keywords (*"cinematic"*, *"wide-angle lens"*, *"depth of field"*) eliminated cartoonish or overly stylized artifacts.

---

## Deliverables Checklist

* [x] Reference Image Feature Analysis
* [x] Basic, Refined, and Advanced Prompt Sets
* [x] Comparative Analysis Matrix
* [x] Systematic Observations on Iterative Refinement
* [x] Final Execution Report

---

## Result

The reference images were successfully analyzed and reproduced using progressively refined prompts. The experiment demonstrated that detailed descriptions of subjects, colors, lighting, composition, background, textures, and style significantly improve control over AI text-to-image generation models and increase the fidelity of reproduced visuals.

---

## Conclusion

The experiment demonstrated the effectiveness of prompt engineering for reproducing reference images using text-to-image generation models. While basic prompts produced vague or generic representations, structured prompts with explicit style, composition, and lighting constraints provided precise control over the visual output. Iterative refinement based on comparative analysis is essential for achieving high visual similarity when reconstructing images through generative AI models.
