# device_linaro_hikey_tv
AOSP TV device source for Hikey and Hikey960

Establich build environment as in:
https://source.android.com/source/devices

Replace the folder named hikey in devices/linaro/ with this repo and rename it to hikey

Add Android TV binaries from google by downloading 'Launcher, Remote, TV' for Nexus Player (Fugu):
https://developers.google.com/android/nexus/blobs-preview

Extract the binaries and accept the licence agreement by copying the downloaded file to the source directory
```
tar -xvzf google-fugu-*.tgz
./extract-google-fugu.sh
```

Continue the build process as in https://source.android.com/source/devices

Credits for AOSP TV setup: Peter Yoon https://github.com/peyo-hd
