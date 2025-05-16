# pattern-with-spaces.c
// Online C compiler to print pattern with spaces  EDCBA  DCBA   CBA    BA   A
// Online C compiler to print pattern with spaces

EDCBA
 DCBA
  CBA
   BA
    A
    
#include <stdio.h>
int main() {
    int i,j;
    for(i=0;i<5;i++)
    {
        for(j=0;j<=i-1;j++)
         printf(" ");
        for(j=4-i;j>=0;j--)
         printf("%c",65+j);
        printf("\n");
    }
    return 0;
}
