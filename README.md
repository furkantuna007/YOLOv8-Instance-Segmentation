# YOLOv8-Instance-Segmentation - Fruit Detection

Aim of the project is to apply Instance Segmentation using new version of You Only Look Once (YOLOv8) algorithm to classify three different fruit types: Watermelon, blackberry and pineapple. The images has been selected randomly from internet, it has 20 photos for each of the classes. I have applied data augmentation to these 60 photos in order to create a larger dataset as well as improve the robustness of the model. I have selected 80/20 ratio for train and validation sets and test the model later. In order not to spoil the accuracy of the model, we avoided some applications such as graying the photo while applying data augmentation. The labeling done using Roboflow and this dataset also can be found at Roboflow Universe. <a href="https://universe.roboflow.com/furkan-tuna-vrcvi/yolov8-firsttry/model/">
    <img src="https://app.roboflow.com/images/try-model-badge.svg"></img>
</a>
