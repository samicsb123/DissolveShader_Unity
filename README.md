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
<img width="1223" height="634" alt="Sfera0" src="https://github.com/user-attachments/assets/9d653ac0-2d6f-4873-83cf-89d943cfb723" />
<img width="1920" height="645" alt="Sfera0 5" src="https://github.com/user-attachments/assets/b1601ba7-ce9d-40b4-95d1-984458bba54e" />
<img width="1918" height="665" alt="Sfera1" src="https://github.com/user-attachments/assets/6ec9e320-a14d-47c1-8671-baff346868c1" />
<img width="1920" height="1080" alt="Graph1" src="https://github.com/user-attachments/assets/c3e77cfc-cdc4-40f2-99ac-013d29cfdc36" />
