# this-is-test1
#include <iostream>
#include "windows.h"

using namespace std;

int main()
{
	int A, B, PA, DA, PB, DB;
	SetConsoleCP(1251);
	SetConsoleOutputCP(1251);
	cout << "Введіть A: ";
	cin >> A;
	cout << "Введіть B: ";
	cin >> B;
	PA = A / 10;
	DA = A % 10;
	PB = B / 10;
	DB = B % 10;
	(DA + DB <= PA + PB) ? printf("\n true") :
		printf("\n false");


	return 0;
}
