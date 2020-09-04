# Find-Nth-Term-C
#include <stdio.h>

int main(){
   int n;
   int a;
   int b;
   int c;
   int s=0;
   scanf("%d %d %d",&a,&b,&c);
   int d=b-c;
   int y=0;
   scanf("%d",&n);
   for(int i=0;i<=n;i++){
       y=y+(2*a+(i-1)*d);


   } 
   printf("%d",y);
}
