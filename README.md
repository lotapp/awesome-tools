# 逆天开发辅助工具

**防止失效，我都Fork一份到自己的github中，并完善了部分文档**（过时请Issue下）
> `看文档`：我的Github；`看源码`：原地址

PS：其实很多工具我以前曾经提过：**[大公司都有哪些开源项目~~~阿里，百度，腾讯，360，新浪，网易，小米等](https://www.cnblogs.com/dunitian/p/5581520.html)**

- [逆天开发辅助工具](#%E9%80%86%E5%A4%A9%E5%BC%80%E5%8F%91%E8%BE%85%E5%8A%A9%E5%B7%A5%E5%85%B7)
    - [IDE](#ide)
        - [1.VSCode推荐插件](#1vscode%E6%8E%A8%E8%8D%90%E6%8F%92%E4%BB%B6)
            - [1.1.Public](#11public)
            - [1.2.Python](#12python)
            - [1.3.JavaScript](#13javascript)
            - [1.4.DataBase](#14database)
            - [1.5.xxx](#15xxx)
            - [1.6.NetCore](#16netcore)
            - [other](#other)
        - [2.NoteBook快捷键](#2notebook%E5%BF%AB%E6%8D%B7%E9%94%AE)
            - [2.1.编辑模式快捷键](#21%E7%BC%96%E8%BE%91%E6%A8%A1%E5%BC%8F%E5%BF%AB%E6%8D%B7%E9%94%AE)
            - [2.2.命令模式快捷键](#22%E5%91%BD%E4%BB%A4%E6%A8%A1%E5%BC%8F%E5%BF%AB%E6%8D%B7%E9%94%AE)
            - [2.3.设置系列](#23%E8%AE%BE%E7%BD%AE%E7%B3%BB%E5%88%97)
        - [3.JetBrains系列快捷键](#3jetbrains%E7%B3%BB%E5%88%97%E5%BF%AB%E6%8D%B7%E9%94%AE)
        - [4.VI快捷键：](#4vi%E5%BF%AB%E6%8D%B7%E9%94%AE)
    - [1.Web](#1web)
    - [2.Python](#2python)
        - [2.1.调试](#21%E8%B0%83%E8%AF%95)
        - [2.2.Asyncio](#22asyncio)
        - [2.3.todo](#23todo)
    - [3.DataBase](#3database)
        - [3.1.SQL](#31sql)
            - [1.优化](#1%E4%BC%98%E5%8C%96)
                - [1.1.Soar](#11soar)
                - [1.2.SQLAdvisor](#12sqladvisor)
            - [2.抓包](#2%E6%8A%93%E5%8C%85)
                - [2.1.go-sniffer](#21go-sniffer)
            - [3.代理](#3%E4%BB%A3%E7%90%86)
            - [测试](#%E6%B5%8B%E8%AF%95)
                - [SQLer](#sqler)
        - [3.2.NoSQL](#32nosql)
        - [3.3.多功能工具](#33%E5%A4%9A%E5%8A%9F%E8%83%BD%E5%B7%A5%E5%85%B7)
    - [4.Spark](#4spark)
    - [5.Architecuture](#5architecuture)
        - [5.1.常用算法](#51%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95)
            - [5.1.1.分布式ID](#511%E5%88%86%E5%B8%83%E5%BC%8Fid)
            - [5.1.2.布隆过滤](#512%E5%B8%83%E9%9A%86%E8%BF%87%E6%BB%A4)
    - [6.System](#6system)

## IDE

### 1.VSCode推荐插件

#### 1.1.Public

1. Markdown：**`Markdown All in One`**
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

## 2.Python

扩展：<https://github.com/lotapp/awesome-python-cn>

### 2.1.调试

### 2.2.Asyncio

扩展：<https://github.com/lotapp/awesome-asyncio-cn>

### 2.3.todo

## 3.DataBase

### 3.1.SQL

扩展：<https://github.com/lotapp/awesome-mysql-cn>

**MySQL常用工具包**：
> <https://www.percona.com/doc/percona-toolkit/3.0/index.html>

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

#### 3.代理



#### 测试

##### SQLer

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

### 3.3.多功能工具

**360开源一款多数据源SQL分析引擎:`Quicksql`**
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

#### 5.1.2.布隆过滤


---

## 6.System
