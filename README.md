# DroneLanding
 Semantic segmentation of aerial images taken by a drone with localization of optimal landing position.


The dataset was provided by a professor, but an equivalent version can be found at https://www.tugraz.at/index.php?id=22387.  \
The code is developed using the Keras/Tensorflow framework.

> The Semantic Drone Dataset focuses on semantic understanding of urban scenes for increasing the safety of autonomous drone flight and landing procedures. The imagery depicts  more than 20 houses from nadir (bird's eye) view acquired at an altitude of 5 to 30 meters above ground. A high resolution camera was used to acquire images at a size of 6000x4000px (24Mpx). The training set contains 400 publicly available images.

The target images contain the following 24 classes:
- tree
- grass
- vegetation
- dirt
- gravel
- rocks
- water
- paved-area
- pool
- person
- dog
- car
- bicycle
- roof
- wall
- fence
- fence-pole
- window
- door
- obstacle
- ar-marker
- conflicting
- unlabeled
- bald-tree


The **goal** is to design and train a robust model for semantic segmentation. Once the predicted masks have been generated, we want to find the optimal landing position for the drone. This is defined as the position that allows for the safest landing, prioritizing empty spots on grass or paved areas to avoid damage to objects or people.

### _Content_:
- [DroneLanding_VaccariSimone.ipynb](https://github.com/MomiQB/DroneLanding/blob/main/DroneLanding_VaccariSimone.ipynb): main notebook
