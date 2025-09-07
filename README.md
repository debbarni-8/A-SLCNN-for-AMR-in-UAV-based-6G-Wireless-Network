# A-SLCNN-for-AMR-in-UAV-based-6G-Wireless-Network
Manuscript ID: IEEE LATAM Submission ID: 9500 Authors:

Debbarni Sarkar 

Samarth Verma 

Rupa Kumari 

Yogita

Vipin Pal

Satyendra Singh Yadav


<img width="573" height="444" alt="download (4)" src="https://github.com/user-attachments/assets/56565623-32f4-48e6-9fa3-4e9c47bfa0b1" />

# 📁 Included Scripts

This repository contains all scripts required to reproduce the simulation and numerical results presented in the article.


| Script | Related Figure(s) | Description |
|--------|-------------------|-------------|
| **Fig4_6_8_9_PROPOSED.ipynb** | Fig. 4, Fig. 6, Fig. 8, Fig. 9 and TABLE III | Fig. 4: Training process of the proposed model. Fig. 6: Performance comparison between the baseline and proposed models. Fig.8: Performance of the SLCNN model on 26 modulation schemes. Fig.9: Classification performance at different SNR levels. Training and testing time of the proposed model. |
| **Fig_5.ipynb** | Fig. 5 | Comparison of the proposed model performance on different datasets.  |
| **Fig6_GRU.ipynb, Fig6_LSTM.ipynb, Fig6_CLDNN.ipynb, Fig6_ResNet.ipynb** | Fig. 6 and TABLE III| Performance comparison between the baseline and proposed models: (a) Accuracy, (b) Precision, (c) Recall, and (d) F1-score. Training and testing time of the baselines models. |
| **Fig_7.ipynb** | Fig. 7 | Classification performance with varying simulation parameters: (a) Learning rate at dropout 0.45, (b) Dropout at learning rate 0.001. |

# 📁 Dataset
in our experiment RML2016.10a, RML2016.10b, RML2018.01a and HisarMod2019.1 datasets have been used.
| Dataset | Link | 
|--------|-------------------|
|RML2016.10a| [RML-2016a(1)](https://www.deepsig.ai/datasets/)/ [RML-2016a(2)](https://www.kaggle.com/datasets/nolasthitnotomorrow/radioml2016-deepsigcom)|  
|RML2016.10b| [RML-2016b(1)](https://www.deepsig.ai/datasets/)/ [RML-2016b(2)](https://www.kaggle.com/datasets/marwanabudeeb/rml201610b/code)|  
|RML2018.01a| [RML-2018a(1)](https://www.deepsig.ai/datasets/)/ [RML-2018a(2)](https://www.kaggle.com/datasets/pinxau1000/radioml2018)| 
|HisarMod2019.1|[HisarMod2019](https://pan.quark.cn/s/016a2f6861a2#/list/share)|

# 💻 Required Files
- Fig4_6_8_9_PROPOSED, Fig6_GRU.ipynb, Fig6_LSTM.ipynb, Fig6_CLDNN.ipynb, Fig6_ResNet.ipynb are the same folder.
- Fig_5.ipynb, Fig_7.ipynb are are standalone.

# 💻 Requirements
- The training and testing procedures are executed using the Keras DL API, with TensorFlow as the computational backend and an Nvidia M60 GPU for acceleration.

# ✉️ Contact
satyendra@nitm.ac.in
