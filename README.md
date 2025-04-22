# Direction-Cosine-and-Direction-Ratio-Calculator
Team Name: Collaz codebreakers
Team member:
1. MD.TAMIM IQBAL(2103094)
2. Mushfiqur Rahman(2103061)
3. Mst. Sumaiya Aktar Srabony(2103100)
4. Md. Rraf Hasan(2103062)
5.    Shuvo Saha(2103081)
6. Md. Arifin Alim Nabid(2103117)
7.   Md. Motiur Rahman San(2103086)
8.   Fariha Anjum Aupy(2103078)
9.  Md. Mahbub Morsed(2103101)
10. Maruf Hasan Shuvo(2103112) 
Task: Direction of cosine and Direction of Ratio
Objective:
The objective of this code is to provide a set of functions and a user-friendly interface to calculate direction cosines and direction ratios for 3D vectors and lines in space. It allows the user to perform the following tasks:

1. Determine the direction cosines and direction ratios for a line segment connecting two points in 3D space.
   - This is achieved by taking input for the coordinates of two points, calculating the vector between them, and then computing the direction cosines and direction ratios for that vector.

2. Determine the direction cosines and direction ratios for a 3D vector entered as a string in the format of its components.
   - The user can input a vector as a string, and the code extracts the coefficients of the vector components (i, j, and k) and calculates the direction cosines and direction ratios.

3. Determine the direction cosines of a line joining a given point to the origin (0,0,0).
   - The code takes input for the coordinates of a point and calculates the direction cosines and direction ratios for the line connecting that point to the origin.
Working process:
The code you provided is a C++ program that calculates direction cosines and direction ratios for 3D vectors and lines in space.

1. **Input**: The code takes user input to select one of three options:
   - Determine the direction cosines and direction ratios for a line segment connecting two points in 3D space.
   - Determine the direction cosines and direction ratios for a 3D vector entered as a string.
   - Determine the direction cosines of a line joining a given point to the origin (0,0,0).

2. **Direction Cosines Calculation**:
   - The code calculates the direction cosines (l, m, n) for vectors in the 3D space.
   - It uses the formula for direction cosines, which is the components of the vector divided by its magnitude.

3. **Direction Ratios Calculation**:
   - The code calculates the direction ratios (p, q, r) for vectors in the 3D space. Direction ratios are the integers representing the proportions of the direction cosines.

4. **Vector Parsing**:
   - When determining the direction cosines and direction ratios for a vector entered as a string, the code parses the input string to identify the coefficients of the vector components (i, j, k).

5. **User Interaction**:
   - The code interacts with the user through a console menu, prompting the user to choose one of the three options and providing instructions for input.

6. **Output**:
   - The code displays the calculated direction cosines and direction ratios to the user, as well as the direction of the cosines in the form of fractions when possible.

7. **Error Handling**:
   - The code performs limited error checking by verifying that the input vector string contains valid characters. However, it lacks extensive error handling and may produce unexpected results or errors for certain types of input.

8. **Numerical Precision**:
   - The code performs mathematical calculations using floating-point arithmetic, which can lead to precision issues for very large or very small vectors.

9. **Organization**:
   - The code is organized into functions to handle different tasks, enhancing readability and modularity.
Obstacle:
The code you provided may not give correct results or may encounter issues for the following types of inputs:

1. **Invalid Vector Input**: When determining direction cosines and direction ratios for a vector, the code checks for the presence of certain characters (e.g., 'i', 'j', 'k', '+', '-', '*') to identify the components. However, it doesn't thoroughly validate the format or structure of the input. If the user enters a vector string with an unexpected format, the code may produce incorrect results or behave unpredictably.

2. **Numerical Precision**: The code uses floating-point arithmetic to calculate the direction cosines. This approach may introduce numerical errors, especially when dealing with very large or very small numbers. For extremely large or small vectors, the results may not be accurate.
