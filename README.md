# Interactive_facial_keypoint_WebApp 
This was implemented with  Py Torch TorchVision as this is a small project. 
I implemented this using Naimish Net architecture. I did modify the top softmax layer which had pairs of (x,y) euclidian distance into 1D array. 
The web app calls the model upon getting the Face; The image goes through Flask wrapper and updates the Face with facial key points
This is a supervised learning , as I trained the model with True keypoints and with celebrity faces .
Logistic regression was used, as I had to minimikze euclidean distance between my predicted points on the face to actual keypoints.
Haar cascade algorith was used to extract face alone from any image. Please donot try with multiple faces or animal faces.The code doesnot support that yet.

You can run python server.py
which calls the Interactive web , and you provide a face and you see the model key point predicted face with the points:)
Enjoy.. 
No need for GPU, it ran on my 2015 MACOS in 1/2 hour. Inference takes less than a minute 
I will clean up the code soon so this is concise. Sorry for the in convinience
