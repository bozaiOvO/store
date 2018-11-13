# git 
git和github不一样！！！
git是分布是版本控制工具，能够与gitHub配合达到管理代码与版本，拥有推送，更新，克隆，回退的作用。

## 推送到github
+ git add xxx文件
+ git commit -m '你的备注'
+ git push (推入到git)

## 更新
+ git pull 

## git新项目
+ 从github上复制相应代码。

## 从github或者gitEE克隆
+ git clone xxxxx 

## git初始化
+ git init 

## 检测git状态
+ git status

## 滚回某版本
+ git reset --hard HEAD^         回退到上个版本
+ git reset --hard HEAD~x        回退到前x次提交之前，以此类推，回退到n次提交之前
------

## git回滚到任意版本
+ git log  打印出来所有版本
+ git reset --hard sha码      退到/进到 指定commit的sha码 

## 从过去穿越到现在（命令行未关闭）
+ 复制那个sha码
+ git reset --hard sha码

## 设置身份和邮箱

+ 目的是为了辨别哪一个身份（自己或者某一个同事在哪个电脑）上传的git。

### 还有就是和github绑定，github如何知道你有这个权限上传到某仓库呢？
+ 1、每一次都输入github账户密码，以验证你的权限（相当麻烦）
+ 2、绑定SSH，这样就可以让github知道你这个电脑拥有上传这个github的权限。