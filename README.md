# A-B-for-Input-Output-Practice-VI-

A+B for Input-Output Practice (VI)

Problem Description

Your task is to calculate the sum of some integers.

 
Input

Input contains multiple test cases, and one case one line. Each case starts with an integer N, and then N integers follow in the same line. 

 
Output

For each test case you should output the sum of N integers in one line, and with one line of output for each line in input.  


Sample Input

4 1 2 3 4

5 1 2 3 4 5

 
Sample Output

10

15 

解答：

#include<stdio.h>

main()

{

    int n,a,b,i,j,sum;
    
    sum=0;
    
    while(scanf("%d\n",&n)!=-1)
    
    {
    
    
            for(j=0;j<n;j++)
            
             {
             
                 scanf("%d",&a);
                 
                 sum+=a;
                 
             }
             
             printf("%d\n",sum);
             
             sum=0;
             
        
    }
}

