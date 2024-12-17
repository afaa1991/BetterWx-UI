# BetterWx-UI

微信Windows版 4.0 双开&防撤回&多账号共存 UI工具<br>
支持平台：Windows x64<br>
版本支持：4.0+<br>
<br>
根据大佬zetaloop开源 制作的 ui 工具<br>
大佬开源地址 [https://github.com/zetaloop/BetterWX](https://github.com/zetaloop/BetterWX)<br>
UI工具开源地址 [https://github.com/afaa1991/BetterWx-UI](https://github.com/afaa1991/BetterWx-UI)<br>

## 说明

1.不支持3.9的微信。<br><br>
2.以管理员模式启动，在修改之前，原文件会备份到 Weixin.dll.bak 和 Weixin.exe.bak。<br><br>
3.防撤回无提示。<br>
&emsp;【所有 revokemsg 消息变为未知消息，不响应撤回操作】<br><br>
4.多开。<br>
&emsp;【移除 lock.ini 锁文件检测】<br><br>
5.共存版制作器。<br>
&emsp;【生成一个 Weixinζ.exe 和 Weixin.dlζ，其设置数据保存在 global_confζg、自动登录端口数据保存在 host-redirect.xmζ】<br><br>
6.不是共存启动器，不是共存启动器，不是共存启动器。<br>
&emsp;不要当启动器用，当然你要这么用也没问题。<br>
&emsp;更好的方式是分别为目录下的 Weixinζ.exe 创建快捷方式使用。<br><br>

## 常见问题

1.找不到weixin.dll。<br>
&emsp;请确认是4.0+的版本，不支持3.9。<br>
&emsp; WeiXin.dll 在4.0的安装目录对应的版号文件夹里面。<br>
&emsp;通过官方安装的微信一般能自动获取路径。<br><br>
2.微信 3.9.x 能用吗？<br>
&emsp;猜你想找 huiyadanli/RevokeMsgPatcher。<br><br>
3.共存、多开、防撤回这几个特性我可以挑选几个 or 全都要吗？<br>
&emsp;除了多开是作为共存的前置条件，别的可以自己选。<br><br>
4.企业微信能用吗？<br>
&emsp;不支持。<br><br>
5.win7，win8 能用吗<br>
&emsp;不能。    <br>
&emsp;基于tauti制作，只支持win10和win11 带 webview2 的系统。<br>
&emsp;win7,win8不支持，解决 webview2 运行时也能用。<br><br>
5.防撤回有没有提示。<br>
&emsp;没有，我也不会，等大佬们解决。<br><br>
6.怎么批量启动多个账号。<br>
```
start "" "D:\AppData\Tencent\Weixin\Weixin.exe"
start "" "D:\AppData\Tencent\Weixin\Weixin1.exe"
```
&emsp;修改“D:\AppData\Tencent\Weixin” 为你的微信安装目录。<br>
&emsp;Weixin1.exe 共存的exe文件名。需要启动哪个，添加哪个。<br>
&emsp;以上内容保存到 bat 文件，运行。<br><br>

## 更新说明

### 1.0.1

&emsp;默认 管理员模式启动。 <br>

## 下载地址 1.0.1
&emsp;[https://wwtt.lanzn.com/isin52i2f50d](https://wwtt.lanzn.com/isin52i2f50d)
