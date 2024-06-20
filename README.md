# 💤 LazyVim Configure

---
![Uploading image.png…]()
---

# Install
#### 要求:
```
Lua >=5.0
Neovim >= 0.9.0
Git >= 2.19.0
```
#### 使用PowerShell安装Lazyvim
##### 备份您当前的 Neovim 文件:
```
# required
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak

# optional but recommended
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
```
##### 克隆启动器
```
git clone https://github.com/LazyVim/starter $env:LOCALAPPDATA\nvim
```
##### 删除 .git 文件夹，以便稍后将其添加到自己的存储库
```
Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force
```
##### 启动nvim！
```
nvim!
```
##### 详细->[LazyVim](https://www.lazyvim.org/)

# configure
#### 配置清单

## Coding

