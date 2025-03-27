# jspro1
🎯 Objective
The purpose of this project is to create an interactive box that dynamically changes its background color based on mouse movement.

✅ Key Functionalities:
Mouse Hover Detection: Detect when the mouse pointer enters the box.

Position Analysis: Identify whether the pointer is on the left or right side of the box relative to the center.

Color Intensity Calculation:

Pointer on the left side → transition to red with increasing intensity.

Pointer on the right side → transition to black with increasing intensity.

🛠️ Technologies Used
HTML5

CSS3

JavaScript

📚 How It Works
Mouse Entry Detection:

Listens for mousemove and mouseenter events to detect when the mouse enters and moves over the box.

Position Calculation:

Calculates the mouse's X-coordinate (offsetX) relative to the box.

Divides the box into left and right sections using the center as a reference.

Dynamic Color Transition:

If the pointer is on the left side, the box smoothly transitions to shades of red based on proximity to the left.

If the pointer is on the right side, the box transitions to shades of black, darkening as the pointer moves to the right.