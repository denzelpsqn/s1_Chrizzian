# s1_Chrizzian



#include <iostream>
using namespace std;
int main()
{
	string name;
	int age = 0;

	cout << "Please enter your Full Name: ";
	cin >> name;

	cout << "Please enter your Age: ";
	cin >> age;



	cout << "\n Enter 'A' for Abu Dhabi";
	cout << "\n Enter 'B' for Sharjah";
	cout << "\n Enter 'C' for Ajman";
	cout << "\n Enter 'D' for Dubai";
	cout << "\n Enter 'E' for Rak";
	cout << "\n Enter 'F' for Umm-Al-Quwain";
	cout << "\n Enter 'G' for Furajah";
	cout << "\n Enter 'H' for Al Ain";
	cout << "\n\nPlease Enter your Location: ";
	char loc;
	cin >> loc;

	switch (loc) {

	case 'A': cout << "Transportation Charge : AED 1000." << endl; break;
	case 'B': cout << "Transportation Charge : AED 500." << endl; break;
	case 'C': cout << "Transportation Charge : AED 390." << endl; break;
	case 'D': cout << "Transportation Charge : AED 650." << endl; break;
	case 'E': cout << "Transportation Charge : AED 250." << endl; break;
	case 'F': cout << "Transportation Charge : AED 300." << endl; break;
	case 'G': cout << "Transportation Charge : AED 300." << endl; break;
	case 'H': cout << "Transportation Charge : AED 1000." << endl; break;
	default: cout << "No Transportation available." << endl;
	}
	char ans, Y;
	cout << "\nDo you want to avail Transportation?(Y/N): ";
	cin >> ans;
	if (ans == 'Y') {
		cout << "Your Transportation will be Confirmed.";
	}
	else {
		cout << "The Transportation will be cancelled.";
	}
	return 0;
}
