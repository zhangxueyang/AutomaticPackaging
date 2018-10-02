# AutomaticPackaging
自动化打包工具  自己的学习记录
先贴两个地址:基本上别人写的，我只是搬运过来，解决一点问题，做记录，自己用！

[iOS利用Shell脚本,一键打包发布到AppStore](https://blog.csdn.net/u013602835/article/details/79790020)
[iOS- 一键自动打包发布到Fir和AppStore](https://www.jianshu.com/p/05dc9f925467)

自己用的时候遇到了一些问题

我是用  xcode 9 打包的  用他们没修改的  会报  推送证书的错误
原因是新版xcde 脚本打包的 新特性

解决办法:
![解决办法](https://github.com/zhangxueyang/AutomaticPackaging/blob/master/%E5%9B%BE%E7%89%87%E8%B5%84%E6%BA%90/Snip20181002_7.png)

按照图示解决就好 

或者下载我的 直接修改为你对应项目的文件

key 是项目 bundle identifier
value 是 项目中对应的   Provisioning Profile

正式的选正式的   ad hoc 就选对应的 ad hoc 

[教你打包的地址 绝对权威](https://developer.umeng.com/docs/66632/detail/66748)
