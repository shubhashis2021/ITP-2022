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
 
  
# ASSIGHMENT -2
 THIS REPOSITION CONTAINS ASSIGNMENT-2 OF ITP COUSE
 # TEAM MEMBERS:
 enrollment no and github ids

IEC2021042-shubhashis2021

IEC2021043-Strom2002Coder

IEC2021044-RITAM-DAS

IEC2021045-aryans08
 
 
 GROUP NUMBER:11
 FACULTY NAME: Dr. MD Javed sir
 MENTOR NAME: MD. Meraz sir

 # ALGORITHM(OF ASSIGNMENT-2): 
• Include header file i.e,<stdio.h>, <stdlib.h>, <stringh.h> .
• Declare a structure named library for holding composite data of
string, integer and float type .
• Then define strut library arr[limit] for accessing data members.
• Start a while loop with condition (x=1).
• Make switch case consisting of 7 cases
• Case 1: to input data for book
• Case 2: for displaying the book data
• Case 3: for displaying the books of the author given from the
console.
• Case 4:to list the title of the specified book.
• Case 5:to know count of books in library .
• Case 6:to list the book in accession number
• Case 7: to exit from the process .
• For case 1 for taking input of the string part use fflush(stdin)
and fgets() And for entering the price and flag use scanf() with
appropriate access specifier.
• Further in case 1 use arr[j].acc_no=j for storing there accession
no of the book. And then increment j by 1(J++).
• In the case 2 of the switch case use puts() to print the string
part and printf() function for printing price of book.
• Further in case 2, if(arr[I].f==0) then print book is issued else
print not issued.
• In case 3 take input from the console for the author name by fflush(stdin) & fgets() and check that if(strcmp(arr[I].author,aut)==0) then print arr[I].nam else print “no book avilable”.
• In case 4 ask for the accession number from the console and then print the book added to the library to that particular accession number by if(arr[I].acc_no==accession ) then print arr[i].nam .
• In case 5 simply print value of “j” for knowing the count of books in the library.
• In case 6 start a loop from i=0 to I<j and print arr[i].nam .
• In case 7 make value of x=2 for terminating the while loop.
                                         
                    
 # PROCEDURE(WORKING OF CODE 0F ASSIGNMENT -2):                     
1. A composite data type i.e, structure namely library is declared consisting of integer ,float and two character array each of size 1000 for storing the name of book and name of author
2. Array of structure data type of length 1000 is declared for storing details of book of library.
3. Now the compiles moves inside while loop as the condition is true(x=1).
4. Value of k is first initialised to 0 before each iteration and then it asks every time for giving the choice .
5. Let us say the user has entered 1 as choice now the cursor goes inside the switch case and goes to choice number 1 there it first takes the name of book from console and stores it inside arr[j].nam the then it asks for the name of the author of he book and stores it in arr[j].author then it takes the value of book from user and also asks for the status of book i.e issued or not.Then it assigns the accession no to the book i.e the value of which was initially initialised to “0” and then j++ for counting number of books in library
6. Still the compiler is inside the while loop thus it again asks for entering choice from the user and it goes on until the user give choice as 7 .
 
 7. Now let us say console has given choice as 5 then the cursor again goes inside the switch case and directs itself to case no 5 and prints the number of book present in the library i.e, the value of “j” using the printf() function.
8. If choice no 7 is given then then the value of x is assigned to 0 thus condition of while loop(x=1) becomes false and it comes out of loop.
9. Thus the program of working of library is terminated.
 procedure(working of code):-
1. A composite data type i.e, structure namely library is declared consisting of integer ,float and two character array each of size 1000 for storing the name of book and name of author
2. Array of structure data type of length 1000 is declared for storing details of book of library.
3. Now the compiles moves inside while loop as the condition is true(x=1).
4. Value of k is first initialised to 0 before each iteration and then it asks every time for giving the choice .
5. Let us say the user has entered 1 as choice now the cursor goes inside the switch case and goes to choice number 1 there it first takes the name of book from console and stores it inside arr[j].nam the then it asks for the name of the author of he book and stores it in arr[j].author then it takes the value of book from user and also asks for the status of book i.e issued or not.Then it assigns the accession no to the book i.e the value of which was initially initialised to “0” and then j++ for counting number of books in library
6. Still the compiler is inside the while loop thus it again asks for entering choice from the user and it goes on until the user give choice as 7 .
 
 7. Now let us say console has given choice as 5 then the cursor again goes inside the switch case and directs itself to case no 5 and prints the number of book present in the library i.e, the value of “j” using the printf() function.
8. If choice no 7 is given then then the value of x is assigned to 0 thus condition of while loop(x=1) becomes false and it comes out of loop.
9. Thus the program of working of library is terminated.
                                         
                                         
 # TIME COMPLEXITY OF CODE OF ASSIGHNMENT -2 :
The time complexity of the code is defined in the worst case .As the max value of structure type array can take is 1000 and we know 10^8 in nearly 1 second thus, O(1000)=10^3/10^8=0.00001 sec. 
                               
                                         
                                         
                                       
                                         
                                         
 
 

 
 

 
