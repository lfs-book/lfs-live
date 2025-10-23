# yaml-cpp-$PKG_VER

YAML 1.2 Parser & Generator for C++

## URL: https://github.com/jbeder/yaml-cpp/archive/$PKG_VER/yaml-cpp-$PKG_VER.tar.gz

**Required Dependencies**: cmake

## Build yaml-cpp by running
```
cmake -DCMAKE_INSTALL_PREFIX=/usr \
  -DBUILD_SHARED_LIBS=ON          \
  -DYAML_BUILD_SHARED_LIBS=ON     \
  -DCMAKE_BUILD_TYPE=Release      \
  -Wno-dev .. 

ninja
```
## Now, as the root user:
```
ninja install
```

Contents

Installed Libraries: libyaml-cpp.so.0.8

Short Descriptions:
 libyaml-cpp.so: Library for yaml-cpp