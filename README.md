# Draggable-Image-Slider
This JavaScript-based image slider allows users to scroll through images by dragging or clicking arrow icons.
The slider features smooth transitions and automatically adjusts based on user interactions.

# Key Features:
Drag-to-Slide: Users can click and drag to scroll through images horizontally.
Arrow Controls: Left and right arrow icons enable navigation between images.
Auto-Slide Adjustment: The slider automatically adjusts the position after dragging, snapping to the nearest image.
Responsive Design: The slider works with touch inputs for mobile devices.

# How It Works:
DOM Interaction: The code selects and manipulates DOM elements like the image carousel and arrow icons.
Draggable Events: Mouse and touch events are used to enable dragging and calculate the scroll distance.
Arrow Navigation: Clicking the arrows shifts the images left or right based on the image width and adjusts the icons' visibility accordingly.
Auto Slide: After dragging, the slider automatically snaps to the closest image for a seamless user experience.

# Event Listeners:
mousedown / touchstart: Begins the dragging motion.
mousemove / touchmove: Handles dragging and updates the scroll position.
mouseup / touchend: Stops dragging and triggers the auto-slide adjustment.
Click events on arrow icons to scroll through images.
