# Face Recognition

## Approach Taken

We have a list of known images which we have encoded using the function face_encodings() along with names of the people.
We turn on the camera and start capturing video frame by frame.
We then detect the number of faces and their position in each frame.
The known face encodings are compared with the faces detected, and if a match is made, the corresponding name is shown on the screen.

To increase the processing speed, the frames are reduced to 1/4th their size and then processed. While drawing the rectangle, the size is restored.

### Video demo
https://youtu.be/MnmIoUsJdCw


![image](https://user-images.githubusercontent.com/79102084/179277001-3e0da310-b21a-434e-a92a-022b5ab0ae6b.png)
