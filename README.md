java c
GENG3405. Part 1 – 2024 
Submission (LMS) by 5 pm 16 September 2024. 
This is a group assignment. Please do FRUIT 
The assignment tests both your ability to do the tasks and to explain how you did them. Instructions 
1.   A1 is obtained as follows: Take the last three digits of the student number of each group member and divide it by 1000. Then find arithmetic average of the numbers obtained for all group members.
2.   The submitted (hard copy) report should start with the cover sheet (use the standard form). The cover sheet must list all group members and be signed by all members of the group. The absence of the name and signature of a group member will automatically result in zero mark for this member.
3.   The report should include the full justifications of your solutions, the programs developed and full references to the sources you used.
4.   ChatGPD or similar are not allowed.
Problem 1 Determine A1. Explain how it is determined.
Problem 2: Stress rotation (Friction) A block contains a fracture inclined at a=40o, with respect to the horizontal and holds on friction, Fig. 1.2. The block is loaded by stress px=40MPa, py=50MPa, pz= 18MPa. Determine if sliding can occur over the fracture. In order to do this, develop a Matlab/Python program to determine the possibility of sliding for any values of stress, angle of inclination and friction coefficient. Use the friction lawτmax  = c+μσN                (1)
where tmax is the maximum shear stress in the plane of the fracture, σN is the normal stress acting on the fracture plane.For particular calculations to be reported, the values of the parameters c and μ (the cohesion and friction coefficient, respectively)   should be obtained from the appropriate literature. For illustration, use aluminium over aluminium or granite over granite  (Civil, Mining and Environmental).
In your report, please explain the  theory behind your algorithm  with the reference to the corresponding slides in the lecture notes.
Note. The cohesion can in some cases be zero. In all cases you need to justify your choice of parameters c and μ by properly referring to the source (e.g. handbook).

Fig. 1.2 Block with fracture under compressive loading.
Problem 3 Determination of thickness of two layers. Linear model (Use Matlab/Python for computations.) A wall made of steel developed two corroded layers: the external layer of thickness d2  is heavily damaged and the internal layer of thickness d1  is relatively less damaged as can be seen in Fig. 2. The total thickness of the wall, L, is known but the thicknesses of the damaged layers are unknown. To determine these thicknesses without disrupting the wall, ultrasonic measurements are conducted by placing a transmitter of acoustic pulses at the point A and a receiver at the point B as shown in Fig. 2. The system times measure the durations tp and ts needed for the p (pressure)
- wave and s (sear) - wave to traverse the wall.
The aim of this question is to construct a linear model (a set of linear equations) top determi代 写GENG3405. Part 1 – 2024Python
代做程序编程语言ne the unknown thicknesses. You can proceed according to the following steps:
1. Model formulation. Suppose the thicknesses, d1 and d2 of the damaged layers are known. Write the equations to determine the times tp and ts needed for p and s waves to cross the wall. Assume that the total wall thickness, L, is known as well as the p - and s wave velocities: c0(p) , c1(p) , c2(p) , c0(s) , c1(s) , c2(s)   of each layer and the undamaged material, see Fig. 2.
2. Test example. Suppose you know the thicknesses of the layers: d1 =2 mm and d2= 1 mm. Determine the times tp and ts needed for p and s waves to traverse the wall. Assume L=10 mm,
c0(p)  = 5 km / sec
c1(p)  = 4.45721093750000 km / sec
c2(p)  = 4.68033845625000 km / sec
c0(s)  = 3.125 km / sec
c1(s)  = 1.61766128656250 km / sec
c2(s)  = 2.05351933062500 km / sec
3. Model calibration. Suppose you know the durations tp and ts . Determine the thicknesses from the model built in step 1. Check if they coincide with the values for the thicknesses assumed in step 2.
4. Model analysis. Suppose that the measurements of the times are conducted with small errors: the value measured for tp is 0.2% lower than the one obtained in step 2, while ts is 0.1% higher than the one obtained in step 2. Determine the layer thicknesses with these slightly incorrect values for the times and find the error in the thickness determination. Use two direct methods and two iterative methods of your choice. For the iterative methods, use a tolerance (relative error) of 10-6. How many iterations are required to achieve the specified tolerance. Compare your results to the thicknesses obtained in step 2. Comment on the agreement or discrepancy that you obtain when you use direct and iterative methods. Check the condition number and comment.
5. Improvement of the  method. Suppose you conduct  10 measurements with random errors, independently and uniformly distributed within the interval (-0.1%, 0.1%) and then average the result. Has the situation improved? How many measurements you need to achieve a 10% accuracy?

Fig. 2. Schematics of ultrasonic measurements of layer thicknesses.
Problem 4. Different thicknesses of the combined damaged layer at different points – interpolation 
1.   Damaged layers do not usually have uniform. thickness. Through the acoustic measurements (from Problem 3) the values for the total thickness (d=d1+d2) were found at different points along the z-axis, Fig. 2. These values are listed in Table 1. Using these points find the functional dependence d(z) using (a) polynomial interpolation, (b) cubic spline interpolation and (3) the best fit quadratic polynomial using the least squares method. Use Matlab for computations.
2.   Compare the results and comment on the comparison
Table 1. Values of the combined thickness of the damaged zone for different values of z. 
z, mm 
0 
10 
20 
30 
40 
50 
60 
d, mm 
2.9 
3.1 
2.1 
3.3*(1+A1) 
4 
4.4 
3.9 





         
加QQ：99515681  WX：codinghelp
