# Cross-compile GNS-SDR under Petalinux2020.1

### Install the SDK customized by MYIR
The CD image provided by MYIR contains a compiled SDK package, which is located in the 03_tools/myirtools/sdk-qt.tar.xz. Copy the SDK pakage to the working directory in ubuntu(eg:$HOME/work/). Then uncompress as follows:
```
$ cd $HOME/work
$ tar -Jxvf sdk-qt.tar.xz
$ ./sdk.sh
```