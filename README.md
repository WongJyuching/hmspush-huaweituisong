# hmspush-huaweituisong  

## 添加 HMS Push 华为推送所需的软件                              ——————以下设置操作所需时间约 10min————

### FCM 连接设置说明  
请使用支持 FCM 的国内系统和对应科学软件，建议使用：  
- Clash  
- Clash Verge  
- Clash Meta 类工具  
### 安装如下APP-附件可下载
- HMS Push
- HMS Core
- Lspatch
- Shizuku

#### 方案1（规则模式）（以 Clash 为例）  
1. 进入 Clash 设置  
   - 点击 **设置 → 网络**，将所有选项勾选（若应用无法联网，可尝试关闭「允许 IPv6」）  
2. 设置 Hosts  
   - 点击 **设置 → 覆写 → Hosts → 右上角 +**  
   - 添加以下条目（键为域名，值为 IP）  
     - `mtalk.google.com` → `108.250.10.188`  
     - `alt5-mtalk.google.com` → `142.250.10.188`  
     - `alt7-mtalk.google.com` → `64.233.177.188`  
   - 添加三至四条即可，然后点击确认  
3. 设置完成后即可测试连接，需要开启规则模式！！（否则所有流量均通过VPN）

### 三星 OneUI 5 / 6 / 7 特殊设置 
1. 绕过国行 FCM 检测：  
   - **设置 → 网络 → 访问控制模式**，选择「仅允许已选择的应用」  
   - 点击最下面的「访问控制应用包列表」，添加以下应用：  
     - Android 系统（`android`）  
     - `com.samsung.android.sskds`  
     - `com.android.settings`  
2. 启用 VPN 规则模式：  
   - 开启后即为全局 FCM 科学上网：  
     - 国内 App 仍走国内网络，不消耗 VPN 流量和电量  
     - 隐藏 Clash 通知即可实现无感出国  ，电量消耗一天约4%不到

---
#### 方案2（全局模式）（以 Clash 为例）  

导入VPN地址 -- 全局模式 -- 开启VPN连接 --注意需要App设置为优化模式/无限制模式  ————此模式会让所有流量通过VPN，包括微信、Bilibili等


### FCM 相关域名及 IP  

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


### 可通过LibChecker查看是否支持HMS Push / FCM  ，Libcheker请自行搜索下载

  ### —————————————HMS 华为推送——测试通过如下APP  可能随不同APP版本有出入—————————   
    
    同花顺、富途牛牛、高德地图、百度地图、汽水音乐、QQ音乐（可能无法正常跳转）
    支付宝（可能无法正常跳转）、豆包、小红书、阿里云盘、哔哩哔哩
    安居客、永安行、淘宝、抖音极速版、今日头条、京东、米家、QQ邮箱7.0版本、网易邮箱大师7.7.6版本、闲鱼（低版本）、中国电信、12306
    钉钉（可能无法注册）、飞书（大概率闪退）、番茄小说、小黑盒、菜鸟、贴吧、饿了么、美团（大概率闪退或无法支付）
    航旅纵横、彩云天气、哔哩哔哩漫画、知乎、微博、Boss直聘
    QQ（可能报外挂检测）、Tim（可能报外挂检测）
    
    ！微信无法使用HMS Push！
    等

    其他APP未测试过


  ### FCM推送 ————————测试通过如下APP  可能随不同APP版本有出入 进入此APP设置应用为优化

    Telegram系、X、ChatGPT、Outlook、12306、Google系、小红书、知乎、微软系
    钉钉、Binance、OKX、Bitget、Play Store、Ins、Teams等明显国外的App

