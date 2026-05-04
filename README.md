# ARP Spoofing Detection using Machine Learning and Deep Learning
Description

This project aims to detect ARP Spoofing attacks using Machine Learning (ML) and Deep Learning (DL) techniques.

ARP Spoofing is a network attack that allows an attacker to intercept, alter, or block communication between devices on a network. This project provides an intelligent approach to identify such attacks based on network traffic data.

# Models

The following models are implemented and evaluated:

Random Forest
LightGBM
Multi-Layer Perceptron (MLP)

These models are trained on labeled datasets to classify network traffic as either:

Normal
ARP Spoofing attack

# Dataset

The project uses labeled network traffic data:

CIC_MITM_ArpSpoofing_All_Labelled_datasets.csv

# PCAP to CSV Conversion

To convert raw network traffic files (.pcap) into structured .csv format, you can use:

https://github.com/ahlashkari/CICFlowMeter

This tool extracts relevant network flow features required for training and evaluation.

# Graphical Interface

A simple graphical interface is included:

arp_detection_app.html

Features:

    Simulation of ARP Spoofing detection
    Testing with sample data
    Visualization of results

# Project Structure
├── models/                      
├── ARP_models.ipynb            
├── CIC_MITM_ArpSpoofing_...    
├── arp_detection_app.html      
├── data_to_test.csv            
└── README.md

# Installation and Usage


Clone the repository:

    git clone https://github.com/Tiho99/ARP-spoofing-using-ML-DL
    cd ARP-spoofing-using-ML-DL

Install dependencies
pip install -r requirements.txt

#Run the notebook


jupyter notebook ARP_models.ipynb
Launch the interface

Open the following file in your browser:

arp_detection_app.html

# Objective

Detect ARP Spoofing attacks effectively
Compare the performance of ML and DL models
Provide a simple interface for testing and demonstration

# Author

Tiho99

# License

This project is intended for educational and research purposes.
