<!-- README.md, bin_android/python3.5 (branch)
   - <https://github.com/sceext2/bin_android>
  -->

# bin_android/python3.5


## Program

+ **python 3.5.1**
  
  <https://www.python.org/>


## Sources

+ **python 3.5.1**
  
  <https://python.org/ftp/python/3.5.1/Python-3.5.1.tar.xz>

+ **bzip2 1.0.6**
  
  <http://www.bzip.org/1.0.6/bzip2-1.0.6.tar.gz>

+ **xz 5.2.1**
  
  <http://tukaani.org/xz/xz-5.2.1.tar.xz>

+ **openssl 1.0.2e**
  
  <http://artfiles.org/openssl.org/source/old/1.0.2/openssl-1.0.2e.tar.gz>

+ **readline 6.3**
  
  <https://ftp.gnu.org/gnu/readline/readline-6.3.tar.gz>

+ **ncurses 5.9**
  
  <https://ftp.gnu.org/pub/gnu/ncurses/ncurses-5.9.tar.gz>

+ **sqlite 3.8.10.2**
  
  <https://www.sqlite.org/2015/sqlite-autoconf-3081002.tar.gz>

+ **gdbm 1.11**
  
  <https://ftp.gnu.org/gnu/gdbm/gdbm-1.11.tar.gz>


## Compile Tools

+ **Android NDK r11b**
  
  <http://dl.google.com/android/repository/android-ndk-r11b-linux-x86_64.zip>

+ **python3-android** (build scripts)
  
  <https://github.com/sceext2/python3-android> <br />
  <https://github.com/GRRedWings/python3-android>

+ Host: `ArchLinux`
  
  ```
  $ uname -a
  Linux SCEEXT-ARCH-LT-201603 4.4.5-1-ARCH #1 SMP PREEMPT Thu Mar 10 07:38:19 CET 2016 x86_64 GNU/Linux
  $ 
  ```


## Target

**`Android 5.1`** (`ARMv6`, 32bit)

(`11b-21-arm-linux-androideabi-4.9`, `PIE`)


## Test

Simply tested on `Android 5.1`. 
(Did not run the test suit of python. )

```
$ ls -al
-rwxr-xr-x u0_a97   u0_a97    8866612 2016-04-14 23:45 python3.5
$ ./python3.5 --version
WARNING: linker: ./python3.5: unused DT entry: type 0x6ffffffe arg 0x14d68
WARNING: linker: ./python3.5: unused DT entry: type 0x6fffffff arg 0x3
Python 3.5.1
$ ./python3.5
WARNING: linker: ./python3.5: unused DT entry: type 0x6ffffffe arg 0x14d68
WARNING: linker: ./python3.5: unused DT entry: type 0x6fffffff arg 0x3
Python 3.5.1 (default, Apr 14 2016, 22:13:32)
[GCC 4.9 20150123 (prerelease)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import os
>>> os
<module 'os' from '/data/data/jackpal.androidterm/app_HOME/ba/py35/python3.5.1_arm32_android_pie/lib/python3.5/os.py'>
>>> import sys
>>> sys.executable
'/data/data/jackpal.androidterm/app_HOME/ba/py35/python3.5.1_arm32_android_pie/bin/python3.5'
>>> exit()
$ 
```


<!-- end README.md -->


