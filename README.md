# Calculate
#include <iostream>
using namespace std;

int x, y;

void getValue() {

	cout << "your first number: ";
	cin >> x;
	cout << "your second number: ";
	cin >> y;
}

void Calculation() {

	char symbol;
	cout << "* / + -";
	cout << "Choose a mathematical sign: ";
	cin >> symbol;

	switch (symbol)
	{
	case '+': cout << "Result: " << x + y;
		break;
	case '-': cout << "Result: " << x - y;
		break;
	case '/': cout << "Result: " << x / y;
		break;
	case '*': cout << "Result: " << x * y;
		break;
	}
}

int main() {
	getValue();
	Calculation();
}
