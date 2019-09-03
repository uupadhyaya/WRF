# WRF
Installation and configuration of WRF version 3.9 and WRF-Chem 3.9 with KPP in OpenSUSE Leap 42.2

# Installation of WRFv 3.9

### Softwares installed using Zypper

zypper install -t pattern devel_C_C++

zypper install -t pattern devel_basis

### Linking Software Packages

ln –sf /usr/bin/gcc-6 /usr/bin/cc
ln –sf /usr/bin/gcc-6 /usr/bin/gcc
ln –sf /usr/bin/cpp-6 /usr/bin/cpp
ln -sf /usr/bin/gcc-ar-6 /usr/bin/gcc-ar
ln -sf /usr/bin/gcc-nm-6 /usr/bin/gcc-nm




