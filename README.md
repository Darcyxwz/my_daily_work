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
1. https://tailwindcss.com/docs/aspect-ratio
2. https://tailwindcomponents.com/cheatsheet

UnoCSS 笔记：
https://unocss.dev/interactive/

1. https://developer.mozilla.org/zh-CN/docs/Web/CSS/backdrop-filter
2. https://tailwindcss.com/docs/guides/vite
3. https://unocss.dev/integrations/vite
4. 各种页面常见布局：https://sweet-kk.github.io/css-layout/#/?id=%e5%90%84%e7%a7%8d%e9%a1%b5%e9%9d%a2%e5%b8%b8%e8%a7%81%e5%b8%83%e5%b1%80%e7%9f%a5%e5%90%8d%e7%bd%91%e7%ab%99%e5%ae%9e%e4%be%8b%e5%88%86%e6%9e%90%e7%9b%b8%e5%85%b3%e9%98%85%e8%af%bb%e6%8e%a8%e8%8d%90

## 2023.7.21
1. 做我前几天发的sass的视频的时候
【Udemy排名第一的高级CSS课程】Advanced CSS and Sass - 高级 CSS 和 Sass：Flexbox、网格、动画（中英文字幕）
有不会的位置
看这个网站, 现代布局的坑基本全都涵盖了
https://sweet-kk.github.io/css-layout/#/?id=%e5%90%84%e7%a7%8d%e9%a1%b5%e9%9d%a2%e5%b8%b8%e8%a7%81%e5%b8%83%e5%b1%80%e7%9f%a5%e5%90%8d%e7%bd%91%e7%ab%99%e5%ae%9e%e4%be%8b%e5%88%86%e6%9e%90%e7%9b%b8%e5%85%b3%e9%98%85%e8%af%bb%e6%8e%a8%e8%8d%90
2. https://github.com/bradtraversy/50projects50days
这个回去看

## 2023.7.27
【使用HTML和CSS创建霓虹灯按钮悬停动画效果 | 源码下载】 https://www.bilibili.com/video/BV1zR4y1h7Xq/?share_source=copy_web&vd_source=12cf81bfefc09138078bf7a58e9c6425
【[CSS]这是你要的高级感吗-视觉差名片】 https://www.bilibili.com/video/BV1Mf4y1x7DK/?share_source=copy_web&vd_source=12cf81bfefc09138078bf7a58e9c6425
【百叶窗经典特效（css+html）】 https://www.bilibili.com/video/BV1eb4y1q7ZB/?share_source=copy_web&vd_source=12cf81bfefc09138078bf7a58e9c6425

几个比较经典的动效, 工作中也很常用, 可以收藏看看实现, 跟着练习

下周就不做css这块了，你们觉得css薄弱的要午休和下班了多学多看。

下周我在网上找一些 react 的简单的组件，让你们学习原理，如果学得快的话，8月中旬的时候让你们参与到正式开发中，一开始先抽离组件给你们写，后面再教你们写复杂的逻辑，把组件拼接成应用。

## 2023.7.31
不懂的APi看这个网站,有教程，教程看不懂就问我
https://zh-hans.react.dev/
https://react.dev/
一个中文一个英文

这是进阶的资料
https://overreacted.io/zh-hans/a-complete-guide-to-useeffect/
react核心开发者的博客，有中文，这一篇要多看几遍

https://www.developerway.com/
其他react原理的进阶

https://www.patterns.dev/
前端的设计模式

## 2023.8.2
```import { MapStyleSwitcherV2 } from "uikit";```

一般来说，index文件是默认的后缀，会自动寻找含有"index"的文件；这里uikit是一个包，但是引用需要到一个具体的文件，所以这里的全称是"uikit/index.tsx"

## 2023.8.4
git reset --hard origin/main强制用本地origin/main替换本分支

不要在main分支上执行代码的更改，尤其不要执行push操作，这样会直接改变origin/main！
所以，以下是正常的流程：
1. git branch -b branch-name
2. 进行代码的更改
3. 执行commit操作，记录这次代码的更改
4. git rebase origin/main
5. 处理merge矛盾点
6. git rebase --continue

## 2023.8.7
fetch origin rebase origin/main后执行下面的语句

rm -rf .git/refs/original/
git reflog expire --expire=now --all
git gc --prune=now

不要再把大文件推到git中

我拉一个分支叫 wenbao
文保相关的推送就从这个分支拉。然后发pr到wenbao

https://github.com/react-component
按顺序看这几个，[footer](https://github.com/react-component/footer) [portal](https://github.com/react-component/portal) [drawer](https://github.com/react-component/drawer) [dialog](https://github.com/react-component/dialog)

## 2023.8.15
今天学会了useMemo(()=>{}, []);这是一个只与依赖项关联起来的函数，只有当依赖项改变才会计算结果，且以依赖项作为参数。
```js
const calcLeft = useMemo(() => {
    let totalLeft = 0;

    for (let i = 0; i < activeIndex; i++) {
      totalLeft += 48;
      totalLeft += labels[i].length * 16;
    }

    return totalLeft;
  }, [activeIndex]);
```

以下包含了多项知识点：map(), onClick,  clsx()特殊用法
```
{labels.map((label, index) => (
          <div key={index} onClick={() => setActiveIndex(index)} className={clsx("flex justify-center items-center h-36 text-16 font-500 cursor-pointer", activeIndex === index ? "text-[#0064C8]" : "text-[#303030]")}
          style={{
            width: label.length * 16 + 48,
          }}>{label}</div>
        ))}
```

以下是onClick常规用法：
```js
function handleClick(event) {
  // 获取被点击的 div 元素的内容
  const clickedContent = event.target.textContent;
  console.log("点击的内容：", clickedContent);
  // 在这里你可以对 clickedContent 做你想要的操作
}

onClick={(event)=>handleClick(event)}
```

如果handle函数没有参数：
```js
onClick={handleClick}
```
没有'()'就不会执行！

## 2023.8.16
将本地分支与远程分支连接起来：git branch -u origin/ep

git remote prune origin 清除已经被销毁的远程分支

git commit -m "content" -n 不执行代码格式的更改，直接提交

pnpm add -g git-cz

symphony\apps\electric-pile\tsconfig.json 在这里有路径规范

## 2023.8.17
如何让一个小div在一个大div中水平居中？

回答：将小div放在另一个div中：<div className="flex justify-center"> <div id="小div" /> </div>，因为flex的div会自动撑满他的两边（定高不定宽的话），可以方便居中。
文字居中的处理：<div className="flex1 text-center/text-start/text-end">content</div>，flex-1的对象也会自动两边撑满！

## 2023.8.19
https://www.maliquankai.com/2019/05/17/2019-05-17-small-program-design/

微信小程序设计规范_小程序分享图片尺寸_全智能时代的博客-CSDN博客：https://blog.csdn.net/qq_31432773/article/details/127763931

小程序的设计尺寸是多少? - 知乎： https://www.zhihu.com/question/436983202

做小程序设计，不得不说的7个坑：https://www.uisdc.com/7-traps-in-mini-program-design

## 2023.8.20
git分支命名规范：
feature-xxx-开发者名字（可姓名首字母简写）（功能开发分支，以自己开发功能模块命名，功能测试正常后提交远程pr，原则上一个分支尽量开发一个功能模块。不要多个功能模块在一个分支上开发）
feature-xxx-fix-开发者名字（同上）（功能bug修复分支，feature分支合并之后发现bug，在合并后的分支（如main或develop）上创建分支进行修复，之后rebase无冲突后合并回相应分支）
【补充：feature分支在申请合并之后，未合并之前还是可以提交代码的，所以feature在合并之前还可以在原分支上继续修复bug，此时不用新建分支】
bugfix-xxx-开发者名字（同上）（bug修改分支，在main或develop分支上创建，修复完成后合并到main或develop）

【注意：分支改动完，提交前都要确认是否有冲突，冲突是否解决完】

每个git commit记录都需要按照固定格式，具体格式为：

第一行：作者，功能模块名称或者 功能模块ID
第二行：提交描述。中英文均可

## 2023.10.8
1. 登录的原理

2. Form的概念不清晰, 不局限于 ant design, 对 html5 的表单似懂非懂

3. 路由系统掌握的不够深刻

4. devtools 网络面板不会用

5. procomponents https://procomponents.ant.design/components/modal-form






