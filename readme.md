Automated builds of **libcurl** using vcpkg.

Compiled as completely standalone dynamic libraries (.dll) using the Static C Runtime (/MT) with Control Flow Guard (CFG) enabled.

Releases contain `libcurl.dll` formatted in a `$arch\Release\` directory structure.

To obtain the latest release in a build environment:

```
cd path\to\libcurl
del libcurl.zip
curl -LJO https://github.com/MediaArea/libcurl-Windows/releases/latest/download/libcurl.zip
tar -xf libcurl.zip
```
