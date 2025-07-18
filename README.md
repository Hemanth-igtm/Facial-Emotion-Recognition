# Facial Emotion Recognition – Classical Features vs CNN
A comparative project implementing multiple approaches for facial emotion recognition:
 CNN (Deep Learning)
 HOG + ML
 LBP + ML
 ORB + ML
 SIFT + ML
 
 # Repository Structure
 notebooks/
├─ cnnnn.ipynb       # CNN approach
├─ FER_usingHOG(1).ipynb  # HOG + ML
├─ lbp2.ipynb        # LBP + ML
├─ ORB.ipynb         # ORB + ML
└─ SIFT1.ipynb       # SIFT + ML

# Dataset should follow:
data/
├─ train/<class_name>/*.jpg
└─ test/<class_name>/*.jpg

# How to Run
Clone this repository:
git clone <repo-url>
cd <repo-folder>

Install dependencies:
pip install numpy opencv-python scikit-learn scikit-image tensorflow keras matplotlib seaborn

Open a notebook in Jupyter and run all cells:
For CNN → notebooks/cnnnn.ipynb
For HOG → notebooks/FER_usingHOG(1).ipynb
For LBP → notebooks/lbp2.ipynb
For ORB → notebooks/ORB.ipynb
For SIFT → notebooks/SIFT1.ipynb

# Notes
Update dataset paths inside each notebook.
Ensure OpenCV contrib for SIFT/ORB: pip install opencv-contrib-python
