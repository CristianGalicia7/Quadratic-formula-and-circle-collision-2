# Quadratic-formula-and-circle-collision-2
c++ code that determines if two circles collide 
//CGalicia Center of a circle equation and radius of a circle 02-12-2015
#include <iostream>
#include <math.h>
using namespace std;
int main()
{	
	double h1, k1, h2, k2, r1, r2, d;
	//(x-h)^2+(y-k)^2=r^2
	cout<<"Enter value for h1=";
	cin>>h1;
	cout<<"Enter value for k1=";
	cin>>k1;
	cout<<"Enter value for h2=";
	cin>>h2;
	cout<<"Enter value for k2=";
	cin>>k2;
	cout<<"Enter value for r1=";
	cin>>r1;
	cout<<"Enter value for r2=";
	cin>>r2;
	d=sqrt ((h2-h1)*(h2-h1)+(k2-k1)*(k2-k1));
	cout<<"\n The sum of the radii is "<<r1+r2;
	cout<<"\n The distane between centers "<<d;
	if(d<=r1+r2)
	cout<<"\n Collision Occurs \n";
	else
	cout<<"\n No Collision \n";


}
