# 逆天开发库

**防止失效，我都Fork一份到自己的github中，并完善了部分文档**（过时请Issue下）
> `看文档`：我的Github；`看源码`：原地址

PS：其实很多工具我以前曾经提过：**[大公司都有哪些开源项目~~~阿里，百度，腾讯，360，新浪，网易，小米等](https://www.cnblogs.com/dunitian/p/5581520.html)**
> **常用解决方案**：<https://github.com/LessChina>

- [逆天开发库](#%e9%80%86%e5%a4%a9%e5%bc%80%e5%8f%91%e5%ba%93)
    - [IDE](#ide)
        - [1.VSCode推荐插件](#1vscode%e6%8e%a8%e8%8d%90%e6%8f%92%e4%bb%b6)
            - [1.1.Public](#11public)
            - [1.2.Python](#12python)
            - [1.3.JavaScript](#13javascript)
            - [1.4.DataBase](#14database)
            - [1.5.xxx](#15xxx)
            - [1.6.NetCore](#16netcore)
            - [other](#other)
        - [2.NoteBook快捷键](#2notebook%e5%bf%ab%e6%8d%b7%e9%94%ae)
            - [2.1.编辑模式快捷键](#21%e7%bc%96%e8%be%91%e6%a8%a1%e5%bc%8f%e5%bf%ab%e6%8d%b7%e9%94%ae)
            - [2.2.命令模式快捷键](#22%e5%91%bd%e4%bb%a4%e6%a8%a1%e5%bc%8f%e5%bf%ab%e6%8d%b7%e9%94%ae)
            - [2.3.设置系列](#23%e8%ae%be%e7%bd%ae%e7%b3%bb%e5%88%97)
        - [3.JetBrains系列快捷键](#3jetbrains%e7%b3%bb%e5%88%97%e5%bf%ab%e6%8d%b7%e9%94%ae)
        - [4.VI快捷键：](#4vi%e5%bf%ab%e6%8d%b7%e9%94%ae)
    - [1.Web](#1web)
        - [1.1.多平台](#11%e5%a4%9a%e5%b9%b3%e5%8f%b0)
            - [1.1.1.Taro（推荐）](#111taro%e6%8e%a8%e8%8d%90)
            - [1.1.2.MPVue（潜力）](#112mpvue%e6%bd%9c%e5%8a%9b)
            - [1.1.3.Chameleon（观察中）](#113chameleon%e8%a7%82%e5%af%9f%e4%b8%ad)
            - [1.1.4.Flutter（APP）](#114flutterapp)
        - [1.2.xxx](#12xxx)
    - [2.Python](#2python)
        - [2.1.调试](#21%e8%b0%83%e8%af%95)
        - [2.2.Asyncio](#22asyncio)
        - [2.3.优化](#23%e4%bc%98%e5%8c%96)
            - [2.3.1.Numpy](#231numpy)
            - [2.3.2.Numba](#232numba)
        - [2.3.测试](#23%e6%b5%8b%e8%af%95)
            - [2.3.1.代码检测](#231%e4%bb%a3%e7%a0%81%e6%a3%80%e6%b5%8b)
                - [1.Sonar](#1sonar)
                - [2.Bandit](#2bandit)
                - [3.PyType](#3pytype)
                - [4.Other](#4other)
    - [3.DataBase](#3database)
        - [3.1.SQL](#31sql)
            - [1.优化](#1%e4%bc%98%e5%8c%96)
                - [1.1.Soar](#11soar)
                - [1.2.SQLAdvisor](#12sqladvisor)
            - [2.抓包](#2%e6%8a%93%e5%8c%85)
                - [2.1.go-sniffer](#21go-sniffer)
            - [3.中间件](#3%e4%b8%ad%e9%97%b4%e4%bb%b6)
                - [3.1.MyCat（常用）](#31mycat%e5%b8%b8%e7%94%a8)
                - [3.1.Sharding-JDBC（常用）](#31sharding-jdbc%e5%b8%b8%e7%94%a8)
                - [3.2.DBProxy(基于Atlas) or Zebra](#32dbproxy%e5%9f%ba%e4%ba%8eatlas-or-zebra)
                - [3.3.kingshard（热门）](#33kingshard%e7%83%ad%e9%97%a8)
                - [3.4.Gaea（潜力）](#34gaea%e6%bd%9c%e5%8a%9b)
                - [3.5.Other](#35other)
            - [4.binlog](#4binlog)
                - [4.1.Canal](#41canal)
            - [5.运维](#5%e8%bf%90%e7%bb%b4)
                - [MySQL常用工具包](#mysql%e5%b8%b8%e7%94%a8%e5%b7%a5%e5%85%b7%e5%8c%85)
                - [SQLServer常用工具包](#sqlserver%e5%b8%b8%e7%94%a8%e5%b7%a5%e5%85%b7%e5%8c%85)
                - [5.1.慢查询工具](#51%e6%85%a2%e6%9f%a5%e8%af%a2%e5%b7%a5%e5%85%b7)
            - [6.测试](#6%e6%b5%8b%e8%af%95)
                - [6.1.SQLer](#61sqler)
        - [3.2.NoSQL](#32nosql)
            - [3.2.1.集群系](#321%e9%9b%86%e7%be%a4%e7%b3%bb)
                - [1.Codis](#1codis)
                - [2.TwemProxy](#2twemproxy)
                - [3.overlord](#3overlord)
                - [扩展](#%e6%89%a9%e5%b1%95)
            - [3.2.2.私有云](#322%e7%a7%81%e6%9c%89%e4%ba%91)
        - [3.3.多功能工具](#33%e5%a4%9a%e5%8a%9f%e8%83%bd%e5%b7%a5%e5%85%b7)
    - [4.Spark](#4spark)
    - [5.Architecuture](#5architecuture)
        - [5.1.常用算法](#51%e5%b8%b8%e7%94%a8%e7%ae%97%e6%b3%95)
            - [5.1.1.分布式ID](#511%e5%88%86%e5%b8%83%e5%bc%8fid)
            - [5.1.2.布隆过滤](#512%e5%b8%83%e9%9a%86%e8%bf%87%e6%bb%a4)
    - [6.System](#6system)

## IDE

**常用谷歌浏览器插件**：<https://www.cnblogs.com/dunitian/p/5848931.html>

### 1.VSCode推荐插件

#### 1.1.Public

1. Markdown：**`Markdown All in One`**
    - MarkDown To PDF：**`md2pdf`**
2. JetBrains快捷键：**`IntelliJ IDEA Keybindings`**
3. Git历史插件：**`Git History`**
4. 微软开源的AI插件支持`C#, C++, TypeScript/JavaScript`：**`Visual Studio IntelliCode`**
5. _项目图标：vscode-icons_

PS：VSCode的`Markdown All in One`插件，列表选项卡只有3个空格的解决方案:
> <https://www.cnblogs.com/dotnetcrazy/p/10748165.html>

#### 1.2.Python

1. 基本：**`Python`**
2. 扩展：`Python Extension Pack`
3. **`Python Preview`**：预览的时候**图示执行过程**
4. 类型检查：**`pyright`**
5. Jupyter Notebook预览插件：`VS Code Jupyter Notebook Previewer`

pyright的说明：<https://github.com/Microsoft/pyright>

不装插件（没提示）

![20190507210220.png](https://i.loli.net/2019/05/07/5cd181e0539d7.png)

装了插件（有提示）

![20190507210128.png](https://i.loli.net/2019/05/07/5cd181ac9436a.png)

#### 1.3.JavaScript

1. **JS、CSS压缩：`Minify`**
2. **给不同区块的括号上不同的色；`Bracket Pair Colorizer`**
3. 在谷歌浏览器中调试：**`Debugger for Chrome`**
    - 当前文件在默认浏览器中打开：**`open in browser`**
4. 智能提示CSS与ID：**`HTML CSS Support`**
5. 自动给`CSS文件`添加不同浏览器的CSS3前缀：**`Autoprefixer`**
    - PS：会删除`-webkit-box-orient: vertical;` 记得手动添加一下（关注git文件对比就能快速定位）
6. px转rem：**`cssrem`**
    - PS：记得设置移动端默认字体大小：`"cssrem.rootFontSize": 20` 
7. less编译为css：**`Easy LESS`**
8. 查看语法兼容性：**`Can I Use`**
    - PS：搜索html5就能找到
9. 实时监测JS输出：**`Quokka.js`**
    - PS：只支持`js`和`ts`文件
10. 语法检测：**`ESLint`**、`jshint`、`HTMLHint`
11. js文档注释：`Document This`（`Ctrl+Alt+D`）
12. CSS样式跳转：`CSS Peek`
13. Vue框架智能提示：`Vetur`
14. 缩写补全：`JavaScript (ES6) code snippets`
15. 格式化插件：`Beautify`
16. 文件版权声明：vscode-fileheader   ctrl+alt+i

#### 1.4.DataBase

1. MySQL VSCode版IDE：**`MySQL`**
2. SQLServer插件：**`mssql`**
3. 支持大部分传统数据库：`SQLTools`or`vscode-database`
4. Redis客户端插件：`Redis console`

#### 1.5.xxx

#### 1.6.NetCore

1. 基本：**`C#`**、**`C# Extensions`**
2. NuGet：**`NuGet Package Manager`**
3. 函数文档注释：`XML Documentation Comments`（///就生成注释）
4. _IL视图：IL Viewer_

#### other

1. VSCode+Markdown下的快速上传插件：`PicGo`
    - 上传剪贴板图片：`Ctrl + Alt + U`
    - 上传本地的文件：`Ctrl + Alt + E`
2. epub格式阅读：`epub reader`

---

### 2.NoteBook快捷键

**`Ctrl + Shift + P`查看快捷键**

#### 2.1.编辑模式快捷键

| 快捷键          | 说明                           |
| --------------- | ------------------------------ |
| `Tab键`         | 智能提示                       |
| `Ctrl + /`      | 注释、取消注释                 |
| `Ctrl + Enter`  | 执行当前Cell，停留在本Cell     |
| `Shift + Enter` | 执行当前Cell，并跳转到下一行   |
| `Alt + Enter`   | 执行当前Cell，并插入一行在后面 |
| `上、下箭头`    | 移动聚焦的代码块               |

#### 2.2.命令模式快捷键

**PS：在编辑框中按`ESC`即可进入**

| 快捷键             | 说明                   |
| ------------------ | ---------------------- |
| `f`                | 查找替换               |
| `c`                | 复制Cell               |
| `x`                | 剪贴Cell               |
| **`dd`**           | **删除代码块**         |
| **`a`**            | **在Cell前面插入一行** |
| **`b`**            | **在Cell后面插入一行** |
| **`m`**            | **Cell切换成Markdown** |
| **`y`**            | **Cell切换成Code**     |
| `Enter`            | **进入编辑模式**       |
| `v`                | 在Cell后一行粘贴Cell   |
| `Shift + v`        | 在Cell前一行粘贴Cell   |
| `Shift + 上下箭头` | 选中多行               |

#### 2.3.设置系列

**1.设置默认路径**：
> <https://www.cnblogs.com/dotnetcrazy/p/9261524.html>

生成配置文件：jupyter-notebook --generate-config

打开配置文件：code ~/.jupyter/jupyter_notebook_config.py

设置默认路径：c.NotebookApp.notebook_dir = '/home/dnt/桌面/work'

**2.设置服务器自定义密码**:
> <https://www.cnblogs.com/dotnetcrazy/p/9824004.html>

**3.安装目录的扩展包**：
> <https://www.cnblogs.com/dotnetcrazy/p/10609041.html>

**4.其他系列**：
> <https://www.cnblogs.com/dotnetcrazy/p/9160514.html#2.1.编程环境>

### 3.JetBrains系列快捷键

| 快捷键                | 说明               |
| --------------------- | ------------------ |
| F6                    | 调试               |
| F8                    | 跳过方法体         |
| Alt + Enter           | 导入命名空间       |
| Alt + 上下箭          | 移动到上下方法     |
| Alt + 鼠标选中        | 选中多行           |
| Ctrl + 鼠标悬浮       | 对象信息           |
| Ctrl + P              | 参数提示           |
| Ctrl + 空格           | 代码提示           |
| Ctrl + Shift + 空格   | 显示方法预览       |
| Ctrl + Shift + 上下箭 | 上下移动当前行     |
| Alt + Shift + 左右箭  | 上一步下一步跳转   |
| Ctrl + Alt + L        | 格式化代码         |
| Ctrl + Shift + [      | 折叠代码块         |
| Ctrl + Shift + ]      | 展开代码块         |
| Ctrl + Shift + [      | 选择直到代码块开始 |
| Ctrl + Shift + ]      | 选择直到代码块结束 |
| Ctrl + Shift + I      | 快速显示定义       |
| Ctrl + Shift + Enter  | 在下一行插入       |
| Ctrl + Alt + Enter    | 在上一行插入       |
| Ctrl + Delete         | 删除到单词结束     |
| Ctrl + Backspace      | 删除到单词开头     |
| Ctrl + W              | 选中当前代码块     |
| Ctrl + Shift + W      | 取消选中代码块     |
| Ctrl + Z              | 返回上一步         |
| Ctrl + Shift + Z      | 撤销上一步         |
| Ctrl + Shift + V      | 打开剪贴板列表     |
| Shift + F6            | 左侧导航文件重命名 |

---

### 4.VI快捷键：

**命令摸模式下搜索**：`/关键词`
> n下一个，N下一个

PS：想要不高亮显示就/xxx查找一个不存在的即可

**命令摸索下替换**：`:%s/old_str/new_str/g`

**命令摸索跳转**：`G`跳转到最后一行

---

## 1.Web

**未来趋势：分布式无服务的前端架构**：
> <https://juejin.im/post/5cdc3dc2e51d453b6c1d9d3a>

### 1.1.多平台

**逆天点评：目前来说：`Taro`市面上的资料比`MPVue`略多，可能从`填坑躺雷`角度来说`Taro`更成熟**（毕竟早几年出来）`chameleon`正在观察中
> `MPVue`是`Vue`语法，`Taro`是`React`语法，看个人偏爱，这两个都是支持`微信`/`百度`/`支付宝`等多个小程序（一份代码多端运行，包括`H5`）

PS：`Vue`和`React`是前端两大擎天柱，国内`Vue`多点，国外`React`多点（从世界范围看，`React`第一，`Vue`第二
> 微信小程序官方推荐：<https://github.com/Tencent/wepy>

#### 1.1.1.Taro（推荐）

**【推荐】Taro京东开源的多端统一框架**（`小程序`，`H5`，`ReactNative`）
> <https://github.com/LessChina/taro>

```shell
逆天点评：这个之前我有提到过

最近百度小程序也比较火，大有超越微信小程序的趋势，这款也支持百度小程序和支付宝小程序了

前端大一统早就是经常提的，Taro就是这一款开发框架（采用`React`语法标准，支持`JSX`和`TypeScript`）

最重要的是有个强大的后盾~`京东`，而且这款开源的确是京东为数不多的良心之作了，希望不要和360一样，各种开源胎死腹中......

相关链接：
https://taro.aotu.io
https://nervjs.github.io/taro
https://github.com/NervJS/awesome-taro
https://nervjs.github.io/taro/docs/README.html
https://juejin.im/book/5b73a131f265da28065fb1cd

https://nerv.aotu.io
https://nervjs.github.io/docs

京东前端团队：https://aotu.io
https://github.com/NervJS
https://github.com/o2team
```

小程序市场分析：https://baijiahao.baidu.com/s?id=1612578358728437062

#### 1.1.2.MPVue（潜力）

**美团开发的一款基于Vue.JS的小程序开发框架**：
> <https://github.com/LessChina/mpvue>

架构图：

![架构](https://img2018.cnblogs.com/blog/1127869/201905/1127869-20190523112632147-781323848.jpg)

#### 1.1.3.Chameleon（观察中）

滴滴开源的一款多平台开发的利器：`chameleon`
> <https://github.com/lotapp/chameleon>

架构图：

![架构](https://img2018.cnblogs.com/blog/1127869/201905/1127869-20190523110343982-1338328075.png)

头条小程序的案例：
> <https://github.com/lotapp/cml-tt-sets>

#### 1.1.4.Flutter（APP）

**Flutter快速入门demo**：
> <https://github.com/alibaba/flutter-go>

![导图](https://camo.githubusercontent.com/b59e4856a54d720712862c763ac3fade321e9dc9/68747470733a2f2f696d672e616c6963646e2e636f6d2f7466732f5442313955616851517a6f4b31526a535a466c58586169345658612d313530302d313130362e706e67)

PS：可以把它当做`flutter`开发者帮助APP，里面包含`flutter`常用`140+`组件的`demo`演示与中文文档，你可以把它作为使用`Flutter`的示例

### 1.2.xxx

---

## 2.Python

扩展：<https://github.com/lotapp/awesome-python-cn>

### 2.1.调试

### 2.2.Asyncio

扩展：<https://github.com/lotapp/awesome-asyncio-cn>

### 2.3.优化

#### 2.3.1.Numpy

#### 2.3.2.Numba

**Anaconda开源的即时编译器**：
> <https://github.com/lotapp/numba>

添加一个装饰器就可以了（Numba 使用 LLVM 编译器基础结构 将原生 python 代码转换成优化的机器码）

```py
from numba import jit

# 当使用 @jit 时，请确保您的代码有 numba 可以编译的内容，比如包含库（numpy）和它支持函数的计算密集型循环。否则它将不会编译任何东西，并且您的代码将比没有使用 numba 时更慢，因为存在 numba 内部代码检查的额外开销
@jit
def function(x):
    # 循环或数据密集型计算或
    return x
```

![架构](https://camo.githubusercontent.com/d632db38d871baaca8afe8eccc01dcb211a4a037/68747470733a2f2f63646e2d696d616765732d312e6d656469756d2e636f6d2f6d61782f3838302f312a396e36577045586a7544326c42536c58325f705530672e706e67)

PS：案例：<https://github.com/numba/numba-examples>
> <https://github.com/lotapp/gtc2019-numba>

### 2.3.测试

#### 2.3.1.代码检测

##### 1.Sonar

**业内比较常用的是`SonarQube`**：
> <https://www.sonarqube.org/features/multi-languages/>

![图示](https://www.sonarqube.org/index/clean-code.png)

##### 2.Bandit

**Python代码安全漏洞检测工具**：
> <https://github.com/lotapp/bandit>

参考文章：<https://www.freebuf.com/sectool/204995.html>

##### 3.PyType

谷歌开源的**Python代码的静态类型分析器**：
> <https://github.com/lotapp/pytype>

##### 4.Other

监视Python代码的**内存使用情况**的库：
> <https://github.com/lotapp/memory_profiler>

---

## 3.DataBase

### 3.1.SQL

扩展：<https://github.com/lotapp/awesome-mysql-cn>

#### 1.优化

##### 1.1.Soar

**【推荐】`SQL`自动优化和改写的工具**
> <https://github.com/lotapp/soar>

PS：**Web版扩展**：<https://github.com/lotapp/soar-web>

```shell
可以自动优化 MySQL 语法族，并且给出为什么要这样优化的理由。功能特点：

跨平台支持
目前只支持 MySQL 语法族协议的 SQL 优化
支持基于启发式算法的语句优化
支持复杂查询的多列索引优化（UPDATE、INSERT、DELETE、SELECT）

echo "select title from sakila.film" | ./soar 
# Query: 25807E6B94BEA72C
★ ★ ★ ★ ☆ 80分
SELECT
  title
FROM
  sakila. film
##  最外层SELECT未指定WHERE条件
* **Item:**  CLA.001
* **Severity:**  L4
* **Content:**  SELECT语句没有WHERE子句，可能检查比预期更多的行(全表扫描)。对于SELECT COUNT(\*)类型的请求如果不要求精度，建议使用SHOW TABLE STATUS或EXPLAIN替代。
```

拓展文章：

- <https://mp.weixin.qq.com/s/7sj2HnOQsNP_Zf_07C1FFQ>
- <https://mp.weixin.qq.com/s/XJvRjkSab4B5zPdWBOhi1w>

##### 1.2.SQLAdvisor

**【推荐】美团开源的SQL索引优化工具**：
> <https://github.com/LessChina/SQLAdvisor>

```shell
# 1.帮助
sqladvisor --help
Usage:
  sqladvisor [OPTION...] sqladvisor

SQL Advisor Summary

Help Options:
  -?, --help              Show help options

Application Options:
  -f, --defaults-file     sqls file（sql文件）
  -u, --username          username（用户名）
  -p, --password          password（密码）
  -P, --port              port（端口）
  -h, --host              host（ip地址）
  -d, --dbname            database name（数据库名）
  -q, --sqls              sqls（sql语句，以;分隔）
  -v, --verbose           1:output logs 0:output nothing

# 2.命令使用（命令行传参时，参数名与值需要用空格隔开）
sqladvisor -h ip地址 -P 端口 -u 用户名 -p '密码' -d 数据库名 -q "sql语句" -v 1

# 3.配置文件使用
sqladvisor -f sql.cnf  -v 1

cat sql.cnf
[sqladvisor]
username=xx
password=xx
host=xx
port=xx
dbname=xx
sqls=sql1;sql2;sql3....

# 注意
SQL中的子查询、or条件、使用函数的条件 会忽略不处理
命令行传入sql参数时，注意sql中的双引号、反引号等都需要用\转义。建议使用配置文件形式调用
```

架构图：<https://tech.meituan.com/2017/03/09/sqladvisor-pr.html>

![jpg](https://awps-assets.meituan.net/mit-x/blog-images-bundle-2017/2b8b7d7a.jpg)

---

#### 2.抓包

##### 2.1.go-sniffer

**【推荐】抓包截取项目中的数据库请求并解析成相应的语句**：
> <https://github.com/lotapp/go-sniffer>

![demo](https://raw.githubusercontent.com/40t/go-sniffer/master/images/demo.gif)

```shell
该工具通过抓包截取项目中的数据库、redis 请求解析成相应的语句。便于调试，不要修改代码，直接嗅探项目中的数据请求。使用说明如下：
=======================================================================
[使用说明]

    go-sniffer [设备名] [插件名] [插件参数(可选)]

    [例子]
          go-sniffer en0 redis          抓取redis数据包
          go-sniffer en0 mysql -p 3306  抓取mysql数据包,端口3306

    go-sniffer --[命令]
               --help 帮助信息
               --env  环境变量
               --list 插件列表
               --ver  版本信息
               --dev  设备列表
    [例子]
          go-sniffer --list 查看可抓取的协议

=======================================================================
[设备名] : lo0 :   127.0.0.1
[设备名] : en0 : x:x:x:x:x5:x  192.168.1.3
[设备名] : utun2 :   1.1.11.1
=======================================================================
```

---

#### 3.中间件

##### 3.1.MyCat（常用）

**【推荐】常用中间件：`Mycat`**（性能一直是个问题）
> <https://github.com/lotapp/Mycat-Server>

PS：MyCat性能提升版
> <https://github.com/lotapp/Mycat2>

##### 3.1.Sharding-JDBC（常用）

`Sharding-JDBC`之前是当当开源的，后来用的人多了，生态圈完善了之后就贡献给了Apache
> <https://github.com/lotapp/Sharding-JDBC>

![架构](https://static.oschina.net/uploads/space/2018/1112/110017_jW49_2720166.png)

对比图:
![对比](https://img2018.cnblogs.com/blog/1127869/201906/1127869-20190604232453985-20657530.png)

##### 3.2.DBProxy(基于Atlas) or Zebra

**【推荐】美团开源数据库代理**：
> <https://github.com/lotapp/DBProxy>

[点我看手册:](https://github.com/lotapp/DBProxy/blob/master/doc/USER_GUIDE.md)

![管理](https://raw.githubusercontent.com/lotapp/DBProxy/master/doc/img/dbproxy-function.jpg)

PS：3年前我提过一次360开源的`MySQL中间层Atlas`，美团的也是基于它的拓展
> <https://github.com/lotapp/Atlas>

**扩展：美团还有一款Java开发的数据库中间件：`Zebra`**
> <https://github.com/Meituan-Dianping/Zebra>

![架构](https://img2018.cnblogs.com/blog/1127869/201906/1127869-20190604223728848-1693625017.png)

##### 3.3.kingshard（热门）

**【推荐】Go开发的高性能MySQLProxy**：
> <https://github.com/lotapp/kingshard>

架构：

![架构](https://camo.githubusercontent.com/f6498f3e325d1d8cfc8a8b1b3dcc46ab3ee8050a/687474703a2f2f7777342e73696e61696d672e636e2f6c617267652f3665353730356135677731657632367a68796d6c336a3230716f306b306467722e6a7067)

PS：作者录制了讲解的视频：<https://www.imooc.com/learn/1078>

##### 3.4.Gaea（潜力）

**【推荐】小米基于mysql协议开源的数据库中间件，支持分库分表、sql路由、读写分离、连接池等基本特性**：
> <https://github.com/lotapp/Gaea>

自述：分库分表方案兼容了`mycat`和`kingshard`两个项目的路由方式，在设计、实现阶段参照了`mycat`、`kingshard`和`vitess`，并使用`tidb parser`作为内置的`sql parser`
> ![架构](https://raw.githubusercontent.com/lotapp/Gaea/master/docs/assets/architecture.png)

##### 3.5.Other

**DAL是携程框架部开发的数据库访问框架，支持代码生成和水平扩展**：
> <https://github.com/lotapp/dal>

1. Dal的定位是数据库访问层。是以数据访问类（dao）的形式出现。Dal包括生成的dao代码和dal client底层api。Dal底层使用标准的数据库访问协议访问实际的数据库。
2. Dal本身不是数据库，也不实现数据库协议。Dal依赖具体的数据库实现数据访问的工作。
3. Dal主要功能是ORM，sharding等。Dal支持简单的基于单库的事务，但dal不支持分布式事务
4. Dal也不支持数据库同步工作。数据库同步请使用数据库自带或第三方工具

PS：Net和Java用的比较多些

#### 4.binlog

##### 4.1.Canal

**【推荐】阿里巴巴mysql数据库binlog的增量订阅组件**：
> <https://github.com/LessChina/canal>

```shell
Golang：https://github.com/CanalClient/canal-go
NetCore：https://github.com/CanalClient/CanalSharp
```

![架构](https://camo.githubusercontent.com/46c626b4cde399db43b2634a7911a04aecf273a0/687474703a2f2f646c2e69746579652e636f6d2f75706c6f61642f6174746163686d656e742f303038302f333130372f63383762363762612d333934632d333038362d393537372d3964623035626530346339352e6a7067)

基于日志增量订阅&消费支持的业务：

1. 数据库镜像
2. **数据库实时备份**
3. 多级索引 (卖家和买家各自分库索引)
4. search build
5. **业务cache刷新**
6. **价格变化等重要业务消息**

原理相对比较简单：

1. canal模拟mysql slave的交互协议，伪装自己为mysql slave，向mysql master发送dump协议
2. mysql master收到dump请求，开始推送binary log给slave(也就是canal)
3. canal解析binary log对象(原始为byte流)

**PS：支持kafka消息投递 and 支持prometheus监控**

**1.MySQL配置：**

```shell
[mysqld]
log-bin=mysql-bin # 添加这一行就ok
binlog-format=ROW # 选择row模式
server_id=1 # 配置mysql replaction需要定义，不能和canal的slaveId重复
```
canal的原理是模拟自己为mysql slave，所以这里一定需要做为mysql slave的相关权限:（针对已有的账户可直接通过grant）

```sql
CREATE USER canal IDENTIFIED BY 'canal';  
GRANT SELECT, REPLICATION SLAVE, REPLICATION CLIENT ON *.* TO 'canal'@'%';
-- GRANT ALL PRIVILEGES ON *.* TO 'canal'@'%' ;
FLUSH PRIVILEGES;
```

**2.建立与Canal的连接demo：**
![client](https://github.com/CanalClient/CanalSharp/raw/master/assets/668104-20180925182816462-2110152563.png)

```csharp
Install-Package CanalSharp.Client

//canal 配置的 destination，默认为 example
var destination = "example";
//创建一个简单CanalClient连接对象（此对象不支持集群）传入参数分别为 canal地址、端口、destination、用户名、密码
var connector = CanalConnectors.NewSingleConnector("127.0.0.1", 11111, destination, "", "");
//连接 Canal
connector.Connect();
//订阅，同时传入Filter，如果不传则以Canal的Filter为准。Filter是一种过滤规则，通过该规则的表数据变更才会传递过来
connector.Subscribe(".*\\\\..*");
//获取数据但是不需要发送Ack来表示消费成功
connector.Get(batchSize);
//获取数据并且需要发送Ack表示消费成功
// connector.GetWithoutAck(batchSize);
```

**3.测试**：

```sql
insert into test values(1000,'111');
update test set name='222' where id=1000;
delete from test where id=1000;
```

![client](https://github.com/CanalClient/CanalSharp/raw/master/assets/ys.gif)

Kafka接入参考：https://github.com/alibaba/canal/wiki/Canal-Kafka-RocketMQ-QuickStart

---

**阿里巴巴分布式数据库同步系统**：
> <https://github.com/alibaba/otter>

![架构](https://camo.githubusercontent.com/2988fbbc7ddfe94ed027cd71720b1ffa5912a635/687474703a2f2f646c322e69746579652e636f6d2f75706c6f61642f6174746163686d656e742f303038382f313138392f64343230636131342d326438302d336435352d383038312d6239303833363036613830312e6a7067)

原理描述：

1. 基于**Canal**开源产品，获取数据库增量日志数据
2. 基于**zookeeper**，解决分布式状态调度的，允许多node节点之间协同工作.
3. 典型管理系统架构，manager(web管理)+node(工作节点)
    - manager运行时推送同步配置到node节点
    - node节点将同步状态反馈到manager上

PS：**解决异地机房数据同步问题**

#### 5.运维

##### MySQL常用工具包

**MySQL常用工具包**：[percona-toolkit](https://www.percona.com/downloads/percona-toolkit/LATEST/)
> 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/index.html>

列几个常用的：

1. `pt-summary`：查看`服务器信息`
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-summary.html>
2. `pt-diskstats`：查看`磁盘开销`使用信息
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-diskstats.html>
3. `pt-mysql-summary --user=用户名 --password=密码`：查看`mysql`的`信息`
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-mysql-summary.html>
4. `pt-ioprofile`：查看mysql表和文件的`IO开销`
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-ioprofile.html>
5. `pt-show-grants --user=root --password=密码`：**查看mysql`授权`**
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-show-grants.html>
    - PS：通过`--revoke`、`-separate`等,可以撤消用户的特定权限
6. `pt-duplicate-key-checker --host=localhost --user=root --password=密码`：**`查找`数据库表中`重复的索引`**
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-duplicate-key-checker.html>
7. `pt-deadlock-logger --user=root --password=密码 --host=localhost`：**查看mysql`死锁信息`**
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-deadlock-logger.html>
8. `pt-query-digest /var/lib/mysql/localhost-slow.log`：**分析`慢查询日志`**
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-query-digest.html>
9. `pt-index-usage /var/lib/mysql/localhost-slow.log`：**从`慢查询`日志中分析`索引使用情况`**
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-index-usage.html>
10. `pt-config-diff /etc/my.cnf /etc/my_master.cnf`：**`查看`不同mysql`配置文件的差异`**
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-config-diff.html>
11. `pt-online-schema-change --alter "DDL语句" --execute --user=用户名 --password=密码 D=数据库名,t='表名'`：**不加锁的情况下`修改表结构`**（`在线DDL修改工具`）
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-online-schema-change.html>
12. `pt-slave-find --host=localhost --user=root --password=密码`：查找mysql的`从库和同步状态`
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-slave-find.html>
13. `pt-table-checksum --user=root --password=密码`：`验证`数据库`复制的完整性`
    - 官方文档：<https://www.percona.com/doc/percona-toolkit/LATEST/pt-table-checksum.html>

安装附录：

```shell
# Ubuntu：# curl https://www.percona.com/downloads/percona-toolkit/2.2.20/deb/percona-toolkit_2.2.20-1_all.deb > percona-toolkit-2.2.20.deb
# CentOS：# curl https://www.percona.com/downloads/percona-toolkit/2.2.20/RPM/percona-toolkit-2.2.20-1.noarch.rpm > percona-toolkit-2.2.20.noarch.rpm
[dnt@localhost ~]$ curl https://www.percona.com/downloads/percona-toolkit/2.2.20/RPM/percona-toolkit-2.2.20-1.noarch.rpm > percona-toolkit-2.2.20.noarch.rpm
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 1700k  100 1700k    0     0   309k      0  0:00:05  0:00:05 --:--:--  426k

[root@localhost dnt] ls
percona-toolkit-2.2.20.noarch.rpm

# Ubuntu：# sudo apt install ./percona-toolkit-2.2.20.deb -y
# CentOS：# yum install percona-toolkit-2.2.20.noarch.rpm -y
[root@localhost dnt] yum install percona-toolkit-2.2.20.noarch.rpm -y
已加载插件：fastestmirror
正在检查 percona-toolkit-2.2.20.noarch.rpm: percona-toolkit-2.2.20-1.noarch
percona-toolkit-2.2.20.noarch.rpm 将被安装
正在解决依赖关系
--> 正在检查事务
---> 软件包 percona-toolkit.noarch.0.2.2.20-1 将被 安装
--> 解决依赖关系完成

依赖关系解决

========================================================================================================================================
 Package                         架构                   版本                       源                                              大小
========================================================================================================================================
正在安装:
 percona-toolkit                 noarch                 2.2.20-1                   /percona-toolkit-2.2.20.noarch                 5.7 M

事务概要
========================================================================================================================================
安装  1 软件包

总计：5.7 M
安装大小：5.7 M
Downloading packages:
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
  正在安装    : percona-toolkit-2.2.20-1.noarch                                                                                     1/1
  验证中      : percona-toolkit-2.2.20-1.noarch                                                                                     1/1

已安装:
  percona-toolkit.noarch 0:2.2.20-1

完毕！
```

##### SQLServer常用工具包

一般都是使用`RedGate`的工具：[www.red-gate.com](https://www.red-gate.com/products/)
> PS：就是出`NET Reflector`的那家公司

![RedGate](https://img2018.cnblogs.com/blog/1127869/201907/1127869-20190706201412111-1019779719.png)

##### 5.1.慢查询工具

先简单分析下慢查询日志：

```shell
# Time: 2019-05-22T21:16:28.759491+08:00
# User@Host: root[root] @ localhost []  Id:    11
# Query_time: 0.000818  Lock_time: 0.000449 Rows_sent: 5  Rows_examined: 5
SET timestamp=1558530988;
select * from mysql.user order by host; # SQL语句
```

1. `Time`：查询的**执行时间**（`start_time`）
2. `User@Host: root[root] @ localhost []  Id:11`：执行 sql 的**主机信息**
3. `Query_time`：SQL**`查询`**所**耗**的**时**间
4. `Lock_time`：**锁定时间**
5. `Rows_sent`：所**发送的行数**
6. `Rows_examined`：**锁扫描的行数**
7. `SET timestamp=1558530988;`：SQL**执行时间**

现在可以说说工具了，推荐两款：

1.自带的慢日志分析工具：**mysqldumpslow**：
> **查询最慢的10条SQL：`mysqldumpslow -s t -t 10 /var/lib/mysql/localhost-slow.log`**

```shell
-s 按照那种方式排序
    t: 查询时间
    c：访问计数
    l：锁定时间
    r:返回记录
    al：平均锁定时间
    ar：平均访问记录数
    at：平均查询时间
-t 返回多少条数据（可以理解为top n）
-g 可以跟上正则匹配模式，大小写不敏感。
```

PS：使用mysqldumpslow的分析结果不会显示具体完整的sql语句：

1. **翻页sql不一样，性能也是不一样的，越往后的页数越容易出现慢查询，而mysqldumpslow把所有翻页sql当成一个sql了**
2. eg：`select * from tb_table where uid=20 group by createtime limit 10000, 1000;` ==> `select * from tb_table where uid=N group by createtime limit N, N;`
    - 不管你uid和limit怎么变，mysqldumpslow认为是一样的

---

2.`percona-toolkit`中的 **`pt-query-digest`**（[官方文档](https://www.percona.com/doc/percona-toolkit/3.0/pt-query-digest.html)）
> **分析慢查询日志：`pt-query-digest /var/lib/mysql/localhost-slow.log`**

1. 使用tcppdump捕获MySQL协议数据，然后报告最慢的查询：
    - `tcpdump -s 65535 -x -nn -q -tttt -i any -c 1000 port 3306 > mysql.tcp.txt`
    - `pt-query-digest --type tcpdump mysql.tcp.txt`
2. 查看来自远程进程列表上最慢的查询：
    - `pt-query-digest --processlist h=ip`

---

PS：还有一款**`mysqlsla`**我没用过，所以贴个参考文章，感兴趣的同志自己研究下
> <https://www.cnblogs.com/fengchi/p/6187099.html>

#### 6.测试

##### 6.1.SQLer

**【推荐】根据SQL和配置文件生成接口的工具（支持`SQLServer` and `MySQL`）**
> <https://github.com/lotapp/sqler>

SQLer是一个小巧的便携式服务器，使您可以使用SQL查询编写API，以便在任何人点击时执行它，还可以让您定义验证规则，以便您可以验证请求正文/查询参数，以及使用简单的数据转换 javascript语法。 sqler使用nginx样式配置语言（HCL）和jd引擎进行自定义表达式（与传统的 SQL 生成 RESETful API 的工具不同，这个工具允许你自定义一些 API 的前、后处理，Auth 之类的行为）

```json
// 启动命令
sqler -config=path to config file

// 配置示例
adduser {
// 参数校验
    validators {
        user_name_is_empty = "$input.user_name && $input.user_name.trim().length > 0"
        user_email_is_empty = "$input.user_email && $input.user_email.trim(' ').length > 0"
        user_password_is_not_ok = "$input.user_password && $input.user_password.trim(' ').length > 5"
    }

    bind {
        name = "$input.user_name"
        email = "$input.user_email"
        password = "$input.user_password"
    }

    methods = ["POST"]
    // 权限校验
    authorizer = <<JS
        (function(){
            log("use this for debugging")
            token = $input.http_authorization
            response = fetch("http://requestbin.fullcontact.com/zxpjigzx", {
                headers: {
                    "Authorization": token
                }
            })
            if ( response.statusCode != 200 ) {
                return false
            }
            return true
        })()
    JS

    exec = <<SQL
        INSERT INTO users(name, email, password, time) VALUES(:name, :email, :password, UNIX_TIMESTAMP());
        SELECT * FROM users WHERE id = LAST_INSERT_ID();
    SQL
}
```

### 3.2.NoSQL

#### 3.2.1.集群系

##### 1.Codis

**【推荐】基于代理的Redis集群解决方案，支持管道和动态扩展**：
> <https://github.com/LessChina/codis>

架构图：

![架构](https://raw.githubusercontent.com/LessChina/codis/release3.2/doc/pictures/architecture.png)

##### 2.TwemProxy

**memcached和redis的轻量级代理`TwemProxy`**：
> <https://github.com/lotapp/twemproxy>

##### 3.overlord

**【推荐】bilibili开源的memcached和redis的集群解决方案**：
> <https://github.com/lotapp/overlord>

PS：基于mesos和etcd提供的自动化缓存节点管理平台

架构图：

![架构](https://raw.githubusercontent.com/lotapp/overlord/master/doc/images/cache-platform-arch.png)

##### 扩展

**如果不想要集群，只是扩充单机能力，那么就可以考虑`Pika`**
> PS：最好只当一个过渡使用，根据经验：**360的开源维护一般都不超过2年**

**Pika是与redis兼容的nosql**（主要解决redis由于存储数据量巨大而导致内存不够用的容量瓶颈）
> <https://github.com/lotapp/pika>

PS：可以用在twemproxy或者codis中来实现静态数据分片

#### 3.2.2.私有云

**搜狐开源的Redis私有云平台**：
> <https://github.com/lotapp/cachecloud>

![架构](https://camo.githubusercontent.com/debf929f0dcbc94fdb20258754f417322ccbc8b4/687474703a2f2f69302e6974632e636e2f32303137303632342f333038345f37353366613731315f346431645f376635315f373430355f3037373233633165343366365f312e706e67)

官方很细心提供了入门视频：<http://pan.baidu.com/s/1c2mET5e>

### 3.3.多功能工具

**360开源一款多数据源SQL分析引擎:`QuickSQL`**
> <https://github.com/lotapp/Quicksql>

![架构图](https://github.com/lotapp/Quicksql/raw/master/doc/picture/p1.png)

**SQL数据库的通用命令行界面**（支持TiDB、Cassandra、MySQL、MSSQL、Sqlite等）
> <https://github.com/lotapp/usql>

PS：搭建在线IDE的时候可以使用

---

## 4.Spark

**基于`SparkSQL`的即席查询服务**
> <https://github.com/lotapp/IQL>

**PS：即席查询：`根据自己的需求,灵活的选择查询条件,系统能够根据用户的选择生成相应的统计报表`**

基于SparkSQL实现了一套即席查询服务，具有如下特性：

- 优雅的交互方式，支持多种datasource/sink，多数据源混算
- spark常驻服务，基于zookeeper的引擎自动发现
- 负载均衡，多个引擎随机执行
- 多session模式实现并行查询
- 采用spark的FAIR调度，避免资源被大任务独占
- 基于spark的动态资源分配，在无任务的情况下不会占用executor资源
- 支持Cluster和Client模式启动
- 基于Structured Streaming实现SQL动态添加流
- 类似SparkShell交互式数据分析功能
- 高效的script管理，配合import/include语法完成各script的关联
- 对数据源操作的权限验证

支持的数据源：hdfs、hive、hbase、kafka、mysql、es、solr、mongo

支持的文件格式：parquet、csv、orc、json、text、xml
![](https://camo.githubusercontent.com/27226ae882866c454d60824c37abe23f1458880a/68747470733a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333539373036362d653139636465663530376664373761372e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430)

---

## 5.Architecuture

### 5.1.常用算法

#### 5.1.1.分布式ID

**【推荐】美团开源分布式ID解决方案**：
> <https://github.com/lotapp/Leaf>

架构图：

![架构图](https://p1.meituan.net/travelcube/210ca1564c70b228ed46f3b33c9bb9b161120.png)

参考文章：

1. [Leaf——美团点评分布式ID生成系统](https://tech.meituan.com/2017/04/21/mt-leaf.html)
2. [Leaf：美团分布式ID生成服务开源](https://tech.meituan.com/2019/03/07/open-source-project-leaf.html)

PS：扩展 ~ `Snowflake算法`

![核心](https://awps-assets.meituan.net/mit-x/blog-images-bundle-2017/eee18df9.png)

#### 5.1.2.布隆过滤


---

## 6.System
