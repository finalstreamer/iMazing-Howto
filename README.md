# 基于iMazing的IPA安装教程

## 目录

- [背景](#背景)
- [最低要求](#最低要求)
- [准备工作](#准备工作)
- [安装使用iMazing](#安装使用iMazing)
- [写在最后](#写在最后)
- [参考资料](#参考资料)

## 背景
老早前，iTunes 是可以直接安装 IPA 应用程序的，但是后面苹果抽风禁止了这个功能，导致你想安装应用程序就特别麻烦。不过 iMazing 后来把 iTunes 这个功能给实现了，并且更方便更傻瓜，比较推荐。

## 最低要求
* Windows：Windows 7 或者更高
* MacOS：macOS 10.10 或者更高

## 准备工作
如果你的系统是Windows7 SP1，需要提前下载依赖包  Microsoft .NET Framework 4.6.2，下载链接：</br>
https://download.microsoft.com/download/F/9/4/F942F07D-F26F-4F30-B4E3-EBD54FABA377/NDP462-KB3151800-x86-x64-AllOS-ENU.exe </br>
特殊的，很可能你会遇到 "Microsoft .NET Framework 4.6.2" 无法安装， 提示 "已处理证书链，但是在不受信任提供程序信任的根证书中终止。" 的问题，解决方式：</br>
《已处理证书链,但是在不受信任提供程序信任的根证书中终止 - Windows 7安装.Net Framework 4.6.2时出现此问题》</br>
https://blog.csdn.net/inchat/article/details/104294302 </br>

## 安装使用iMazing
1. 访问 https://imazing.com/download 下载对应系统的最新版本 iMazing，当前以Windows 为例。</br>
2. 安装 iMazing ，中间可能需要在线下载依赖包(运行库，iTunes 等)，过程可能比较久，请等待完成。安装完后「试用」即可，并且「无需备份」。</br>
3. 使用数据线连接手机。</br>
4. 点击左侧已经连接的手机，找到 应用程序。</br>
5. 点击底部「拷贝到设备->文件」，然后从电脑中选择对应的你想安装的 IPA 安装包进行安装即可。</br>

## 写在最后
总的来说，iMazing安装使用都挺简单。</br>
另外提醒下，如果你的 IPA 是已经签名的安装包，那么可能还有一个比 iMazing 更简单的方式：</br>
利用MacOS或者另外一台苹果设备通过「DirDrop」直接把 IPA 发到你想安装的手机或平板上，剩下它会自动安装的。</br>

## 参考资料
* iMazing: https://imazing.com/zh
* 已处理证书链,但是在不受信任提供程序信任的根证书中终止 - Windows 7安装.Net Framework 4.6.2时出现此问题: https://blog.csdn.net/inchat/article/details/104294302
