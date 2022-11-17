# merryx

**Work IN PROGESS**

你也可以叫他 merry-extended.

基于 Anillc 开发的 merry ，一个简单的 Hexo 主题二次开发，支持背景图， about / link 页面特别优化，评论区等个人刚需功能。

> **如果你打算从 merry 迁移过来**
>
> 注意本主题已经完全“左置化”，请在预览之后再考虑是否要迁移！

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
    - [ ] 主流评论平台支持
        - [ ] Waline / miniValine <!--Why not Valine? https://yun.yunyoujun.cn/guide/third-party-support.html#valine -->
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

## Demo  

[Demo](https://blogs.christine.pp.ua)

## Usage  

```bash
cd hexo
git clone https://github.com/ChristineEllenvia/merryx.git themes/merryx
```

修改 \_config.yml  

```yml
theme: merryx
```
