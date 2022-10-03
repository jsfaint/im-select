# im-select

使用[aardio](https://aardio.com/)开发的[im-select](https://github.com/daipeihust/im-select)克隆版，仅支持windows系统。

原始的`im-select`在win10下使用需要添加多语言，即需要同时有英文与中文，通过win+space切换切换语言。
个人还是更习惯从win95时代就在使用的ctrl+space，win10也支持设置快捷键使用ctrl+space来切换输入法中英文状态，所以就有了这个版本。

可搭配[Visual Studio Code](https://code.visualstudio.com/) vim扩展使用，微软拼音以及搜狗输入法均可工作。

## 使用方法

```batch
REM 获取输入法状态，英文返回en，中文返回zh
im-select.exe

REM 设置输入法为英文
im-select.exe en

REM 设置输入法为中文
im-select.exe zh
```
