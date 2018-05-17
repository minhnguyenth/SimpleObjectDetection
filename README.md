# Simple Object Detection And Tracking Without Color
- Extract every 2 sequential images of the video
- Convert them to gray scale images
- Subtract these 2 images to find foreground, output a difference image
- Threshold the difference image to get the binary version of it
- Find contours from the image
- Keep only the largest contours under a very simple assumption that this is the object we are tracking (!)
- Find centroid of the object and mark it on the frame

Code reference: http://anikettatipamula.blogspot.ro/2012/12/ball-tracking-detection-using-opencv.html
  
