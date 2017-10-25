# Object_Tracking
Object / Motion tracking in python, using background substraction algorithm.

# Made with: (some are required to run)
- Python
- OpenCV
- Anaconda2
- ffmpeg integration

# Usage:
- Simply run the code from your IDE

- Move the sliders as follows:
  threshold = how sensitive to motion (lower values = more sensitivity)
  weight = how fast or slow the background updates (higher values = update faster, better for fast moving objects so they won't have a    "trail" when tracking)
  search range = when using single object tracking, defines the search range to update the user square, high values may lead to the user's square moving to other objects while low values may lead to the object being lost while tracking.
  delay = simply the delay in showing the frames, lower values = less delay.
  
  - press esc to exit.
  
  - if you want to change a video simply enter the name of the new video in the code.
  
  # Motion Tracking:
  - By default the algorithm tracks every movement on the screen.
  
  --- TO BE CONTINUED...
