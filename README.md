# Cube
View my [cube creation](https://olliearrison.github.io/) made with THREE.js and Vue. 

Inspired by [demo code](https://github.com/mrdoob/three.js/blob/master/examples/webgl_buffergeometry_points.html) and [demo animation](https://threejs.org/examples/webgl_buffergeometry_points.html).

## Added features
1. Painting light onto the 3D cube using the mouse:
When you drag the mouse over the cube, I transform the screen-space position to the normalized device coordinates. Next, I set up a raycaster to take that intersection point and cast a ray within worldspace in the direction of the camera. The raycaster gathers a list of intersections in 3D space. Finally, I loop through each of the intersected points, muliplying the color attribute by (1.10, 1.05, 1.04). Using multiply creates a smooth glowing effect that leans slightly warm. 

2. Changed background color and added fog in order to reduce visual clutter.


<img width="722" height="740" alt="Screenshot 2025-09-02 at 1 36 30 PM" src="https://github.com/user-attachments/assets/eaf4ffb4-727a-4011-bfda-5944494d7816" />

<img width="718" height="671" alt="Screenshot 2025-09-02 at 1 37 35 PM" src="https://github.com/user-attachments/assets/35f86417-58bf-410f-bcd4-b46227f8cd3d" />
