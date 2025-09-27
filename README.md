# Image-Classification-CNN-vs-Random-Forest-vs-SVM
This project looks into image classification by comparing deep learning with more traditional machine learning methods. A Convolutional Neural Network (CNN) is trained alongside Random Forest and SVM models, and their results are measured using accuracy and F1-scores. To make the comparison clear, the notebook also shows confusion matrices and classification reports.

## What’s included
- **Notebook**: End‑to‑end training & evaluation pipeline
- **Models**: CNN (Keras), Random Forest & SVM (scikit-learn)
- **Metrics**: Accuracy, F1-score, classification report, confusion matrix
- **Saves models** using `pickle`/`joblib`

## How to run (Colab)
1. Open Google Colab.
2. Mount Google Drive if your dataset is there.
3. Update the dataset path in the cell that asks for it.
4. Run all cells (Runtime → Run all).
5. Check the printed metrics and confusion matrices at the end.

## Requirements
Check `requirements.txt`. Install locally with:
```bash
pip install -r requirements.txt
```
