## git 命令行

### 概念

本地版本管理
中心版本管理（cvcs）
分布式版本管理（dvcs）

#### 整体配置

git config --system //系统配置
git config --global //用户全局配置
git config --local //单个项目配置
git config --list //查看项目配置列表

#### 新建仓库

git init //初始化仓库
git clone <repos> //克隆现有仓库
git add <file/folder> //添文件目录
git status <-s/--short> //状态预览

#### .gitignore 文件

[各种语言的.gitignore模版](https://github.com/github/gitignore)


#### 文件对比
git diff <--staged> // 只显示未暂存的变动 : --staged/--cached对比暂存区与最后一次提交的变化。
