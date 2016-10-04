# libVLC for UWP NuGet package
libVLCX.nuspec and libVLCX.targets files to build the libVLCX NuGet package

## How to build the libVLCX NuGet package
Build the [libVLCX.UWP project](https://code.videolan.org/videolan/vlc-winrt/tree/master/modules/libVLCX.UWP) and put the result in build/amd64 and build/x86 folders. Then, run the command :

```nuget pack libVLCX.nuspec```

## libVLCX usage
This package is not intended to be used directly from your code. You should use [VLC.MediaElement](https://github.com/kakone/VLC.MediaElement).

But, you can look at [the source code of VLC](https://code.videolan.org/videolan/vlc-winrt) or [VLC.MediaElement](https://github.com/kakone/VLC.MediaElement) to see how you can use it. You must add the *Microsoft Visual C++ 2013 Runtime Package for Windows Universal* extension to your project if you want to use the libVLCX package directly.

## Download
[![NuGet](http://img.shields.io/nuget/v/libVLCX.svg)](https://www.nuget.org/packages/libVLCX)
