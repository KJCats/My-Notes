Title: C++ Functions
Date: 25.09.2025
Time: 11:15
Tags: [[programming]], [[c++]]

---
# C++ Functions

```c++
#include <iostream>

int addNumbers(int first_number, int second_number){
	int sum = first_number + second_number;
	return sum;
}
```

Functions follow the syntax: return_type functionName(parameters){
	body
}

```c++
int main(int argc, char **argv)
{
	int first_number = 12;
	int second_number = 9;
	
	int sum;
	sum = addNumbers(first_number, second_number);
	std::cout << "The sum of " << first_number << " and " << second_number << " is equal to " << sum << "\n";
}
```

# References