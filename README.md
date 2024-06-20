# 💤 LazyVim Configure

---

# Install
#### 要求
```
Lua >=5.0
```
#### PowerShell
```
# required
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak

# optional but recommended
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
```
```
git clone https://github.com/LazyVim/starter $env:LOCALAPPDATA\nvim
```
```
Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force
```
```
nvim!
```

# configure
#### 配置清单
