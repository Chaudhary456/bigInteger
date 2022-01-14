# biginteger
A C++ library to perform mathematical operations over VERY LARGE NUMBERS.  
Tools Used: C++,OOPS concept.  
What you can do?   
1) add two numbers.  
2) multiply two numbers.  
3) compare two numbers.     
4) substract two numbers.   
5) divide two numbers.   
6) find factorial(n).   
7) find a power b.  
8) convert decimal to binary.     
9) find |x|.     



Use #include<biginteger.h> , if you add the file in the include folder in MinGW.  
Use #include "biginteger.h" , if you add the file in the local folder.  
  
Input both numbers as string, str1 and str2.
  
l1 = str1.length()    
l2 = str2.length()  
n1 = biginteger(str1)  
n2 = biginteger(str2)  
  
  
SYNTAX to use the features?  
  
1) compare:  
   Syntax:  n1.compareTo(n2)  
   Return:  1 (n1>n2)  
           -1 (n1<n2)  
            0 (n1=n2)  
   Time Complexity: O(max(l1,l2))    
   Limits: No Limits.  


2) Addition:  
   Syntax:  n1.add(n2)  
   Return:  n1+n2    
   Time Complexity: O(max(l1,l2))    
   Limits: Didn't works on +ve and -ve pair of numbers.  
   

3) Multiplication:  
   Syntax:  n1.multiply(n2)  
   Return:  n1*n2  
   Time Complexity: O(l1*l2)      
   Limits: No Limits.  
   
   
4) Substraction:  
   Syntax:  n1.findDiff(n2)  
   Return:  |n1-n2|
   Time Complexity: O(max(l1,l2))    
   Limits: n1>=0 && n2>=0.  
   
   
5) Factorial:  
   Syntax:  n1.factorial()    
   Return:  n1!   
   Time Complexity: O(pow(l1,n1))    
   Limits: n1>=0.     
   
   
6) Power:  
   Syntax:  n1.power(n2)    
   Return:  n1 to the power n2.   
   Time Complexity: O(pow(l1,n2))    
   Limits: n1>=0 && n2>=0.   
   
   
7) Absolute:  
   Syntax:  n1.absolute()    
   Return:  |n1|.   
   Time Complexity: O(1)    
   Limits: None.  
   
   
8) Division:  
   Syntax:  n1.divideby(n2)    
   Return:  n1 to the power n2.   
   Time Complexity: O(l1)    
   Limits: n1>=0 && n2>0.  
   

9) Decimal to Binary:  
   Syntax:  n1.tobinary()    
   Return:  Binary value of n1.   
   Time Complexity: O(l1*log(n1)).      
   Limits: n1>=0.    

10) Logical NOT  
   Syntax:  n1.NOT()    
   Return:  NOT value of n1 in binary form.   
   Time Complexity: O(l1).      
   Limits: n1>=0.  


11) Logical XOR  
   Syntax:  n1.tobinary()    
   Return:  XOR value of n1 and n2 in binary form.     
   Time Complexity: O(max(l1,l2)).      
   Limits: n1>=0 and n2>=0.  


12) Logical AND  
   Syntax:  n1.tobinary()    
   Return:  AND value of n1 and n2 in binary form.     
   Time Complexity: O(max(l1,l2)).   
   Limits: n1>=0 and n2>=0.  


13) Logical OR  
   Syntax:  n1.tobinary()    
   Return:  OR value of n1 and n2 in binary form.     
   Time Complexity: O(max(l1,l2)).       
   Limits: n1>=0 and n2>=0.  