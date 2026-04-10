**Written Summary**

**Methods** –

First, each problem was analyzed and broken down into smaller problems. Since the solutions were already given, the procedure for solving these problems normally was known. However, to approach from an automation perspective, this changes the model. Each problem was broken down to only solve for one unknown at a time. Each unknown was solved by either given known values or unknowns that were previously solved for earlier in the problem. To achieve this, the problems were each written down on paper and solved algebraically before they were placed into python.

Before the actual coding began, the python file also had to be set up. Necessary Python libraries were imported to the code including numpy and pint. From pint, the Unit Registry was used. This was imported so the calculations and numbers could be assigned labels.

With the Python file set up, the coding began. The knowns were placed into Python and assigned units. The knowns were assigned units using the Unit Registry package. After the knowns were assigned, functions were set up. Only one function for each problem was created. The use of functions was important for this project in regard to the variable input feature. The arguments of each function were the given values from the problem. The outputs were the unknowns of each problem. The paper algebra work was then placed into Python. After breaking the problem up into smaller parts and solving it for one unknown at a time, the problems were solved. Comments were then added to each part of code to explain what each line of code is doing.

The final part of the procedure was to comply with the other tasks that were requested. The problems had been solved, and variable inputs had already been accounted for. In Problem \#2, the forces of each unknown were converted from Newtons to Force Pounds to show the Python code is capable of unit conversion. All the tasks had been completed that were asked of the team using the Python code.

**Results** –

Our team of technicians were tasked with developing a Python tool with the ability of performing typical statics calculations for our structural engineering firm. The tool will help the firm in efforts to modernize and simplify calculations. The tool is supposed to:

1.  Perform unit conversion and analysis,
2.  Handle distributed and point loads acting on static members,
3.  And can properly take in user input and provide an accurate result.

The Python code, overall, calculates the forces, resultant forces, and direction angles in 2D and 3D static equilibrium problems using trigonometric and algebraic equations. We determined unknown forces and their respective direction using vector decomposition and equilibrium conditions in our analysis of the three static problems.

Problem 2

The value of the forces represent load distribution across structures, a crucial objective for structural safety and design. By following static equilibrium conditions, our team coded the Python tool to ensure the forces balanced in the horizontal and vertical directions.

In Problem 2, forces F1 and F2 are given, 800 N and 200 N\*m, respectively, the segment lengths, SegB = 2 m and SegC = 2 m, and Θa which is 60 degrees. The “calc_Force” function in Python finds the unknown forces at points A, B, and C. Finding the components of the force at C required a force balance equation and moment equilibrium. The same goes for the forces acting on point A.

The angle theta with respect to the y-axis is 54.33°. The force magnitude is 685.89 N.

Problem 3

This problem involved position vectors, each given in meters, and vectorizing forces. Fc and Fb. The “calc_F_r” function found the magnitude of the position vector, which was used to normalize the force directions, vectorized each force, added individual force components, calculated the magnitude of the resultant force, and finally determined the directional angles. We used basic math principles such as the Pythagorean Theorem to find the magnitude of the resultant force and inverse trig functions to find the angles. The tool for this problem helped analyze the resultant in 3D space based on known force positions.

The angles of alpha, beta, and gamma are 149.04°, 90.00°, and 59.04°, respectively. The force magnitude is 756.72 newtons.

Problem 4

The problem tells us that FB (800 N) is acting at an angle ΘB = 330° and FR (1250 N) is acting at ΘR = 0°. Our Python tool successfully found the magnitude and direction of FA. The tool determines the unknown force by resolving forces into their x and y components. It computes an unknown force in a 2D static equilibrium problem using vector decomposition and trigonometry.

The angle theta with respect to y axis is 54.33°. The force magnitude is 685.89 newton.
