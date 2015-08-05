
A simple cef3 client with Qt.

![](https://github.com/j1111011/qtcefclient/blob/master/qcef3_1650.jpg?raw=true)


Build
-----

* QT5.5.0 for msvc2013
* CEF 3.2357.1281.gd660177

You can download CEF3 here: [CEF3 Builds](http://cefbuilds.com/).

* Extract the following and copy to `qcef3_1650/`.

```
Debug/
Release/
include/
Resources/
libcef_dll/
```

* 

* Open `qcef3_1650/qcef3_1650.sln`, then build. (VS 2013)


Project
-------

* cefclient
    - the main cef3 client project
* cefclient_process
    - a separate sub-process executable project
    - `SUB_PROCESS_DISABLED` option in `cefclient.cpp`
* libcef_dll
    - cef3's c++ wrapper
