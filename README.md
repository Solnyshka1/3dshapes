![image](https://github.com/user-attachments/assets/50010b3e-e413-40d4-a8cf-fcd238977e68)
Description
This project demonstrates polymorphism by using an interface (Shape3DInterface) to define a contract for 3D shapes. Multiple classes (Sphere, Cylinder, Cube) implement this interface, providing specific implementations for calculating surface area and volume.

Polymorphism Explanation
The list of Shape3DInterface objects utilizes polymorphism, as each object in the list can be any of the three shape types. The surfaceArea() and volume() methods are invoked on the interface reference, allowing for dynamic method binding based on the actual object's class.
