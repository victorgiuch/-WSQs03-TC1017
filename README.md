# -WSQs03-TC1017
Fun with Numbers
#include <iostream>
using namespace std;

int main()
{
	int n1, n2, s, r, m, d;

	cout << "Give me a number"<< endl;
	cin >> n1;

	cout << "Give me another number" << endl;
	cin >> n2;

	s = n1 + n2;
	cout << " The sum of the two nombers is" << s << endl;

	r = n1 - n2;
	cout << "the difference of the two numbers is" << r << endl;

	m = n1 * n2;
	cout << "The multiplication of the two numbers is" << m << endl;

	d = n1/n2 ;
	cout << "The division of the two numbers is" << d << endl;

	return 0;
}

