# Satelite-image-to-map-conversation-using-Cgans
This project uses a Pix2Pix GAN with a U-Net generator to convert satellite images into road maps. Trained on the Massachusetts Roads Dataset, the model leverages adversarial, L1, and SSIM losses for accurate segmentation. Built with PyTorch and deployed using Flask for real-time inference.
Satellite Image to Map Translation using Pix2Pix GAN
This project implements an advanced Pix2Pix GAN to convert satellite images into road maps, using a U-Net-based generator and a multiscale PatchGAN discriminator for improved edge precision and detail capture.

📌 Overview
Translates paired satellite images into their corresponding road maps.

Utilizes Massachusetts Roads Dataset for supervised training.

Designed for urban planning, GIS systems, and autonomous navigation aids.

🧠 Key Features
U-Net Generator for preserving spatial features.

Multiscale PatchGAN Discriminator for better feature-level realism.

Loss Functions: Adversarial loss, L1 loss, and SSIM loss for structural accuracy.

🛠️ Tech Stack
Python, PyTorch, OpenCV, Flask

Deep Learning Libraries (Torchvision, NumPy, Matplotlib)

🚀 Output
The trained model effectively segments roads and generates high-quality map-style images from raw satellite views.
