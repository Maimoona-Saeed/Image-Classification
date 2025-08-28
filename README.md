# Image Classification Using Deep Learning

- Models: ConvNeXt, Swin Transformer, VGG19 (transfer learning + fine-tuning), Custom CNN  
- Custom CNN Architecture: 3 Convolutional Blocks (Conv2D → BatchNorm → ReLU → MaxPool), Classification Block (Flatten → Dense → Dropout → Dense → Dropout → Output Softmax)  
- Framework: TensorFlow 2.x / Keras  
- Dataset: 4 classes — Cloudy, Desert, Green Area, Water  
- Data Split: Train 70%, Validation 15%, Test 15%  
- Training: 10 epochs per model, batch size 32, optimizer Adam (lr=1e-4), loss categorical_crossentropy  
- Metrics: Accuracy, Precision, Recall (Sensitivity), Specificity, F1-Score  
- Data Handling: Data augmentation (flip, rotation, zoom, brightness), oversampling if imbalance observed  
- Evaluation & Visualization: Accuracy and loss curves (train/validation/test), confusion matrix, per-class and overall metrics  
- Outputs: Best model checkpoints, logs, evaluation plots, final weights  
