# 微信小程序练手小项目

问题一：Atom中微信小程序文件代码高亮

1、打开 config.cson 配置文件
同时按下快捷键 Command + Shift + P 唤起命令面板, 输入 Application: Open Your Config , 点击回车键 , 将会打开文件 config.cson

2、修改 config.cson 配置文件
在 core 下面添加
```
customFileTypes:
  'text.html.basic': ['wxml']   
  'source.css': ['wxss']   
  'source.js': ['wxs']
```

3、配置完成！ 重新打开 .wxml, .wxss, wxs 后缀的文件，将会看到彩色的代码。
