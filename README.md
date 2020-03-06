# Close_Eye
 Detect Close Eye

Download URL
http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2

Extract with Winrar etc.

Download URL
https://github.com/tomoemagica/Close_Eye

Place the close_eye.py file in the DFL\workspace folder.

how to use
py close_eye.py

Search for face images in the DFL\workspace\data_src\aligned folder,
Face image with closed eyes
Move to DFL\Workspace\data_src\aligned\close_eye folder.

Only the face close to the front works.
Profiles cannot be detected.

It worked fine with a 512x512 pixel face.
For a 256x256 pixel face,
Line 23 of the source code
if abs (y0-y1) <10:
You may need to change the threshold of 10.
