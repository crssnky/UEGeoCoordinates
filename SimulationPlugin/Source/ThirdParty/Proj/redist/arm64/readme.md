build and copy here dlls.
- jpeg62.dll(https://github.com/libjpeg-turbo/libjpeg-turbo.git)  
I use CMake. CMake outputs VS2019 sln with ARM64 conf. 
- lzma.dll(https://sevenzip.osdn.jp/sdk.html)  
Open lzma1900/C/Util/LzmaLib/LzmaLib.dsw with VS2019. You get a solution. It output to `C:/Util/LZMA.dll` after build. It ignore project configulation.
- sqlite3.dll(https://github.com/sqlite/sqlite.git)  
I use nmake(Please read sqlite's README.md).  
My build env is Win10 x64. If you too, lemon.exe and mkkeywordhash.exe have to be built by x64. 
- tiff.dll(https://gitlab.com/libtiff/libtiff.git)  
I use CMake too. CMake outputs VS2019 sln with ARM64 conf. 
- zlib.dll(https://github.com/madler/zlib.git)  
I use CMake too. CMake outputs VS2019 sln with ARM64 conf.  
(UEGeoReference original file is "zlib1.dll". "zlib1" is official file name. Read it(https://github.com/madler/zlib/blob/master/win32/DLL_FAQ.txt).)