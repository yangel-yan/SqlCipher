# SciPher
整理SQLcipher后编译成功后生成的项目，可以直接导入VS2012后编译出.exe

可以解密Sqlite加密的db文件，例如微信

步骤：

1.右键解决方案——属性——项目依赖项——Shell依赖于StaticLib

2.右键Shell——属性——通用属性——添加新引用——选择StaticLib

3.右键Shell——属性——配置属性——链接器——输出文件——更改为$(OutDir)$(TargetName)$(TargetExt)

