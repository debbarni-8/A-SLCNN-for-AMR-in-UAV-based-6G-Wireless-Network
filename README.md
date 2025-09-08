# A-SLCNN-for-AMR-in-UAV-based-6G-Wireless-Network
Manuscript ID: IEEE LATAM Submission ID: 9500 

Authors:

- Debbarni Sarkar 

- Samarth Verma 

- Rupa Kumari 

- Yogita

- Vipin Pal

- Satyendra Singh Yadav

Affiliation:

-Debbarni Sarkar, Samarth Verma, Rupa Kumari, and Satyendra Singh Yadav are with the Department of ECE, National Institute of Technology Meghalaya, India.

-Yogita is with the Department of CSE, National Institute of Technology Kurukshetra, India

-Vipin Pal is with the Department of CSE, National Institute of Technology Delhi, India.

# 

Design a lighted a DL model for AMR in UAV-based 6G wireless network.
<img width="800" height="600" alt="fig3" src="https://github.com/user-attachments/assets/c8f5ce62-a05a-42a0-820c-002b55497ab3" />


# 📁 Included Scripts

This repository contains all scripts required to reproduce the simulation and numerical results presented in the article.


| Script | Related Figure(s) | Description |
|--------|-------------------|-------------|
| **Fig4_6_8_9_PROPOSED.ipynb** | Fig. 4, Fig. 6, Fig. 8, Fig. 9 and TABLE III | Fig. 4: Training process of the proposed model. Fig. 6: Performance comparison between the baseline and proposed models. Fig.8: Performance of the SLCNN model on 26 modulation schemes. Fig.9: Classification performance at different SNR levels. Training and testing time of the proposed model. |
| **Fig_5.ipynb** | Fig. 5 | Comparison of the proposed model performance on different datasets.  |
| **Fig6_GRU.ipynb, Fig6_LSTM.ipynb, Fig6_CLDNN.ipynb, Fig6_ResNet.ipynb** | Fig. 6 and TABLE III| Performance comparison between the baseline and proposed models: (a) Accuracy, (b) Precision, (c) Recall, and (d) F1-score. Training and testing time of the baselines models. |
| **Fig_7.ipynb** | Fig. 7 | Classification performance with varying simulation parameters: (a) Learning rate at dropout 0.45, (b) Dropout at learning rate 0.001. |
|📁 **Jetson Orin Nano platform**| TABLE IV| Jetson Orin Nano has been considered to assess the performance of the proposed model on real-time hardware.|

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
- To assess the performance on real-time hardware, evaluations have been conducted using the NVIDIA Jetson Orin Nano development platform, equipped with 8 GB of RAM. The device integrates the NVIDIA Ampere Graphics Processing Unit with 1024 Compute Unified Device Architecture cores, delivering up to 40 Tera Operations Per Second of artificial intelligence performance, supported by 8 GB of 128-bit Low-Power Double Data Rate 5 memory with 68 GB per second bandwidth. It is further equipped with a 6-core Arm Cortex-A78AE CPU and 2 NVIDIA DL Accelerator version 2.0 units, while offering support for 1080p30 video encoding and decoding. With a compact form factor of 70 millimeters by 45 millimeters and a configurable power consumption range of 7 to 15 Watts. 
# ✉️ Contact
satyendra@nitm.ac.in 

p21ec004@nitm.ac.in
