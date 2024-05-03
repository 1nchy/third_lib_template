# THIRD_LIB_TEMPLATE

## 简述

这是一个我自己使用的基于 CMake 的第三方库的模板。

~~~txt
third_lib
├── .gitignore
├── CMakeLists.txt
├── LICENSE.md
├── README.md
├── doc                         # 项目文档
│   └── ...
├── include                     # 头文件（对外使用）
│   └── ...
├── src                         # 源文件
│   └── ...
├── example                     # 示例
│   └── ...
├── lib                         # 静态/动态链接库生成文件夹（对外使用）
│   └── ...
└── .vscode                     # 可用于 vscode 调试的配置
    └── ...
~~~