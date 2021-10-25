# Days-of-month
using switch statement
#include<iostream>
using namespace std;
int main()
{
	int num;    //declaring variable num with int datatype
	cout << "Enter the number" << endl; //asks the user to enter a number which will be stored in variable 'num'
	cin >> num;
		switch (num)  //the number will be evaluated and the result will be displayed on screen based on the userinput
		{
		case 1:   
			cout << "JANUARY \n31 days" << endl;
			break;
		case 2:
			cout << "FEBRUARY \n28 days and 29 days on a leap year" << endl;
			break;
		case 3:
			cout << "MARCH \n31 days" << endl;
			break;
		case 4:
			cout << "APRIL \n30 days" << endl;
			break;
		case 5:
			cout << "MAY \n31 days" << endl;
			break;
		case 6:
			cout << "JUNE \n30 days" << endl;
			break;
		case 7:
			cout << "JULY \n31 days" << endl;
			break;
		case 8:
			cout << "AUGUST \n31 days" << endl;
			break;
		case 9:
			cout << "SEPTEMBER \n30 days" << endl;
			break;
		case 10:
			cout << "OCTOBER \n31 days" << endl;
			break;
		case 11:
			cout << "NOVEMBER \n30 days" << endl;
			break;
		case 12:
			cout << "DECEMBER \n31 days" << endl;
			break;
		default:  //if the user enters a number greater than 12 or less than 1 then default case will be exceuted
			cout << "Please enter numbers between 1-12" << endl;
			break;
		}
		return 0;
}
