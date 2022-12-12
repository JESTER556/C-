#include <iostream>

using namespace std;

int main()
{

	int ip1;
	int ip2;
	int ip3;
	int ip4;
	cout << "Enter first part of your IP number : ";
	cin >> ip1; cout << "\n";
	cout << "Enter second part of your IP number : ";
	cin >> ip2; cout << "\n";
	cout << "Enter third part of your IP number : ";
	cin >> ip3; cout << "\n";
	cout << "Enter fourth part of your IP number : ";
	cin >> ip4; cout << "\n";

	if (ip1 <= 255 && ip2 <= 255 && ip3 <= 255 && ip4 <= 255)
	{
		cout << "Ip-address : " << ip1 << "." << ip2 << "." << ip3 << "." << ip4;
	}
	else
	{
		cout << "Something went wrong... Your value greater than 255";
	}

	return 0;
}