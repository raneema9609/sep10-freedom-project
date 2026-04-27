# Entry 5
##### 4/26/26

## Context: 


Over the past few weeks, I started working with my chosen tool called A-Frame. A-frame is a web framework that helps you create 3D objects and scenes that you can view in a browser, allowing me to learn a lot about how to make simple shapes like boxes, spheres, cylinders,etc. Also i was able to learn how to change the positions, rotation, and color of each shape/object to make them look more put together and enaging depending on the scenario. For example, I experimented with creating a ice cream cone shape by combining small spheres and cones, and I changed the sky color to light blue to make my scene look better. I also learned how to use http-server to view my work in 3D mode after making changes. In the beginnning I ran into several problems with figuring out how to position objects in 3D space especially using the x, y, and z coordinates, but with help from Mr.Mueller and practice i was able to strengthen my abilities with the uses of A-frame.

Below is the code I used when practicing with the shapes, allowing me to create a "Ice-Cream" cone: 
<img width="310" height="398" alt="image" src="https://github.com/user-attachments/assets/73e48911-5704-4f34-867a-12a15a01da10" />

The Code:
```
<!doctype html>
<html>

<head>
  <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
</head>


<body>
<a-scene>

<!-- Sphere representing the "ice cream scoop" -->
  <a-sphere position="0 2.75 -5" radius="1.25" color="#EF2D5E"></a-sphere>

  <!-- Cone representing the "cone" part -->

<a-cone position="0 0.75 -5" radius-bottom="1.25" radius-top="0" height="2" color="#D2691E" rotation="180 0 0"></a-cone>

<a-sky color="#87CEEB"></a-sky>

</a-scene>
</body>



</html>
```

## Challenges:

When learning and playing around with my tool, I ran into several issues like 


[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
