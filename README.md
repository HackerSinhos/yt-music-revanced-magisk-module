# YT Music ReVanced Magisk Module
[![CI](https://github.com/HackerSinhos/yt-music-revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/HackerSinhos/yt-music-revanced-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced builder  

### **THIS REPOSITORY CONTAINS ONLY THE YT MUSIC PATCHED FROM https://github.com/j-hc/revanced-magisk-module**

Get the [latest CI release](https://github.com/HackerSinhos/yt-music-revanced-magisk-module/releases).

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules. 

<details><summary><big>Features</big></summary>
<ul>
 <li>Support only present and future YT Music ReVanced and <a href="https://github.com/inotia00/revanced-patches"> YT Music ReVanced Extended</a> apps</li>
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
Note that the <a href="../../actions/workflows/ci.yml">CI workflow</a> is scheduled to build the modules and APKs everyday using GitHub Actions if there is a change in ReVanced patches. You may want to disable it.
</details>

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
