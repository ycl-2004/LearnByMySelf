# Phase 0：从 0 开始的完整学习路径

## YC_Improvement / AI Coding Workflow Tool 学前总准备

> 这份文件是给“完全从 0 开始”的自己看的。  
> 预设你**不懂编程、不懂前后端、不懂 JavaScript、不懂终端、不懂 API、不懂数据库**。  
> 目标不是装懂，而是把地基打到后面能真的开始做项目。

---

# 0. Phase 0 到底是什么？

Phase 0 不是正式开发项目。  
Phase 0 是：

> **让你从“完全不会写代码的人”，进入“看得懂基本代码、能自己写一点逻辑、知道开发世界的基本地图”的阶段。**

如果把后面做项目比喻成盖房子：

- Phase 0 = 认识工具、材料、地图、施工方法
- Phase 1 以后 = 开始真的盖房子

所以在这个阶段，你不用追求：

- 做出很厉害的网站
- 学很多框架
- 学会 AI 开发
- 学会 Java
- 学会数据结构

你只需要做到一件事：

> **不再害怕代码，并且能开始理解“程序到底在干嘛”。**

---

# 1. Phase 0 的最终目标

完成 Phase 0 之后，你应该达到下面这些状态：

## 1.1 认知目标

你要知道：

- 什么是程序
- 什么是代码
- 什么是编程语言
- 什么是 JavaScript
- 什么是 Node.js
- 什么是终端 Terminal
- 什么是文件 / 文件夹 / 路径
- 什么是 Git
- 什么是 API（先理解概念，不求会做）
- 什么是前端 / 后端 / 数据库（先有地图）

---

## 1.2 实作目标

你要做到：

- 会打开 terminal
- 会进入某个文件夹
- 会建立一个文件
- 会用编辑器打开项目文件夹
- 会运行一个 `.js` 文件
- 会读懂最基础的 JavaScript 代码
- 会自己写变量、函数、判断、循环
- 会处理数组和对象
- 会写简单的 async / await
- 会把一个小问题拆成几步逻辑

---

## 1.3 心态目标

你要建立：

- 遇到报错不崩溃
- 看不懂代码时知道怎么拆解
- 知道“现在不懂是正常的”
- 不再把编程当神秘黑盒
- 知道自己后面是为了做项目，不是为了死背语法

---

# 2. Phase 0 不做什么

为了避免你走歪，先明确：

## 现在先不要做这些

- 不要一开始学 React
- 不要一开始学 TypeScript
- 不要一开始学 Java
- 不要一开始学 Spring Boot
- 不要一开始学数据库
- 不要一开始学 LeetCode
- 不要一开始学复杂数据结构
- 不要一开始做 VS Code 插件
- 不要一开始碰“高级 AI Agent 框架”
- 不要一开始就跟着别人抄完整项目

为什么？

因为你现在最缺的不是“高级知识”，而是：

> **最基础的编程理解力**

---

# 3. 你现在到底要学哪些知识？

这部分非常重要。  
我把 Phase 0 需要知道的知识，拆成 7 个模块。

---

# 模块 A：开发世界地图（你先知道世界长什么样）

这是最容易被忽略，但其实最重要的模块。

---

## A.1 什么是编程？

编程就是：

> 把你想让电脑做的事情，拆成一条一条明确的指令，然后用电脑能理解的方式写下来。

比如你想让电脑做一个“计算总分”的功能：

1. 先拿到各科成绩
2. 把它们加起来
3. 输出结果

这就是程序逻辑。

---

## A.2 什么是代码？

代码就是：

> 你写给电脑看的“指令文本”

例如：

```javascript
let a = 3;
let b = 5;
console.log(a + b);
```

这段代码的意思是：

- 设定一个变量 `a = 3`
- 设定一个变量 `b = 5`
- 把 `a + b` 的结果输出出来

---

## A.3 什么是编程语言？

电脑本身不懂人类自然语言，所以我们要用“编程语言”来写指令。

常见语言有：

- JavaScript
- TypeScript
- Python
- Java
- C++
- Go

你现在先学的是：

> **JavaScript**

因为它对你后面做 Web / Node / AI 工具项目最直接。

---

## A.4 什么是前端？

前端是：

> 用户看得到、点得到、操作得到的界面部分

例如：

- 网页按钮
- 输入框
- 页面排版
- 卡片
- 下拉菜单
- 动画

---

## A.5 什么是后端？

后端是：

> 在背后处理数据、逻辑、权限、请求的部分

例如：

- 登录验证
- 把用户资料存起来
- 调 AI API
- 查询历史记录
- 处理业务逻辑

---

## A.6 什么是数据库？

数据库是：

> 用来长期保存数据的地方

例如：

- 用户资料
- 历史记录
- 任务内容
- AI 生成结果

---

## A.7 什么是 API？

API 可以理解成：

> 系统和系统之间的“沟通接口”

比如：

- 前端把代码片段发给后端
- 后端调 AI 模型
- 后端把结果回传给前端

这些中间常常都是通过 API 完成的。

---

## A.8 什么是全栈？

全栈就是：

> 前端 + 后端 + 数据库 都会一点，能把完整系统串起来

你未来目标不是只懂一个按钮，而是：

> **能做出完整系统的人**

---

# 模块 B：电脑与文件系统基础（很多人卡死在这里）

你如果连文件、路径、终端都不懂，后面学代码会非常痛苦。

---

## B.1 什么是文件？

文件就是电脑里的一个具体资料单位。

例如：

- `README.md`
- `index.js`
- `package.json`
- `notes.txt`

---

## B.2 什么是文件夹？

文件夹就是装文件的容器。

例如：

```text
YC_Improvement/
  README.md
  phase0.md
  index.js
```

---

## B.3 什么是路径？

路径就是：

> 某个文件在电脑中的位置

例如：

```bash
/Users/yichenlin/Desktop/YC_Improvement
```

这就是一个文件夹路径。

---

## B.4 什么是扩展名？

扩展名是文件名最后面的部分，用来告诉系统这是什么类型文件。

例如：

- `.js` → JavaScript 文件
- `.md` → Markdown 文件
- `.txt` → 文本文件
- `.json` → JSON 文件

---

## B.5 什么是终端 Terminal？

终端就是：

> 你不用滑鼠点点点，而是直接输入命令和电脑沟通的地方

你以后常用 terminal 来：

- 进入某个资料夹
- 运行代码
- 安装套件
- 用 git 管理版本
- 启动项目

---

## B.6 Phase 0 你必须会的 terminal 指令（macOS）

### `pwd`

显示你现在在哪个路径

```bash
pwd
```

### `ls`

列出当前资料夹有哪些东西

```bash
ls
```

### `cd`

进入某个资料夹

```bash
cd Desktop
cd YC_Improvement
```

### `cd ..`

回到上一层

```bash
cd ..
```

### `mkdir`

建立新资料夹

```bash
mkdir test-folder
```

### `touch`

建立新文件

```bash
touch index.js
```

---

## B.7 你要理解一个关键概念

> “我现在在哪个文件夹里” 很重要

很多人 terminal 出错，不是代码不会，而是：

- 路径错了
- 不在对的 folder
- 文件根本不在当前目录

所以你以后要养成习惯：

```bash
pwd
ls
```

先确认环境。

---

# 模块 C：编辑器与开发环境基础

---

## C.1 什么是代码编辑器？

代码编辑器就是你平常写代码的地方。

你现在建议使用：

- Cursor
- 或 VS Code

---

## C.2 为什么不要用普通记事本？

因为代码编辑器有：

- 语法高亮
- 自动补全
- 错误提示
- 搜索替换
- 文件树
- Git 整合

这些会大幅降低你的学习痛苦。

---

## C.3 正确使用方式

以后尽量不是只开单个文件，而是：

> **Open Folder**

直接打开整个项目文件夹，例如：

```text
YC_Improvement
```

这样你会看到：

- 所有文件结构
- 更像真实开发环境
- 方便后面做项目

---

# 模块 D：JavaScript 基础（Phase 0 核心）

这部分是最重要的。
你现在不是要学完整 JavaScript，而是先学“够你开始写逻辑”的那部分。

---

## D.1 什么是 JavaScript？

JavaScript 是一种编程语言。

它常用在两种地方：

### 浏览器里

控制网页互动，例如按钮点击、表单、动画

### Node.js 里

在电脑 / 服务器端运行 JS 代码

你现在会先在 Node.js 环境里练习基础。

---

## D.2 你必须先理解“值”和“变量”

### 值（value）

值就是具体内容，例如：

- `3`
- `"hello"`
- `true`

### 变量（variable）

变量就是一个“盒子”，你把值放进去，并给它取名字。

例如：

```javascript
let name = "YC";
let age = 22;
```

意思是：

- 一个叫 `name` 的变量，里面放 `"YC"`
- 一个叫 `age` 的变量，里面放 `22`

---

## D.3 常见数据类型

你只要先知道这几个：

### 字符串 string

文字内容

```javascript
let name = "YC";
```

### 数字 number

数值

```javascript
let score = 95;
```

### 布林 boolean

只有两种值：

- `true`
- `false`

```javascript
let isDone = true;
```

### undefined

还没有值

### null

刻意表示“空”

---

## D.4 变量声明：`let` / `const`

### `let`

可以之后重新赋值

```javascript
let count = 1;
count = 2;
```

### `const`

不能重新指向别的值

```javascript
const appName = "YC_Improvement";
```

Phase 0 先记：

> 平常优先用 `const`，会变的再用 `let`

---

## D.5 运算

### 加减乘除

```javascript
let a = 10;
let b = 5;

console.log(a + b);
console.log(a - b);
console.log(a * b);
console.log(a / b);
```

### 字符串相加

```javascript
let first = "Hello";
let second = "World";

console.log(first + " " + second);
```

---

## D.6 条件判断 `if`

当某个条件成立时，执行某段代码。

```javascript
let score = 80;

if (score >= 60) {
  console.log("Pass");
} else {
  console.log("Fail");
}
```

---

## D.7 比较运算

你会常看到：

- `>` 大于
- `<` 小于
- `>=` 大于等于
- `<=` 小于等于
- `===` 严格等于
- `!==` 不等于

例如：

```javascript
let age = 18;

if (age === 18) {
  console.log("Exactly 18");
}
```

---

## D.8 逻辑运算

### `&&`

而且（两边都要成立）

### `||`

或者（其中一个成立）

### `!`

不是

```javascript
let age = 20;
let hasID = true;

if (age >= 18 && hasID) {
  console.log("Allowed");
}
```

---

## D.9 函数 function（极重要）

函数就是：

> 把一段逻辑装起来，之后可以重复使用

例如：

```javascript
function add(a, b) {
  return a + b;
}

let result = add(2, 3);
console.log(result);
```

这段意思是：

- 定义一个函数 `add`
- 它接收两个输入 `a` 和 `b`
- 回传 `a + b`

---

## D.10 参数 parameter

函数括号里的 `a`, `b` 叫参数。
它们是函数需要的输入。

---

## D.11 return

`return` 的意思是：

> 把结果交回去

如果没有 `return`，函数就只是执行，不会把值拿出来。

---

## D.12 数组 array（极重要）

数组就是：

> 把一组资料按顺序放在一起

例如：

```javascript
const fruits = ["apple", "banana", "orange"];
```

你可以把它理解成一个列表。

---

## D.13 数组常见操作

### 取值

```javascript
const fruits = ["apple", "banana", "orange"];
console.log(fruits[0]); // apple
```

### 长度

```javascript
console.log(fruits.length);
```

### 加入新元素

```javascript
fruits.push("grape");
```

---

## D.14 循环 loop

循环就是：

> 对很多资料重复做同一件事

### `for`

```javascript
for (let i = 0; i < 3; i++) {
  console.log(i);
}
```

### `for...of`

```javascript
const fruits = ["apple", "banana", "orange"];

for (const fruit of fruits) {
  console.log(fruit);
}
```

---

## D.15 对象 object（极重要）

对象就是：

> 用“属性名称 : 属性值”的方式存资料

例如：

```javascript
const user = {
  name: "YC",
  age: 22,
  isStudent: true,
};
```

你可以理解成一张资料卡。

---

## D.16 读取对象属性

```javascript
console.log(user.name);
console.log(user.age);
```

---

## D.17 数组 vs 对象

### 数组

适合“列表”

```javascript
["apple", "banana", "orange"];
```

### 对象

适合“一个东西的详细资料”

```javascript
{
  name: "YC",
  age: 22
}
```

---

## D.18 方法：`map`, `filter`

这是后面超常用的东西。

### `map`

把数组里的每个元素“转换”成新内容

```javascript
const numbers = [1, 2, 3];
const doubled = numbers.map((n) => n * 2);

console.log(doubled); // [2, 4, 6]
```

### `filter`

筛选符合条件的元素

```javascript
const numbers = [1, 2, 3, 4];
const bigNumbers = numbers.filter((n) => n > 2);

console.log(bigNumbers); // [3, 4]
```

---

## D.19 字串模板 template literal

更方便组合文字：

```javascript
const name = "YC";
console.log(`Hello, ${name}`);
```

---

## D.20 什么是 console.log？

`console.log()` 是：

> 把某个值印出来给你看

学编程前期你会大量用它来 debug。

例如：

```javascript
const score = 100;
console.log(score);
```

---

# 模块 E：异步 async / await（你后面一定会用）

这是初学者很容易怕的部分，但 Phase 0 只需要先懂概念。

---

## E.1 什么是同步？

同步就是：

> 一步一步照顺序做完，再做下一步

例如：

1. 洗杯子
2. 倒水
3. 喝水

---

## E.2 什么是异步？

异步就是：

> 某件事情要等一下才有结果，你不能傻站着等，所以先去做别的，等结果回来再处理

例如：

- 请求网络资料
- 调 AI API
- 读取数据库

---

## E.3 Promise 是什么？

先不用讲得太深。

你可以先理解：

> Promise = “未来会给你结果的承诺”

---

## E.4 async / await 是什么？

它是一种比较好读的异步写法。

例如：

```javascript
async function getData() {
  return "Hello";
}

async function main() {
  const result = await getData();
  console.log(result);
}

main();
```

你现在先记住：

- `async`：表示这个函数里面有异步逻辑
- `await`：等某个异步结果回来

---

## E.5 为什么这很重要？

因为你后面要做的东西几乎都跟异步有关：

- 调 AI
- 发 API 请求
- 取资料
- 存资料

所以 Phase 0 要先认识它。

---

# 模块 F：Node.js 基础（让 JS 真正跑起来）

---

## F.1 什么是 Node.js？

Node.js 是：

> 一个让 JavaScript 可以在浏览器外面运行的环境

也就是说，你可以在 terminal 里运行 `.js` 文件。

---

## F.2 你为什么需要 Node.js？

因为你后面要做：

- 后端
- API
- 开发工具
- 启动本地项目

都离不开 Node.js。

---

## F.3 如何运行一个 JS 文件？

假设你有一个文件：

```text
index.js
```

内容：

```javascript
console.log("Hello YC");
```

在 terminal 里运行：

```bash
node index.js
```

你会看到：

```text
Hello YC
```

这就是最基础的“运行代码”。

---

## F.4 什么是 package.json？

这是一个项目的说明文件。

它通常会记录：

- 项目名称
- 版本
- 用了哪些套件
- 可以执行哪些 scripts

现在你先知道它是“项目配置中心”就够了。

---

# 模块 G：Git 基础（版本管理）

你已经 `git init` 了，所以现在先建立概念。

---

## G.1 什么是 Git？

Git 是：

> 用来记录代码历史版本的工具

你可以把它理解成：

- 你代码的时光机
- 你每次修改的记录系统
- 你和 GitHub 连接的基础

---

## G.2 什么是 GitHub？

GitHub 是：

> 放 Git 项目的云端平台

你可以把代码上传上去：

- 备份
- 展示
- 未来求职
- 管理项目

---

## G.3 你现在必须知道的 Git 指令

### 初始化

```bash
git init
```

### 查看状态

```bash
git status
```

### 加入暂存区

```bash
git add .
```

### 提交

```bash
git commit -m "write a message"
```

---

## G.4 commit 是什么？

commit 就是：

> “我现在把这次修改记录下来”

例如：

```bash
git commit -m "add phase 0 notes"
```

---

# 4. Phase 0 的学习顺序（非常重要）

你不能乱学。
正确顺序如下：

## 第一步：先懂开发世界地图

- 前端 / 后端 / 数据库 / API
- 文件 / 路径 / terminal
- 编辑器怎么用

## 第二步：学 JavaScript 最基础逻辑

- 变量
- 条件
- 函数
- 数组
- 对象

## 第三步：学怎么运行 JS

- Node.js
- `node index.js`

## 第四步：学简单 async / await

- 先懂异步是什么
- 会看最基础的异步代码

## 第五步：学 Git 最基础

- `git status`
- `git add .`
- `git commit`

这样后面你进入 Phase 1 才不会崩。

---

# 5. Phase 0 的建议时间安排

你说你一天可以学 4–5 小时。
Phase 0 建议先抓 **7 天到 10 天**。

---

## 每天建议结构

### Part 1：理解新概念（1.5 小时）

例如今天学：

- 变量
- 数组
- 函数

### Part 2：自己打代码（2 小时）

不要只看，一定要自己敲。

### Part 3：复盘 + 整理（1 小时）

写出：

- 今天学了什么
- 哪些地方不懂
- 哪些代码要重打一次

### Part 4：Debug / 问题解决（0.5 小时）

看报错、查原因、练习不慌

---

# 6. Phase 0 的 7 天完整路径

---

# Day 1：开发世界地图 + Terminal 基础

## 目标

知道你到底在学什么。

## 学什么

- 什么是前端 / 后端 / 数据库 / API
- 什么是文件、文件夹、路径
- 什么是 terminal

## 练习

在 terminal 里练：

```bash
pwd
ls
cd Desktop
cd YC_Improvement
mkdir practice
cd practice
touch day1.js
ls
```

---

# Day 2：变量 + 数据类型 + console.log

## 目标

学会最基础的值与变量。

## 学什么

- string
- number
- boolean
- let / const
- console.log

## 练习

写一个 `day2.js`：

```javascript
const name = "YC";
const age = 22;
const isStudent = true;

console.log(name);
console.log(age);
console.log(isStudent);
```

然后运行：

```bash
node day2.js
```

---

# Day 3：运算 + 条件判断

## 目标

让代码开始有“逻辑”。

## 学什么

- `+ - * /`
- `if / else`
- 比较运算

## 练习

做一个分数判断：

```javascript
const score = 75;

if (score >= 60) {
  console.log("Pass");
} else {
  console.log("Fail");
}
```

---

# Day 4：函数

## 目标

理解“可重复逻辑模块”

## 学什么

- function
- parameter
- return

## 练习

写这些函数：

- `add(a, b)`
- `greet(name)`
- `isAdult(age)`

---

# Day 5：数组 + 循环

## 目标

会处理一组资料

## 学什么

- array
- `for`
- `for...of`
- `length`
- `push`

## 练习

建立一个任务数组，然后逐个印出来。

---

# Day 6：对象 + map / filter

## 目标

开始接近真实资料结构

## 学什么

- object
- 读取属性
- `map`
- `filter`

## 练习

建立一个 users 数组：

```javascript
const users = [
  { name: "YC", score: 90 },
  { name: "Amy", score: 70 },
  { name: "Tom", score: 50 },
];
```

做两件事：

- 把所有名字取出来
- 筛选出及格的人

---

# Day 7：async / await + Node.js 运行 + Git 基础

## 目标

知道代码怎么运行，知道 Git 是什么

## 学什么

- async / await
- `node filename.js`
- `git status`
- `git add .`
- `git commit`

## 练习

建立一个 async function，跑成功一次。
然后做一次 git commit。

---

# 7. 你完成 Phase 0 时应该会的清单（Checklist）

请你一项一项检查。

## 终端

- [ ] 我知道什么是 terminal
- [ ] 我会用 `pwd`
- [ ] 我会用 `ls`
- [ ] 我会用 `cd`
- [ ] 我会建立文件和文件夹

## 编辑器

- [ ] 我会用 Cursor 或 VS Code 打开 folder
- [ ] 我知道怎么建立 `.js` 文件
- [ ] 我知道怎么编辑并存档

## JavaScript 基础

- [ ] 我知道 string / number / boolean
- [ ] 我会用 `let` / `const`
- [ ] 我会用 `console.log`
- [ ] 我会写 `if / else`
- [ ] 我会写 function
- [ ] 我会写 array
- [ ] 我会写 object
- [ ] 我会用简单循环
- [ ] 我会看懂 `map`
- [ ] 我会看懂 `filter`

## Node.js

- [ ] 我会用 `node filename.js` 跑代码

## 异步

- [ ] 我知道 async / await 是做什么的
- [ ] 我会看简单异步代码

## Git

- [ ] 我知道 Git 是做什么的
- [ ] 我会用 `git status`
- [ ] 我会用 `git add .`
- [ ] 我会用 `git commit -m "..."`

---

# 8. Phase 0 最常见的错误观念

---

## 错误 1：我是不是要把 JavaScript 全部学完才能开始？

不是。

你现在只要学“够开始写逻辑”的部分。

---

## 错误 2：我是不是要把每个语法都背起来？

不是。

编程不是背书，是：

> 理解逻辑 + 会查 + 会练

---

## 错误 3：我看到报错，是不是我很烂？

不是。

报错是编程的日常。
真正的能力不是“不报错”，而是：

> 看到报错后能一步一步查

---

## 错误 4：我是不是应该先学最难最热门的东西？

不是。

你现在最需要的是：

> **能理解 + 能操作 + 能稳定推进**

---

# 9. Phase 0 的学习原则

## 原则 1：自己敲代码，不要只看

光看懂没用，手不动就不会。

---

## 原则 2：每个知识点都要配小练习

例如学函数，就一定写 3 个函数。

---

## 原则 3：不要追求一天懂全部

你的目标不是一天变高手，而是：

> 一天比一天少害怕一点

---

## 原则 4：不懂的词马上记下来

做一个 `questions.md` 文件，记录：

- 今天不懂什么
- 哪段代码不懂
- 哪个报错不懂

---

## 原则 5：理解优先，速度第二

慢一点没关系，乱冲才危险。

---

# 10. Phase 0 和后面项目的关系

你现在学的每一个东西，后面都会用到：

- 变量 → 存资料
- 函数 → 写逻辑
- 数组 → 管理列表资料
- 对象 → 表示用户、请求、结果
- async / await → 调 API、调 AI
- Node.js → 做后端
- Git → 管理项目版本

也就是说：

> **Phase 0 不是“前菜”，它是后面所有内容的基础。**

---

# 11. 你现在最重要的一句话

> **我现在不是在学高级开发，我是在建立“看得懂代码、写得出基础逻辑”的能力。**

只要你做到这点，Phase 1 就能开始。

---

# 12. Phase 0 完成标准（Pass / Not Pass）

## Pass

如果你已经能：

- 自己建立 `.js` 文件
- 用 Node 跑起来
- 写基本变量、函数、数组、对象
- 看懂简单 if / loop / async
- 用 git 做一次 commit

那就算通过。

---

## Not Pass

如果你现在还是：

- 连 terminal 不敢开
- 连代码怎么运行都不会
- 连变量和函数都分不清
- 一看数组对象就糊掉

那就不要急着进入 Phase 1，先把 Phase 0 补稳。

---

# 13. 下一步预告：Phase 1 会学什么？

当你 Phase 0 通过后，下一阶段会进入：

## Phase 1：Backend 基础

你会开始学：

- 什么是 server
- 什么是 request / response
- 什么是 API route
- Express 是什么
- 怎么做一个最基础后端接口

也就是：

> 从“会写基础逻辑”，升级到“开始做系统”

---

# 14. 最后总结

Phase 0 的本质不是让你变成工程师。
Phase 0 的本质是：

> **把你从“完全陌生”带到“我知道代码世界怎么运作，而且我可以开始写”**

你现在最该做的不是焦虑自己不会太多，
而是一个一个把最基本的点打通。

---

# 15. 给现在的自己的一句话

> 不要急着变厉害，先让自己变得不害怕。
> 不要急着做大项目，先让自己能看懂、能运行、能修改最基本的代码。
> 这就是 Phase 0 的胜利。

````

这份可以直接存成：

```text
PHASE0.md
```

放进你的 `YC_Improvement` 文件夹里。

你下一步最对的做法，是把这份当成“学习总纲”，然后我再继续帮你拆成：

> **Phase 0 - Day 1 实际执行版**

也就是不只讲概念，而是直接告诉你：
今天开什么文件、打什么代码、怎么运行、怎么检查自己有没有学会。
````
