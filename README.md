<p align="center">
  <img src="gifbaner.gif" alt="Dataset Banner" width="100%">
</p>

## **Overview**

The C A N C E R corpus focuses on related terminology to assist non-native English speakers affected by the disease, helping patients navigate language barriers—particularly to advance health education and self-management using Machine Translation. The  manually annotated dataset includes terminologies in Finnish (FI), Chinese (ZH), and Urdu (UR), curated from publicly available existing English (EN) data.

---

## 📦 Dataset 

<div align="center">

| Category          | Annotated data | #Pairs |
|-------------------|---------------|--------|
| **In-Domain**     | EN → FI       | 1,494  |
|                   | EN → UR       | 1,494  |
| **Out-of-Domain** | EN → FI       | 291    |
|                   | EN → ZH       | 291    |
|                   | EN → UR       | 291    |

Annotated cancer terminology parallel data
</div>

---

## 📚 **Paper Reference**

> **C A N C E R: Corpus for Accurate Non-English Cancer-related Educational Resources**  


### 📄 **Abstract**

> Improving the quality of cancer terminology through Machine Translation (MT) in non-English languages remains an underresearched area despite its critical role in supporting self-management and advancing multilingual patient education. Existing computational tools encounter significant limitations in accurately translating cancer terminologies, particularly for low-resource languages, primarily due to data scarcity and morphological complexity. To address the gap, we introduce a dedicated terminology resource — Corpus for Accurate Non-English Cancer-related Educational Resources (C A N C E R), a manually annotated dataset in Finnish (FI), Chinese (ZH), and Urdu (UR), curated from publicly available existing English (EN) data. We also examine the impact of data quality versus quantity and compare the performance of the Opus-mt-en-fi, Opus-mt-en-zh, and Opus-mt-en-ur models with the SMaLL-100 multilingual MT model. We assess translation quality using automatic and human evaluation. Results demonstrated that high-quality parallel data, though sparse, combined with fine-tuning, substantially improved the translation of cancer terminology across both high and low-resource language pairs, positioning the C A N C E R corpus as a foundational resource for improving multilingual patient education.
