# README

**Nexo官方文档**：<https://hexo.io/zh-cn/>

**建站基础教程**：<https://zhuanlan.zhihu.com/p/26625249?utm_source=weibo&utm_medium=social>

**Nexo基本操作命令**

```shell
npm install hexo -g #安装Hexo
npm update hexo -g #升级 
hexo init #初始化博客

命令简写 未全局安装的 使用 npx hexo xxx
hexo n "我的博客" == hexo new "我的博客" #新建文章
hexo g == hexo generate #生成
hexo s == hexo server #启动服务预览
hexo d == hexo deploy #部署

hexo server #Hexo会监视文件变动并自动更新，无须重启服务器
hexo server -s #静态模式
hexo server -p 5000 #更改端口
hexo server -i 192.168.1.1 #自定义 IP
hexo clean #清除缓存，若是网页正常情况下可以忽略这条命令
```

```
// 发布
hexo clean 
hexo g 
hexo d
```

**其他建站方法**

Next        <http://theme-next.simpleyyt.com/>>

Jekyll      <http://jekyllcn.com/>

