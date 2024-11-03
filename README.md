# Lab-Task-06
TASK 0:
Using  nested For Loop:
```cpp
#include <iostream>
using namespace std;
int main() {
  for (int i=1;i<=7;i++)
  {
    for(int j=1;j<=i;j++)
    {
      cout<<"*";
  }
  cout<<endl;
}
}
```
OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/2e072b12-0b11-4454-9303-464fa349e567)

Using Nested While Loop:
```cpp
#include <iostream>
using namespace std;
int main() {
  int i=1;
  while(i<=7)
  {
    int j=1;
    while(j<=i)
    {
      cout<<"*";
      j++;
    }
    cout<<endl;
    i++;
  }
}
```
OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/4b294613-d90d-447b-9338-cdf3f3af6675)

TASK 02:
Using For loop:

```cpp
#include <iostream>
using namespace std;
int main() {
  for(int i=1;i<=5;i++)
  {
    for(int j=1;j<=i;j++)
    {
      cout<<j;
    }
    cout<<endl;
  }
}
```
OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/6978b185-8809-489f-bc97-8cc99180f973)

Using Nested While Loop:

```cpp
#include <iostream>
using namespace std;
int main() {
  int i=1;
  while(i<=5)
  {
    int j=1;
    while(j<=i)
    {
      cout<<j;
      j++;
    }
    cout<<endl;
    i++;
  }
}
```
OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/8dfc5e23-1448-49bb-8d0a-bb5aa4ecdf01)

TASK 03:
Using For Loop:

```cpp
#include <iostream>
using namespace std;
int main() {
  for(int i=1;i<=7;i++)
  {
    for(int j=1;j<=i;j++)
    {
      cout<<i;
    }
    cout<<endl;
  }
}
```
OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/f840095f-4d73-4dbf-acf1-f94f8e322efd)

Using Nested While Loop:

```cpp
#include <iostream>
using namespace std;
int main() {
  int i=1;
  while(i<=7)
  {
    int j=1;
    while(j<=i)
    {
      cout<<i;
      j++;
    }
    cout<<endl;
    i++;
  }
}
```
OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/f01a6d91-dd7b-4e25-b3e7-489345f8dec8)

TASK 04:
Using For Loop:

```cpp
#include <iostream>
using namespace std;
int main() {
  for(int i=1;i<=3;i++)
  {
    cout<<"weak"<<i<<endl;
    for(int j=1;j<=7;j++)
    {
      cout<<"Day"<<j<<endl;
    }
    cout<<endl;
  }
}
```
OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/ab5abcb7-eb72-456b-b271-fa1319b299bb)

Using Nested While Loop:

```cpp
#include <iostream>
using namespace std;
int main() {
  int i=1;
  while(i<=3)
  {
    cout<<"Weak"<<i<<endl;
    int j=1;
    while(j<=7)
    {
      cout<<"Day"<<j<<endl;
      j++;
    }
    i++;
  }
}
```
OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/80c37cdd-b4e8-4d6e-aa19-8bcd2b2d47df)



