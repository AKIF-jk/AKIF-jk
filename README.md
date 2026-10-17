# Akif Jawad Khan

AI/ML engineer focused on **computer vision and generative models**. I build models that explain themselves, restore and generate images, and run fast, then package them so they can actually be used: ONNX export, FastAPI and Docker backends, Gradio demos. Computer science at FAST-NUCES. Open to AI Engineer, ML Engineer, Generative AI and Computer Vision roles.

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AKIF-jk)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:akifJawad@proton.me)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akif-jawad-6ba39a288/)
[![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/AkifJK)

## Selected work

**[Explainable Defect Inspector](https://github.com/AKIF-jk/xAI_Defects)** · [live demo](https://huggingface.co/spaces/AkifJK/xAI_Defect)
Zero/few-shot industrial anomaly detection on MVTec AD. Frozen OpenCLIP ViT-L/14 backbone with AdaptCLIP adapters, pixel-level Grad-CAM heatmaps, SHAP patch attribution, and an LLM that turns the top patches into a one-sentence explanation a non-ML inspector can read. Served as a Gradio app on Hugging Face Spaces.
`PyTorch` `OpenCLIP` `Captum` `SHAP` `Gradio`

**[Image Restoration and Face-to-Sketch GAN](https://github.com/AKIF-jk/Generative_AI)**
Oxford-IIIT Pet restoration under salt-and-pepper noise, Gaussian blur and occlusion, using the official splits and seeded, replayable corruption manifests. A single universal restoration autoencoder reaches mean SSIM 0.897 across 36,690 test restorations; a corruption classifier (99.2% accuracy, 0.987 macro-F1) then hard-routes each image to one of three specialist autoencoders. Also a conditional GAN for face-to-sketch on FS2K, tuned with Optuna, exported to ONNX and served through FastAPI, Docker and a React front end.
`PyTorch` `Optuna` `ONNX Runtime` `FastAPI` `Docker` `React`

**[GPU-Accelerated KLT Feature Tracker](https://github.com/AKIF-jk/cuda-klt-tracker)**
Team project taking a sequential C++ KLT tracker from CPU baseline to **10.85x** faster tracking with CUDA (7.5 s vs 81.3 s on 100 frames of 4K video, 5000 features). Profiled with gprof first; the speedup came from cutting host-device transfers, coalescing memory access, and using shared and constant memory. An OpenACC rewrite reached 1.32x on the same workload.
`CUDA` `OpenACC` `C++` `gprof` `Nsight`

**[Vision-Based Tetris Advisor](https://github.com/AKIF-jk/vision-Tetris)**
Classical computer vision pipeline in OpenCV: Otsu thresholding, perspective warp, HSV masking, connected components and Hu moments to read a board from a screenshot, then a Dellacherie-heuristic engine picks the move. 107 of 107 validation pieces classified correctly at roughly 100-300 ms per frame, with no deep learning and no GPU.
`OpenCV` `NumPy`

## Toolbox

- **Models and training:** PyTorch, torchvision, scikit-learn, scikit-image, Optuna, Weights & Biases
- **Vision and generative:** conditional GANs, CLIP / OpenCLIP, Grad-CAM, SHAP, OpenCV
- **Serving and deployment:** ONNX / ONNX Runtime, FastAPI, Docker, Gradio, React (Vite)
- **Performance:** CUDA, OpenACC, C/C++, profiling with gprof and Nsight Systems
- **Languages:** Python, C/C++, CUDA, JavaScript, Java

<details>
  <summary>Other software engineering projects</summary>

- **[LifeLine](https://github.com/AKIF-jk/LifeLine)**: blood bank management system in Java 17, JavaFX and SQLite with layered architecture, role-based access control and JUnit tests.
- Also on my profile: [Plagiarism Detector](https://github.com/AKIF-jk/Plagiarism-Detector), [Temporal Graph Analytics for Football](https://github.com/AKIF-jk/Temporal-Graph-Analytics-for-Football) and [GitLite](https://github.com/AKIF-jk/GitLite---Simplified-Version-Control-System-).

</details>
