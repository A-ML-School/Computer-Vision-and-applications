# Computer-Vision-
Computer Vision Basics


In this section, we will explore a brief intro to computer vision, how computer vision can be applied to solve real-world problems, how you can create computer vision applications with AWS DeepLens, finally, we'll walk through an example DeepLens project.

Computer vision enables machines to detect patterns and gain a high level understanding of images and videos. With computer vision, we can increase our productivity, augment our creativity, and even solve problems better than humans can.

One of the most prominent uses of computer vision is in self-driving cars.
Next, we'll go into how computers are able to do this today and the applications of this technology.

First, a little history on computer vision.
How would you teach your computer to identify a deer?
You might zero in on the eyes,the nose, or the ears. Early applications of computer vision needed hand-annotated images to successfully train a model.

Traditionally, this is how computer vision was done, someone would manually code a rule to detect the eyes pattern, ears, put it together in a certain way and you get a bear.
But this is brittle.What if the bear is walking instead of sitting? What if the deer's face is not known?
Pretty soon, we'll have to code thousands, if not millions of rules. These early applications had limited applications because of the human labor required to annotate images.
Due to these constraints,computer vision was limited in its applications.

Next, we'll take a look at how deep learning impacts computer vision.To overcome these challenges, modern applications in computer vision used neural networks.
Neural networks are made up of layers: input layer, hidden layers, and output layer.
Three main components of neural networks
Input Layer: This layer receives data during training and when inference is performed after the model has been trained.
Hidden Layer: This layer finds important features in the input data that have predictive power based on the labels provided during training.
Output Layer: This layer generates the output or prediction of your model.

The input layer receives the data. Hidden layers find important features in the input data that have predictive power. Output layer is where the result is generated.
With deep learning, instead of manually coding rules,we can feed in a lot of data and havea machine learning model learn the rules for prediction.

In practice how this works,is that deep learning models are made up of a lot of layers that can be updated based on the data. Each layer extracts different information about the image. The first few layers extract basic patterns in the image, such as edges. The next layer might extract details around texture on the polar bear's fur. Finally, over multiple layers, we have a high level map of the unique features.

This high level mapping of features is then pass it to a final layer to determine if there is a polar bear in the image.

Now that you have a sense for how computer vision with deep learning works, the use cases of computer vision.
computer vision can be applied to automate any visual inspection process that once required human eyes. Computer vision can even perform some task better than humans, such as searching through millions of images.
Let's look at how you would apply computer vision towards the use cases mentioned before.

In the field of computer vision, we need to frame the problems in term of task that we're asking the computer to do.We will go deeper into these popular tasks so you can get a sense of what's possible. The most common tasks we ask computers to do is to group images based on some pattern and this could be sorting objects, detecting characters from an image, or even doing content moderation and this called as image classification.

The questions we want to answer with image classification are -what is in it's image and does this image contain what we're looking for.

Prior to machine learning, these tasks typically involve humans manually moderating or looking at images.With image classification, computers can enable humans to be much more productive. Sometimes knowing if an image contains something isn't enough. We want to know where in the image the object of interest is.
As you can see, one of the real-time application for computer vision is autonomous vehicles. For a vehicle to be truly autonomous, it needs to understand the surroundings. We call this task object detection. Object detection answers the question, where in this image are the objects of interests?
Object detection can extend beyond just knowing where something is located. For example, object detection can be used to count how many cars are in a parking lot or how many people shop at a store. More broadly, object detection can also be used to return anchors or landmark points in an image. For example, your favorite photo filter apps rely on object detection to know where your eyes, nose, and mouth are, so apps could fit digital mask to your face. There are use cases where knowing where an object is is not enough.
We want to know more granular information, such as which pixels in an image represent our object of interest. For example, for maps, we want to indicate which region of a satellite image corresponds to a building versus a road. In biology, we want to know which blobs in an image represents cells or parts of cells. It turns out computers are well-suited to these tasks and can exceed human performance.
For these applications, we rely on a task called segmentation. Segmentation tells us the pixel level detail of where an object is in an image. So far, we've talked mainly about computer vision applied to images.

But computer vision is also really helpful for videos. Videos add a time dimension to our image data, allowing machines to detect things that occur over many image frames.
This is really useful for analyzing sports movements and helping us understand the activity demonstrated in a scene.
We can call these tasks activity recognition.




