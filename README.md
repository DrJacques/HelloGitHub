# HelloGitHub
MyFirstRepository
Hello everybody, My name is Jacques Iragena. My attitude isn't bad it's in coding. i love to code every single day.
Bellow is the C++ code to swapfirst name in C++; "jacques"

#include<iostream>
using namespace std;
int main(){
	string s="jacques";
	string reversed_s="";
	int length= sizeof(s)-1;
	for (int i=length; i>=0;--i){
		
		reversed_s+=s[i];
	}
	cout<<reversed_s;
}
