# Detecting-Cancer-in-gigapixel-images

YouTube link explaining the project: https://youtu.be/lJiIA2_Dxz8


Cancer is one of the deadliest diseases that has started conquering and spreading across the world. It becomes more and more important to detect this disease so that the cure and medication can begin. 

The goal of this project is to develop a model that can access gigapixel images and detect the cancerous cells.

Part 1:
In the first part, we are given 21 slides from the starter code. I will be generating over a 1000 images from these slides. 
How is this done?
Firstly, I have cleaned and preprocessed the data.
Secondly, I have randomly selected an image area which is (500,500).
I select that area. This area is then tested. If the tissue is more than 60%, then I have saved the image and its corresponding mask to another folder. 

Part 2:
In this part I have created a model. I have used transfer learning (Inception). 
Thus, I have computed a model that can decode the vectors and create the heatmaps.


# Results:
Validation Accuracy achieved: 94.71%
