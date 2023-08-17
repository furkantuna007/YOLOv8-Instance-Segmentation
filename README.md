# YOLOv8-Instance-Segmentation - Fruit Detection

Aim of the project is to apply Instance Segmentation using new version of You Only Look Once (YOLOv8) algorithm to classify three different fruit types: Watermelon, blackberry and pineapple. The images has been selected randomly from internet, it has 20 photos for each of the classes. I have applied data augmentation to these 60 photos in order to create a larger dataset as well as improve the robustness of the model. I have selected 80/20 ratio for train and validation sets and test the model later. In order not to spoil the accuracy of the model, we avoided some applications such as graying the photo while applying data augmentation. The labeling done using Roboflow and this dataset also can be found at Roboflow Universe. <a href="https://universe.roboflow.com/furkan-tuna-vrcvi/yolov8-firsttry/model/">
    <img src="https://app.roboflow.com/images/try-model-badge.svg"></img>
</a>
<img width="603" alt="Screenshot 2023-08-17 at 12 24 52" src="https://github.com/furkantuna007/YOLOv8-Instance-Segmentation/assets/72814790/0651edd3-8910-45f1-a875-efaffd437437">

General score values of the model:
<img width="1574" alt="Screenshot 2023-08-17 at 12 25 24" src="https://github.com/furkantuna007/YOLOv8-Instance-Segmentation/assets/72814790/629f71b6-1ec3-4da6-a9d5-24a184755430">

Couple of test images with labels:

<img width="450" alt="Screenshot 2023-08-17 at 12 26 15" src="https://github.com/furkantuna007/YOLOv8-Instance-Segmentation/assets/72814790/c963d512-88c3-40a2-966f-591d1659c906">
<img width="911" alt="Screenshot 2023-08-17 at 12 26 30" src="https://github.com/furkantuna007/YOLOv8-Instance-Segmentation/assets/72814790/d65d297a-3462-4c89-afd7-4c65dfa41fbc">
<img width="466" alt="Screenshot 2023-08-17 at 12 27 05" src="https://github.com/furkantuna007/YOLOv8-Instance-Segmentation/assets/72814790/a2ac6c09-fdca-4ef6-8935-4c81987517b5">


