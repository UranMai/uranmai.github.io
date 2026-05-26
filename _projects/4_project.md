---
layout: page
title: Biomechanical Ball Controller in Unity3D
description: Physics-based game controller using IMU/EMG sensors and Leap Motion
importance: 1
category: competitions
img: assets/img/projects_imgs/Preview_ofProject4.png
---

Developed a biomechanical controller for a rolling ball in Unity3D using physics-based modeling and C#. The project focused on simulating realistic motion dynamics — inertia, surface friction, and directional control — to create responsive and physically plausible movement.

**Key aspects:**
- Custom rigidbody physics controller in C#
- Biomechanical force model for natural-feeling acceleration and braking
- Adjustable parameters for surface type and ball properties

**Skills:** Unity3D, C#, Physics simulation, Biomechanical Engineering

---

### Game setup in Unity3D

{% include video.liquid path="assets/video/first_version_of_game_inUnity_compressed.mp4" controls=true autoplay=true loop=true muted=true width="100%" %}

---

### Control with Leap Motion & IMU/EMG Sensors

[Leap Motion](https://www.ultraleap.com/) tracks 3D hand gestures in real time. Combined with IMU/EMG sensors, it enables natural biomechanical input to control the ball.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects_imgs/IMG_0050.jpg" alt="First" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects_imgs/IMG_0052.jpg" alt="Second" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

{% include video.liquid path="assets/video/final_version_with_IMUcontroller.mp4" controls=true autoplay=true loop=true muted=true width="100%" %}

---

### Results — Robotics Poster

<iframe src="{{ 'assets/pdf/Robotics Poster.pdf' | relative_url }}" 
  width="100%" height="620px" style="border: none; margin-top: 10px;">
</iframe>