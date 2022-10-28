# im-select

使用[aardio](https://aardio.com/)开发的[im-select](https://github.com/daipeihust/im-select)克隆版，仅支持windows系统。

原始的`im-select`在win10下使用需要添加多语言，即需要同时有英文与中文，通过`win+space`切换切换语言。
个人还是更习惯从win95时代就在使用的`ctrl+space`，win10也支持设置快捷键使用`ctrl+space`来切换输入法中英文状态，所以就有了这个克隆版。

**支持的输入法（已测试）：**
1. 微软拼音
2. 搜狗输入法

**在以下场景中测试通过：**
1. [Visual Studio Code](https://code.visualstudio.com/) + vim扩展
2. Vim/Neovim in [WSL](https://learn.microsoft.com/en-us/windows/wsl/about)
3. [Obsidian](https://obsidian.md) + [Obsidian Vim IM Select Plugin](https://github.com/ALONELUR/vim-im-select-obsidian)

## 使用方法

```batch
REM 获取输入法状态，英文返回en，中文返回zh
im-select.exe

REM 设置输入法为英文
im-select.exe en

REM 设置输入法为中文
im-select.exe zh
```
