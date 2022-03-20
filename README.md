# Environmental-Standard-Computation-and-Quality-Analysis
Web-based project "Environmental-Standard-Computation-and-Quality-Analysis" 
[Link to Full Project](https://drive.google.com/drive/folders/1uvND3FVsvQlsGh7CZ0HcN6okUqvv-DDW?usp=sharing)
![alt text](https://github.com/wanibhavesh/flask-Go-Green/blob/master/Code/static/gogreen_login.png)

### Developer
- Bhavesh Wani
- Shreyas Fegade
- Vaibhav Chaudhari
- Pavan Datkar

### ABSTRACT
In this century, every government in the world is more concern about forest degradation and deforestation. Nowadays, the world population is increasing at a rapid rate. There are many countries which are economically developed but suffering from adverse effects of pollution. So, it has become essential for growing a sufficient number of trees for feeding oxygen to such a huge population. But with the time passing by, due to deforestation, the oxygen level is depleting to a great extent. As trees are the most important source of oxygen, so there is a need to keep a track of the number of trees in a particular area. A manual survey of tracking trees is practically impossible and costly. In this proposed approach, the web-based software is developed to count the number of trees in a particular area of town. The detection and counting of trees are done using TensorFlow Object Detection API to train dataset of Google Earth Image using Faster Region Convolutional Neural Network (Faster-RCNN). This technique will save a large amount of manual work for monitoring/counting number of trees. The second module is sky detection and analyse the quality of it. As there are number of pollutants present in the air, this algorithm can predict the quality of sky from the trained dataset model (Transfer Learning Inception V3 using Keras). The third module is the vehicle detection and pollution tracking. This module will help in estimating the pollution generated in an area due to vehicles. The dataset for vehicles is trained using the YoloV3 object detection model. 
Keywords: Deep Learning, Flask, Object Detection API, TensorFlow, Faster RCNN, Google Earth Images, Computer Vision, Transfer Learning Inception V3, YoloV3.


### Sqlite3
python
from app import db
db.create_all()

sqlite3 db.db
.tables
.quit
