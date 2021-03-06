
# 工作

## 2018/12/12

- main

  - [x] 申请服务器(OirCA84ZLx7PJdcX5++1+sg00sCcHV7ozAz)，查看文档格式

- Jmeter

  - [x] 明确**如何获得粗细粒度的统计值**
  - [x] 弄清楚结果观察树 => 聚集报告 的映射过程
  - [x] 使用pandas进行`.jtl .csv`文件的处理
  - [ ] ~~查看正则表达式提取到的数据如何存储到文件~~

- 模块耗时

  - [x] 确认**需要升级的文件 && 是否需要重构代码**
  - [x] 重构代码
  - [x] 检查代码

## 2018/12/13
- main

	- [x] 申请服务器(OirCA84ZLx7PJdcX5++1+sg00sCcHV7ozAz)，再测试代码
	- [x] 发压机器与被测机器同步
		1. 在被测试机器上开启一个deamon进程，发压机器在开始、结束发压前后发送信号，被测机器根据收到的信息进行对应操作
	- [x] 查看jmeter源码，弄清楚聚合报告统计细节

## 2018/12/17
- main
	- [x] 写完同步的wiki
	- [x] 明确fisher代码中我需要着重练了解的内容
		- 可能会需要base代码
	- [x] 明确jmeter输出文件内容格式
	- [x] 修改`jmeter_report.py`文件,存储需要输出的内容
	- [ ] 再测模块耗时脚本 
## 2018/12/18
- main
	- [x] 开始写从redis获得数据并修改的代码
	- [ ] 看fisher的代码
	- [x] 看*Grammars_and_parsing_with_Standard_ML*
	- [ ] 看书
## 2018/12/19
- main
	- [x] 明确redis中频次字段读取后以何种方式存储（加密|非加密|解析|可读） 
	- [ ] 后续任务
	- [x] 周报
	- [ ] 开始将ADDL的变种BNF范式改编为BNF范式
		- [ ] 了解SML-yacc使用

## 2018/12/20
- main
  - [x] 测试读写redis的代码
  - [ ] 查询开题答辩相关事宜
  - [x] 看书
  - [x] 写一下周记
  - [x] 做3题leetcode
  - [ ] 开始将ADDL的变种BNF范式改编为BNF范式
    - [x] 了解SML-yacc使用
    - [ ] 了解SML-lex使用

## 2018/12/21
- main
	- [x] 做3题leetcode
	- [x] 开始写开题报告
	- [ ] 了解Python多线程/进程
	- [ ] 开始将ADDL的变种BNF范式改编为BNF范式
    	- [x] 了解SML-yacc使用
    	- [ ] 了解SML-lex使用
## 2018/12/25
- main
	- [x] 做三题leetcode
	- [x] 看看开题答辩PPT什么样子
	- [ ] 编写完成自动化测试的脚本
		- [x] 获得数据库访问权限
		- [x] 规定ssh公钥的存储路径
		- [x] 修改模块耗时脚本的存储逻辑
		- [x] 完成机器性能的参数统计 
	- [ ] 搭建一个Danjgo服务，并和数据库结合

## 2018/12/27
- mian
	- [x] 做三题leetcode
	- [x] 完成email内容的format
	- [ ] 服务器上测试部分功能
		- [ ] 机器性能是否能采集
		- [ ] 模块耗时是否能统计
		- [ ] jmter结果是否能分析
	- [x] 再看*go http auth* || 看一份新的服务器代码（C/C++ or Go）
- misc
- [ ] 可能的话用Xmind从各个维度上总结一下2018年
- [x] 买火车票
- [ ] 思考 **开发、读博、今年暑假的规划（实习 or 跟老师）**
## 2018/12/28
- main
	- [x] 做三题leetcode
	- [ ]  ~~尝试服务器不能使用paramiko包的解决方案~~
		- 直接使用ssh命令 存在的问题(我为什么抵触这样的做法)
			1. 如果想在后台运行, 则看不到错误输出
			2. 没有可靠的文件传输方案
		- 寻找新的开源工具
	- [x] 测试util.py脚本
	- [ ] 测试数据存储提取,email格式是否正确
	- [x] 再看Go相关的项目代码
- misc
	- [ ] 总结一下2018
	- [ ] 找一个现实一点的目标
	- [ ] 工作, 亲人, 房子, 婚姻都要纳入考虑范围之内了 
## 2018/12/29
- main	
	- [x] 思考用面向对象的思想去实现自动化测试平台
	- [x] 编写相关代码
	- [x] 做3题leetcode
	- [ ] 好好休息
	- [ ] 写周记了该

## 2019/1/4
- main
	- [x] 测试自动化测试脚本
	- [ ] 写周记
	- [ ] 看 *现代操作系统* ，准备给yz讲内存管理历史和Linux 和 Windows区别
	- [x] 修改Emacs配置，改字体

## 2019/1/7
- main
   - [x] 测试自动化测试脚本
     - [x] 编写配置迁移脚本
    - [ ] 看*设计模式* 
    - [x] 看*SML-Lex*的使用
    - [x] 做3题leetcode
    - [ ] 看一看**fisher**中关于缓存的设计
    - [ ] 8点回去看*剑桥学习科学手册*
- ps
- 看了 *Linux Programming Interface*

## 2019/1/8
- main
	- [x] 把自动化测试的边脚料弄完
		- [x] `remote_run`为`True‵的加入`rsync`命令，实现同步
		- [x] 邮件格式弄弄
	- [x] 做3题leetcode
	- [x] 看一看*SML-lex SML-yacc*的用法
	- [ ] 看看*设计模式*
	- [ ] 根据C/C++面经整理需要的知识
	- [x] 回去看 *剑桥学习科学手册*
	- [x] 中午吃完饭睡觉
- ps
	- 看了 *Linux Programing Interface*
	- 看了有关*redis*、*select poll epoll*的知识

## 2019/1/9
- main
  - [x] 问奔月要远程机的代码，编写代码并测试
    - [x] 
    - [x] 测试
  - [x] 做3题leetcode
  - [x] 看*Linux Programing Interface*
    - [x] 看有关IO复用的内容 
  - [ ] 看*Redis源码* or *Nginx源码*
  - [ ] 看*select poll epoll源码* 
  - [x] 中午吃饭立马睡觉
  - [ ] 根据C/C++面经整理需要的知识  
- ps
	- 决定转后台了
	- 从Go开始，和卓一起学习
## 2019/1/10
- main
	- [x] 做5题leetcode
	- [x] 把前端需要的数据处理过程带代码协议部分
	- [ ] 调研Go语言写的开源软件现状
	- [ ] 试着使用一下Go的并发机制
	- [ ] 看*redis源码*
	- [ ] 看*Linux Programing Interface*
- ps
    - TODO List 不能早上写了晚上就不不看了啊

## 2019/1/11
- main
  - [x] 做3题leetcode
  - [ ] 理解抽象层次、封装，然后修改代码
  - [ ] 学习`zver`这个**http sever**
  - [ ] 看`redis 源码`
  - [x] 看 *Linux Programing Interface*
  - [x] 看动漫电影[22:10的场，得8:30离开]

## 2018/1/14
- main
  - [x] 做3题leetcode
  - [x] 解决`markdown`渲染问题
  - [x] 使用**Xmind**将**http server**的构成分解
  - [ ] 把后端的相关代码写好
  - [x] 看书
  - [x] 中午先休息

## 2018/1/15
- main
  - [x] 做3题leetcode
  - [x] 决定用什么框架画表格
  - [ ] 思考相关的数据展示

## 2019/1/16
- main
  - [ ] do leetcode
  - [ ] choose the CSS framework to show
  - [x] hacking http server

## 2019/1/17
- main
 - [x] do leetcode
 - [ ] fix the details of the come up with by benyue
 - [x] fix the redis write/read bugs
 - [x] hacking http sever
 - [x] sleep after lunch
 - [ ] read book



## 2019/1/18
- main
 - [ ] do leetcode
 - [x] fix the details of the come up with by benyue
 - [x] hacking *QG-Server*
 - [x] sleep after lunch
 - [x] watch movie (must leave office before 8:30)

## 2019/1/21
- main
  - [x] 做leetcode
  - [x] 困了睡觉
  - [ ] 把信寄了(如果上午回了)
  - [x] 将代码整合到那个框架，并开始新的前端页面图
  - [x] Hack **QG-Server**，似乎要将`HttpData`改为`RequestData`
  - [x] 暂时用`Logger`来做日志系统
  - [ ] 将昨天关于*方法*的思考更进一步，准备整理成博客


## 2019/1/22
- main 
  - [x] 做leetcode
  - [x] 困了睡觉
  - [ ] 开始新的前端界面
  - [x] 测试**QG-Server**的**RequestParser**
  - [ ] 学习一下**CMake**
  - [ ] 学习一下**编译、汇编、链接过程**


## 2019/1/23
- main
  - [ ] do leetcode
  - [x] applicate the web UI framework
  - [x] implement the modify `jmx` function
  - [x] hack **QG-Server**
  - [x] sleep when asleep
  
## 2019/1/24
- main
  - [ ] 做3题leetcode
  - [x] 完成前端页面的迁移
  - [x] hack **QG-Server**
    - [x] 把**Reactor**模式写了
  - [x] 困了睡觉
- ps
  - 似乎发现了*The Linux Programing Interface*的一个错误`List63-4`
    - 后来发现勘误表里面已经有了

## 2019/1/25
- main
  - [ ] 做3题leetcode
  - [x] 把*diff、日期曲线*相关`js python`代码写了
  - [x] hack **QG-Server**
  - [x] 困了睡觉
  - [x] 8点下班看电影
  - [x] 看书

## 2019/1/28
- main
  - [x] 做leetcode
  - [x] 看关于**工厂**的设计模式
    - [ ] ~~看看能否以**工厂模式**重写代码~~
  - [x] 把关于*日期曲线*的代码写了
  - [x] hack **QG-Server**，把Reactor模式代码想好再写
  - [x] 困了睡觉
  - [x] 看书*禅的初心*，*The Linux Programing Interface*

## 2019/1/29
- main
  - [ ] 做leetcode
  - [ ] 完善**QG-Server**中**Reactor**的实现
  - [x] 把*随日期变化的曲线*逻辑写完，前端添加*日期选择*
  - [x] 困了睡觉
  - [ ] 看*Linux Programing Interface*
  - [ ] 看一下**Liya**大佬的面试资料总结
- ps
  - 昨天团建，基本啥事没干

## 2019/1/30

- main
  - [x] 做leetcode
  - [x] 把mentor昨天题的问题改好
  - [ ] 修复`redis write`的bug
  - [x] 困了睡觉
  - [x] 看*Linux Programing Interface*，迅速过完*File IO*，开启*Process*
  - [x] Hack **QG-Server**
  - [ ] 再看一看`redis`的**Reactor**实现

## 2019/1/31

- main
  - [x] 做3题leetcode
  - [x] 完善前端页面展示
  - [x] 修复`redis write`的bug
  - [x] 困了睡觉
  - [x] 开始尝试使用`org-agenda`来管理*TODO-List*
  - [ ] Hack **QG-Server**，寻找合适的**LogSystem**实现
  - [x] 看*Linux Programing Interface*，不要在意类似于*User/Group, Time*之类的内容

## 2019/2/1
- main
  - [ ] 做3题leetcode
  - [ ] 困了睡觉
  - [ ] 把总结写了
  - [ ] 看一看wiki上的详设
  - [ ] 看*Linux Programing Interface*
  - [ ] hack **QG-Server**


