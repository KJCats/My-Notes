Title: C++ Input and Output
Date: 25.09.2025
Time: 11:31
Tags: [[programming]], [[c++]]

---
# C++ Input and Output

| stream    | Purpose                              | Buffered |
| --------- | ------------------------------------ | -------- |
| std::cout | Printing data to the console         | True     |
| std::cin  | Reading data from the terminal       | True     |
| std::cerr | Printing errors to the console       | False    |
| std::clog | Printing log messages to the console | True     |

```c++
#include <iostream>

int main() {
	std::cout << "std::cout output\n";
	std::cerr << "std::cerr output : Something went wrong\n";
	std::clog << "std::clog output : This is a log message\n";
	
	
	int birth_year;
	std::cout << "Enter your birth year:\n";
	std::cin >> birth_year;
	
	int year;
	std::cout << "Enter the current year:\n";
	std::cin >> year;
	
	std::string first_name;
	std::string last_name;
	std::cout << "Enter your First and Last name, seperated by spaces:\n";
	std::cin >> first_name >> last_name
	
	std::cout << "Hello " << first_name << last_name << "."
}
```

# References