# Cross-compile GNS-SDR under Petalinux2020.1

### Install the SDK customized by MYIR
The CD image provided by MYIR contains a compiled SDK package, which is located in the 03_tools/myirtools/sdk-qt.tar.xz. Copy the SDK pakage to the working directory in ubuntu(eg:$HOME/work/). Then uncompress as follows:
```
$ cd $HOME/work
$ tar -Jxvf sdk-qt.tar.xz
$ ./sdk.sh

PetaLinux SDK installer version 2020.1
======================================
Enter target directory for SDK (default: /opt/petalinux/2020.1):
...
```

### Install pip3 and python packages
 ```
 $ sudo tar xvf pip3.tar.xz -C /
 $ sudo tar xvf site-packages.tar.xz -C /

 $ tar pip-24.0.tar.gz
 $ cd pip-24.0/
 $ sudo /opt/petalinux/2020.1/sysroots/x86_64-petalinux-linux/usr/bin/python3 setup.py install

 ```

 check python3 and pip3 list
 ```
 $ sudo /opt/petalinux/2020.1/sysroots/x86_64-petalinux-linux/usr/bin/python3 --version
 Python 3.7.6

 $ sudo /opt/petalinux/2020.1/sysroots/x86_64-petalinux-linux/usr/bin/pip3 list
 Package            Version
 ------------------ ---------
 certifi            2025.6.15
 charset-normalizer 3.4.2
 idna               3.10
 importlib-metadata 6.7.0
 Mako               1.2.3
 MarkupSafe         2.1.5
 meson              0.51.2
 numpy              1.21.6
 pip                24.0
 pyelftools         0.32
 requests           2.31.0
 setuptools         41.2.0
 typing_extensions  4.7.1
 UNKNOWN            0.0.0
 urllib3            2.0.7
 wheel              0.42.0
 zipp               3.15.0
 ```
