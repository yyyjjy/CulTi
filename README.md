<img src='./logo.png' align="left" width="11%" /> 

# CulTi: A Multimodal Dataset for Cross-modal Retrieval in Chinese Cultural Heritage

This repository hosts the dataset **CulTi**, introduced in the paper:  
**"Towards Cross-modal Retrieval in Chinese Cultural Heritage Documents: Dataset and Solution"**  
*Junyi Yuan, Jian Zhang, Fangyu Wu, Huanda Lu, Dongming Lu, Qiufeng Wang*

[![Arxiv](https://img.shields.io/badge/arXiv-Paper-B31B1B.svg)](https://arxiv.org/abs/2505.10921) <!-- TODO: Replace with actual arXiv link -->

---

## 📖 Introduction

China has a long and rich history, encompassing diverse cultural heritage such as **silk patterns** and **Dunhuang murals**.  
To bridge **visual** and **textual modalities** in these domains, we introduce **CulTi**, the **first multimodal dataset** dedicated to Chinese cultural heritage.

- **5,726 image-text pairs**  
- Sources: *Original Patterns From Ancient Chinese Textiles* (silk) & *Complete Collection of Chinese Dunhuang Murals*  
- Each entry includes: **ID, title, image, textual description**  
- Designed for **cross-modal retrieval tasks** (image-to-text, text-to-image)
- 
<p align="center">
    <img src="./imgs/1.png" width="70%">
</p> 

---

## 📂 Dataset Structure
<p align="center">
    <img src="./imgs/2.png" width="70%">
</p> 

- **Images**: high-quality scans of silk patterns, cropped motifs, Dunhuang murals  
- **Texts**: simplified Chinese descriptions, OCR + refined with GPT-4o  
- **Split**: 7:1:2 (train/val/test)

<p align="center">
    <img src="./imgs/3.png" width="70%">
</p> 
---

## 🚀 Download

The dataset is hosted on Google Drive:  

[![Google Drive](https://img.shields.io/badge/Download-Google%20Drive-4285F4?logo=google-drive&logoColor=white)](https://drive.google.com/drive/folders/1Q3lHxhQvwfxehq_VOCyFgWXOK0Wyxux3?usp=share_link) <!-- TODO: Insert real link -->
[![Pan Baidu Code: kvvj](https://img.shields.io/badge/Download-百度网盘-06a7ff?logo=baidu&logoColor=white)](https://pan.baidu.com/s/1DZ8I6GcgGaI8LsZgXLowzw)
⚠️ **Note:** To ensure proper usage, dataset access is **password-protected**.  
Please follow the agreement instructions below.

---

## 📑 Access Protocol

To access the dataset, please:  
1. **Fill in the Data Usage Agreement Form** [![Agreement](https://img.shields.io/badge/Agreement-Form-blue)](https://github.com/yyyjjy/CulTi/blob/main/Legal-Commitment.docx) <!-- TODO: Replace with real link -->  
2. After review, you will receive the **password** via email.  
3. Use the password to unzip the dataset files.

---

## 🧪 Benchmark & Results

We propose **LACLIP**, a local alignment strategy based on Chinese-CLIP,  which significantly improves cross-modal retrieval on CulTi.
<p align="center">
    <img src="./imgs/4.png"  width="70%">
</p> 

<p align="center">
 <img src="./imgs/5.png" width="70%">
</p> 


---
## Future Work  


This dataset will be further extended through **LLM-driven completeness and consistency evaluation** for cultural heritage data augmentation in cross-modal retrieval. Our paper *“LLM-Driven Completeness and Consistency Evaluation for Cultural Heritage Data Augmentation in Cross-Modal Retrieval”* has been accepted at **EMNLP 2025**. For updates and resources, please visit [JianZhang24/C-3](https://github.com/JianZhang24/C-3).  
---

## 📜 Citation

If you use **CulTi** in your research, please cite:

```bibtex
@inproceedings{yuan2025culti,
  title={Towards Cross-modal Retrieval in Chinese Cultural Heritage Documents: Dataset and Solution},
  author={Yuan, Junyi and Zhang, Jian and Wu, Fangyu and Lu, Huanda and Lu, Dongming and Wang, Qiufeng},
  booktitle={ICDAR},
  year={2023}
}


