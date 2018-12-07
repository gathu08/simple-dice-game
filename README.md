#include <iostream>
#include <string>
#include <iomanip>
#include <cstdlib>
#include<ctime>
using namespace std;
int main()
{ 
	// simple dice game 
	srand(time(0));
	for (int i = 0; i < 10; i++)
	{
		int die1 = 1 + rand() % 6;
		int die2 = 1 + rand() % 6;

		cout << die1 << " " << die2 << endl;


	}
	cout << "\n";
	
	system("PAUSE");
	return 0;

}
