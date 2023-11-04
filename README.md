# **Human Eye Pupil Tracking in video using YOLOv8 Segmentation model**
---

# **Introduction**
<p align="justify">
Image segmentation, also known as object segmentation, is the process of assigning a class to each pixel value in a picture. Semantic segmentation of faces can assist computer vision systems in accomplishing tasks such as age recognition, gender and ethnicity prediction, and expression recognition. These tasks are made possible by semantic segmentation, which divides facial regions into key features including the mouth, chin, nose, eyes, and hair.
<p align="justify">
Only the classes in the image will allow us to construct a bounding box through the application of Object Detection models. However, as the enclosing boxes are square or rectangular in shape, it will not reveal anything about the object's shape. Since image segmentation will provide pixel-by-pixel masks for every object, it will be helpful to comprehend the object's finer details.

<p align="justify">
  
**Semantic segmentation** : Semantic Segmentation is the process of assigning a label to every pixel in the image. This is in stark contrast to classification, where a single label is assigned to the entire picture. Semantic segmentation treats multiple objects of the same class as a single entity.
<p align="justify">
Metrics for evaluation:
Intersection over Union (IoU approach): The IoU metric divides the total number of pixels contained in both the target and prediction masks by the number of pixels shared between them.

# **Methods**

The IR camera photos of eye pupils taken from various angles are included in the dataset I utilized for this study. The collection consists of 15 distinct personalities' eye pupil pictures.  

---
<img src=""  width="500" height="500" align="centre" />


We used the Computer Vision Annotation Tool (CVAT) to create annotated images, which are displayed on the CVAT user console, in order to train the YOLOv8 semantic segmentation model.  

---
<img src="" width="500" height="500" align="centre" />

