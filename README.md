# YT Music ReVanced Magisk Module
[![CI](https://github.com/HackerSinhos/yt-music-revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/HackerSinhos/yt-music-revanced-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced builder  

### **THIS REPOSITORY CONTAINS ONLY THE YT MUSIC PATCHED FROM https://github.com/j-hc/revanced-magisk-module**

Get the [latest CI release](https://github.com/HackerSinhos/yt-music-revanced-magisk-module/releases).

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules. 

<details><summary><big>Features</big></summary>
<ul>
 <li>Supports all present and future Youtube Music ReVanced apps (including projects implementing the same API)</li>
 <li> Can build Magisk modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimize APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> receive updates from Magisk app</li>
     <li> do not break safetynet or trigger root detections</li>
     <li> handle installation of the correct version of the stock app and all that</li>
     <li> support Magisk and KernelSU</li>
    </ul>
</ul>
</details>

## If you are having trouble with the classic mount method of the modules
such as,
- **"Reflash needed"** error after reboots
- **"Suspicious mount detected"** warnings from root detector apps

You can consider using [rvmm-zygisk-mount](https://github.com/j-hc/rvmm-zygisk-mount)

## Building Locally
### On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/HackerSinhos/yt-music-revanced-magisk-module/main/build-termux.sh)
```

### On Desktop
```console
$ git clone https://github.com/HackerSinhos/yt-music-revanced-magisk-module
$ cd yt-music-revanced-magisk-module
$ ./build.sh
```