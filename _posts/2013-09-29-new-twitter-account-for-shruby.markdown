---
layout: post
title:  "为 Shanghai Ruby User Group 创建了一个 Twitter 同步账号"
date:   2013-09-29 23:51:20
categories: twitter accounts
---

之前在 [Github](https://github.com/shruby/shruby.github.io/issues/27) 上提到过要为 Shanghai Ruby User Group 弄个 Twitter 账号同步Feeds，经过一晚上的编码，已经完成了。

Twitter 账号是 [@shanghai_ruby](https://twitter.com/shanghai_ruby)，大家可以开始Follow了，虽然目前内容只有两条。

同步用的程序是拿我之前给 Ruby China([@RubyChinaTopics](https://twitter.com/RubyChinaTopics)) 同步用的代码改出来的。
之前那些代码经过多次Bug修复终于稳定下来了，在最近长达半年的时间里完全无需管理也能正常同步，这次在原有代码的基础上进行修改应该也会比较稳定吧。
代码在 [Github](https://github.com/bachue/lightweight-feed-twitter-notifier) 上托管，欢迎提出 issue 和发送 pull request。

该程序目前部署在我自己的Linode VPS上，和 Ruby China 一起同步，应该还是比较稳定的。如果发生任何问题，也欢迎发 issue。我会在非工作时间予以解决（没办法，无法从公司网络访问到自己的VPS ╮（￣﹏￣）╭ ）。
