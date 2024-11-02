> title: Hexo 常用命令
> date: 2023-12-02 10:55:20
> categories: []
> tags: []
> description: Hexo 常用命令
> photos:
>
> * https://wn.twoice.fun:1020//i/2023/12/02/hexo常用命令-2.png

```
hexo init
用于初始化一个本地文件夹为网站的根目录

hexo new
$ hexo new title 新建一篇文章

hexo generate
可以简写成 hexo g 该命令用于生成静态文件

hexo server
$ hexo server 命令用于启动本地服务器，一般可以简写成 hexo s
可以加一些参数
-p    选项，指定服务器端口，默认为 4000
-i    选项，指定服务器 IP 地址，默认为 0.0.0.0
-s    选项，静态模式 ，仅提供 public 文件夹中的文件并禁用文件监视

hexo deploy
hexo d 命令用于部署网站，一般可以简写成

hexo clean
$ hexo clean 命令用于清理缓存文件，是一个比较常用的命令

hexo --safe
表示安全模式，用于禁用加载插件和脚本

hexo --debug
表示调试模式，用于将消息详细记录到终端和 debug.log 文件

hexo --silent
表示静默模式，用于静默输出到终端
```