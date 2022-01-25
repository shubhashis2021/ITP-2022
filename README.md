# ASSIGNMENT-1
This is to submit the assignment-1 of ITP course.
# TEAM MEMBERS
enrollment no and github ids

IEC2021042-shubhashis2021

IEC2021043-Strom2002Coder

IEC2021044-RITAM-DAS

IEC2021045-aryans08

 GROUP NUMBER:11
 FACULTY NAME: Dr. MD Javed sir
 MENTOR NAME: MD. Meraz sir

# ALGORITHM
• Take input from the user for the size of double dimension array (n).
• Define an integer array arr[n][n] and take input from console for the elements of the array arr[n][n].
• Calculate the minimum number of zeros that should be present in any triangular matrix of order n by the formula n(n-1)/2 and store 
it in any variable(number).
• Define a switch case with 2 cases for checking the upper and lower triangularity of the matrix.
• For checking the upper triangularity, set conditions to check arr[i][j] ≠ 0, for all i=j and arr[i][j]=0 for all i>j and set a flag variable 
(f=1) and counter (c++) variable respectively.
• For checking the lower triangularity, set conditions to check arr[i][j] ≠ 0, for all i=j and arr[i][j]=0 for all i<j and sets a flag 
variable (f=1) and counter (c++) variable respectively.
• If the value of counter variable (c)= number and f ≠ 1 then the given matrix is triangular else print the matrix is not triangular. 

# PROCEDURE 
▪ When the compilation begins at first, the compiler asks for the order of the 2D Array from the user.
▪ Enter size of the array as 3 (from console)
▪ Thus the array, arr[3][3] is now declared i.e. n=3
▪ Now the compiler asks from the console to enter the elements in array and the elements are entered row wise.
1 2 3
0 4 8
0 0 6
▪ Now p is a dummy variable which stores n-1 i.e. 3-1 =2. The variable p has been introduced to avoid the error caused by precedence of operator.
▪ Number = nxp/2 = 3x2/2 = 3 (minimum number of zeros in a triangular matrix)
▪ Further compiler will ask console to input 1 or 2 for checking upper or lower triangularity of matrix respectively using the message - “Enter 1 for checking 
upper Triangularity of the matrix or enter 2 for checking the lower triangularity”.
▪ Suppose 1 is input by the console. Now the compiler will execute case 1 of switch case.
▪ For the value i=0, j will take values upto j=0, j=1 and j=2 and simultaneously arr[0][0], arr [0][1], arr[0][2] will be checked for value 0 for i=j or i>j 
accordingly and thus value of “c” or “f” will be updated for each iteration of the inner loop.
▪ Now if f=1, then the compiler will print “not a triangular matrix” and the compiler will come out of the outer loop else i will be incremented to be 1 and
gradually to 2 and thus the other positions like arr[1][0], arr[1][1], arr[1][2], arr[2][0], arr[2][1], arr[2][2] will be checked similarly and value of “c” and “f” 
will be updated.
Finally it will check that value of c = number and f ≠ 1, if found true, it will print “it is a triangular matrix” else it will print “not a triangular matrix”.
 
  

 

 
