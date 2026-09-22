# luce-tiff

A TIFF reader and writer for Luce/Base: strips and tiles, uncompressed, PackBits, LZW and Deflate.

Split out of luce-image on 2026-09-22 so every file format is its own package, like luce-svg and luce-psd. luce-image depends on it for `Image.open`/`save`; it depends on luce-raster, luce-deflate.

```
./test.sh    # the module's test blocks in native and C modes
```
