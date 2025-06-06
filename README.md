There are multiple files in this directory:

ac_system.c --> Computations of modeling for EZ Aquarii Inner Binary Stars motion (EZ Aquarii A & C)
ac_system.py --> 3D Animation of EZ Aquarii A & C orbital motion


ez_aquarii.c --> Computations of modeling for full EZ Aquarii Star System motion (EZ Aquarii A, B, C)
ez_aquarii.py --> 3D Animation of full star system orbital motion


Makefile --> Compilation of ac_system.c and ez_aquarii.c

script.sh --> Execution of ac_system.py and ez_aquarii.py


**Compiling and Executing for just A-C System**

In order to compile this code, type this into the terminal:

make ac-system


In order to execute this code and view the data and animations, type this into the terminal:

chmod +x ac_system.py

./ac_system.py

This will result in the data for this simulation consisting of EZ Aquarii A and C's position and velocity and different timesteps, located in ac_output.txt, and then the animation of the orbital motion of the system in ac_system_animate.gif


**Compiling and Executing for full EZ Aquarii System** ***Similar process to above***

In order to compile this code, type this into the terminal:

make ez-aquarii

In order to execute this code and view the data and animations, type this into the terminal:

chmod +x ez_aquarii.py

./ez_aquarii.py

This will result in the data for this simulation consisting of EZ Aquarii A, B, C's position and velocity and different timesteps, located in ez_aquarii_output.txt, and then the 3d animation of the orbital motion of the system in ez_aquarii_animation.gif, and then the overhead 2d animation of its motion in ez_aquarii_2d_animation.gif.


**Compiling and Executing for Both**

In order to compile, type this into the terminal:

make

In order to execute this code and view the data and animations, type this into the terminal:

chmod +x script.sh

./script.sh

This will result in the data for full EZ Aquarii A, B, C simulation listed in position and velocity and different timesteps, located in ez_aquarii_output.txt, and then the 3d animation of the orbital motion of the system in ez_aquarii_animation.gif, and then the overhead 2d animation of its motion in ez_aquarii_2d_animation.gif. Additionally, the same for just EZ Aquarii A and C will be in ac_output.txt and ac_system_animate.gif, respectively.
