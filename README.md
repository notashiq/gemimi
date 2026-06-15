# Face Replacement Prompt

## Usage
1. Upload the target image as Image 1.
2. Upload your face reference as Image 2 (`@img2`).
3. Paste the prompt below exactly as written.
4. Do not modify the prompt if maximum identity preservation is required.

## Copy & Paste Prompt

```text
I have attached two images:

* Image 1: The target thumbnail containing the character. The character's face is circled for accurate identification.
* Image 2 (@img2): My face.

Task:
Replace only the circled character's face with my face from @img2.

Important requirements:

* Preserve my exact identity and facial features.
* Do not change my face shape, jawline, eyes, nose, lips, eyebrows, hairstyle, skin tone, age, or overall appearance.
* Do not beautify, stylize, age, de-age, or reinterpret my face.
* Keep my face recognizable as the same person from @img2.
* Match the facial expression only if necessary to fit the scene.

Scene consistency:

* Match the lighting, shadows, color grading, contrast, and mood of the original thumbnail.
* Blend my face naturally into the scene while preserving my identity.
* Maintain the original camera angle, head position, perspective, and scale of the character.
* Keep the character's clothing, body, pose, accessories, background, and all other elements unchanged.

Output goal:
Create a realistic, seamless face replacement that looks like I was originally photographed in that scene, while keeping my identity 100% intact and recognizable.

Strictly Follow:

preserve my identity (@img2) with absolute accuracy; do not alter, regenerate, reinterpret, beautify, stylize, enhance, smooth, reshape, or modify any facial feature including my face shape, jawline, chin, cheeks, forehead, hairline, hairstyle, eyebrows, eyes, nose, lips, ears, skin tone, skin texture, facial proportions, natural asymmetry, age, or distinctive characteristics; the final image must depict the exact same person from the reference photo and remain instantly recognizable at first glance; only adjust lighting, shadows, exposure, color grading, and environmental reflections to match the scene while keeping all facial details unchanged; if there is any conflict between scene realism and identity preservation, always prioritize identity preservation; facial modification strength 0%, identity preservation strength 100%, beautification 0%, stylization 0%, reinterpretation 0%, exact facial likeness required.
```

# UPSCALING PROMPT 

```
identity, face structure, pose, and composition, Perform ultra-high-resolution 8K upscaling with maximum detail enhancement. Add realistic skin texture with visible pores, fine lines, and natural imperfections, avoiding any plastic or artificial smoothing, Enhance facial details including sharp eyes, realistic eyelashes, natural eyebrows, detailed lips, and individual hair strands. Apply professional DSLR camera quality using a full-frame camera look with w premium 85mm or 50mm lens, Improve lighting with a natural key light, soft fill light and subtle rim light to separate the subject from the background. Increase clarity and sharpness naturally without over-sharpening. Balance highlights and shadows with improved dynamic range and true-to-life colors. Reduce noise and compression artifacts while preserving original texture. Apply cinematic yet realistic color grading with accurate skin tones and authentic depth of field. Output should look ultra
photorealistic, high-end studio quality, DSLR-level","negative prompt":"over-
smoothed skin, plastic face, cartoon style, anime, painterly look, AI artifacts, distorted face,
fake skin texture, blur, low detail, harsh sharpening, oversaturation, unrealistic lighting,
color bleeding, noise artifacts,

"resolution": "7680x4320",
"quality": "8K",
"style": "photorealistic, DSLR",
"detail_level": "maximum",
"identity_preservation": "strong",
"reference_image_weight": "high",
"noise_reduction": "high without texture loss",
"sharpening": "natural and controlled",
"lighting": "realistic studio lighting",
"camera": {
    "type": "DSLR",
    "sensor": "full-frame",
    "lens": "85mm portrait lens",
    "aperture": "f/1.8"
}```
