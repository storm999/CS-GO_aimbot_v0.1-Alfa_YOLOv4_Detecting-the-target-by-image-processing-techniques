# CS-GO_aimbot_v0.1-Alfa_YOLOv4_Detecting-the-target-by-image-processing-techniques
By using Darknet project (which works with YOLOv4 algorithm), making an auto-aim bot which theoretically will work with any first person shooter video game. 

This work is just a trying yet. Therefore, I called it version 'alfa'.
So many more things should be done in order to make it working properly. 

I uploaded only the file that i edited for doing things you may see in the videos I uploaded.

[<img src="https://img.youtube.com/vi/f5V_xxHn5fM/maxresdefault.jpg" width="50%">](https://youtu.be/f5V_xxHn5fM)
[<img src="https://img.youtube.com/vi/GM9wrz9FDiA/maxresdefault.jpg" width="50%">](https://youtu.be/GM9wrz9FDiA)


I just used person detection ability of Darknet project which was trained by default. Darknet project detects 80 objects in total. Basically rest 79 objects are being detected although they are not used. This just reduces performance obviously.
Therefore, training your own model which will detect only person is a must for better performance. 
Creating your own model requires very good GPU, a lot of time for both downloading or uploading and training. So, I couldn't achieve it. 
Detection reaches 10 fps on a laptop has got gtx1070m and 7700HQ. When game is not running, it reaches 15 fps.

SETUP
Prerequisites: everything that is needed for setting Darknet project up.
Some of them are:
nVidia Cuda, OpenCv, cMake etc. You may find many tutorials about how to install Darknet project.
