## Sample Configure File

```yaml
avatar:

links:
  Github: https://github.com
  About: /about

ga: ''

footer: ''

waline: https://example.com
```

配置文件应放在 ```~/_config.merryx.yml```。

- avator

头像。可接受完整链接/相对目录。

- links

放置在首页的链接。列表式选项。可接受完整链接/相对目录。

- ga

Google Analyze ID。可接受旧的UA-prefix ID 和新的 G-prefix ID。

- footer

页脚，置于 Copyright 一行之上。可接受纯文本/HTML 元素。

- waline

waline 服务端地址。可接受完整链接。（这里没有写相对目录的原因是因为考虑到大多数人会分开部署网站和评论，如果你这么做了的话你**理论上可以**写相对目录，但这未经测试！）
