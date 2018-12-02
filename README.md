# Art-Classification
A DCNN that uses transfer learning to classify images into certain categories.

#To-Do
<ol>
  <li>Hyperparameter tuning on Resnet Architecture. </li>
  <li>Transfer Learning using VGG-16.</li>
</ol>

Dataset link
<ol>
  <li>Training - https://drive.google.com/open?id=1bWhQO4SxzPKz40vxmVOdZKji7yk0eyFd</li>
  <li>Validation - https://drive.google.com/open?id=1Noc3RI2vhheLxzmioP0w1rQDV0C2LxMa</li>
</ol>


How to add conv layers
<ol>
  <li>https://github.com/TheShadow29/FAI-notes/blob/master/notebooks/Using-Pretrained-Pytorch-Models.ipynb</li>
</ol>

art_classification(ResHalf)

<ol>
  <li>
    Batch Size = 4
  </li>
  <li>
    Number of layers freezed = 7
  </li>
  <li>
    Optimizer used -  SGD 
  </li>
 </ol>
 
<b>Project documentation link:</b>
<ol>
  <li> https://docs.google.com/document/d/1posEq02ciGDCIuzvmX1JeN76S2UQmPZDqPVt5UagC9s/edit?usp=sharing </li>
</ol>

<b> Accuracies on freezing layers</b>
<ol>
  <li>All layer freeze: art_classification_all_layer_freeze.ipythn <br/>
   Training complete in 14m 31s<br/>
   Best val Acc: 0.885514</li>
<ol>
