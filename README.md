# SYSU CS - All Sum in One!

<center>

<a href="http://asio.sysumsc.cn/">Page</a> | <a href="https://github.com/SYSUMSC/sysu-cs-asio">Repository</a> | <a href="https://github.com/SYSUMSC/sysu-cs-asio?tab=readme-ov-file#all-sum-in-one">Quick Jump</a>

</center>

## 介绍

本仓库目前主要以收集各类与 SYSU-CS 有关的网站形式的资料为主，具体分四大类：

1. 💎 由个人维护的个人笔记网站/博客网站等，可以了解到各个同学的具体学习经历和比较个人化的知识理解，不乏精品；
2. 🔮 由学生组织维护的教学资料网站等，相对来说范围更广，覆盖面更全，完成度更高，但多样性可能较差；
3. 🧲 课程组维护的教学资料网站等，如实验手册等，适合提前了解特定课程的相关内容；
4. 🎉 其他，例如个人整理的课程资料

出于一些原因，我并不打算在这个仓库中收集诸如课本、真题、大作业等可能引发一系列问题的资料，本仓库希望为各个相对来说更具有原创性的资料提供一个汇总、索引、引流的根入口。

（由于混计人数在混合班中基数较大，所以也收录了一部分 ckc 的资源。）

如果你喜欢这个项目，可以[给这个项目一个 ⭐️](https://github.com/SYSUMSC/sysu-cs-asio)；如果你发现项目中部分资源信息过时或有误（如链接失效、有更合适的描述等），又或者是你想分享更多的资源，请查看[贡献方法](#贡献方法)！

## 目录

- [SYSU CS - All Sum in One!](#sysu-cs---all-sum-in-one)
  - [介绍](#介绍)
  - [目录](#目录)
  - [All-Sum-in-One](#all-sum-in-one)
  - [贡献方法](#贡献方法)
  - [鸣谢 / 灵感来源](#鸣谢--灵感来源)
  - [许可](#许可)

## All-Sum-in-One

> [!IMPORTANT]
>
> 表格仅按照大类进行排序，大类内的先后顺序并不暗示笔记质量！
>
> 另外，针对在 GitHub 仓库中访问的同学：由于 [Idea: Introduce new rule against use of target="_blank" on links](https://github.com/github/erblint-github/issues/26)，所以所有在 GitHub 仓库中访问链接直接点击都会导致直接在当前页跳转，所以如果你希望保留该页面，请使用 鼠标中键/三指/快捷键+左键 等方式访问链接。

**条目统计**： 💎 个人 3 项！

| Title | Description |
| :--- | :--- |
| <a href="https://flowus.cn/xyhelp/share/91f0dd5a-7f17-45e3-9164-bfb96dce48f0" target="_blank">💎 xy3-计算机科学与技术-期末应试笔记</a> | 🥑 xy3的复习期末用的课程笔记，含收集的网课 |
| <a href="https://seanoll.github.io/cpp/" target="_blank">💎 Seanoll-程序设计II(C++)</a> | 🥑 25级程设II课程笔记 |
| <a href="https://github.com/fuuzen/notebook" target="_blank">💎 fuuzen-计算机科学与技术-mkdoc笔记本</a> | 🥑 学习笔记包括计算机、数学、思政的思维导图和笔记 |



## 贡献方法

> [!CAUTION]
>
> 贡献前请先阅读下面内容！
>
> 简单来说就是**不要直接修改 `README.md`**，而是修改 `data.csv`，否则脚本会将其覆盖。

1. 使用 py 脚本一键导入（增加资源推荐这个方案）
    - 输入 <code>python scripts/asio_helper.py <span class="nt">-a</span></code>，然后根据提示输入相关信息即可。
2. 直接编辑 csv 文件（修正资源推荐这个方案）
    - 直接编辑 <code>data.csv</code> 文件，按照 csv 文件格式    在行末添加数据。
    - 请确保你的数据格式和内容正确！（详细要求见下方“注意”。）


您可以使用如下命令来检查渲染后的结果以保证数据没有问题：

```bash
python scripts/asio_helper.py -r # The output will overwrite `README.md`.
```

> [!WARNING]
>
> 1. 本项目仅仅收集资源链接，而不实际存储资源，**请勿提交资源文件**；
> 2. 请注意排版问题，包括但不限于：**中西文间加空格**，**描述末尾加句号**等；

如果发现项目中涉及的内容有误或链接失效等，可以直接修改 `data.csv` 中对应内容。

## 鸣谢 / 灵感来源

- 原项目： [IsshikiHugh/zju-cs-asio](https://github.com/IsshikiHugh/zju-cs-asio)
- [QSCTech/zju-icicles](https://github.com/QSCTech/zju-icicles)
- [timqian/chinese-independent-blogs](https://github.com/timqian/chinese-independent-blogs/tree/master)
- [SaltyfishShop/big_discusson](https://github.com/SaltyfishShop/big_discusson)

以及 Contributors：

<a href="https://github.com/SYSUMSC/sysu-cs-asio/graphs/contributors">
    <img width="550" src="https://contrib.rocks/image?repo=SYSUMSC/sysu-cs-asio" />
</a>

## 许可

本文档采用 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 协议进行许可，转载请注明出处。
