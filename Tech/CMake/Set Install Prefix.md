# Set the install prefix

* Using the follow command to configure
``` bash
cmake ..\src -DCMAKE_INSTALL_PREFIX=<MY INSTALL PREFIX PATH>
```

* Using the follow command to install
``` bash
cmake --build . --config Debug --target install
```
