# M3-D3
AIM:
Create  a C program to read n elements as input and print the last element of the array (integer).
PROGRAM:
```
#include <stdio.h>
int main ()
{
    int n,i;
    scanf("%d",&n);
    int a[n];
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }

    
    printf("%d",a[n-1]);
}
```
OUTPUT:
<img width="897" height="470" alt="image" src="https://github.com/user-attachments/assets/051e905d-a6a9-43af-944c-bfbdc27c9c43" />
RESULT:
Thus the code run successfully!
