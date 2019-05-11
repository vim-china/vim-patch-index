# Vim 补丁归类
> 将 Vim 补丁根据其功能进行归类，方便插件开发者快速定位所需 Vim 版本。


<!-- vim-markdown-toc GFM -->

- [标签](#标签)
  - [job](#job)
  - [terminal](#terminal)
  - [autocmd](#autocmd)
  - [resolve()](#resolve)
- [TODO](#todo)

<!-- vim-markdown-toc -->

## 标签

### job

- 7.4.1274: 首次在 Unix 系统下引入 `job_start()`, `job_status()` 和 `job_stop()`

### terminal

- 8.0.0693: 引入 `:terminal` 命令

### autocmd

- 8.0.1206: 引入`CmdlineEnter` 和 `CmdlineLeave`
- 7.4.2077: 引入`TabClosed`


### resolve()

- 8.1.0894: 修复 Windows 系统下 resolve() 无法返回链接所指向的路径


## TODO

- channel
- timers
