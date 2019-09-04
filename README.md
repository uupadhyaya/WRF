### Create a setenv.sh in /home/<username> directory

  
export PS1='\[\e[1;32m\][\u@\h \W]\$\[\e[0m\]’  
### Resources Limits      
ulimit -s unlimited  

### System Configuration  
export OPENSSL=openssl  
export YACC="yacc -d"  
export J="-j 12"  

### Alias  
LSCOLOR="--color=auto"  
alias ls="ls $LSCOLOR"  
alias ll="ls -lh $LSCOLOR"  
alias la="ls -Ah $LSCOLOR"  
alias lo="ls -lAh $LSCOLOR"  
alias lz="ls -lAhZ $LSCOLOR"  
alias l="ls -lAh $LSCOLOR"  

alias cd..="cd .."  
alias ..="cd .."  
alias c="clear"  
alias e="exit"  
alias k="pkill -u $USER"  
alias top="top -c"  

### Compilers 

export CC=gcc  
export FC=gfortran  
export SERIAL_FC=gfortran  
export SERIAL_F77=gfortran  
export SERIAL_CC=gcc  
export SERIAL_CXX=g++  
export MPI_FC=mpif90  
export MPI_F77=mpif77  
export MPI_CC=mpicc  
export MPI_CXX=mpicxx  

### Set Environment Variables
export PATH=./:$PATH  
export PATH=$HOME/bin:$PATH  

## Directories 

### Define Compiler Directories  

export GCCHOME=$COMPILERS/Gcc  

### Define Common Directories

export DEVELOPS=$HOME/Develops  
export MODULES=$HOME/Modules  
export COMPILERS=$DEVELOPS/Compilers  
export DEPENDENCIES=$DEVELOPS/Dependencies  
export WRF=$DEVELOPS/WRF  
export WRFHOME=$WRF/WRFV3  

export MPIHOME=$DEPENDENCIES/MPIs  
export GRIB2HOME=$DEPENDENCIES/Grib2  
export NCLHOME=$DEPENDENCIES/Ncl  
export JASPERHOME=$GRIB2HOME/Jasper  
export LIBPNGHOME=$GRIB2HOME/LibPNG  
export FLEXHOME=$DEPENDENCIES/Flex  
export NETCDFHOME=$DEPENDENCIES/NetCDF  
export ZLIBHOME=$DEPENDENCIES/Zlib  
export GMPHOME=$DEPENDENCIES/Gmp  
export M4HOME=$DEPENDENCIES/M4  
export MPFRHOME=$DEPENDENCIES/Mpfr  
export MPCHOME=$DEPENDENCIES/Mpc  
export GOHOME=$DEPENDENCIES/Go  
export MPICHHOME=$DEPENDENCIES/Mpich  
export AUTOCONFHOME=$DEPENDENCIES/Autoconf  
export LIBTOOLHOME=$DEPENDENCIES/Libtool  
export AUTOMAKEHOME=$DEPENDENCIES/Automake  
export FLEXHOME=$DEPENDENCIES/Flex  
export BYACCHOME=$DEPENDENCIES/Byacc  
export INTLTOOLHOME=$DEPENDENCIES/Intltool  
export CMAKEHOME=$DEPENDENCIES/Cmake  
export DOXYGENHOME=$DEPENDENCIES/Doxygen  
export CDOHOME=$DEPENDENCIES/Cdo  
export NCOHOME=$DEPENDENCIES/Nco  
export UDUNITSHOME=$DEPENDENCIES/UdUnits  
export ANTLRHOME=$DEPENDENCIES/Antlr  
export HDF5HOME=$DEPENDENCIES/Hdf5  
export BISONHOME=$DEPENDENCIES/Bison  
export SZIPHOME=$DEPENDENCIES/Szip  
export TCLHOME=$DEPENDENCIES/Tcl  
export SZIPHOME=$DEPENDENCIES/Tk  
export PVMHOME=$DEPENDENCIES/Pvm  
export IOAPIHOME=$DEPENDENCIES/Ioapi  

### Versions

export ZLIBv=$ZLIBHOME/Zlib-1.2.10  
export GMPv=$GMPHOME/Gmp-6.1.2  
export M4v=$M4HOME/M4-1.4.18  
export MPFRv=$MPFRHOME/Mpfr-3.1.5  
export MPCv=$MPCHOME/Mpc-1.0.3  
export GOv=$GOHOME/Go-1.1.2  
export NETCDFv=$NETCDFHOME/NetCDF-4.4.4.1[4.4.4]  
export MPICHv=$MPICHHOME/Mpich-3.1  
export AUTOCONFv=$AUTOCONFHOME/Autoconf-2.69  
export LIBTOOLv=$LIBTOOLHOME/Libtool-2.4.6  
export AUTOMAKEv=$AUTOMAKEHOME/Automake-1.15  
export LIBPNGv=$LIBPNGHOME/LibPNG-1.6.26  
export FLEXv=$FLEXHOME/Flex-2.6.0  
export BYACCv=$BYACCHOME/Byacc-1.9  
export GEDITv=$GEDITHOME/Gedit-3.22.0  
export INTLTOOLv=$INTLTOOLv/Intltool-0.50.2  
export JASPERv=$JASPERHOME/Jasper-2.0.12  
export CMAKEv=$CMAKEHOME/Cmake-3.7.2  
export NCLv=$NCLHOME/Ncl-6.0.0  
export DOXYGENv=$DOXYGENHOME/Doxygen-1.8.11  
export CDOv=$CDOHOME/Cdo-1.8.1  
export NCOv=$NCOHOME/Nco-4.6.6  
export UDUNITSv=$UDUNITSHOME/UdUnits-2.2.24  
export ANTLRv=$ANTLRHOME/Antlr-2.7.7  
export HDF5v=$HDF5HOME/Hdf5-1.8.18  
export PNETCDFv=$PNETCDFHOME/Pnetcdf-1.8.1  
export BISONv=$BISONHOME/Bison-2.1  
export SZIPv=$SZIPHOME/Szip-2.1.1  
export TCLv=$TCLHOME/Tcl-8.6.6  
export TKv=$TKHOME/Tk-8.6.6  
export IOAPIv=$IOAPIHOME/Ioapi-3.2  

### Binary PATH
  
export PATH=$ZLIBv/bin:$PATH  
export PATH=$GCCv/bin:$PATH  
export PATH=$GMPv/bin:$PATH  
export PATH=$M4v/bin:$PATH  
export PATH=$MPFRv/bin:$PATH  
export PATH=$MPICHv/bin:$PATH  
export PATH=$AUTOCONFv/bin:$PATH  
export PATH=$LIBTOOLv/bin:$PATH  
export PATH=$AUTOMAKEv/bin:$PATH  
export PATH=$LibPNGv/bin:$PATH  
export PATH=$FLEXv/bin:$PATH  
export PATH=$CMAKEv/bin:$PATH  
export PATH=$JASPERv/bin:$PATH  
export PATH=$DOXYGENv/bin:$PATH  
export PATH=$BYACCv/bin:$PATH  
export PATH=$LIBPNGv/bin:$PATH  
export PATH=$NCLv/bin:$PATH  
export PATH=$NETCDFv/bin:$PATH  
export PATH=$CDOv/bin:$PATH  
export PATH=$NCOv/bin:$PATH  
export PATH=$UDUNITSv/bin:$PATH  
export PATH=$HDF5v/bin:$PATH  
export PATH=$PNETCDFv/bin:$PATH  
export PATH=$BISONv/bin:$PATH  
export PATH=$ANTLRv/bin:$PATH  
export PATH=$NCOv/bin:$PATH  

### Library Path
  
export LD_LIBRARY_PATH=$MPICHv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$ZLIBv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$GMPv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$MPICHv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$AUTOCONFv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$LIBTOOLv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$AUTOMAKEv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$LIBPNGv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$JASPERv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$DOXYGENv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$NCLv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$FLEXv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$NETCDFv/lib64:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$UDUNITSv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$HDF5v/lib64:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$PNETCDFv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$BISONv/lib:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$ANTLRv/lib64:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$NCOv/lib64:$LD_LIBRARY_PATH  
export LD_LIBRARY_PATH=$SZIPv/lib64:$LD_LIBRARY_PATH  

### Include Path  

export INCLUDE=$ZLIBv/include:$INCLUDE  
export INCLUDE=$GCCv/include:$INCLUDE  
export INCLUDE=$GMPv/include:$INCLUDE  
export INCLUDE=$AUTOCONFv/include:$INCLUDE  
export INCLUDE=$LIBTOOLv/include:$INCLUDE  
export INCLUDE=$AUTOMAKEv/include:$INCLUDE  
export INCLUDE=$LIBPNGv/include:$INCLUDE  
export INCLUDE=$FLEXv/include:$INCLUDE  
export INCLUDE=$JASPERv/jasper/include:$INCLUDE  
export INCLUDE=$DOXYGENv/include:$INCLUDE  
export INCLUDE=$FLEXv/include:$INCLUDE  
export INCLUDE=$MPICHv/include:$INCLUDE  
export INCLUDE=$NETCDFv/include:$INCLUDE  
export INCLUDE=$UDUNITSv/include:$INCLUDE  
export INCLUDE=$HDF5v/include:$INCLUDE  
export INCLUDE=$PNETCDFv/include:$INCLUDE  
export INCLUDE=$ANTLRv/include:$INCLUDE  
export INCLUDE=$NCOv/include:$INCLUDE  
export INCLUDE=$SZIPv/include:$INCLUDE  

### Flex
export FLEX=$FLEXHOME  
export FLEX_LIB_DIR=$FLEXv/lib  

### Hdf5
export HDF5DIR=$HDF5v  
export HDF5_DIR=$HDF5DIR  
export HDF5_LIB_DIR=$HDF5v/lib  

### Netcdf
export NETCDF_HOME=$NETCDFv  
export NETCDF_PREFIX=$NETCDF_HOME  
export NETCDF_INC=$NETCDFv/include  
export NETCDF_LIB=$NETCDFv/lib64  
export NETCDF4_LIB=$NETCDF_LIB  
export NETCDF_ROOT=$NETCDFv  
export NETCDF4_ROOT=$NETCDFv  
export NETCDF=$NETCDF_ROOT  

### Jasper
export JASPERLIB=$JASPERv/lib  
export JASPERINC=$JASPERv/include  

### Ncl
export NCL_NCARG=$NCLv  

### WRF
export WRFV3=$WRFHOME  
export WRF_SRC_ROOT_DIR=$WRFHOME  
export WRF_EM_CORE=1  
export WRF_NMM_CORE=0  
export WRFIO_NCD_LARGE_FILE_SUPPORT=1  

### WRFChem  
export WRF_CHEM=1  
export WRF_KPP=1  

### UdUnits  
export UDUNITS_PATH=$UDUNITSv  
export UDUNITS2_PATH=$UDUNITSv  

### Antlr  
export ANTLR_PATH=$ANTLRv  
export CLASSPATH=$ANTLRv:$CLASSPATH  

### PVM
export PVM_ROOT=/usr/lib/pvm3  
export PVM_ARCH=LINUX64  
export PVM_RSH=/usr/bin/ssh  
export PATH=$PVM_ROOT/bin:$PATH  
export PVM_ARCH=LINUX64  

### Ioapi
export BIN=Linux2_x86_64gfort  
export PATH=$IOAPIv/Linux2_x86_64gfort/bin:$PATH  

# WRF
Installation and configuration of WRF version 3.9 and WRF-Chem 3.9 with KPP in OpenSUSE Leap 42.2

## Installation of WRFv 3.9  

### Softwares installed using Zypper  

zypper install -t pattern devel_C_C++  
zypper install -t pattern devel_basis  

### Linking Software Packages  

ln –sf /usr/bin/gcc-6 /usr/bin/cc    
ln –sf /usr/bin/gcc-6 /usr/bin/gcc  
ln –sf /usr/bin/cpp-6 /usr/bin/cpp  
ln -sf /usr/bin/gcc-ar-6 /usr/bin/gcc-ar  
ln -sf /usr/bin/gcc-nm-6 /usr/bin/gcc-nm

### Software Installed from Source 

Tcl version 8.6.6  
./configure --prefix=$TCLv  

Tk version 8.6.6  
./configure --prefix=$Tkv  

Autoconf version 2.69  
./configure --prefix=$AUTOCONFv  

Automake version 1.15  
./configure --prefix=$AUTOMAKE  

M4 version 1.4.18  
./configure --prefix=$M4v  

Flex version 2.6.0  
./configure --prefix=$FLEXv  

Zlib version 1.2.10  
./configure --prefix=$ZLIBv  
Szip version 2.1.1  
./configure --prefix=$SZIPv  

Byacc version 1.9  
cp Byacc-1.9 $BYACCv  
tar zxvf byacc.1.9.tar.Z   

Intltool version 0.50.2  
./configure --prefix=$INTLTOOLv     

Jasper version 2.0.12  
export JAS_ENABLE_AUTOMATIC_DEPENDENCIES=false  
cmake -G "Unix Makefiles" -H$HOME/Tarballs/jasper-2.0.12 -B$JASPERv -DCMAKE_INSTALL_PREFIX=$JASPERv $OPTIONS  

Libpng version 1.6.26  
export LDFLAGS=-L/home/uupadhyaya/Develops/Dependencies/Zlib/Zlib-1.2.8/lib  
export CPFLAGS=-I/home/uupadhyaya/Develops/Dependencies/Zlib/Zlib-1.2.8/include  
./configure --prefix=$LIBPNGv  

Bison version 2.1  
./configure --prefix=$BISONv  

Doxygen version 1.8.11  
./configure --prefix=$DOXYGENv  

Antlr version 2.7.7  
./configure --prefix=$ANTLRv  

Udunits version 2.2.24  
./configure --prefix=$UDUNITSv  

Mpich version 3.1  
export CFLAGS="-D_LARGEFILE_SOURCE -D_LARGEFILE64_SOURCE -D_FILE_OFFSET_BITS=64"  
./configure --prefix=$MPICHv --enable-shared  

Hdf5 version 1.8.18  
export FC=gfortran  
export CC=gcc  
export CXX=''  
./configure --prefix=$HDF5v --enable-fortran --enable-shared --enable-hl --enable-unsupported --enable-cxx   --with-zlib=$ZLIBv --with-pic \  
            2>&1 | tee $HDF5v.config            
make 2>&1 | tee $HDF5v.make --prefix=$HDF5v    
make install 2>&1 | tee $HDF5v.install  

NetCDF version 4.4.1.1    
export CPPFLAGS="-I${NETCDFv}/include -I${HDF5v}/include"    
export LDFLAGS="-L${NETCDFv}/lib64 -L${HDF5v}/lib64"  
export NETCDF_LIBS="-I$(NETCDFv)/include -L$(NETCDFv)/lib64 -lnetcdff -lnetcdf"  
export CC=gcc  

export FC=gfortran  
./configure --prefix=$NETCDFv --disable-dap --enable-netcdf-4 --enable-logging --enable-fortran --enable-shared  
NetCDF FORTRAN version 4.4.4    
export INCDF="-I${NETCDFv}/include"   
export LNCDF="-L${NETCDFv}/lib64"  
export CPPFLAGS="-DgFortran $INCDF -I${HDF5v}/include"  
export LDFLAGS="$LNCDF -L${HDF5v}/lib -fPIC"  
export NETCDF_LIB=$NETCDFv/lib64  
export NETCDF_INC=$NETCDFv/include  
./configure --enable-large-file-tests --disable-shared --prefix=$NETCDFv 2>&1 | tee $NETCDFv.config  
make 2>&1 | tee $NETCDFv.make  
make install 2>&1 | tee $NETCDFv.install  
// Note: Earlier versions of NetCDF was bundled with NetCDF-C and NetCDF-Fortran. However, with newer   versions, NetCDF-C and NetCDF-Fortran come in different packages. WRFv3.6 was compiled with NetCDF version  4.1.3. //  

### Link the following software libraries
  
ln –sf /home/<username>/Develops/Dependencies/NetCDF/NetCDF-4.4.4.1[4.4.4]/lib64/libnetcdf.a  /usr/lib/libnetcdf.a
ln –sf /home/<username>/Develops/Dependencies/NetCDF/NetCDF-4.4.4.1[4.4.4]/lib64/libnetcdff.a /usr/lib/libnetcdff.a
ln -sf /home/<username>/Develops/Dependencies/Bison/Bison-2.1/bin/yacc /usr/bin/yacc  
cp /home/<username>/Develops/Dependencies/Hdf5/Hdf5-1.8.18/lib64/libhdf5*a /home/uupadhyaya/Tarballs/ioapi-3.2/Linux2_x86_64gfort/.
cp /home/<username>/Develops/Dependencies/Hdf5/Hdf5-1.8.18/lib64/libnetcdf*.a /home/<username>/Tarballs/ioapi-3.2/Linux2_x86_64gfort/.
cp /home/<username>/Develops/Dependencies/Zlib/Zlib-1.2.12/lib/*.a /home/uupadhyaya/Tarballs/ioapi-3.2/Linux2_x86_64gfort/.
  
Cdo version 1.8.1 rc2  
export CFLAGS=-fPIC --enable-netcdf-4 --enable-zlib --with-hdf5=$HDF5v --with-jasper=$JASPERv --with-  netcdf=$NETCDFv  
./configure --prefix=$CDOv  

Nco version 4.6.6  
export CC=gcc  
export FC=gfortran  
export NETCDFv=/home/uupadhyaya/Develops/Dependencies/NetCDF/NetCDF-4.4.4.1[4.4.4]  
export NETCDF_INC=/home/uupadhyaya/Develops/Dependencies/NetCDF/NetCDF-4.4.4.1[4.4.4]/include  
export NETCDF_LIB=/home/uupadhyaya/Develops/Dependencies/NetCDF/NetCDF-4.4.4.1[4.4.4]/lib64  
export NETCDF4_ROOT=$NETCDFv  
export UDUNITS2_PATH=$UDUNITSv  
export CPPFLAGS="-DHAVE_NETCDF4_H -I${NETCDFv}/include -I${ANTLRv}/include -I${HDF5}/include"
export CFLAGS="-I${NETCDFv}/include -L${HDF5v}/lib -L${NETCDFv}/lib64 -I${ANTLR_PATH}/include    L${ANTLR_PATH}/lib64 -fPIC"  
export NETCDF_INC=$NETCDFv/include  
export NETCDF_LIB=$NETCDFv/lib64  
export YACC="yacc -d"  
export PATH=/home/uupadhyaya/Develops/Dependencies/Flex/Flex-2.6.0/bin:$PATH  
export LD_LIBRARY_PATH=/home/uupadhyaya/Develops/Dependencies/Flex/Flex-2.6.0/lib:$LD_LIBRARY_PATH  
export INCLUDE=/home/uupadhyaya/Develops/Dependencies/Flex/Flex-2.6.0/include:$INCLUDE  
./configure --prefix=$NCOv --enable-udunits --disable-static --enable-netcdf4 --disable-shared  

Ncl version 6.0.0  
cd $NCLv  
tar zxvf ncl_ncarg-6.0.0.Linux_SUSE_ia64_nodap_gcc412.tar.gz  
// Noted: Used SUSE version. The latest version are available for CentOS, RHEL and Debian System. The   latest version for NCL for CentOS has also been installed.//  

### WRF (Version 3.9, released April 17, 2017)  

Make sure the following environments are set in your .bashrc or setenv.sh   
export WRF_EM_CORE=1  
export WRF_NMM_CORE=0   
export WRFIO_NCD_LARGE_FILE_SUPPORT=1    

wget http://www2.mmm.ucar.edu/wrf/src/WRFV3.9.TAR.gz     
tar zxvf WRFV3.9.TAR.gz  
cd WRFV3  
./configure    
Select Linux x86_64 option: 34 ----> dmpar GNU (gfortran/gcc)    
./compile em_real >& compile.log  

### WRF-Chem (Version 3.9, released April 18, 2017)    
wget http://www2.mmm.ucar.edu/wrf/src/WRFV3-Chem-3.9.TAR.gz    
tar zxvf WRFV3-Chem-3.9.TAR.gz  
./clean -a  
Make sure the following environments are set in your .bashrc   
export WRF_CHEM=1  
export WRF_KPP=1  
./configure  
./compile em_real >& compile.log  

### WPS (Version 3.9)
cd ..  
wget http://www2.mmm.ucar.edu/wrf/src/WPSV3.9.TAR.gz     
tar zxvf WPSV3.9.TAR.gz  
cd WPS  
./configure  
Select 3 as the supported platform (Linux x86_64, gfortran(dmpar))    
./compile >& compile.log  
