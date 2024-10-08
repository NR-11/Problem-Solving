### A
```c++
#include <iostream>
using namespace std;
int main() {
	string x;
	cin >> x;
	cout << "Hello, " << x;
	return 0;
}
```

---
### B
```c++
#include <iostream>
using namespace std;
int main() {
	int x1;
	long long x2;
	char x3;
	float x4;
	double x5;
	cin >> x1 >> x2 >> x3 >> x4 >> x5;
	cout << x1 << endl << x2 << endl << x3 << endl << x4 << endl << x5;
	return 0;
}
```

---
### C
```c++
1. #include <iostream>
2. using namespace std;
3. int main() {
5. long long x, y , sum1, sum2,sum3;
6. cin >> x >> y;
7. sum1 = x + y;
8. sum2 = x * y;
9. sum3 = x - y;
10. cout << x << " + " << y<<" = "<< sum1 << endl << x << " * " << y <<" = " << sum2 << endl << x << " - " << y << " = " << sum3 ;
11. return 0;
12. }
```

---
### D
```c++
#include <iostream>
using namespace std;
int main() {
	long long a,b,c,d,x;
	cin >> a >> b >> c >> d;
	x = (a*b) - (c*d);
	cout << "Difference = " << x;
	return 0;
}
```
---
### E
```c++
#include <iostream>
#include <iomanip>
using namespace std;
int main() {
	float R;
	double pi = 3.141592653,area;
	cin >> R;
	area = pi * (R * R);
	cout<< fixed<<setprecision(9)<<area;
	return 0;
}
```
---
### F
```c++
#include <iostream>
#include <iomanip>
using namespace std;
int main() {
	long long a, b,c;
	cin >> a >> b;
	c = (a % 10) + (b % 10);
	cout <<c;
	
	return 0;
}
```
NOTE : i use `number % 10 ` to get the last number

---
### G
```c++
#include <iostream>
using namespace std;
int main() {
	long long x,y;
	cin >> x;
	y = (x * (x + 1)) / 2;
	cout << y;
	return 0;
}
```
NOTE : to calculate the summation of numbers from 1 to your number use `(N*(N+1))/2`

---
### H
```c++
```
---
### I 
```c++
#include <iostream>
using namespace std;
int main() {
	long long a, b;
	cin >> a >> b;
	if (a >= b) {
		cout << "Yes";
	}
	else {
		cout << "No";
	}
	return 0;
}
```
---
### J
```c++
#include <iostream>
using namespace std;
int main() {
	long long a, b;
	cin >> a >> b;
	if (a % b == 0 || b % a == 0) {
		cout << "Multiples";
	}
	else {
		cout << "No Multiples";
	}
	return 0;
}
```
---
### K
```c++
#include <iostream>
using namespace std;
int main() {
	int a, b, c;
	cin >> a >> b >> c;
	if (a <= b && a <= c) {
		if (b > c) {
			cout << a << " " << b;
		}
		else {
			cout << a << " " << c;
		}
	}
	else if (b <= a && b <= c) {
		if (a >= c) {
			cout << b << " " << a;
		}
		else {
			cout << b << " " << c;
		}
	}
	else if (c <= a && c <= b) {
		if (a > b) {
			cout << c << " " << a;
		}
		else {
			cout << c << " " << b;
		}
	}
	return 0;
}
```
---
### L
```c++
#include <iostream>
using namespace std;
int main() {
	string f1, l1;
	cin >> f1 >> l1;
	string f2, l2;
	cin >> f2 >> l2;
	if (l1 == l2) {
		cout << "ARE Brothers";
	}
	else {
		cout << "NOT";
	}
	return 0;
}

```
---
### M
```c++
#include <iostream>
using namespace std;
int main() {
	char x;
	cin >> x;
	if (x >= 'A' && x <= 'Z') {
		cout << "ALPHA" << endl<<"IS CAPITAL";
	}
	else if (x >= 'a' && x <= 'z') {
		cout << "ALPHA" << endl << "IS SMALL";
	}
	else if (x >= '0' && x <= '9') {
		cout << "IS DIGIT";
	}
	return 0;
}
```
---
### N
```c++
#include <iostream>
using namespace std;
int main() {
	char x,y;
	cin >> x;
	if (x >= 'A' && x <= 'Z') {
		y = x + 32;
		cout << y;
	}
	else if (x >= 'a' && x <= 'z') {
		y = x - 32;
		cout << y;
	}
	return 0;
}
```
---
### O
```c++
#include <iostream>
using namespace std;
int main() {
	long long x,z,a;
	char y;
	cin >> x>>y>>z;
	if (y == '+') {
		a = x + z;
		cout << a;
	}
	else if (y == '-') {
		a = x - z;
		cout << a;
	}
	else if (y == '*') {
		a = x * z;
		cout << a;
	}
	else if (y == '/') {
		a = x / z;
		cout << a;
	}
	return 0;
}
```
---
### P
```c++
#include <iostream>
using namespace std;
int main() {
	long long x,y;
	cin >> x;
	y = x / 1000;
	if (y % 2 == 0) {
		cout << "EVEN";
	}
	else {
		cout << "ODD";
	}
	return 0;
}
```
---
### Q
```c++
```

---
### R
```c++
#include <iostream>
using namespace std;
int main() {
	long long x,y,m,d,lol;
	cin >> x;
	y = x / 365;
	cout << y << " years"<<endl ;
	m = (x % 365) / 30;
	cout << m << " months"<<endl;
	d = (x % 365)%30;
	cout << d << " days";
	return 0;
}
```
---
### S
```c++
```
---
### T
```c++
```
---
### U
```c++
```
---
### V
```c++
```
---
### W
```c++
```
---
### X
```c++
```
---
### Y
```c++
```
---
### Z
```c++
```