#include <iostream>
#include <stdio.h>
#include <limits.h>
#include <cstdlib>
#include <time.h>

using namespace std;

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char** argv) 
	{
	int i, n, move, m;
	int array1[80];
	long ltime = time (NULL);
    int stime = (unsigned int) ltime/2;
	srand(stime);
	cout << "Enter array lenght between 50 and 80" << "\n";
	cin >> n;
	if (n<50 || n > 80)
	{
		cout << "Try again" << "\n";
		cin >> n;
	}
	cout << 213241231231123 << "\n";
	for (i = 0; i < n; i++)
	{
		array1[i] = rand();
	}
	cout << 3333333 << "\n";
	for (i = 0; i < n; i++)
	{
		cout << array1[i] << "   ";
	}
	cout << "enter move number  \n";
	cin >> move;
	for (int m = 0; m < n - move; m++)
	{
		array1[m] = array1[m+move];
		cout << array1[m] << "   ";
	}
	}
