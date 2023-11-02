# Minecraft Server 配置文件  
  
## 简介  
  
这个仓库包含了 Minecraft Server 及 MCDReforged 的配置文件。
用以维护服务器配置，以及供他人复刻等价服务器测试。

  
## 文件结构  
  
* `server.properties`: 这是主要的服务器配置文件。你可以在这个文件中设置各种选项，如游戏规则、世界设置、服务器名称等。  
* `bukkit.yml`: 这个文件用于配置 Bukkit 插件。如果你正在使用 Bukkit 插件，你应该编辑这个文件来配置你的插件。  
* `permissions.yml`: 这个文件用于配置服务器权限。你可以在这个文件中定义不同玩家和组的权限。  

## 推荐系统
* archlinux
* ubuntu
* fedora
* 类似的linux系统

## 依赖
* git
* python 3.10及以上
* MCDReforged(python module)
* java 17
  
## 使用方法  
* 确保依赖安装完毕,并下载此仓库
* 在仓库文件夹内的`server/`文件夹下安装fabric的mc服务端启动器,并将启动器名称改为`fabric-server-launch.jar`
* 在仓库文件夹内的`mods/`文件夹下安装`mods/mods.md`文件内所列的模组
* 设置你的环境变量如果你需要自定义java路径，变量名为`MY_JAVA_PATH`
    * 如你的java路径为`path/bin/java`,那么变量值为`"path/bin"`
* 启动服务器在仓库文件夹下输入`python3 -m mcdreforged init`初始化`MCDR`
    * 输入`python3 -m mcdreforged`即可启动
  

  
## 注意事项  
  
* 在编辑配置文件之前，建议备份原始文件，以防止意外情况发生。  
* 请确保你理解你正在编辑的配置项的含义和影响，不要随意更改它们。  
* 如果你的 Minecraft Server 是多人游戏服务器，建议在编辑配置文件之前与所有管理员协商，以确保大家的意见达成一致。  
  
## 贡献指南  
  
如果你有任何问题或建议，或者你想分享你自己的配置文件，欢迎在 issues 或 pull requests 中提供反馈。同时，如果你有任何改进或优化的建议，也欢迎提出。  
