# clear

**Description :**
    This method is used to remove all the elements from the set and make its size zero

**Example :**
```cpp
//Run code to demonstrate use of set.clear()
#include<iostream>
#include<set>

int main(){
    // Create a set object holding integers
    std::set<int> myset {1, 2, 3, 4, 5};
    myset.clear();
    std::cout << "Size of myset is : " << myset.size() << std::endl;

    return 0;
}

```
**[Run Code](https://ideone.com/14Ccn)**

