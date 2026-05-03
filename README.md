<img width="829" height="230" alt="image" src="https://github.com/user-attachments/assets/ab5caf54-9a65-4611-9a2d-af89dff768bc" /># ARP-spoofing-using-ML-DL
how we can detect ARP spoofing using Machine Learning and Deep learning 

🔍 Overview
ARP Spoofing is a Man-in-the-Middle attack where an attacker sends fake ARP (Address Resolution Protocol) replies to associate their MAC address with a legitimate IP address, allowing them to intercept network traffic.
This project builds and compares three detection models:
ModelTypeDescriptionRandom ForestMLEnsemble of 100 decision trees with balanced class weightsLightGBMMLGradient boosting with histogram-based learning, 300 estimatorsMLP (Improved)DLDeep neural network: 1024→512→256→128→64→32 with BatchNorm + Dropout

