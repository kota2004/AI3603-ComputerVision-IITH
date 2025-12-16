# AI3603-ComputerVision-IITH
## Accepted CVIP 2025-IIT Ropar

Intro: Text-to AI generated image Quality Evaluator<br>
Used DL/CV Techniques: CLIP Vision Transformer, Resnet50<br>
Tech-stack used: Pytorch and Python<br>
Metrics: SRCC, PLCC<br>
What is done during the project: Done literative review, we replicated results of a research paper with our code and improved the results with slight modification in methodology<br>
Dataset used: AGIQA‑3k contains around 3,000 AI-generated images along with their text prompts and human-labeled scores for two aspects: perceptual quality and text–image alignment. For each image–prompt pair, human annotators provide MOS-style scores.<br>

For perceptual quality between image and patch embeddings with 11 text-variants and their similarity measurement was converted to scores by MLP head and<br>
For image-text alignment between image and text-prompt, patch and text-prompt and their similarity measurement was converted to scores by MLP head.<br>
The scores was then compared with ground truth values.<br>

During inference, SRCC and PLCC was used as measure if low poor quality else high quality images.<br>

For more info check out code and report.
