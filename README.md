Parallax Tilt Effect Theory:

The parallax tilt effect creates an illusion of depth and movement on a 2D surface by slightly rotating elements based on the user’s cursor position. This effect is often used in web design to make interfaces more interactive and visually appealing.

How It Works:
Perspective and Transformations:
The perspective property in CSS is used to give a 3D space to the elements. It defines how far the object is from the viewer.
The transform property is used to rotate the elements along the X and Y axes based on the cursor’s position.
Mouse Movement Detection:
JavaScript is used to detect the mouse movement over the elements. The position of the cursor relative to the center of the element is calculated.
These calculations are then used to set CSS variables (--rX and --rY) which control the rotation angles.
Smooth Transitions:
CSS transitions are applied to ensure the rotation happens smoothly, enhancing the visual effect.
