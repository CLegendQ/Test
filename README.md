#include <iostream>
#include <iomanip>
#define Pi 3.1415926
using namespace std;
int main()
{
	double r;
	double h;
	double C;//圆周长
	double S;//圆面积
	double S2;//圆球表面积
	double V;//圆球体积
	double V2;//圆柱体积
	cout<<"请输入半径和高"<<endl;
	cin>>r>>h;
	C=2*Pi*r;
	S=Pi*r*r;
	S2=4*Pi*r*r;
	V=4*Pi*r*r*r/3;
	V2=S*h;
	cout<<setiosflags(ios::fixed)<<setprecision(2)<<"圆周长"<<C<<endl;
	cout<<setiosflags(ios::fixed)<<setprecision(2)<<"圆面积"<<S<<endl;
	cout<<setiosflags(ios::fixed)<<setprecision(2)<<"圆球表面积"<<S2<<endl;
	cout<<setiosflags(ios::fixed)<<setprecision(2)<<"圆球体积"<<V<<endl;
	cout<<setiosflags(ios::fixed)<<setprecision(2)<<"圆柱体积"<<V2<<endl;
	return 0;
}
