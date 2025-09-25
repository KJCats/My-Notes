Title: C++ Functions
Date: 25.09.2025
Time: 11:15
Tags: [[programming]], [[c++]]

---
# C++ Functions

```c++
#include <iostream>

int addNumbers(int first_number, int second_number) {
	return first_number + second_number;
}
```

Functions follow the syntax: return_type functionName(parameters){
	body
}

```c++
#include <iostream>
using namespace std;

int addNumbers(int first_number, int second_number) {
	return first_number + second_number;
}

int main() {
	int first_number {3};
	int second_number {7};
	
	cout << "First Number: " << first_number << "\n";
	cout << "Second Number: " << second_number << "\n";
	
	int sum {addNumbers(first_number, second_number)};
	cout << "Sum: " << sum << "\n";
	
	return 0;
}
```


# References