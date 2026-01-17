# Procedural Dissolve Shader

## 1. Project Overview
This project implements a **Procedural Dissolve Shader** using Unity's Shader Graph (URP). The shader simulates a disintegration effect commonly used in video games for character deaths or environmental transitions.

## 2. Technical Implementation
- **Engine:** Unity 2022.3 (Universal Render Pipeline)
- **Technique:** Alpha Clipping with Gradient Noise.
- **Math Logic:** $$Alpha = step(Amount, Noise)$$
  - A grayscale noise texture is compared against a threshold (`Amount`).
  - Pixels below the threshold are discarded using the Alpha Clip setting.

## 3. How to Run
1.  Download this repository (Code -> Download ZIP).
2.  Open Unity Hub -> Add -> Select the unzipped folder.
3.  Open `Scenes/SampleScene`.
4.  Select the **Sphere** and adjust the **Amount** slider in the Inspector.

## 4. Visual Results
*(Upload screenshots here if needed)*
