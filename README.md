# Object-Recognition-Aimbot
Utilizes YOLO Darknet, CUDA, OPENCV, and Windows library to aim for user in FPS games at the target that been trained for the Neural Network

Demo:
https://cdn.discordapp.com/attachments/489642661347721216/515039976573108224/ezgif-4-c7e8efc7f2be.gif

Discontinued due to absurd computing power required to run efficiently.
GTX 1060 can barely run at 40 fps with yolo tiny weights leading to inaccurate aiming.

Current unresolved issues:
Object detector will often lose track of nearest object for a very short duration (milliseconds) and try to aim at the next detected object.
This leads glitchy aiming between multiple targets (see demo).