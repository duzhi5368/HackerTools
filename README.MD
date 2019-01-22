# 结构

- apktool将xml资源文件反编译成可以查看。并把class.dex文编译成了可以smali文件。
- dex2jar将class.dex文件转换成jar包的工具
- jd-gui可以读取jar包的工具

# 步骤

- 解压apk
- 想看xml文件，就使用 apktool d xxxooo.apk ，这样的xml就不是乱码
- 想看dex文件，就是用 d2j-dex2jar.bat classes.dex 得到jar包
- 用jd-gui打开jar包可以看到源代码

