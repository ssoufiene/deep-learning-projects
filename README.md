# Deep_Learning
This repo contains some models impelmentations and some projects.

**Projects**
| Project      | Descripiton      | Links        |
| ------------- | ---------------- | ---------------------------------|
| [Sartorius Cell Segmentation](Cells_Segmentation_with_Detectron_2.ipynb)   |For segmentation i used Detectorn 2 , the first step was converting the RLE-formated data to COCO. I used k_cross validation and implmented custom trainner object for the maP evaluator.    | [Link](Cells_Segmentation_with_Detectron_2.ipynb)|
| [Car Damage Detection and Classification with YOLOV8 and Gradio](Car(2).ipynb)  |employed YOLOv8, for the identification and classification of car damages. The model was trained on [CarDD](https://arxiv.org/abs/2211.00945) dataset, since the dataset was big , I only trained for 30 epochs and used cosine lr scheduler for fine_tuning, then i built a simple [gradio app](gradio.ipynb) for the model        | [Model's Code](Car(2).ipynb)          [Model's weights](best.pt)                                                                                                        [Gradio code](gradio.ipynb)|


**Models** : 
| Model         | Descripiton      | Link to Code           |
| ------------- | ---------------- | ---------------------------------|
| AlexNet       |Implementation in  Pytorch          | [Link](AlexNet(1).ipynb)|
| VGG19        |Implemntation in  PyTorch         | [Link](VGG19.ipynb)|
| ResNet       |Implementation in  Pytorch          | [Link](Resnet(2).ipynb)|
| SAM          | Zero shot instance segmentation    | [Link](SAM(1).ipynb)
| Detectron2     | Smoke detection     | [Link](Smoke_detection_with_Detectron_2.ipynb)



