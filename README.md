# XMRigCC Windows build dependencies

This repository contains all needed (prebuild) dependencies to build XMRigCC on Windows with TLS support.

## Versions:

- OpenSSL v1.0.2m (mingw/gcc)


### Thanks xmrig for compilation (https://github.com/xmrig/xmrig-deps/releases):
- libuv 1.19.0 (gcc/MSVC)
- libuv 1.15.0 (gcc/x86)
- libmicrohttpd 0.9.58


### Thanks stathis for compilation (https://www.npcglib.org/~stathis/blog/precompiled-openssl/):
- OpenSSL v1.1.0f (MSVC)


### SHA256 checksums:
```
a47898ca5febb861dd76c98490b50036e97711e0916225afcfdcc94239020791  ./gcc/openssl/x86/lib/libcrypto.a
7ae96183d02a17b7237cce9d14ef070e440b4184277f0c6589057838ed287a56  ./gcc/openssl/x86/lib/libssl.a
d31d43ff1a337f332c6c0b9a29c033a725cf308d43f630d0e44f764cce8141e3  ./gcc/openssl/x64/lib/libcrypto.a
46eb1f1fc3d350a00b60eb9fc52197c1f3a2d06fdfb2ccc70b98abde80ab7156  ./gcc/openssl/x64/lib/libssl.a
e470681105eea577ce75ef2bb4fa2dcb27adcbbf5fd64fe5e0dcc62ac649cfb4  ./gcc/libuv/x86/lib/libuv.a
b2a90e33f6a12e6a082fe4e91d5b94fdfdb95930c1fa2b66f907a41e2dbfddd1  ./gcc/libuv/x64/lib/libuv.a
14e282a33ce187e0b3ee2a64015ec523f4a06af6849ca7b5a78e60c77030535d  ./gcc/libmicrohttpd/x86/lib/libmicrohttpd.a
dea2d09cd94a2ae2b34c77e72b8e2fcc3741bfbb1ca54dfec59f4c08588dbbae  ./gcc/libmicrohttpd/x64/lib/libmicrohttpd.a
95e1fdc36cdc9bf1af9246427715185b6d0325de46b90256db614a98f4da3542  ./msvc2017/openssl/x86/lib/libssl.lib
41b90deaf833b6cde9339c988135413dffb19bba6a4bcecc57d19f9b74cfdf02  ./msvc2017/openssl/x86/lib/libcrypto.lib
ae4db081206a6f9f14fb77a57992be7e78ef2ebc6a8ca9dc8d07d1c0f3979b27  ./msvc2017/openssl/x64/lib/libssl.lib
1caa7654a1897f3ab440a5842ebc9444664d14f4165692e4ee1521eb780c42a8  ./msvc2017/openssl/x64/lib/libcrypto.lib
a10613c74ecc083fe58f499f5c93eee0864b66c6825ef7be4c8bee1d0175a634  ./msvc2017/libuv/x86/lib/libuv.lib
3709a0a7f1f62dab0d7636f4dd2ea69ff29a879e166b27319bbb35a318185e1d  ./msvc2017/libuv/x64/lib/libuv.lib
36adf14831a6c7f9f40303a00db3d52293c6f08eb5017d6e6394bb175dde6b4d  ./msvc2017/libmicrohttpd/x86/lib/libmicrohttpd.lib
d0978a3023c340bb3d252cdab832ce0bf9b1e2148a699bbb7434e4ba02da493e  ./msvc2017/libmicrohttpd/x64/lib/libmicrohttpd.lib
cb5cce163a4139030b03b2f062e0159fe18bb633a35858aecb826a6d31c7c0b9  ./msvc2015/openssl/x86/lib/libssl.lib
d354b9bc4b794873784a10cb6eabefa98d538740d0a507916bfb881b8af3d105  ./msvc2015/openssl/x86/lib/libcrypto.lib
ed26e0ea83b923751b5a81ba622a19bdf87a153f38a9df1195aeac0527c80bc2  ./msvc2015/openssl/x64/lib/libssl.lib
4813dedf74c056937f6301125bc858e600e5be7979c60305669b961bf39b49e6  ./msvc2015/openssl/x64/lib/libcrypto.lib
eb113d721dca46a334aa92121745eb7e01940bd36997e873e38f8fce3c7e2ae4  ./msvc2015/libuv/x86/lib/libuv.lib
c0c7d1575d7af0891af904daa247238c28a4e3c54e43e339ce4634ed3c156f09  ./msvc2015/libuv/x64/lib/libuv.lib
b0e35d5b17eba17db0a1163c8d1f12c13064d725e4c2bc487ab377a6f2590d38  ./msvc2015/libmicrohttpd/x86/lib/libmicrohttpd.lib
63277b0a48643beaefabb1164c2aa70e21c54982c594775f907ef4fcfb7a93df  ./msvc2015/libmicrohttpd/x64/lib/libmicrohttpd.lib
```
