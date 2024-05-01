# AI-Face-Body-and-Hand-Pose-Detection
In this project we will able to detect our face, eyebrows, lips and our hand poses along with different joints 
 
What’s covered in the project
1.	Setting up Media Pipe
It includes model like media pipe holistic which further includes three different models
A) One to detect facial landmarks 
B) One to detects joints of our hand
C) One to detect the poses in our body
2.	Detecting poses, facial landmarks and dual hand poses.
3.	Visualizing detections to the screen
When we use OpenCV we use get a feed in BGR and when we passed it in our holistic model we want
The color to be in RGB 
 
What we have done in the project
1.	First we have installed the models and import the dependencies for the mediapipe and OpenCV
2.	Then we have setup our drawing utilities i.e. mp_drawing and mp_holistic .
3.	In this we have 4 different models in the media holistic. A) Face landmarks B) Right-hand components C)  Left-hand components D) Pose detection 
4.	After this we have done the styling using mp_drwaing.landmarks which contains four parameters in it two of them are landmark_drawing_spec are used for joints or dots, connection_drwaing_spec is used for lines which connects the dots.
 
