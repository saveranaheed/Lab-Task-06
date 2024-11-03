# Lab-Task-06
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
Output]![task 6 1 1](https://github.com/user-attachments/assets/4b294613-d90d-447b-9338-cdf3f3af6675)



