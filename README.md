# Lab-20.30
#include <iostream>
using namespace std;

/*
_Prototypes for value returning functions_
Examine the code and try running the program. Fix the error by adding the necessary prototype.
*/
double half(double quantity)
{
	return quantity / 2.0;
}

int main() {
  double number, result;

	cout << endl << "Please input a number to half" << endl;
	cin >> number;

	cout << endl << endl;

	result = half(number);
	
	cout << "Half of your number is " << result;
}

//	*********************************************************************
//	half
//
//	task:	  This function takes a quantity and returns half its value
//	data in:  the value to halve (double)
//	data out: the input divided by 2 (double)
//	********************************************************************
