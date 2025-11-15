# 3D-Render-Using-Java
A small 3D software renderer written in pure Java, inspired by and built by following the excellent work of Rogach.
This project renders a rotating 3D object entirely on the CPU using only Java’s standard libraries — no OpenGL, LWJGL, or external engines.

› Features:
• Pure Java software rasterizer
• Triangle drawing with barycentric coordinates
• Z-buffer depth handling
• Flat shading using face normals
• Mesh subdivision (“inflation”) to create smoother shapes

› Mouse controls:
• Left drag → rotate
• Middle drag → pan
• Mouse wheel → zoom

› Faint static background grid (like Blender)

› Simple and educational code structure

› How It Works:
The renderer transforms 3D vertices using rotation matrices, rasterizes triangles into a BufferedImage, shades them using normals, and writes pixels manually. Everything is done on the CPU, making the project great for learning how rendering works internally before using a real graphics API.

› Credits:
Huge thanks to Rogach, whose original software renderer tutorial served as the foundation and inspiration for this project.
