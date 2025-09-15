# BCC_XAI_Framework

Interpretable deep learning pipeline for **Basal Cell Carcinoma (BCC)** detection using dermoscopic images, clinical photos, and metadata.

## TL;DR
- **Task:** Binary BCC detection in dermoscopy + clinical context  
- **Approach:** Tri-modal **ensemble** (CNNs per modality) with **XAI** (SHAP, LIME, Grad-CAM)  
- **Results:** AUROC **0.9992**, Accuracy **99.02%** on held-out evaluation  
- **Why it matters:** High-sensitivity, clinician-friendly explanations for safety-critical decisions

## Methods (Short)
- Dermoscopy: CNN backbone (transfer learning), stain/lighting normalization  
- Clinical: CNN fine-tuned with augmentation  
- Metadata: Logistic/XGBoost  
- Fusion: Logit-level ensemble; threshold tuned for high sensitivity  
- XAI: SHAP, LIME, Grad-CAM (global + local explanations)

## Repro (Planned)
This repo will host cleaned notebooks + figure scripts (300-dpi plotting) as I finalize journal submission.  
For now, see the paper + thesis for full details.

## Links
- **Conference:** ICCCNet 2025 – “A Robust Ensemble Deep Learning Framework for Interpretable Detection of Basal Cell Carcinoma” (8-min talk)  
- **Thesis:** Master’s dissertation (PDF)  
- Contact: hello@entrixai.com
