# Pineapple Detection on Pizza 🍍🍕
Detect the presence of pineapple on pizza.

## Dataset
The training dataset consists of approximately 60 images of pineapple pizzas, with 20 unaugmented images.  
The validation set contains 4 images.  
Each image is annotated with bounding boxes to indicate the pineapple's location.

## Training Process
Training was conducted using **Detectron2** and **X101-FPN** as a pretrained base.  
The training process closely follows the official Detectron2 guide with minor modifications.  
The model was trained for 3000 iterations over the course of 10-15 minutes.

## Results
The model performs well overall, but it's not perfect. It sometimes misses pineapples or detects non-pineapple objects. This is likely due to the limited size of the dataset and the high variance in how pineapples appear across different images.
| | | | |
|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="500" alt="screen shot 2017-08-07 at 12 18 15 pm" src="results\image1.jpg?raw=true">|<img width="500" alt="screen shot 2017-08-07 at 12 18 15 pm" src="results\image2.jpg?raw=true">|<img width="500" alt="screen shot 2017-08-07 at 12 18 15 pm" src="results\image3.jpg?raw=true">|<img width="500" alt="screen shot 2017-08-07 at 12 18 15 pm" src="results\image4.jpg?raw=true">|