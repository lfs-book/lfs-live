
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
*_SUPPORT: Enable support for various compression libraries and file attributes
LZ4_SUPPORT=1: Support for the LZ4 compression standard, use this if you want faster speeds at the cost of compression efficency


Contents

Installed Programs: lz mattrib mbadblocks mcat mcd mcheck mcomp mcopy mdel mdeltree mdir mdoctorfat mdu mformat minfo mkmanifest mlabel mmd mmount mmove mpartition mrd mren mshortname mshowfat mtools mtoolstest mtype mxtar mzip tgz uz floopy

Short Descriptions
lz: 
mattrib: 
mbadblocks: 
mcat: 
mcd: 
mcheck: 
mcomp: 
mcopy: 
mdel: 
mdeltree: 
mdir: 
mdoctorfat: 
mdu: 
mformat: 
minfo: 
mkmanifest: 
mlabel: 
mmd: 
mmount: 
mmove: 
mpartition: 
mrd: 
mren: 
mshortname: 
mshowfat: 
mtools: 
mtoolstest: 
mtype: 
mxtar: 
mzip: 
tgz: 
uz: 


