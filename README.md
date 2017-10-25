# Object Tracking
Object / Motion tracking in python, using background substraction algorithm.

# Made with:
- Python
- OpenCV
- Anaconda2
- ffmpeg integration (this one is crucial)

# Usage:
- Simply run the code from your IDE

- Move the sliders as follows:
  threshold = how sensitive to motion (lower values = more sensitivity)
  weight = how fast or slow the background updates (higher values = update faster, better for fast moving objects so they won't have a       "trail" when tracking)
  search range = when using single object tracking, defines the search range to update the user square, high values may lead to the user's   square moving to other objects while low values may lead to the object being lost while tracking.
  delay = simply the delay in showing the frames, lower values = less delay.
  
- press esc to exit.
  
- if you want to change a video simply enter the name of the new video in the code.
  
  ## Motion Tracking:
  - By default the algorithm tracks every movement on the screen.
  - You can control the amount of movement using the threshold trackbar.
  
  ## Object Tracking:
  - Pressing the key 'T' switches to single object tracking mode.
  - Need to select the top left and bottom right corners of the object
    in order for the program to track the object.
  - If the program has issues tracking your object you may need to change
    "search range" trackbar value.
  - Pressing the key 'C' will clear the current object selection and return
    the program to motion tracking mode.
    
Feel free to use the code and ask questions if you have any :)
