# Automated Myopia Diagnosis - Eagle Eye
Eagle Eye is an application that can automatically prescribe lens powers to a user
<br>
<br>
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Snellen_chart.svg" width=200>
 
# Inspiration
More than 30% of the world's population suffers from vision problem NOT including undiagnosed cases, of which there are over 1 billion
 
# Procedure
Our app is accurately able to the power of the patient's vision using computer vision (Canny Edge Detection) and focal vision/distance relationships.
 
<img src='https://turbosnu.files.wordpress.com/2016/01/screenshot.jpg' width=600>  
 
# Step 1
First, the user calibrates the app to their phone's camera. The app then accurately displays the distance the user is from an object and makes them walk 5 feet away. 
 
Calibration - finds the focal length of the camera
<br>
<br>
<img src="https://render.githubusercontent.com/render/math?math=\FocalLength = \frac{(Pixel Width \cdot DistanceToObject)}{ObjectWidth}\]">
<br>
<img src="https://render.githubusercontent.com/render/math?math=\Distance = \frac{(Focal Length \cdot Object Width)}{Pixel Width}\]">
 
# Step 2
Next, the app allows the user to adjust the level of blur on the object.
 
# Step 3
Once the level of blur displayed on the screen matches with what the user sees in real life, our app maps the blur level to a corresponding optical vision power (20/20, 20/50, etc.) to provide an approximation of the level of their vision.
 

