# Pineapple Detection on Pizza 🍍🍕
Detect the presence of pineapple on pizza.

## Dataset
The training dataset consists of approximately 60 images of pineapple pizzas, with 20 unaugmented images.  
The validation set contains 4 images.  
Each image is annotated with bounding boxes to indicate the pineapple's location.

## Training Process
Training was conducted using **Detectron2** with an **X101-FPN** backbone pre-trained on COCO.  
The training process closely follows the official Detectron2 guide with minor modifications.  
The model was trained for 3000 iterations over the course of 10-15 minutes.

## Results
The model is good, not perfect tho, it doesnt detect all pineapples and sometimes it detect non-pineapples, it is probably caused by small dataset and high variance of pineapples
| | | | |
|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="500" alt="screen shot 2017-08-07 at 12 18 15 pm" src="results\image1.jpg?raw=true">|<img width="500" alt="screen shot 2017-08-07 at 12 18 15 pm" src="results\image2.jpg?raw=true">|<img width="500" alt="screen shot 2017-08-07 at 12 18 15 pm" src="results\image3.jpg?raw=true">|<img width="500" alt="screen shot 2017-08-07 at 12 18 15 pm" src="results\image4.jpg?raw=true">|