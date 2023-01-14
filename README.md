# A basic gripper
- I have designed a URDF of a pretty basic gripper in pybullet. This gripper acts as a pick and place bot.
- Small cubes with holes inside them are loaded in the world.
- The gripper picks up a cube from its initial location and places it at some desired final location.
- In order to pick the cube, the gripper inserts a stick inside its hole. Before lifting it, it also locks the cube, so that while displacing, it doesn't fall down.
- After reaching the desired location, the gripper moves down, unlocks the cube, removes the stick, thereby placing the cube at its final position.

### In order to view the gripper's demonstration, follow these steps:
- Clone the repository using `git clone https://github.com/Somya-Bansal159/A-basic-gripper`.
- Create a virtual environment and install pybullet in it using `pip install pybullet`.
- Activate the environment and run [gripper.py](gripper.py).
- You can modify the file in order to change the cube locations and number of cubes (maximum 10).
