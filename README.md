# drone-dataset
Drone dataset to lock on enemy drones

This dataset prepared for academical and competition purpose.The main idea of this dataset is to guide our drone to other drones.The dataset includes ~1400 drone images and label files.The labes files are in format of both .txt and .xml.So, You can use it with Tensorflow, Darknet and PyTorch too.Most of images taken from Google and Yandex's image search toolbox.The other images are croped from drone videos that I downloaded from Youtube.The results are very good.(will be updated)


Here is the [link](https://www.kaggle.com/dasmehdixtr/drone-dataset-uav) of dataset

# Some Results

## Bonus-1
The xmlparser is written to solve a issue that occured in labelimg.When I labeled photos with LabelImg, There was no problem firstly.Then,When I changed the path of images(and format of images like jpg or png) the xml files become a problem.Because the path in the label xml file and the image path looks diffrent.So, Instead of label the photos again, @kubilaysalih write a script to change the path in the label xml files, so easyly we can train our images in every PC.


## Bonus-2

I also added a python script(txt_path_generator_yolo) to write the path of images in a txt file to train YOLO-v3.
