# 设置Git代理
## 走HTTP(首选)
git config --global http.proxy "http://127.0.0.1:7890"

git config --global https.proxy "https://127.0.0.1:7890"

## 走SOCKS(备选)
git config--global http.proxy "socks5://127.0.0.1:7890"

git config--global https.proxy "socks5://127.0.0.1:7890"

## 设置用户
git config --global user.name windlaugh-me

git config --global user.email 1874134696@qq.com

## 查看设置（^+z退出）
git config --list

## 取消设置
git config --global --unsethttp.proxy

git config --global --unsethttps.proxy

# git设置public
找到仓库，点击settings,拉到最下面，找到change visibility修改

# vscode中git使用
## 初始化存储库
![](![](2022-06-06-16-42-30.png).png)
## 调出源代码管理库
![](![](2022-06-06-16-43-29.png).png)
## 推到github
![](![](2022-06-06-16-44-35.png).png)