## apk反编译工具

该工具支持将apk包反编译为Java,assets,res,libs,manifest,并且保持开发时的app的目录结构

该工具还支持将apk反编译为smali进行动态调试

### 使用方法

- 将apk包放入到根目录apk下,重命名为input.apk
- 在终端输入./gradlew dA(decompileApk)
- 反编译后的Java代码,assets等在app目录下,smali代码在smali目录下

### 备注
目前在Linux系统运行正常,Windows和Mac待验证