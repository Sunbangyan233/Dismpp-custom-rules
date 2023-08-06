# Dismpp-Custom-Rules

适用于[Dism++](https://github.com/Chuyu-Team/Dism-Multi-language)的自定义清理规则

**规则偏极限，请勿用于生产环境！**

## How to Use ?

推荐💡：从[Releases页面](https://github.com/Sunbangyan233/Dismpp-custom-rules/releases)（还在鸽）下载，将解压得到的zip文件丢到/Config文件夹里，Then，重启Dism++。

亦可🤔：从当前存储库[下载](https://github.com/Sunbangyan233/Dismpp-custom-rules/archive/refs/heads/main.zip)，手动将 <**每个**> Custom开头的xml规则文件 **<单独>打包** 成zip文件，Then，丢到/Config文件夹，重启Dism++。

## 一些小问题❓

### BETA和Releases有什么区别？

- BETA版本仅限测试，没有充分数据样本测试稳定性，有可能使你的部分文件被错误清理掉；
  
  而Releases版本经过了充分测试，可以用Dism++清理掉更多的无用文件，并且不影响正常运行。

- BETA版本的文件清理规则前会加[BETA]并且在描述中加入项目地址。

  ~~而Releases版本当然就没有这些啦~~Releases还有，不删了


### 为什么清理掉的空间与显示的不符？

扫描到的↓

![](https://picdm.sunbangyan.cn/2023/08/06/ywkrh7.png)

实际删掉的↓

![](https://picst.sunbangyan.cn/2023/08/06/ywz1qt.png)

原因：大概是文件正被占用？实在不行 <b>taskmgr.exe</b> 结束下进程再删~

## 编写规则参考

[自定义规则.md
](https://github.com/Chuyu-Team/Dism-Multi-language/blob/master/www.chuyu.me/zh-Hans/library/Dism%2B%2BLibrary/%E8%87%AA%E5%AE%9A%E4%B9%89%E8%A7%84%E5%88%99.md)
