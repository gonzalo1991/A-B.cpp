# A-B.cpp
include <iostream>
using namespace std;

int main() {
	int a;
	int b;
	std::cin>>a;
	std::cin>>b;
	if(a>b)
	{
		std::cout<< "el mayor es a";
	}

	else {
		if(b > a)
		{
			std::cout<<"el menor es b"<<endl;
	}
		else{
			std::cout<<"son iguales"<<endl;
	}
		}

}
