# SocketX
<h3>什么是 SocketX</h3>
SocketX 是一个通用的 Bukkit/Spigot 服务器 API 接口，通过网络让其他程序/语言可以调用这些接口实现开发插件。<br>
不会用 Java 开发 Bukkit 插件的小伙伴们就可以通过 SocketX 使用自己喜欢的语言来写插件了，任何一种支持 Socket 的语言都可以开发插件！<br>
<h3>它如何工作？</h3>
SocketX 作为一个 Bukkit 插件运行，加载后会打开指定一个端口监听，你可以使用任何一种语言来开发插件，通过与服务器建立 Socket 长连接，然后发送特定 json 格式数据即可执行操作，游戏内的一些事件也会通过 Socket 推送。<br>
<h3>开发进度</h3>
目前仍处于规划阶段，正在制定接口规范，以及具体协议细节。<br>
<h3>关于</h3>
本项目由 SakuraMC & TimeTreeStudio 合作开发<br>
