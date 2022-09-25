# RayTracing-in-OneWeekend
This repo is my implementation of RayTracing in One Weekend book.
## Platform  
---
- macOS, Linux, windows

## Dependency  
---
- g++ std=c++11
## How to run
---
- you can simply build with build.sh
```
./build.sh
```
- and you can get the result image image.ppm
## Feature
---
A simple raytracer from scratch, starting from a output of a pure color image, I built a simple vector computation library, defined classes for ray, hittable objects, materials(lambertian, dielectric, metal), etc.
## Result
---
- red sphere
![a red sphere](./Image/png/redSphere.png)
- normal-color sphere
![normal color sphere](./Image/png/normalsColoredSphere.png)
- after sampled
![sampled normal sphere](./Image/png/sampledNormalSphere.png)
- diffuse sphere
![diffuse sphere](./Image/png/diffuseSphere.png)
![gamma diffuse](./Image/png/gammaDiffuseSphere.png)
- metal sphere
![metal sphere](./Image/png/materialSpheres.png)
fuzzier
![metal fuzz](./Image/png/metalFuzzSpheres.png)
- dielecticShperes
![dielectic](./Image/png/dielectricShperes.png)
- depth of field
![DOF](./Image/png/depthOfField.png)
![zoom in](./Image/png/zoomIn.png)
- final
![final](./Image/png/final.png)

