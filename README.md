# LITTER-EVALUATION-AND-MONITORING-METHOD-FOR-POULTRY-FARMING-USING-DEEP-LEARNING
This project is to propose a transfer learning-based approach for litter monitoring and classification.

**Abstract:**
In the current practice, poultry litter is evaluated manually by poultry farmers
based on their expert knowledge. Nevertheless, the judgment may lead to error,
as the observation may differ from person to person. This study proposed a
transfer learning-based approach for litter monitoring and classification. The
proposed approach is applied to three high-performance pre-trained deep
learning methods, namely YOLOv3, YOLOv4, and SSD. These methods were
chosen due to their efficiency in real-time applications, and are popularly used
in various object detections and classifications. Experimented on 1294 poultry
litter images collected from two cameras and two different bedding materials:
rice husk and sawdust, the efficacy of the algorithms in classifying the amount
of litter into two classes, namely less than 50% or more than 50% of the total
bedding area in an image, is demonstrated. The experimental results showed
that all the deep learning methods produced an excellent performance with an
accuracy greater than 90% using the selected hyperparameters. It is also found
that YOLOv4 outperformed YOLOv3 and SSD in classifying images of poultry
litter, by achieving the maximum accuracy of 97.17%.

**The model folder in this repository contains the 3 custom model training files:** 
1. YOLOv3
2. YOLOv4
3. SSD

In each model's file, it consisted of modified configuration file, custom jupyter notebook file for training and other necessary files.

**The process involved:**
1. Gather the poultry litter dataset.
2. Labelling the dataset based on classes using Roboflow tool.
3. Export dataset based on model (YOLO used XML format while SSD used Pascal-VOC format).
4. Split dataset into training, validation and testing sets with 70%, 10% and 20%, respectively.
5. Download pre-trained model.
6. Run training and testing using ipynb file.
7. Evaluate model's performance using confusion matrix.

My dataset is confidential.
Any enquires can be emailed to muhammadzakiluhur@gmail.com

Thank you!
