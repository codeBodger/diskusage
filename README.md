# Building and apk finding instructions:
- Edit `android.defaultConfig.versionName` in `app/build.gradle`
- From a file in the root directory:
  - do Build > Select Build Variant... and select debug (release doesn't work for some reason)
  - then do Build > Build App Bundle(s) / APK(s) > Build APK(s)
- Find the built file in `app/build/outputs/apk/debug/diskusage-vX.X-XX-debug.apk`

DiskUsage
=========

DiskUsage app for Android

DiskUsage provides a way to find files and directories on storage card which consumes a lot of space.<br>
It displays diagram on which directories are displayed proportional to their size, also a few levels of subdirectories are displayed. Users are allowed to zoom in to look at specific directory content.<br>
Purpose of the program is to provide a way to find and cleanup spacehogs on storage card. It is not general purpose file manager.<br>

Screenshot for an ancient version:<br>
<img src="extra/screenshot.png">

YouTube video:
https://www.youtube.com/watch?v=TIiCQfWdtVg
