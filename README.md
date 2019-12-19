MinGW-w64安装教程——著名C/C++编译器GCC的Windows版本：https://www.jianshu.com/p/d66c2f2e3537

安装c/c++、code runner扩展

c/c++扩展主要使用它的代码智能提示(c_cpp_properties.json)，任务构建(tasks.json) 配起来比较麻烦，建议code runner替代它，代码调试(launch.json)功能需要debugger的时候使用。所以一般只需要配置个c_cpp_properties.json用于代码提示，然后code runner来执行代码就足够了。

code runner扩展主要用于执行代码

这两个扩展都依赖于MinGW，所以使用前要先安装好MinGW

c/c++扩展配置教程：https://code.visualstudio.com/docs/cpp/config-mingw

