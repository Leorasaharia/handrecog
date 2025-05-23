I wanted to create something immersive — where I could control virtual objects just by moving my hand in front of a webcam. No VR gloves. No controllers. Just me, my webcam, Python, and Unity.

My vision was simple:
Build a Unity scene with floating blocks that I could grab, push, or destroy using just hand gestures — like making a fist or doing a pushing motion.

I started with Python, using MediaPipe by Google. It's surprisingly powerful for tracking hand landmarks with just a webcam.

I used ** mediapipe + opencv ** to detect my hand in real time.

Each frame gave me 21 3D landmarks for my hand — fingertips, joints, palm center, etc.

![image](https://github.com/user-attachments/assets/eec53d88-d63b-47e8-a661-507bab446ee8)


I wrote logic to detect gestures:

If all my fingers were curled = fist

If my palm moved quickly forward (along the Z-axis) = push

**Real-Time Interaction**
It felt surreal to see my virtual hand mirror my actual hand — and to interact with the world by just moving in front of a webcam. No buttons. Just motion.

I could grab and destroy blocks by making a fist.

I could shove blocks away by pushing my palm forward.

It was like controlling a virtual world with magic.

![image](https://github.com/user-attachments/assets/5b67ef62-99c9-438f-971f-47b8d067c94e)


**This project taught me how natural interactions can transform the way we play and build things in virtual spaces. Combining AI-powered hand tracking with real-time 3D environments gave me a whole new perspective on intuitive interface design.

If you’re ever curious about building something like this — do it. Watching your hand control a virtual world is a kind of magic you create yourself.**
