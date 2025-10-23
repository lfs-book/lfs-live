# Calamares
A ultra-customizable Qt based installer for Linux Distributions

**URL:** https://github.com/calamares/calamares/releases/download/v$PKG_VER/calamares-$PKG_VER.tar.gz

**Required Dependencies:** kf6, kpmcore, yaml-cpp, polkit-qt
## Build Calamares by running
```
cmake -D CMAKE_INSTALL_PREFIX=/usr \
      -D WITH_QT6=ON \
      -Wno-dev 
      -G Ninja ..

ninja
```

# Now as the root user
```
ninja install
```


Contents

Installed Programs: calamares

Short Descriptions:
calamares - Installer binary