# Face-Mask-Safeness-Detection
Detects all the frontal faces in the video and predicts REALTIME if the person is wearing a mask or not

Here I used Haar Cascades to detect where in the video frame ALL the faces are and then the CNN model tries to detect if that person is wearing a mask or not.
Depending on the result a bounding box is drawn accordingly.
