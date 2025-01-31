

# **LogBERT Anomaly Detection - HDFS and BGL Datasets**  

This repository contains **two Jupyter notebooks** designed to examine **HDFS and BGL datasets** using the **LogBERT anomaly detection model**. The implementation is based on the paper:  

> **LogBERT: Log Anomaly Detection via BERT**  
> **Guo, Haixuan**  
> *All Graduate Theses and Dissertations, Spring 1920 to Summer 2023, 8110.*  
> [**Full Paper Link**](https://digitalcommons.usu.edu/etd/8110)  

---

## **Repository Source and Modifications**  
This repository is **forked** from the original implementation at:  
[**LogBERT Repository**](https://github.com/HelenGuohx/logbert)  

Several modifications were made to **accommodate new datasets and fix coding errors** in the original implementation.  

### **Code Changes**  
The following files were modified to support additional datasets and correct programming errors:  
- `bert_pytorch/predict_log.py`  
- `bert_pytorch/train_log.py`  
- `bert_pytorch/dataset/sample.py`  

---

## **Datasets**  
The **original datasets** were sourced from the **LogHub repository**:  
[**LogHub Datasets**](https://github.com/logpai/loghub)  

### **Dataset Storage Directories**  
- `~/.dataset` → Stores **original datasets** after downloading.  
- `project/output` → Stores **intermediate files and final results** during execution.  

---

## **Setup Instructions**  
### **Running the Jupyter Notebooks**  
Each notebook corresponds to a different dataset:  
- **HDFS Notebook**: Runs LogBERT on the HDFS dataset.  
- **BGL Notebook**: Runs LogBERT on the BGL dataset.  

Ensure that the datasets are correctly placed in the `~/.dataset` directory before execution.  

---

## **Implementation Details**  
LogBERT is a **BERT-based deep learning model** for **log anomaly detection**. It leverages **self-attention mechanisms** to learn log sequence patterns and detect anomalies effectively.  

### **Changes from the Original Implementation**  
- **Added support for HDFS and BGL datasets**.  
- **Fixed coding errors in prediction, training, and dataset processing scripts**.  
- **Improved dataset handling and storage structure**.  

