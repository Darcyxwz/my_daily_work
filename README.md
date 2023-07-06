# my_daily_work
This repository is about what I do every day. 
I'll also write about what I learn in my daily life in this md file.
My works are in other repositories. You can look into the dates when I update codes for those repositories.
## plans
由于github仓库不能储存node_modules文件，但是在package.json文件中仍会显示相关依赖的内容，所以在下载github文件至本地之后，直接执行pnpm install (npm install)，即可自动把要下载的依赖包补全。但是其中有一部分不能用这个指令下载补全，要从package.json中寻找下载指令。

创建一个vite+react+ts模板文件：https://vitejs.cn/vite3-cn/guide/#trying-vite-online，按流程操作

熟悉git的基本操作：https://learngitbranching.js.org/?locale=zh_CN

mapbox配置：first, create a vite directory. Second, https://visgl.github.io/react-map-gl/docs/get-started. Third, "./App.css": delete the #root part (show the whole view)

先熟悉下react基础语法和使用：
1. react学习：https://react.dev/learn
2. 状态库valtio学习：https://valtio.pmnd.rs/

第一周任务（已完成）：
1. 本周内，在github建立仓库，用于提交日常练习代码
2. 学习react，并能依据文档，独立完成文档demo
3. 学习总结，建议用md文件，汇报自己学习到的知识点

后续学习计划（*）：
1. 学习mapbox（mapbox的使用还是简单的，入门应该比较快，就是你试试和react结合起来）
2. 学习hook的使用（可以找找博客，掘金，思否等网站都有）
学习目标：
1. 新建一个react项目（已完成）
2. 在项目中添加地图（已完成）
3.在成功添加地图后，参考mapbox的example，成功添加图层

（*）可以自己动手写下demo，有个库react-mapgl，https://visgl.github.io/react-map-gl/

## 2023.6.25
1. 成功创建了vite+react+ts的项目，并且跑起来
2. 学习了部分git基本操作，预计本周之内学完，本次上传的文件不全，只是复制上去了，我还没有把github与本地文件链接起来，回家研究一波，应当可以解决
3. 正在学习井字棋项目，在跟随向导完成任务，预计明天完成这个项目
## 2023.6.26
1. 已经将github与本地文件链接起来，可以在本地直接commit，仍需研究git剩余基本知识（下载了github desktop）
2. 学习并完成井字棋项目，并上传至github，名字为tic-tac-toe(showing the past moves)
## 2023.6.27
1. 上午继续学习react用法，回去继续看thinking in react，之后要学习state用法
2. 开始学习mapbox，看示例，看地图
## 2023.6.28
1. 今天完成了to-do-list代码
2. 上午看了少量mapbox
## 2023.6.29
1. 整理昨天to-do-list知识点
2. 研究mapbox基本用法
## 2023.6.30
1. 将mapbox从html形式转化为react形式
2. 上传了搭建简单resium文件的代码，初始位置定位为武汉地面
3. 用mapbox将武汉用多边形包围起来
## 2023.7.5
1. js方面：react+ts
css库：unocss/tailwindcss
构建工具：vite
状态库：valtio
额外补充：rxjs
项目必备：mapbox(https://docs.mapbox.com/mapbox-gl-js/guides/)
2. 有个中文网站：https://www.naivemap.com/mapbox-gl-js-cookbook/starter/
3. 补充下：
  css动画库:Framer Motion（https://framer.com/projects/?reason=web-login&id=fbf3acc9-5de5-4859-a7d5-93be0294279d）
  hook库: ahooks
4. 先克隆代码
5. 项目克隆之后
包管理器是pnpm
不要用其他的包管理器安装
6. 我们的技术栈是 vite + react + react-router + mapbox + deck.gl + typescript
状态管理叫 valtio
请求库有两个 react-query   @ngify/http
时间库 date-fns
辅助库 lodash-es  ahooks
写样式 unocss sass
主流的我们基本都在用, 而且版本还很新
先把东西都装起来
pnpm north-dev  能跑起来就是都装好了
之后我们再谈其他的

tailwindcss 三道例题：

https://tailwindcomponents.com/component/statics-viewer

https://tailwindcomponents.com/component/dishant-singh-6

https://tailwindcomponents.com/component/storage-card-horizon-ui-tailwind

tailwindcss 笔记：
https://tailwindcomponents.com/cheatsheet/

1. https://developer.mozilla.org/zh-CN/docs/Web/CSS/backdrop-filter
2. https://tailwindcss.com/docs/guides/vite
3. https://unocss.dev/integrations/vite
4. 各种页面常见布局：https://sweet-kk.github.io/css-layout/#/?id=%e5%90%84%e7%a7%8d%e9%a1%b5%e9%9d%a2%e5%b8%b8%e8%a7%81%e5%b8%83%e5%b1%80%e7%9f%a5%e5%90%8d%e7%bd%91%e7%ab%99%e5%ae%9e%e4%be%8b%e5%88%86%e6%9e%90%e7%9b%b8%e5%85%b3%e9%98%85%e8%af%bb%e6%8e%a8%e8%8d%90


