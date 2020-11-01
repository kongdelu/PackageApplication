# PackageApplication
Xcode升级到8.3后，使用命令行打包ipa时，报错“xcrun: error: unable to find utility "PackageApplication"”，下载PackageApplication文件，放到 /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin/ 这个路径下，然后执行 chmod +x /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin/PackageApplication 命令即可。


打包脚本：
https://github.com/webfrogs/xcode_shell
