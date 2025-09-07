# A-SLCNN-for-AMR-in-UAV-based-6G-Wireless-Network
Manuscript ID: IEEE LATAM Submission ID: 9500 Authors:

Debbarni Sarkar 

Samarth Verma 

Rupa Kumari 

Yogita

Vipin Pal

Satyendra Singh Yadav

# 📁 Included Scripts

This repository contains all scripts required to reproduce the simulation and numerical results presented in the article.


| Script | Related Figure(s) | Description |
|--------|-------------------|-------------|
| **Fig4_6_8_9_PROPOSED.ipynb** | Fig. 4, Fig. 6, Fig. 8, Fig. 9 and TABLE III | Fig. 4: Training process of the proposed model. Fig. 6: Performance comparison between the baseline and proposed models. Fig.8: Performance of the SLCNN model on 26 modulation schemes. Fig.9: Classification performance at different SNR levels. Training and testing time of the proposed model. |
| **Fig_5.ipynb** | Fig. 5 | Comparison of the proposed model performance on different datasets.  |
| **Fig6_GRU.ipynb, Fig6_LSTM.ipynb, Fig6_CLDNN.ipynb, Fig6_ResNet.ipynb** | Fig. 6 and TABLE III| Performance comparison between the baseline and proposed models: (a) Accuracy, (b) Precision, (c) Recall, and (d) F1-score. Training and testing time of the baselines models. |
| **Fig_7.ipynb** | Fig. 7 | Classification performance with varying simulation parameters: (a) Learning rate at dropout 0.45, (b) Dropout at learning rate 0.001. |

# 📁 Dataset
RML2016.10a.tar, RML2016.10b.tar, 2018.01.OSC.0001_1024x2M.h5.tar, HisarMod2019.1 datasets areavailable from DEEPSIG

# 💻 Required Files
- Fig4_6_8_9_PROPOSED, Fig6_GRU.ipynb, Fig6_LSTM.ipynb, Fig6_CLDNN.ipynb, Fig6_ResNet.ipynb are the same folder.
- Fig_5.ipynb, Fig_7.ipynb are are standalone.

# 💻 Requirements
- The training and testing procedures are executed using the Keras DL API, with TensorFlow as the computational backend and an Nvidia M60 GPU for acceleration.

# ✉️ Contact
satyendra@nitm.ac.in
