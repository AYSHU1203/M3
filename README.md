# EX-11-EMI-CALCULATOR

## AIM

To write a program to prepare EMI calculator using function without return type and with arguments.

## ALGORITHM

1.	Start the program.
2.	Read principal amount, rate of interest and months.
3.	Pass these values as arguments to function.
4.	Calculate EMI using the formula, amt=(prpow(1+r,t))/(pow(1+r,t)-1)
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>
#include <math.h>

void calcEMI(float p,float r, float t){
    
    r=r/(12*100);
    t=t*12;
    float emi = (p*r*pow(1+r,t))/(pow(1+r,t)-1);
    printf("Monthly EMI is= %.3f",emi);
}
int main(){
    float p,r,t;
    p = 345000.80;
    r = 9.25;
    t= 4;
    calcEMI(p,r,t);
    return 0;
}
```


## OUTPUT
![438643469-0ba848f9-661d-4d83-abda-b47bca596c67](https://github.com/user-attachments/assets/d454ed72-3f2e-44bf-87bf-488cb7a99ef1)






## RESULT

Thus the program to prepare EMI calculator using function without return type with arguments has been executed successfully
 
 


# EX-12-FIBONACCI-SERIES
## AIM
To write a C program to generate the Fibonacci series for the value 6.

## ALGORITHM
1.	Start the program.
2.	Read number of terms to display.
3.	Add the previous two terms and store it in new term.
4.	Assign 2nd term to 1st term and 3rd term to 2nd term.
5.	Repeat steps 3 and 4 n number of times.
6.	Display the result.
7.	Stop the program.

## PROGRAM
```
#include <stdio.h>

int main() {
    int n = 11, first = 0, second = 1, next, i;
    
    for (i = 0; i < n; i++) {
        printf("%d ", first);
        next = first + second;
        first = second;
        second = next;
    }
    
    printf("\n");
    return 0;
}
```

## OUTPUT

![438643946-fed77334-4a2c-4ee0-a061-1af855060874](https://github.com/user-attachments/assets/1d523243-8298-446b-ac49-b57741c95435)








## RESULT
Thus the program to generate the Fibonacci series for the value 6 has been executed successfully.
 
 


# EX-13-ONE-DIMENSIONAL-ARRAY
## AIM
To write a C program to read n elements as input and print the last element of the array.

## ALGORITHM
1.	Start the program.
2.	Read a variable.
3.	Read the array values n number of times.
4.	Print the last element.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>

int main() {
    int n;
    scanf("%d", &n);
    int arr[n];
    for (int i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }
    printf("%d\n", arr[n - 1]);
    return 0;
}
```
## OUTPUT
![438644381-21effe37-c596-48f1-9faa-666811ee73b7](https://github.com/user-attachments/assets/597222cd-e07e-4df3-a060-d1a0cb64af73)










## RESULT
Thus the program to read n elements as input and print the last element of the array has been executed successfully.
 
 


# EX-14-POSITIVE-ARRAY-ELEMENTS
## AIM
To write a C Program to count total number of positive elements in an array.

## ALGORITHM
1.	Start the program.
2.	Read a variable.
3.	Read the array values n number of times.
4.	If the array value can be divided by 2 then increment count by 1.
5.	Display result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main(){
    int n,count=0;
    scanf("%d",&n);
    int arr[n];
    for(int i=0;i<n;i++){
        scanf("%d",&arr[i]);
    }
    for(int i=0;i<n;i++){
        if(arr[i] % 2 == 0){
            count++;
        }
    }
    printf("Total even elements: %d\n",count);
    return 0;
}
```


## OUTPUT
![438644926-87f74776-f326-46b2-8794-ba30a4182fef](https://github.com/user-attachments/assets/e6901c8a-b3ef-4359-88a1-ea06736f36a3)






## RESULT
Thus the program to count total number of positive elements in an array has been executed successfully.





 
 


# EX -15 - Replace All Even Elements With 'E' In One Dimensional Array

## Aim:
To write a C program to replace all even elements with 'E' in one dimensional array

## Algorithm:
1.	Input the array:
  Read the size of the array.
  Input the elements of the array.
2.	Iterate through the array:
 	For each element of the array, check if the element is even (i.e., if the element modulo 2 equals 0).
3.	Replace even elements with 'E':
     If an element is even, replace that element with the character 'E'.
4.	Output the updated array:
 Print the updated array after replacements.

## Program:
```
#include <stdio.h>
int main(){
    int n=10;
    int a[10] = {5,6,4,12,19,121,1,7,9,63};
    for(int i =0;i<n;i++){
        if(a[i] % 2 ==0)
        printf("0 ");
        else 
        printf("%d ",a[i]);
    }
    
}
```

## Output:
![438645472-6f76d8e8-c439-4de5-ac04-e0782cd2b2e3](https://github.com/user-attachments/assets/0352fe08-ecc6-4657-8f5f-59f5f090f1d5)

 


## Result:

Thus, the program to replace all even elements with 'E' in one dimensional array was verified successfully.



