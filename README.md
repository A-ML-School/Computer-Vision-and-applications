# Computer-Vision-
Computer Vision Basics


In this section, we will explore a brief intro to computer vision, how computer vision can be applied to solve real-world problems, how you can create computer vision applications with AWS DeepLens, finally, we'll walk through an example DeepLens project.

Computer vision enables machines to detect patterns and gain a high level understanding of images and videos. With computer vision, we can increase our productivity, augment our creativity, and even solve problems better than humans can.

One of the most prominent uses of computer vision is in self-driving cars.
Next, we'll go into how computers are able to do this today and the applications of this technology.

First, a little history on computer vision.
How would you teach your computer to identify a  polar bear?
You might zero in on the eyes,the nose, or the ears.

Traditionally, this is how computer vision was done, someone would manually code a rule to detect the eyes pattern, ears, put it together in a certain way and you get a bear.
But this is brittle.What if the bear is walking instead of sitting? What if the bear's face is not known?
Pretty soon, we'll have to code thousands, if not millions of rules.
Due to these constraints,computer vision was limited in its applications.

Next, we'll take a look at how deep learning impacts computer vision.To overcome these challenges, modern applications in computer vision used neural networks.
Neural networks are made up of layers: input layer, hidden layers, and output layer.
The input layer receives the data. Hidden layers find important features in the input data that have predictive power. Output layer is where the result is generated.
With deep learning, instead of manually coding rules,we can feed in a lot of data and havea machine learning model learn the rules for prediction.

In practice how this works,is that deep learning models are made up of a lot of layers that can be updated based on the data. Each layer extracts different information about the image. The first few layers extract basic patterns in the image, such as edges. The next layer might extract details around texture on the polar bear's fur. Finally, over multiple layers, we have a high level map of the unique features.

This high level mapping of features is then pass it to a final layer to determine if there is a polar bear in the image.


