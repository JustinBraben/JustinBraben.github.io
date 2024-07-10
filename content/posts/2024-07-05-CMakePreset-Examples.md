---
{
    .title = "CMakePreset-Examples",
    .date = @date("2020-07-06T00:00:00"),
    .author = "Justin Braben",
    .draft = false,
    .layout = "page.html",
    .tags = [],
}  
--- 

# CMakePreset Examples

CMake is a blessing and curse. It is marvelous how it allows you to cross platform develop to fully
with C++. However the syntax and developer experience when new to it leaves much to be desired.

For the past year or so I have been using CMake pretty much exclusively for my C++ projects. I would like to 
share some examples in CMake that hopefully help you not fall into the same rabbit holes I found myself in.


```
cmake_minimum_required(VERSION 3.21)
```