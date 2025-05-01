#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    char c[100];
    fgets(c,sizeof(c),stdin);
    for(int i=0;c[i]!='\0';i++)
    {
        char ch=c[i];
        int ans=ch;
        printf("%d ",ans);
    }
    return 0;
}
