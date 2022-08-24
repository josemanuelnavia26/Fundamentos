#include "stdafx.h"
#include <iostream>
#include "conio.h"

using namespace std;

int main(){
	int n1,n2,n3;
	cout<<"ingresar el valor de n1:";
	cin>>n1;
	cout<<"ingresar el valor de n2:";
	cin>>n2;
	cout<<"ingresar el valor de n3:";
	cin>>n3;
	if (n1>=n2)
		if(n1>=n3)
			cout<<"el mayor es:"<<n1<<endl;
		else
			cout<<"el mayor es:"<<n3<<endl;
	else
		if(n2>=n3)
			cout<<"el mayor es:"<<n2<<endl;
		else
			cout<<"el mayor es:"<<n3<<endl;
	getch()
	return 0;

 }
