### Variables
- the variable for number is `int` 
- The Maximum value for Integers (int) is `2147483647` 


- the variable for character is `char`
- The Maximum value for char is `127`

- the variable for strings is `string`

- int
- float
- char
- string
- boolean
- double
- long long

### Assignment operator
num1 + 1 = num1++
1 + num1 = ++num1

num2 - 1 = num2--
1 - num2 = --num2

### Division and Modulus
#### Division
12345 / 10 = 1234
12345 / 100 = 123
12345  / 1000 = 12
12345 / 10000 = 1
12345 / 100000 = 0

#### Modulus
12345 % 10 = 5
12345 % 100 = 45
12345 % 1000 = 345
12345 % 10000 = 2345
12345 % 100000 = 12345

NOTE : Number %2 = 
	0 if the number is even
	1 if the number is odd





### OTHER
Use setprecision(9) to print 9 digits after decimal point.
to use it we must import the iomanip `#include <iomanip>`
example 
```c++
#include <iostream>
#include <iomanip>
using namespace std;
int main() {
	long long R;
	double pi = 3.141592653,area;
	cin >> R;
	area = pi * (R * R);
	cout<< fixed<<setprecision(9)<<area;
	return 0;
}
```

- to calculate the summation of numbers from 1 to your number use `(N*(N+1))/2`
![[Pasted image 20241005141740.png]]

- if we will use [ascii table](https://www.ascii-code.com/) we must use a `char` variable 


