# Machine-Learning-Mouse-Annotations-Project

This project aims to train a model to localize the mice in the video. Mouse locations are first annotated using DeepLabCut tool. DeepLabCut is an open-source toolkit for marker less pose estimation of animals. It is based on Convolutional Pose Machines and uses deep learning to estimate the 3D positions of body landmarks from 2D images. The toolkit can be used to automatically annotate images for a variety of tasks, including tracking the movement of animals, monitoring behaviour, and studying biomechanics. 
DeepLabCut tool is used to make 7 joints: “nose”, “left ear”, “right ear”, “left hip”, “right hip”, “tail base”, “tail end”. It is also used to mark 2 corners, “left top” and “right bottom” of the bounding box. The mouse is inside the bounding box constructed from 2 corner point.
Finally, a neural network is used to predict the mouse location.
