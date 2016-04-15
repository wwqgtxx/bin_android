<!-- README.md, bin_android/nodejs5 (branch)
   - <https://github.com/sceext2/bin_android>
  -->

# bin_android/nodejs5


## Program

+ **node.js 5.10.1**
  
  <https://nodejs.org/en/>


## Sources

+ **node.js 5.10.1**
  
  <https://nodejs.org/dist/v5.10.1/node-v5.10.1.tar.gz>


## Compile Tools

+ **Android NDK r11b**
  
  <http://dl.google.com/android/repository/android-ndk-r11b-linux-x86_64.zip>

+ `node.js` build guide
  
  <https://github.com/nodejs/node/blob/master/BUILDING.md#android--android-based-devices-eg-firefox-os>

+ Host: `ArchLinux`
  
  ```
  $ uname -a
  Linux SCEEXT-ARCH-LT-201603 4.4.5-1-ARCH #1 SMP PREEMPT Thu Mar 10 07:38:19 CET 2016 x86_64 GNU/Linux
  $ 
  ```


## Target

*`Android 5.1`** (`ARMv6`, 32bit)

(`11b-21-arm-linux-androideabi-4.9`, `PIE`)


## Test

Simply tested on `Android 5.1`. 

```
$ ls -al
-rwxr-xr-x u0_a97   u0_a97   20152288 2016-04-14 23:36 node
-rwxr-xr-x u0_a97   u0_a97    3077864 2016-04-14 23:36 openssl
$ ./node --version
WARNING: linker: ./node: unused DT entry: type 0x6ffffffe arg 0x22fc70
WARNING: linker: ./node: unused DT entry: type 0x6fffffff arg 0x3
v5.10.1
$ ./node
WARNING: linker: ./node: unused DT entry: type 0x6ffffffe arg 0x22fc70
WARNING: linker: ./node: unused DT entry: type 0x6fffffff arg 0x3
> process.versions
{ http_parser: '2.6.2',
  node: '5.10.1',
  v8: '4.6.85.31',
  uv: '1.8.0',
  zlib: '1.2.8',
  ares: '1.10.1-DEV',
  modules: '47',
  openssl: '1.0.2g' }
> .exit
$ 
```


<!-- end README.md -->


