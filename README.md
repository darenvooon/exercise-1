# Discussion
# exercise-1- Question 1
The Python script creates a single box with increasing size from left to right in Blender. It sets up two variables, size and spacing, to determine the initial size of the box and the distance between the centers of each box. The script then creates the box using bpy.ops.mesh.primitive_cube_add() and sets its size and location parameters to (size, size, size) and (0, 0, 0), respectively. The size of the box is then increased to (2*size, 2*size, 2*size) using bpy.ops.transform.resize() and moved to the right by a distance of spacing using bpy.ops.transform.translate(). Finally, the size of the box is increased again by 1.0 and set to (3*size, 3*size, 3*size) using bpy.ops.transform.resize(). The end result is a single box with increasing size arranged horizontally from left to right.

# exercise-1- Question 2
This Python script creates three boxes in Blender with increasing size from left to right. It does this by first setting up two variables, size and spacing, which determine the initial size of the first box and the distance between the centers of each box, respectively. 
The script then uses a for loop to create three boxes, with the size and location parameters of each box set to the current size and position.
After each box is created, the script increments size by 1.0 and updates the location parameter to move each new box to the right of the previous one. 
The end result is three boxes with increasing size arranged horizontally from left to right.
