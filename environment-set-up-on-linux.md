---
description: '#Visual Studio Code #C++ #C #Linux'
---

# Environment Set Up On Linux

## Contents

### Install VScode&#x20;

{% embed url="https://code.visualstudio.com/docs/setup/linux" %}
how to install vscode on linux
{% endembed %}



### Install C/C++ extension

1. Open VS Code.
2. Select the Extensions view icon on the Activity bar or use the keyboard shortcut (Ctrl+Shift+X).
3. Search for `'C++'`.
4. Select **Install**.&#x20;



### Check Compiler

```bash
g++ version
```



### Hello World

#### Create Directory and Add Source file

```
mkdir Algorithm
cd Algorithm
code .
touch hello
```



#### Add Source Code&#x20;

```cpp
#include <iostream>

int main()
{
    std::cout << "Hello World" << std::endl;
}
```



#### Build Source Code&#x20;

1. Click Terminal > Run Build Task (or Use Keyboard Shortcut 'Ctrl + Shift + B')
2. check gcc toolset(compiler)(select 'C/C++: g++ build active File 'compiler: /usr/bin/g++')



#### Run Hello World

1. open Terminal&#x20;
2. type './helloworld'
3. if you check 'Hello World', It's success

## Reference

[https://code.visualstudio.com/docs/languages/cpp](https://code.visualstudio.com/docs/languages/cpp)
