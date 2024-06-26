## 温馨提示

这是笔者写于 2024-02-20 的补充提示，为读者解答为何前面的章节都未提及 script-setup 组件语法的信息。

笔者在执笔之初，考虑到降低初学过程中的各种心智负担，以及当时处于 script-setup 组件语法尚未完全稳定的背景下，所以在最后一章 [高效开发](/efficient) 之前的章节，都只提供了组件的标准写法的讲解。

除非遇到框架进行了 Breaking Change （例如从 Vue 2 升级到了 Vue 3 这种大版本更新），否则标准写法是始终有效的，在笔者多年的学习经历和实际收获里，也是比较相信一点：不论学习什么语言或者框架，只要基础打的好，未来总是可以轻松地举一反三去解决遇到的各类问题。

因此如果读者通过各类脚手架创建的 Vue 3 项目，在组件看到 `<script setup>` 这种风格的组件，以及诸如 `defineXxx` 风格的 API ，这是 `.vue` 组件所支持的一种语法糖，可以随时在 [高效开发](/efficient) 一章了解相关的 API 用法。

另外从 Vue 3.4 版本之后所新增的 API 未在本书的介绍范围内，请读者在阅读的过程中也可以查阅官方的 API 一起学习，不论是本书还是其他计算机书籍，官方文档永远是最好的查询手册。

:::tip
语法糖（英语：Syntactic sugar）是由英国计算机科学家彼得·兰丁发明的一个术语，指计算机语言中添加的某种语法，这种语法对语言的功能没有影响，但是更方便程序员使用。语法糖让程序更加简洁，有更高的可读性。
:::
