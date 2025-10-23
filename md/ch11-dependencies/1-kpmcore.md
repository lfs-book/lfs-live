# kpmcore-$PKG_VER

KDE Library for managing partitions within Qt applications

## URL: https://download.kde.org/stable/release-service/$PKG_VER/src/kpmcore-$PKG_VER.tar.xz

**Required Dependencies**: kf6, smartmontools, polkit-qt, dosfstools, and exfatprogs
**Optional Dependencies**: ntfs-3g, btrfs-progs, xfs-tools

## Build kpmcore by running
```
SKIP_OPTIONAL='LibSpectre;CHM;LibZip;DjVuLibre;EPub;QMobipocket;Discount'

cmake -DCMAKE_INSTALL_PREFIX=/usr \
      -DCMAKE_BUILD_TYPE=Release         \
      -DBUILD_TESTING=OFF                \
      -DFORCE_NOT_REQUIRED_DEPENDENCIES="$SKIP_OPTIONAL" \
      -Wno-dev -G Ninja ..

ninja

```
## Now, as the root user:
```
ninja install
```

Contents

Installed Libraries: libkpmcore.so.13

Short Descriptions:
 libkpmcore.so: Library to expose KPM functions