# Number Plate Detection and Censoring

A CNN model trained by transferring learning from YOLOv5 developed by Ultralytics on 440 images of cars alongwith annotations of their numberplates over 100 epochs. It recognizes and censors numberplates in images in order to protect the identities of the original owners of the cars.

## Accuracy

* Final Precision = 0.916
* Final Recall = 0.92
* Final MAP = 0.918
* Best MAP = 0.936 (Epoch 41)
* Best Precision = 0.931 (Epoch 41)
* Best Recall = 0.909 (Epoch 28)

## Tools used:
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)

## Links

* [Dataset Link](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection)
* [YOLOv5 GitHub Repo](https://github.com/ultralytics/yolov5)
