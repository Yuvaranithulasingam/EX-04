# EX-4(D)           COUNT OF PUNCTUATIONS

## AIM:
To write a C program to count the number of punctuation characters exists in a string using for loop.

## ALGORITHM:
1.Include necessary header files.
2.Define the main function.
3.Compile and run the program.
4.Run the program.
5.Display the output.

## PROGRAM:
```
#include <stdio.h>  
#include<string.h>
int main ()  
{  
   int i, count = 0;  
   char str[100] ;
   scanf("%[^\n]%*c",str);
   for(i = 0; i < strlen(str); i++)
   {  
       if(str[i] == '!' || str[i] == ',' || str[i] == ';' || str[i] == '.' || str[i] == '?' ||   
       str[i] == '-' || str[i] == '\'' || str[i] == '\"' || str[i] == ':') 
       {  
                count++;  
        }  
   }  
   printf("%d ",count);  
   return 0;  
}  
```

## OUTPUT:
![image](https://github.com/Yuvaranithulasingam/EX-04/assets/121418522/3d093da1-be4d-4f16-b0a3-7ab089f09ee5)

## RESULT:
 Thus the program to find the count of punctuations has been executed successfully.
