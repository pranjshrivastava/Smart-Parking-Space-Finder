# Smart-Parking-Space-Finder

# Problem Statement:
The project aimed to solve the problem of finding empty parking spaces in the university
parking area. As the parking area is large, it becomes tough to know which spots are empty and
which are not, as all the spots are not visible from the entry of the parking.

# Objective:
The objective is to develop an AI model that can detect empty parking spaces from aerial
imagery generated through drones that are equipped with a camera.
We use a Mask RCNN model.

# DATASET :
This is the set of images that is used for training the model.
Here we have taken a number of images of aerial view of parking areas for the dataset.
We have annotated the images i.e. we have marked the empty parking spaces, so that the model
can learn what to detect. For the annotation, we have used an online tool called Makesense.ai

#Libraries:
1. Torchvision : This is the Computer Vision framework, PyTorch, that is used by the model
2. detecto : This is the framework for the AI model, it is based on Mask RCNN.
3. Ffmpeg-python : This is the library that helps us to take video and divide it into images by
defining the time and width of division. This will be used in the step where we divide our input
video.
4. Matplotlib and Pillow : These libraries are used for viewing, resizing images in the further
steps.
5. Moviepy : This Library helps use to stitch images together in order to generate output video.
