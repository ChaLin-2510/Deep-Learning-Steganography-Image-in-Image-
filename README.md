# Deep-Learning-Steganography-Image-in-Image-
### 🧑 Thực hiện:
- Lâm Quốc Chung – 20120258  
- Lâm Duy Thiên  - 20120192

## 🎯 Mục tiêu  
- Triển khai hai mô hình **SteganoGAN (Zhang et al., 2019)** và phiên bản **cải tiến dựa trên TISGAN (Two‑Step Image‑in‑Image Steganography via GAN, 2025)**.  
- Đánh giá chất lượng **ảnh stego** (tính ẩn) và **khả năng phục hồi ảnh secret** trên tập dữ liệu **CelebA**.  
- So sánh định lượng qua chỉ số **PSNR** và **SSIM**, cùng quan sát trực quan.

## 🔧 Môi trường thực nghiệm  
- **Google Colab** (GPU T4) – 20.000 ảnh CelebA (10.000 cover, 10.000 secret).  
- **Kích thước ảnh**: resize về 128×128, batch size = 8.  
- **Thư viện**: PyTorch, torchvision, matplotlib, scikit‑image, tqdm.

- **Link Full Source Code & Report:** https://drive.google.com/drive/folders/1y2lNJq_SlEJqE05ECC3AyPOdVBAUI6lA?usp=drive_link
- **Link Data:** 
