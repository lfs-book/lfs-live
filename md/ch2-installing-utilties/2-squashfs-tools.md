
# squashfs-tools-$PKG_VER
Tools for squashfs, a highly-compressed read-only UNIX compliant file system outputted to a single file


## URL: https://github.com/plougher/squashfs-tools/archive/refs/tags/$PKG_VER.tar.gz // todo fix


## Build squashfs-tools by running
```
make \
 GZIP_SUPPORT=1 \
 XZ_SUPPORT=1 \
 ZSTD_SUPPORT=1 \
 LZMA_XZ_SUPPORT=1 \
 XZ_SUPPORT=1 \
 XATTR_SUPPORT=1 \
```

## Now, as the root user:
```
make install
```

Command Explanations:
*_SUPPORT: Enable support for various compression libraries and file attributes, for this book we'll primarly be recommending ZSTD or XZ.  
  
LZ4_SUPPORT=1: Support for the LZ4 compression standard, use this if you want faster speeds at the cost of compression efficency  


Contents

Installed Programs: mksquashfs, sqfscat, sqfstar, unsquashfs

Short Descriptions:
mksquashfs: Make a squashfs from a specific disktop
unsquashfs: Uncompress a squashfs filesystem to disk
sqfscat: Cat files from a squashfs filesystem without uncompressing everything. 
sqfstar: Create a squashfs from a tar file

