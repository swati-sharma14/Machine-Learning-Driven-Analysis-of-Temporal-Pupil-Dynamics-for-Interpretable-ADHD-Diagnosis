# Machine Learning-Driven Analysis of Temporal Pupil Dynamics for Interpretable ADHD Diagnosis  

### Accepted at *Computers in Biology and Medicine (CIBM)*  

This repository contains the implementation of our paper:  

> **Machine Learning-Driven Analysis of Temporal Pupil Dynamics for Interpretable ADHD Diagnosis**  
> Swati Sharma, Mrinmoy Chakrabarty, Sonia Baloni Ray, Jainendra Shukla  

We introduce an interpretable machine learning framework that leverages temporal pupil dynamics to distinguish ADHD and control groups. By extracting novel dynamic dilation/constriction rate features and integrating behavioral metrics, our models achieve strong diagnostic accuracy while maintaining clinical interpretability.  

[Paper DOI – [https://doi.org/10.1016/j.compbiomed.2025.110878](10.1016/j.compbiomed.2025.110878)]  

---

## Key Features
- Extraction of block-wise pupil features (dilation/constriction rates, size metrics).  
- Integration of task performance and reaction time measures.  
- Multiple models tested: traditional ML, sequential deep learning, and our hybrid CLAGNet (CNN–LSTM–Attention–GMM).  
- Emphasis on interpretability with statistical validation, feature importance, and visualization.  

---

## Results (Highlights)
- Accuracy: up to 88.9%  
- AUROC: up to 91.5%  
- Sensitivity: 97.8%  
- Specificity: 82.2%  

# Citation
If you use this work, please cite our paper:
@article{sharma2025adhd,
  title={Machine Learning-Driven Analysis of Temporal Pupil Dynamics for Interpretable ADHD Diagnosis},
  author={Sharma, Swati and Chakrabarty, Mrinmoy and Ray, Sonia Baloni and Shukla, Jainendra},
  journal={Computers in Biology and Medicine},
  year={2025},
  doi={to be updated}
}
