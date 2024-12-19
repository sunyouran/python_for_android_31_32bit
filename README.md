python3.7.9 source code cross compler to android 12 api31 .

step 1 
mkdir out
download the source file to out
adb push ./out  /system/bin
adb shell 
export PYTHONHOME=/system/bin/out
cp /system/bin/out/bin/python3.7 /system/bin/

python3.7  /data/test.py


python3.7: ELF 32-bit LSB pie executable, ARM, EABI5 version 1 (SYSV), dynamically linked, interpreter /system/bin/linker, not stripped

../configure CC=/home/steven/my_build_tool/android-ndk-r26d/toolchains/llvm/prebuilt/linux-x86_64/bin/armv7a-linux-androideabi31-clang CXX=/home/steven/my_build_tool/android-ndk-r26d/toolchains/llvm/prebuilt/linux-x86_64/bin/armv7a-linux-androideabi31-clang++ AR=/home/steven/my_build_tool/android-ndk-r26d/toolchains/llvm/prebuilt/linux-x86_64/bin/llvm-ar  RANLIB=/home/steven/my_build_tool/android-ndk-r26d/toolchains/llvm/prebuilt/linux-x86_64/bin/llvm-ranlib READELF=/home/steven/my_build_tool/android-ndk-r26d/toolchains/llvm/prebuilt/linux-x86_64/bin/llvm-readelf PROFDATA=/home/steven/my_build_tool/android-ndk-r26d/toolchains/llvm/prebuilt/linux-x86_64/bin/llvm-profdata LD=/home/steven/my_build_tool/android-ndk-r26d/toolchains/llvm/prebuilt/linux-x86_64/bin/ld --host=armv7a-linux-androideabi31 --build=x86_64-linux-gnu   --target=armv7a-linux-androideabi31 --enable-shared --disable-ipv6 --with-system-ffi ac_cv_file__dev_ptmx=yes ac_cv_file__dev_ptc=no  --prefix=/home/steven/1588/lll/cpython-3.7.9/build.am3352/out
