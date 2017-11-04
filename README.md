# GXB
作业
#求一元二次方程x^2+3X-5.6=0的根
#include "stdio.h" 
#include "math.h" 
/*求一元二次方程ax*x+bx+c=0的解*/ 
main() 
{ 
float a,b,c,x1,x2,d; 
printf("请输入a："); 
scanf("%f",&a); 
printf("请输入b："); 
scanf("%f",&b); 
printf("请输入c："); 
scanf("%f",&c); 
d=b*b-4*a*c; 
if(d < 0) 
printf("方程没有实数解.\n"); 
if (d==0) 
{ 
x1=(-b)/(2*a); 
printf("x1=%f\n",x1); 
} 
if (d>0) 
{ 
x1=(-b+sqrt(d))/(2*a); 
x2=(-b-sqrt(d))/(2*a); 
printf("x1=%f,x2=%f\n",x1,x2);} 
}
