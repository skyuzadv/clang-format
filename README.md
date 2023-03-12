vscode + llvm + clangd + cmake 环境下程序开发配置文件

.clang 配置文件：

`.clang-format`

`.clang-tidy`

llvm 参数配置文件：`clangd-arguments.json` ：用作代码静态分析

users-snippets ：用户代码片段

`c.json`, `cpp.json`

`.gitignore` 添加git忽略文件或者文件夹
参考GitHub官方：`gitignore` 项目，提供各种编程语言定制的忽略文件或者文件夹模板，几乎不用修改拿来可以使用。
官方为Visual Studio项目订制的一个.gitignore文件
`gitignore`项目链接：https://github.com/github/gitignore

开发环境配置：
`windows ： clangd + cmake + cmake tools + codelldb + doxygen documentation generator'
clangd : C/C++ completion, navigation, and insights

cmake :CMake langage support for Visual Studio Code
notes:计算机本地需要安装cmake software

cmake tools:
Extended CMake support in Visual Studio Code

codelldb:
A native debugger powered by LLDB. Debug C++, Rust and other compiled languages

doxygen documentation generator:
Let me generate Doxygen documentation from your source code for you

arh + wsl:
`arhlinux ：wsl + clangd + cmake + cmake tools + codelldb + doxygen documentation generator'