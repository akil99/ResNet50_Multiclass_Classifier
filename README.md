# ResNet50_Multiclass_Classifier
Building ResNet from scratch for Multi-class Classification. A Residual Network to classify 17 different classes of flower images. <br/>
Implemented using Keras with Tensorflow as backend.<br/>

**Image Dataset:** http://www.robots.ox.ac.uk/~vgg/data/flowers/17/ <br/>
*(A 17 category flower dataset with 80 images per class)*<br/>

**2 fundamental building blocks of ResNet:**<br/>
- Identity block<br/>
*Main path: Conv -> Batch_norm -> ReLU -> Conv -> Batch_norm -> skip connection -> ReLU*<br/>
*Skip connection: X*<br/>
- Convolutional block <br/>
*Main path: Conv -> Batch_norm -> ReLU -> Conv -> Batch_norm -> skip connection -> ReLU*<br/>
*Skip connection: X -> Conv -> Batch_norm* <br/>

**ResNet50 Architecture** <br/><br/>
![alt tag](https://github.com/akil99/ResNet50_Multiclass_Classifier/blob/master/ResNet50_Architecture.png)
