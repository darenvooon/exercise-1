# exercise-1- Question 1
import bpy

# create a new cube mesh
mesh = bpy.data.meshes.new("Cube")

# define the cube vertices and faces
vertices = [(1, 1, 1), (1, -1, 1), (-1, -1, 1), (-1, 1, 1), (1, 1, -1), (1, -1, -1), (-1, -1, -1), (-1, 1, -1)]
faces = [(0, 1, 2, 3), (4, 7, 6, 5), (0, 4, 5, 1), (1, 5, 6, 2), (2, 6, 7, 3), (4, 0, 3, 7)]

# create the cube object
object = bpy.data.objects.new("Cube", mesh)

# add the object to the scene
scene = bpy.context.scene
scene.collection.objects.link(object)

# set the object's vertices and faces
mesh.from_pydata(vertices, [], faces)
mesh.update()
