#include<stdio.h>
#include<math.h>
float f(float x)
{
    return (x*x*x-4*x-9);
}
void main()
{
    float x1=2,x2=3,x3,z;
    float y=0.00001;
    int i=1;
    do
    {
        x3=(x1+x2)/2;
        printf("/nThe approx value of x=%f/n",x3);
        z=f(x3);
        if(z>0)
        {
            x2=x3;
        }
        else
            x1=x3;
        i++;
    } while (fabs(x1-x2)>=y);
}
