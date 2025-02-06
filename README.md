
#TrOCR Text Recognition for Cyrillic Handwriting

This project focuses on fine-tuning Microsoft's TrOCR (Transformer-based Optical Character Recognition) model to recognize handwritten Cyrillic text. The approach involves freezing early layers of the model and retraining it on a specialized dataset to improve accuracy for handwritten text in the Cyrillic script.


## Features

- Pretrained TrOCR Model: Based on [Microsoft's TrOCR](https://huggingface.co/microsoft/trocr-base-stage1) architecture for OCR tasks.
- Layer Freezing: Only retraining higher layers to preserve general text recognition capabilities while adapting to Cyrillic handwriting.
- Dataset Fine-Tuning: Trained on a [dataset](https://www.kaggle.com/datasets/constantinwerner/cyrillic-handwriting-dataset) of handwritten Cyrillic text samples.
- Efficient Training: Reducing training time and computational cost by leveraging transfer learning.

