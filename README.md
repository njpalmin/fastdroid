fastdroid-vnc-server
====================

Compilable Fastdroid VNC server for Android, originally by Danke Xie (http://code.google.com/p/fastdroid-vnc/).  This also includes a copy of libjpeg shared by the user "Tim in Boulder" in [this post](https://groups.google.com/d/msg/android-ndk/AjVzQQ-C9Zo/H33p4_84cb4J).

Added `jni` and `external` directories, and made some changes to the root `Android.mk`

How to compile
--------------
1. Install the latest NDK: http://developer.android.com/tools/sdk/ndk/index.html
2. In the parent diretory of `jni`, run this: `$NDK_DIR/ndk-build`
3. The exectuable fvnc file is generated under ./obj/local/



