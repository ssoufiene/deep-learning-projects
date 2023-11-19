# Deep Learning
This repo contains deep learning model’s implementation and other Computer Vision projects that I’ve worked on the last couple of months.

**Projects** :
| Project      | Descripiton      | Links        |
| ------------- | ---------------- | ---------------------------------|
| Sartorius Cell Segmentation   |For segmentation i used Detectorn 2 , the first step was converting the RLE-formated data to COCO. I used k_cross validation and implemented custom trainer object for the mAP evaluator.    | [Link](Cells_Segmentation_with_Detectron_2.ipynb)|
| Car Damage Detection and Classification with YOLOV8 and Gradio |Employed YOLOv8, for the Detection and classification of car damages. The model was trained on [CarDD](https://arxiv.org/abs/2211.00945) dataset, since the dataset was big , I only trained for 30 epochs and used cosine lr scheduler for fine_tuning, then i built a simple [gradio app](car_damage_detection/gradio.ipynb) for the model.        | [Model's Code](car_damage_detection/Car(2).ipynb)          [Model's weights](car_damage_detection/model_weights/best.pt)                                         [Gradio code](car_damage_detection/gradio.ipynb)|


**Models** : 
| Model         | Descripiton      | Link to Code           |
| ------------- | ---------------- | ---------------------------------|
| AlexNet       |Implementation in  Pytorch          | [Link](AlexNet(1).ipynb)|
| VGG19        |Implemntation in  PyTorch         | [Link](VGG19.ipynb)|
| ResNet       |Implementation in  Pytorch          | [Link](Resnet(2).ipynb)|
| SAM          | Zero shot instance segmentation    | [Link](SAM(1).ipynb)
| Detectron2     | Smoke detection     | [Link](Smoke_detection_with_Detectron_2.ipynb)



