# Planetary-Science-Prototype
This is part of a longer-term project of mine, to build a simulation of planetary interiors since I always wanted to have a customizable, flexible calculator but everything out there was either pre-built for specific planets and non-customizable, or awkward to use or download, so this is my solution to this problem. 
My project has 2 parts right now, a 1st prototype and a 2nd prototype. The 1st prototype is a simple, 2-layer model I built to give myself an idea of what to do, and the 2nd prototype is a multi-layer model that is more accurate.


1st Prototype: 
This prototype only split the planet into 2 pieces, and inner and outer layer, and was more for a proof-of-concept than 
anything, since it wasn't super-accurate. However, I liked it simply to see how such a calculator should be built.


2nd Prototype:
This prototype is significantly better than the 1st. It splits a planet into N layers, then finds the pressure and density at every layer, then finds the overall density and mass of the planet, and also draws a few charts to visualize the data. While I have to admit I used some AI to build the charts because I got stuck on making the arrays fit, and used a smidge of AI to debug my code, all of the concepts, math and ideas were mine when I built it. 

If you have to choose between the 2 prototypes, choose the 2nd prototype. It is much more powerful-simply put in the bulk modulus of the material, and the radius and known mass of the planet, and it will carry out the rest. There is a small bug; at small radii, there is a divide-by-zero error that makes the values go negative and makes the charts a bit odd, but otherwise the code is effective as far as things go.

<img width="710" height="305" alt="Screenshot 2026-10-22 202300" src="https://github.com/user-attachments/assets/61a62e2f-4c7e-4e77-aea3-e25bd92b5988" />

<img width="711" height="284" alt="Screenshot 2026-10-22 202313" src="https://github.com/user-attachments/assets/a0786dae-1134-4fcd-a11e-e9978eaffd55" />

