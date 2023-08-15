# 目录
## DAY1
~~怎么链接过去~~
## DAY2
## DAY3

***
# DAY1
```MYLOVE_LANGUAGE
√	AI的考核 
√	GIT学习和使用
×	洗澡
√	考古车CAN通讯&测试
√	CMAKE构建程序&CMakeLists.txt语法
```



``` linux
$ git add file
$ git commit -m "anything"
$ git log
$ git status
$ git checkout -- file
$ git remote add origin git@github.com:michaelliao/learngit.git //示例
$ git push -u origin master
```

[GIT指令大全.pdf](./git-cheat-sheet.pdf) Or [GIT指令大全.html](https://liaoxuefeng.gitee.io/resource.liaoxuefeng.com/git/git-cheat-sheet.pdf)

***

# DAY2
> TourGroup_Help编译不过去哇哇哇:disappointed_relieved:protoc到底在哪里:rage:
> 
> 使用一点表情，调解一下情绪:relaxed:
> 
> [Click here for more emoji.](https://github.com/zhouie/markdown-emoji)
```linux
ifconfig		 #先查查IP地址，下同
ip add 
ssh user@hostname #玩树莓派的好东西
- - - - - - - - - - 
```
```
#补个CMake 
CMakeLists.txt 						#自己构建时不可打错唷
cmake_minimum_required(VERSION 3.0.0) #指定使用的 cmake 的最低版本
```
```
#PROJECT 指令的语法是：
project(<PROJECT-NAME> [<language-name>...])
project(<PROJECT-NAME>
       [VERSION <major>[.<minor>[.<patch>[.<tweak>]]]]
       [DESCRIPTION <project-description-string>]
       [HOMEPAGE_URL <url-string>]
       [LANGUAGES <language-name>...])
```
```
add_executable(可执行程序名 源文件名称) 		   #指定生成的可执行文件名
camke ..									 #..一般是build目录中使用，通用情况时camke （path where include CMakeLists.txt ）
SET(VAR [VALUE] [CACHE TYPE DOCSTRING [FORCE]])	# [] 中的参数为可选项, 如不需要可以不写 VAR：变量名 VALUE：变量值 多是配合宏用来指定目录的
set(CMAKE_CXX_STANDARD 11)					  # 指定c++标准
```
```
EXECUTABLE_OUTPUT_PATH					   #指定可执行程序输出的路径叫做EXECUTABLE_OUTPUT_PATH，它的值通过set命令进行设置
aux_source_directory(< dir > < variable >)	#查找某个路径下的所有源文件 dir：要搜索的目录 variable：将从dir目录下搜索到的源文件列表存储到该变量中
PROJECT_SOURCE_DIR						  #宏 

。。。有空再补。。。
```
# DAY3


>前面的世界以后再来探索吧 . . . 


![](./strange.jpg)