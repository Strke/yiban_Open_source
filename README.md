# yiban_Open_source
易班自动打卡开源版  
在编写此代码时参考了[易班自动打卡脚本（适用于湖南工程学院健康打卡系统)](https://github.com/PRaichu/yiban)  
# 实现原理  
通过抓取 上一次打卡信息 然后作为这一次的打卡信息，然后通过请求 打卡信息的网站 实现打卡 ，然后这些还会通过邮件来通知用户 是否打卡成功。
# 注意事项
在开源版中，如果你想让这个代码在你电脑上跑起来你需要安装 像 *xlrd*这样的一些库，然后还要再发邮箱的函数里填写你的*邮箱*和*邮箱授权码(这个如果你不会就问问度娘吧)* 
,还有要在test.xls 文件中添加一些信息。  

还有那个账户和密码
![账户和密码查看的地方](https://github.com/mayali123/yiban_Open_source/blob/main/img-storage/ME%5D6OY5~%25UO83K%40%7D3R3YLFI.png)
# 不足的地方    
本代码仅仅实现了 运行后 打卡    

并不能做到真正意义上的 *自动打卡*  我准备 在 *Linux*(本想法已经在我的Ubuntu上验证)  下使用 *crontab* 命令来定时执行程序  就可以自动在固定时间自动打卡了  

可以配合 电脑 在某一时间 自动开机 这样电脑都不要我们自己打开了（本想法我还没有验证） 真正的做到了*自动打卡* 哈哈哈

代码有些的其实可以写的更好一些，等下次有时间在继续改进 

后面尽可能实现我上面的想法 并将起写到这里来 哈哈哈哈哈

# 声明
本代码是仅作为学习使用，不得将上述内容用于商业或者非法用途。如有侵权，马上联系我，我立马删除。我的邮箱：2584379836@qq.com
