# 2026.9.7
## TodoList
- [x] github 使用教程
- [x] git 使用教程
- [ ] python 使用教程
- [x] 复习 Markdown语法

# Git笔记

1. ### 版本控制    
   > 什么是版本控制
   ==本质是版本迭代==
   - 统计控制量
   - 管理多人项目    
    > 常见版本控制
    ==Git SYN CVS==
    -  SYN 中央集群 
    -  Git 分布式
    > 区别

2. ### 基本Linux命令
   - cd 切换
   - cd.. 切换上一个目录
   - pwd 显示当前目录
   - clear 清屏
   - ls 列出显示
   - touch 创建
   - rm 删除文件
   - mkdir 创建文件夹
   - rm -r 删除目录
   - mv 移动
   - history 查看历史命令
  
3. ### git配置
   
   已配置完成

4. ### 基本知识
    > 工作区域
    - 工作目录
    - 暂存区
    - 资源库
    
5. ### 项目搭建（实操
   - add 
   - commit 
   - push
   - pull
   - checkout
   - clone\fetch
    > 本地库搭建

    选择文件夹 
    1. git init (自建)
    2. git clone [url] （克隆其他人的东西）
   > git 文件操作
    - git status 产看文件状态
    - git add . 添加文件到暂存区
    - git commit -m "注释"
    - git push 远程
   > 忽略文件
   在主文件目录创建 .gitignore
    ```
    * .tet 忽略所有此文件名
    ! .lin 但这个除外
    /temp  #仅忽略项目根目录下的TODO文件，不包括其他目录temp
    bash/ 向下忽略

    ```

6. ### 码云使用
   ssh 免密码登录
   ssh-keygen -t rsa 本地生成ssh

7. ### 实操体验
   1. 创建远程库
   2. 创建本地库
   3. 修改文件查看不同
      > `git diff read.txt`  
   4. 版本回退
      > `git log` 查看日志
      > `git log –pretty=oneline` 更加整洁
      > `git reset --hard HEAD^\(版本号)` 回退版本
      > `git reflog` 查看版本号
      