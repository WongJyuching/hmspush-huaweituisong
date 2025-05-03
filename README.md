# hmspush-huaweituisong  
添加HMS Push 华为推送所需的软件  
  
    FCM连接请使用支持FCM的国内系统和对应科学软件，建议 Clash / Clash Verge / Clash Meta类  


进入Clash 1️⃣点击设置---网络全部勾选（出现应用无法联网可尝试关闭此界面的允许IPv6开关）
          2️⃣设置——覆写——Hosts——右上角+号————键填写mtalk.google.com，值填写108.250.10.188————以此类推，添加三四个即可，测试通过的是    mtalk.google.com  108.250.10.188  、    alt5-mtalk.google.com   142.250.10.188  、    alt7-mtalk.google.com  64.233.177.188  
          3️⃣添加完成后点击确认


对三星OneUI5/6/7 1️⃣绕过国行FCM检测，额外点击设置————网络——访问控制模式（选择仅允许已选择的应用）————点击最下面访问控制应用包列表（搜索添加Android系统（android）、com.samsung.android.sskds、com.android.settings）三个软件————————开启VPN规则模式——————即可开启全局FCM 科学上网不断可一直连接外网FCM通知 国内应用可走国内网络不消耗VPN流量和电量 隐藏Clash通知可实现无感出国

    
    mtalk.google.com  108.250.10.188  
    mtalk4.google.com  
    mtalk-staging.google.com  
    mtalk-dev.google.com  
    alt1-mtalk.google.com  
    alt2-mtalk.google.com  
    alt3-mtalk.google.com  
    alt4-mtalk.google.com  
    alt5-mtalk.google.com   142.250.10.188  
    alt6-mtalk.google.com  
    alt7-mtalk.google.com  64.233.177.188  
    alt8-mtalk.google.com  


可通过LibChecker查看是否支持HMS Push / FCM  ，Libcheker请自行搜索下载

  —————————————HMS 华为推送——测试通过如下APP  可能随不同APP版本有出入—————————   
    
    同花顺、富途牛牛、高德地图、百度地图、汽水音乐、QQ音乐（可能无法正常跳转）
    支付宝（可能无法正常跳转）、豆包、小红书、阿里云盘
    安居客、永安行、淘宝、抖音极速版、今日头条、京东、米家、QQ邮箱7.0版本、网易邮箱大师7.7.6版本、闲鱼（低版本）、中国电信、12306
    钉钉（可能无法注册）、飞书（大概率闪退）、番茄小说、小黑盒、菜鸟、贴吧、饿了么、美团（大概率闪退或无法支付）
    航旅纵横、彩云天气、哔哩哔哩漫画、知乎、微博、Boss直聘
    QQ（可能报外挂检测）、Tim（可能报外挂检测）
    
    ！微信无法使用HMS Push！
    等

    其他APP未测试过


  —————————————FCM推送 ————————测试通过如下APP  可能随不同APP版本有出入，设置应用为优化—————————————————— 

    Telegram系、X、ChatGPT、Outlook、12306、Google系、小红书、知乎、微软系、钉钉、Binance、OKX、Bitget、Play Store、Ins、Teams等明显国外的App

