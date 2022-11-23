---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
---

# 就业经验分享

互联网寒冬 —— 如何提升自己的抗风险能力

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---

# 防杠声明

<br/>

- 个人观点，不一定对

<br/>

- 每年就业形势不同，今年的经验不一定适用于几年后

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# 背景：互联网寒冬

<div class="mt-8 flex">
  <div v-click>
    <img src="/1.png" class="w-100"/>
    <img src="/2.png" class="w-100"/>
  </div>
  <img v-click src="https://pic1.zhimg.com/80/v2-ab83c1ca8d5f3d9ddb483d45c88b0f48_720w.webp" class="w-100 ml-5"/>
</div>


---
layout: center
---​

# Part 1: 想进大厂，你需要准备些什么
​
---

---
layout: two-cols
---

<template v-slot:default>

# 技术开发岗

<br/>

1. 服务端开发 (Java/Go/C++...)
2. Web 前端开发
3. 算法
4. 客户端开发(ios/android/qt...)
5. 测试开发
6. 数据分析

</template>
<template v-slot:right>

# 非技术

<br/>

1. 产品经理
2. 测试
3. 运营
...


</template>

---

# 求职时间点

<br>

## 春招 - 实习：

<br>

* 面试时间：过年后 - 5 月
* 面试难度：低于秋招，head count 会多一点

## 秋招 - 正式：

<br>

* 面试时间：8 - 10 月
* 难度高，hc 少，即使技术面试过了也要排序

---

# 大厂 offer = 实习 + 项目 + 八股 + 算法

<br/>

## 项目

<br/>

1. 2-3 个相关项目，一般为前后端分离项目
2. 要求：项目复杂度、有亮点

<br>

## 算法

<br/>

1. leetcode mid 题目都可以解出来

<br/>

## 八股

<br/>

1. 通用：数据结构与算法 + 操作系统 + 计算机网络
2. 相应岗位知识：(前端) HTML + CSS + JavaScript + Vue or React + 前端工程化(webpack/vite)...


---
layout: center
---​

# Part 2: 程序员必备资源
​
---

---
layout: two-cols
---

<template v-slot:default>

# 常用网站

<br/>

1. [github](https://github.com)
2. [leetcode](https://leetcode.cn)
3. [Google](https://google.com)
4. [StackOverflow](https://stackoverflow.com/)
5. [掘金](https://juejin.cn/)
6. [牛客](https://www.nowcoder.com/)

</template>
<template v-slot:right>

# 学习资源

<br/>

### 算法

<br/>

1. labuladong (公众号)
2. 代码随想录 (公众号)

<br/>

### 计算机基础

<br/>

1. 小林 coding (公众号)：图解网络、图解系统
2. 王道考研

<br>

### 项目

<br>

1. https://github.com/explore

</template>

---

# 前端资源

<br/>

1. [MDN](https://developer.mozilla.org/zh-CN/)
2. [前端学习路线](https://objtube.github.io/front-end-roadmap/#/)
3. [前端知识图谱](https://gitee.com/jishupang/web_atlas)
4. JavaScript高级程序设计
5. [Vue.js 官方文档](https://cn.vuejs.org/)
6. [ES6 入门教程](https://es6.ruanyifeng.com/#docs/symbol)
7. [web 面试题](https://vue3js.cn/interview/)
8. [掘金上的文章收藏](https://juejin.cn/user/2032361777410605/collections)
9. [前端の神博客，github 1.5k star](https://blog.touchczy.top/#/)

---

# Part 3: 个人建议

<br/>

1. 抛弃学生思维，主动 + 自学

<br/>

2. 选择大于努力