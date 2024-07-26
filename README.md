## 梯子

[fenghost](https://www.fenghost.net/) 用了很多年，价格公道，速度可以

软件方面之前[总结](https://github.com/riskers/blog/issues/38)过，现在使用的是 clashX

## IDE

* VSCode: 写前端的时候使用
* IDEA CE: 写 Java 时使用，社区版足够了
* Gioland: 付费了

## Mac 软件

### 命令行

* [iTerm2](https://iterm2.com/) + [ZSH](https://www.zsh.org/) + [oh my osh](https://ohmyz.sh/) 的组合，启用的插件有:

  * dotenv
  * git
  * macos
  * docker
  * autojump
  * zsh-autosuggestions

  [主题](https://www.slant.co/topics/7553/~theme-for-oh-my-zsh)

* [homebrew](https://brew.sh/) 安装
  * [autojump](https://github.com/wting/autojump): 更容易地跳转到某个路径，节省大量时间
  * [tldr](https://tldr.sh/): better `man`
  * [cheat.sh](https://github.com/chubin/cheat.sh): better `man`
  * [httpie](https://httpie.io/): better `curl`
  * [prettyping](https://github.com/denilsonsa/prettyping): better `ping`
  * [bat](https://github.com/sharkdp/bat): better `cat`
  * [fd](https://github.com/sharkdp/fd): better `find`
  * [fzf](https://github.com/junegunn/fzf): better `ctrl + f`
  * [bottom](https://github.com/ClementTsang/bottom): better `top`
  * ~[exa](https://github.com/ogham/exa): better ls~
  * [eza](https://github.com/eza-community/eza) better ls
  * [tig](https://github.com/jonas/tig): git 扩展
  * [procs](https://github.com/dalance/procs): better `ps`
  * [gib](https://github.com/DavSanchez/gib): 生成 .gitignore 文件
  * [mecert](https://github.com/FiloSottile/mkcert): 生成自签名证书
  * kubectl / helm

  > 完整见 [Brewfile](./Brewfile)，通过 `brew bundle dump --describe` 生成，换设备的话，执行 `brew bundle install` 就会安装 Brewfile 里所有的软件。

* [tmux](https://github.com/tmux/tmux) - [配置](https://gist.github.com/riskers/4cf70b3de35906d0df7009ecbfeba3a7)

### 效率软件

* [RIME](https://rime.im/): 速度很快的输入法，本地安装不联网 - [配置](https://gist.github.com/riskers/9bd441f0483325ef991f2b40da7d2eed)
* [SwitchKey](https://github.com/itsuhane/SwitchKey): 快速切换输入法
* [Alfred](https://www.alfredapp.com/): 快速启动应用、粘贴版管理、Snippets 用得最多
* [Thor](https://github.com/gbammc/Thor): 一键启动软件
* [Bob](https://github.com/ripperhe/Bob): 翻译软件，可以自由选择翻译源，还可以截图翻译
* [airBuddy](https://v2.airbuddy.app/): 可以快速在多个 Mac 设备切换蓝牙设备
* [MaxSnap](https://noteifyapp.com/maxsnap-mac-window-manager/): 快速移动窗口、改变窗口大小
* [超级右键](https://apps.apple.com/cn/app/%E8%B6%85%E7%BA%A7%E5%8F%B3%E9%94%AE-irightmouse/id1497428978?mt=12): 丰富 Mac 右键
* [Dash](https://kapeli.com/dash): API 查询，付费了
* [thunderbird](https://www.thunderbird.net/en-US/): 邮箱客户端，好用，免费

### 开发工具

* [sublimemerge](https://www.sublimemerge.com/): [sourceTree](https://www.sourcetreeapp.com/) 的 resolve conflict 需要第三方软件，已替换为 sublimemerge
* [postman](https://www.postman.com/)
* 抓包
  * [Charles](https://www.charlesproxy.com/)
  * [Proxyman](https://proxyman.io/)
  * [whistle](https://github.com/avwo/whistle): 可以作为 Charles 的替代 [介绍](https://github.com/kaiye/kaiye.github.com/issues/27) [介绍](https://zhuanlan.zhihu.com/p/79037633)
* 内网穿透
  * [VSCode port forwarding](https://code.visualstudio.com/docs/editor/port-forwarding)
  * [ngrok](https://ngrok.com/): 内网穿透软件
  * [bore](https://github.com/ekzhang/bore): 另一款内网穿透软件
* [SwitchHosts](https://github.com/oldj/SwitchHosts): 快速切换 Hosts 的工具
* [dbeaver](https://dbeaver.com/): 免费的数据库 GUI 软件
* [robo 3T](https://robomongo.org/): MongoDB GUI 软件
* [AnotherRedisDesktopManager](https://github.com/qishibo/AnotherRedisDesktopManager): Redis GUI 软件
* [Docker Desktop](https://www.docker.com/products/docker-desktop/)
* [Lens](https://k8slens.dev/): k8s GUI

<!-- 改键软件: https://github.com/pqrs-org/Karabiner-Elements -->

### 图片、视频

* ~[iShot](https://www.better365.cn/ishot.html): 用过的最好用的截图软件，可以加阴影~
* [snipaste](https://www.snipaste.com/): 代替 iShot，因为贴图功能是免费的
* [CleanShot X](https://cleanshot.com/): 史诗级截图软件，不过年订阅费有点贵
* [LICEcap](https://www.cockos.com/licecap/): GIF 录屏
* [PicGo](https://github.com/Molunerfinn/PicGo): 图片上传到图床，我使用的是阿里云 OSS
  * [sapic](https://github.com/sapicd/sapic): 支持多种存储方式，需要自架
* [getKap](https://getkap.co/): 视频录屏软件
* [gifski](https://gif.ski/): 视频转成 GIF 图片

<!-- https://www.jianshu.com/p/84f363d8fc1f -->

### 其他

* [CleanMyMac X](https://macpaw.com/cleanmymac): 系统清理软件
  * [腾讯柠檬大师](https://lemon.qq.com/): 作为 CleanMyMac 的替代品
  * [easydevo](https://easydevo.boringboring.design/)
* 开源清理 Mac
  * [mac-cleanup](https://twitter.com/HiTw93/status/1754294011685142835) - 清理 Mac
  * [GUI clean](https://github.com/mac-cleanup/mac-cleanup-py) - 清理 Mac 
* [Irvue](https://apps.apple.com/us/app/irvue/id1039633667?mt=12): 换 Mac 壁纸
* RSS
  * [Reeder](http://reederapp.com/mac/): RSS 软件 - [搭建 RSS 服务](https://github.com/riskers/blog/issues/50)
  * [NetNewsWire](https://ranchero.com/netnewswire/): 可以作为 Reeder 免费替代品
* [1password](https://1password.com/): 密码管理，有计划换成 [elpass](https://elpass.app/)
* 系统菜单栏管理
  * ~[bartender](https://www.macbartender.com/)~
  * [Ice](https://icemenubar.app/)
  * ibar
  * [hidden](https://github.com/dwarvesf/hidden)
  * [vanilla](https://matthewpalmer.net/vanilla/)
* [itsycal](https://www.mowglii.com/itsycal/): 菜单栏日历软件
* Video Download
  * [Downie](https://software.charliemonroe.net/downie/): 视频下载，收费
  * [lux](https://github.com/iawia002/lux): 视频下载，免费
* [IINA](https://github.com/iina/iina): 很好用的视频播放器
* [infuse](https://firecore.com/infuse): 支持云盘视频
* [BLEUnlock](https://github.com/ts1/BLEUnlock): Apple Watch 自动解锁 Mac，感觉比 Apple 原生解锁合理一点
* [Skim](https://pdf.wondershare.net/ad/pdf-editor-mac.html): PDF 软件
* [MarginNote](https://www.marginnote.com/): 看 PDF 书籍，记录笔记


## 输出

### Learning English

* [relingo](https://relingo.net/en/index): Chrome 插件，划词翻译 + 单词本 (已买终身会员)
* [languagereactor](https://www.languagereactor.com/): 看 Youtube 视频，有双语字幕，且可以查单词、语法，可快速重播某一段、可看到全文等功能
* [grammarly](https://app.grammarly.com/): 一个好用的浏览器插件，检查英文语法
* [qwerty](https://qwerty.kaiyi.cool/): 英文打字练习

### PPT

* [字由](http://www.hellofont.cn/): 艺术字体
* [Flat UI](http://designmodo.github.io/Flat-UI/): 配色
* 快速产出 PPT:
  * [NodePPT](https://github.com/ksky521/nodeppt): MD 转为 PPT，[Share](https://riskers.github.io/share/) 就是用它做的
  * [Marp](https://yhatt.github.io/marp/): MD 转为 PPT，适合紧急演讲使用
  * [slides](https://slides.com/): 在线 PPT 工具
  * [sway](https://sway.office.com/): 在线 PPT 工具
* 素材
  * https://www.iconfont.cn/

### 脑图、流程图

* https://whimsical.com/
* https://excalidraw.com/
* https://milanote.com/
* https://miro.com/
* https://webdemo.myscript.com/
* https://www.zenflowchart.com/
* https://asciiflow.com/#/
* https://sketchboard.me/


都是 [omnigraffle](https://www.omnigroup.com/omnigraffle) 的替代品，我用的是 whimsical 和 excalidraw 比较多，因为免费。

### 图片

* 代码生成图片:
  * https://carbon.now.sh/
  * https://ray.so/
  * https://text2image.jaychen.fun/
* PPT 背景图
  * https://coolbackgrounds.io/
  * https://www.hituyu.com/

### 笔记

* [Notion](https://www.notion.so/): 主力知识管理
* [Dayone](https://dayoneapp.com/): 日记
* [Joplin](https://joplinapp.org/): 支持 webdav，搭配坚果云做同步，一般用来写博客
* [MWeb](https://www.mweb.im/): 当作一款好用 MD 编辑器

一般我用 Dayone 把每天做的事情记录下来，周末用 Notion 做个简单的周报。

### 财务管理

* [beancount](https://github.com/beancount/beancount)


## Chrome 插件

* Proxy SwitchyOmega
* JSONView
* Vimium
* AdBlock
* Momentum
* Raindrop.io: 收藏夹
* **Loom** / Screenity: 录制视频
* Tampermonkey
* Grammarly
* Language Reactor: YT 翻译软件
* Relingo: 划词类翻译软件
* **Requestly** / ModHeader: 拦截请求

## 在线应用

* [herowand](https://editor.herowand.com/): 可视化 JSON、CSV 等
* sheel 命令解释查询: https://www.explainshell.com/
* 调试正则
  * http://refiddle.com/
  * https://regex101.com/
* 调试 glob: https://globster.xyz/
* 调试 AST: https://astexplorer.net/
* 邮件签名图: https://github.com/o2team/sign
* 在线设计图片
  * https://www.canva.cn/
  * https://designer.microsoft.com/
  * https://pearmini.github.io/colorfu/


## 字体

比较爱折腾，一款看腻了就换一个

* [Cascadia Code](https://github.com/microsoft/cascadia-code)
* [Roboto Mono](https://www.cufonfonts.com/font/roboto-mono)
* [Go Mono](https://fontlibrary.org/en/font/go-mono)
* [Dank Mono](https://dank.sh/)
* [Fira Code](https://github.com/tonsky/FiraCode)
* [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
* [Operator Mono](https://github.com/keyding/Operator-Mono)
* [Comic Mono](https://dtinth.github.io/comic-mono-font/)

可以使用 [RightFont](https://rightfontapp.com/) 管理字体
