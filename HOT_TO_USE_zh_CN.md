# 如何使用

1. 在 `qclassgen.py` 的同级目录下建立要给 `build` 文件夹

2. 编写你的类的**头文件**， 然后在必要的地方写入一句 `#include "YOURCLASS.gen"`

3. 在控制台输入 

    ```
    qclassgen.py YOURCLASS.h build/YOURCLASS.gen build/YOURCLASS.cpp
    ```