# Network-Traffic-Protocol-Fingerprinting
## Project Overview
This project implements a machine learning model to identify network protocols (HTTP, DNS, SSH) based on traffic behavior rather than port numbers.

## How it Works (Methodology)
1. *Feature Extraction:* We focus on two main features:
   - Packet_Length: The size of the data packets.
   - Inter_Arrival_Time: The time delay between consecutive packets.
2. *Algorithm:* We used the *Random Forest Classifier* because it's highly accurate for tabular network data.
3. *Training:* The model was trained on a dataset of 300 samples (100 for each protocol).

## Results
The model achieved high accuracy in distinguishing between protocols.
![Model Results](./result2.png)
