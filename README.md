# Image Fusion using Wavelet Transform

## Project Overview  
Image fusion is a technique that combines multiple images with different focus areas into a single, high-quality image. This improves clarity, enhances details, and ensures that important features from all input images are retained. By leveraging **Discrete Wavelet Transform (DWT)** and **Stationary Wavelet Transform (SWT)**, our approach minimizes distortions and preserves critical image information.  

This method is widely used in **medical imaging, remote sensing, surveillance, and security applications**, where clear and detailed images are essential.  

## Features  
- ✅ Combines **DWT and SWT** for high-quality image fusion  
- ✅ **Retains fine details and sharpness** in fused images  
- ✅ **Minimizes distortions and enhances clarity**  
- ✅ **Preserves edges and spatial details** for better feature extraction  
- ✅ **Ideal for multi-focus image fusion** used in medical imaging, security, and surveillance  
- ✅ **Outperforms traditional fusion techniques** with better accuracy in metrics like PSNR and SSIM  

## How to Use  
1. **Load Input Images** – Provide multiple images with different focus levels.  
2. **Apply Discrete Wavelet Transform (DWT)** – Decomposes images into frequency bands.  
3. **Apply Stationary Wavelet Transform (SWT)** – Preserves image details without downsampling.  
4. **Fusion Process** – Combines DWT and SWT results to generate a high-quality image.  
5. **Output the Final Fused Image** – The resulting image retains critical features and improved clarity.  

## Installation  
### Prerequisites  
Ensure you have Python installed on your system. You also need the following libraries:  

```bash
pip install numpy opencv-python pywt matplotlib
```
## Clone the Repository
```bash
git clone https://github.com/yourusername/ImageFusion-Wavelet
cd ImageFusion-Wavelet
```

## Run the Program
```bash
python image_fusion.py
```

## Conclusion
This hybrid DWT + SWT approach significantly improves multi-focus image fusion by preserving essential details and reducing distortions. It is a powerful technique for various real-world applications requiring clear and accurate images.


## ⭐ Give a Star!  
If you like this project, feel free to ⭐ the repo.  
Your support motivates me to build more projects!






