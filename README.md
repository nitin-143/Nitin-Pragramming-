#Largest number of 5 array elements-
#include<stdio.h>
int max();
void main()
{
    int a[5], l, i;
    printf("enter 5 elements = ");
    
        for(i=0; i<5; i++)
         {
            scanf("%d", &a[i]);
         }
        
     l = max(a);
    
    
     printf("largest number = %d", l);
        
}

// function program 
int max(int a[])
{
    int i=1, m;
    m = a[0];
    while(i<=5)
     {
        if(m<a[i])
         { 
            m=a[i];   
         }
        i++;
     }
  return m;
}

 
