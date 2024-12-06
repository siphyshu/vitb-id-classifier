# vitb-id-classify 🪪
---

Classifies VITB ID cards into hosteller, day scholar, and faculty[^*].

## How?
- Dataset acquired of 11 IDs in different angles and lighting conditions totalling 112 images + 12 control.
- Training was done on 100 images using [teachable machine](https://teachablemachine.withgoogle.com/). It took ~2 minutes.
- Used Tensorflow.js to import the model on the webpage, which is just a simple HTML file.

## Demo:
https://github.com/user-attachments/assets/942c29b2-aad5-45c0-8331-f274d87b62d6

[^*]: the model doesn't detect faculty ID cards as we didn't have a faculty cards dataset. if you have the means of acquiring these images, feel free to submit a PR.
