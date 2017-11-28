Step:
1.cd wxWidgets3.0.3
2.mkdir compile
3.cd compile
4../configure --disable-shared --enable-unicode --with-osx_cocoa  --with-macosx-version-min=10.9 --with-macosx-sdk=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.11.sdk/ --prefix=`pwd` --disable-svg --enable-universal-binary=i386,x86_64
5.make

the release of wxWidgets will be saved in compile.

To get some important infomation:
1.tell you what compile flags to use: ./wx-config -cxxflags
2.tell you what link flags to use：./wx-config –libs
