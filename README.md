# Computer-Vision-Lab

# 🧿 Computer-Vision-Lab

A collection of small, focused computer vision experiments using **PyTorch**, **OpenCV**, and **deep learning**.

## 🔍 What’s inside?

- `notebooks/`
  - **01_image_basics.ipynb** – reading, resizing, color spaces, basic transforms  
  - **02_edge_detection.ipynb** – Canny, Sobel, contour detection  
  - **03_cnn_classification.ipynb** – simple CNN on CIFAR-10 / MNIST  

- `src/`
  - `datasets.py` – dataset + dataloader helpers  
  - `models.py` – CNN architectures  
  - `train.py` – training loop template  

## 🛠 Tech Stack

- Python, PyTorch  
- OpenCV, torchvision  
- Jupyter Notebooks  

## ▶️ How to run

```bash
git clone https://github.com/AdityaViraj/Computer-Vision-Lab.git
cd Computer-Vision-Lab
pip install -r requirements.txt
jupyter notebook
