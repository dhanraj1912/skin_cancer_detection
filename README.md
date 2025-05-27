# skin_cancer_detection
– Developed a binary image classifier for skin lesion detection (benign vs. malignant). – Used 10,000 labeled dermoscopic images from Kaggle resembling ISIC/HAM10000 datasets.
– Preprocessed data using resizing (224x224), normalization, label encoding, and augmentation.
– Used EfficientNetB0 with transfer learning and custom dense layers (ReLU, Softmax).
– Trained the model using Adam optimizer over 50 epochs; binary cross-entropy loss.
– Achieved 99% training and 93% validation accuracy; evaluated using F1-score, ROC-AUC, etc.
– Tools: Python, TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn.




Output:
<img width="381" alt="Screenshot 2025-05-27 at 6 07 22 PM" src="https://github.com/user-attachments/assets/e53187fe-79b1-4e79-8d4b-ce675814cb7b" />
