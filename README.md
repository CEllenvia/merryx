# merryx

**Work IN PROGESS**

你也可以叫 merry-extended.

基于 Anillc 开发的 merry ，一个简单的 Hexo 主题二次开发，“计划”支持背景图， about / link 页面特别优化，评论区等个人刚需功能。

> **如果你打算从 merry 或者是其他主题迁移过来**
> 
> 这是一份**劝退**说明！
> 
> 对于 merry 用户：
> 
> 注意本主题已经完全“左置化”<!--我做出了一个违背祖宗的决定.gif-->，请在预览之后再考虑是否要迁移！
> 
> 对于其他主题用户：
> 
> 你需要了解清楚这个 theme 的局限——这个本来就是我一时颅内高潮搞的，至今也**只完成了基本评论区支持**！
> 
> 比我写的好的 theme 大有的是。除非你**确实追求极端简洁**，<!--我没有那种俗世的欲望.gif-->，否则请不要用！
> 
> 同时适用于上述两种用户：
> 
> <!--当然魔改主题改炸了也不关我事.webp （不是-->

我的确在上面写了东西——找不找得到就不是我的问题了。 :-D

> Christine Ellenvia, [2022/11/18 B9:03]
>
> 挺好）
> 
>
> Christine Ellenvia, [2022/11/18 B9:03]
>
> 这劝退指南估计能劝退 99.9% 的人）
> 
>
> Christine Ellenvia, [2022/11/18 B9:03]
>
> 当然魔改主题改炸了也不关我事.webp （不是
> 
> 
> Moe🍥 23333, [2022/11/18 B9:06]
>
> 但咱不是人，咱是猫猫✓
> 
>
> Moe🍥 23333, [2022/11/18 B9:06]
>
> 这就去 Fork 一份部署到 Vercel 上面（
> 
>
> Christine Ellenvia, [2022/11/18 B9:06]
>
> 这劝退指南估计能劝退 99.9% 的生命体）
>
>
> Christine Ellenvia, [2022/11/18 B9:06]
>
> 别我还有 commit 没交
>
>
> Moe🍥 23333, [2022/11/18 B9:06]
>
> 但咱是虚拟猫猫，没有生命体（
>
> 
> Christine Ellenvia, [2022/11/18 B9:07]
>
> [Edited]
>
> 这劝退指南估计能劝退 99.9% 的实体）

功能：

- [x] merry 原版功能
  - [x] 简单设计
  - [x] LaTeX 支持 <!--不是我说 这真的不是从 NeXT Computers Inc. 学的？-->
  - [x] 完整 Darkmode 适配
  - [x] 支持谷歌统计
  - [x] URL 头像引用
  - [x] 主页 Links 自定义
- [ ] merryx 拓展功能
  - [x] 自适应页脚
  - [ ] 背景图
  - [ ] ~~宽屏设备文章双列显示支持~~（暂时不准备支持了，因为主页渲染准备全部左置）
  - [ ] 按照 Hexo 推荐实现的将 _config.yml 放到 hexo 根目录中。
  - [ ] 主流评论平台支持
    - [x] Waline / miniValine （目前只支持到 Waline。其他支持等待切换功能完成后陆续上线。）<!--Why not Valine? https://yun.yunyoujun.cn/guide/third-party-support.html#valine -->
    - [ ] Disqus & DisqusJS
    - [ ] utterances
    - [ ] 实验支持评论系统 （大概率是因为不太常用，相较前几个）
      - [ ] Giscus
      - [ ] LiveRe
      - [ ] Twikoo
  - [ ] about / link 页面特别优化
    - [ ] about 页面支持列出社交平台 (目标实现 https://poplite.xyz/about.html ，当然不是纯文字而是按钮，此处目标实现 https://www.yunyoujun.cn/ 左栏)
    - [ ] link 页面支持单/多行排布，头像引入等基本支持

<!--Christine Ellenvia, [2022/7/3 B9:32]
tmd 我感觉我给自己挖了个巨坑

千畔, [2022/7/3 B9:34]
加油（-->

## 预览

[Demo](https://blogs.christine.pp.ua)

## 用法

```bash
cd hexo
git clone https://github.com/CEllenvia/merryx.git themes/merryx
```

修改 \_config.yml  

```yml
theme: merryx
```

## 自定义配置

[Link](https://github.com/CEllenvia/merryx/blob/main/configure.md)
