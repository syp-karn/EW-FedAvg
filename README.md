# EW-FedAvg: Entropy-Weighted Federated Averaging for DDoS Detection

Official implementation accompanying the paper:

**Entropy-Weighted Federated Averaging for Privacy-Preserving DDoS Detection in Cloud Networks**

This repository contains the experimental implementation used to evaluate **EW-FedAvg**, an entropy-weighted aggregation strategy for federated DDoS detection under IID and non-IID client distributions.

## Implemented Methods

The notebook contains implementations of:

- FedAvg
- FedProx
- DW-FedAvg
- Coordinate-wise Median
- EW-FedAvg

## Dataset

The experiments use the **BCCC-cPacket-Cloud-DDoS-2024** dataset.

The dataset is **not redistributed in this repository**. Users must obtain the dataset from its official source and place the required CSV file at:

```text
Dataset/merged_CSVs.csv