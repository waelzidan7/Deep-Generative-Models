# Deep Generative Models — University Coursework

**Contributors:** Wael Zidan and Tarek Diab  
**Stack:** Python · PyTorch · NumPy · Matplotlib · Jupyter Notebook  
**Datasets:** MNIST and CelebA (specific exercises)

A collection of collaborative university exercises exploring four approaches to deep generative image modeling. The notebooks demonstrate implementations, training workflows, evaluation and image generation; this is **academic coursework**, not a deployed machine-learning product. Some code is based on university exercise material; please credit course starter code where applicable.

## Exercises

| Exercise | Implementation and concepts |
| --- | --- |
| [EX4 — PixelCNN](notebooks/EX4_PixelCNN.ipynb) | Autoregressive image modeling; masked and vertical/horizontal convolutions; pixel sampling and conditional generation |
| [EX5 — Variational Autoencoders](notebooks/EX5_VAE.ipynb) | Convolutional VAE, reconstruction, latent interpolation and image inpainting |
| [EX6 — Normalizing Flows](notebooks/EX6_Normalizing_Flows.ipynb) | RealNVP-style affine coupling, invertible transformations and likelihood estimation |
| [EX7 — Diffusion Models](notebooks/EX7_Diffusion_Models.ipynb) | DDPM, U-Net denoising, MNIST experiments, CLIP conditioning and classifier-free guidance |

## How to explore

1. Install a compatible Python version and the packages in [`requirements.txt`](requirements.txt). GPU availability is recommended for training.
2. Open the notebook you want to study in JupyterLab or Google Colab.
3. Obtain the relevant dataset separately. Some cells depend on Colab paths or packages not completely captured by a frozen environment file.
4. Run the cells in order, adapting paths and hardware requirements as needed.

**Reproducibility note:** These are original course-format experiments, **not** a fully packaged install-and-run training suite. Large datasets, checkpoints and original rendered notebook outputs are intentionally not committed.

## Acknowledgments and responsible sharing

These are **collaborative academic exercises** by Wael Zidan and Tarek Diab, with possible university-supplied starter material. This repository documents coursework, not exclusively individually authored code. Never commit Kaggle API credentials (`kaggle.json`), private data or model weights containing restricted information.
