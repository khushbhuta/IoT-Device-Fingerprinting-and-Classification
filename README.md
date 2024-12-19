# IoT-Device-Fingerprinting-and-Classification

This project focuses on building a robust classification system for IoT Devices. I have created device fingerprints for IoT Devices using network traffic analysis to classify them and detect anomalies. The goal is to create an efficient way to classify anomalies through new techniques that involve hardware-level features too. 
I have mainly worked on frequency-domain analysis(applying FFT to network-level features) and multimodal feature integration to detect anomalies and classify non-attack devices. The CNN method did not yield efficient results and was hence scrapped.

#### Testing:
For validating this method, I have tested my models on multiple open-source IoT-Network-Traffic datasets. The results can be seen as a section in my comprehensive report. 

Datasets used:
1. [UNSW NB-15 (Anomaly Detection Dataset)](https://research.unsw.edu.au/projects/unsw-nb15-dataset)
2. [UNSW Traffic Traces Dataset](https://iotanalytics.unsw.edu.au/iottraces.html)
