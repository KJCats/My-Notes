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
	
	int age {20};
	std::cout << "Age: " << age << "\n";
	
	std::cerr << "std::cerr output : Something went wrong\n";
	std::clog << "std::clog output : This is a log message\n";
	
	
	std::string name;
	
	std::co
}
```

# References