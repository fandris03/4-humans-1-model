# 4-humans-1-model

## Description

**Task:**

•    Object detection and classification of drone images of traffic and public areas.

•    The dataset consists of 8629 images of 10 different classes, including cars, vans and pedestrians.

•    Our goal is to investigate the model’s behaviour, analyse its mistakes, and compare the fine-tuned model with the original, general-purpose model.

**Model:**

•    a YOLO11m model finetuned on the VisDrone-DET dataset.

•    The model has 20.1M parameters, and an F1 score of 53.26%

•    the YOLO11m model was originally trained on the Common Objects in Context (COCO) dataset, comprising 80 different classes, around 9 of which are traffic- or vehicle-related

## Sources

VisDrone dataset: https://huggingface.co/datasets/Voxel51/VisDrone2019-DET

VisDrone YOLO11m HuggingFace: https://huggingface.co/dronefreak/visdrone-yolo11m

Original YOLO11m GitHub: https://github.com/ultralytics/ultralytics/tree/main

YOLO11m official website: https://docs.ultralytics.com/models/yolo11

## Research
- [https://arxiv.org/pdf/2410.22898](https://arxiv.org/pdf/2410.22898)
