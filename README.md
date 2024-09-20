# Plugx 开源情报集合

## 特点
### Dll侧加载
存在三个文件，Loader 通常为合法的exe，具有数字签名。Dll为恶意Dll，从Dat解密Shellcode并加载，Dat为加密后的Shellcode
- Loader 
- Dll 
- Dat 
加载流程如下图所示

![image](https://github.com/user-attachments/assets/e09636f0-c8af-42c4-9091-91dec8ee1a83)


### 进程注入
自带功能，默认开启，默认进程如下图所示   

![image](https://github.com/user-attachments/assets/3f9fd336-d62c-49d9-8c06-acfdac074e60)
![image](https://github.com/user-attachments/assets/a7845fba-cea6-42ca-8d01-7f5052eebba7)



### 支持协议
- TCP（HTTP）
- UDP
- DNS
- ICMP（14年以后版本才有）
- HTTPS（新版本）

### 链接
- [DragonRank，一家中文 SEO 操纵服务提供商](https://blog.talosintelligence.com/dragon-rank-seo-poisoning/)
- [ShadowPad 构建器](https://nao-sec.org/2024/06/building-caspers-shadow.html)
- [外交幽灵行动：中国积极开展网络间谍活动，利用稀有工具攻击中东、非洲和亚洲的政府实体](https://unit42.paloaltonetworks.com/operation-diplomatic-specter/)
- [遗留威胁：在 Open Directory 中发现 PlugX Builder/Controller](https://hunt.io/blog/legacy-threat-plugx-builder-controller-discovered-in-open-directory)
- [揭开谜团：深入了解 PlugX 恶意软件的历史](https://www.splunk.com/en_us/blog/security/unmasking-the-enigma-a-historical-dive-into-the-world-of-plugx-malware.html)
- [PlugX 恶意软件通过漏洞利用进行传播](https://asec.ahnlab.com/en/49097/)
- [通过非标准证书追踪 ShadowPad 基础设施）](https://hunt.io/blog/tracking-shadowpad-infrastructure-via-non-standard-certificates)
- [PlugX USB 蠕虫病毒跨越国界，开始肆虐）](https://news.sophos.com/en-us/2023/03/09/border-hopping-plugx-usb-worm/)
- [调查伪装成合法 Windows 调试工具的 PlugX 木马病毒](https://www.trendmicro.com/en_us/research/23/b/investigating-the-plugx-trojan-disguised-as-a-legitimate-windows.html)
- [Mustang Panda APT 集团利用欧盟委员会主题诱饵传播 PlugX 恶意软件](https://blog.eclecticiq.com/mustang-panda-apt-group-uses-european-commission-themed-lure-to-deliver-plugx-malware) 
- [中国 PlugX 恶意软件隐藏在您的 USB 设备中吗？](https://unit42.paloaltonetworks.com/plugx-variants-in-usbs/)
- [深入研究 Mustang Panda 组织的 PlugX 样本](https://kienmanowar.wordpress.com/2022/12/27/diving-into-a-plugx-sample-of-mustang-panda-group/)
- [PlugX 加载器的演变](https://engineers.ffri.jp/entry/2022/11/30/141346)
- [威胁分析报告：PlugX RAT 加载程序的演变](https://www.cybereason.com/blog/threat-analysis-report-plugx-rat-loader-evolution)
- [PlugX：值得珍藏的护身符](https://www.trellix.com/blogs/research/plugx-a-talisman-to-behold/)
- [PlugX 的“GULP”](https://cyberandramen.net/2022/01/06/a-gulp-of-plugx/)
- [THOR：PKPLUG 组织在 Microsoft Exchange Server 攻击期间部署了此前未见过的 PlugX 变种](https://unit42.paloaltonetworks.com/thor-plugx-variant/)
- [TA416 坠毁并携带 Golang PlugX 恶意软件加载器返回](https://www.proofpoint.com/us/blog/threat-insight/ta416-goes-ground-and-returns-golang-plugx-malware-loader)

### 资料文件
- [《深入了解 Polaris 的武器库和情报见解》](https://github.com/badboycxcc/Plugx/blob/main/2024-08-Sailing%20the%20Seven%20SEAs.pdf)   
- [《揭秘 TeleBoyi：中国 APT 组织瞄准全球关键基础设施》](https://github.com/badboycxcc/Plugx/blob/main/JSAC2024_1_8_yi-chin_yu-tung_en.pdf)
- [《RAT 的秘密生活：通过剖析多个后门来串联线索》](https://github.com/badboycxcc/Plugx/blob/main/JSAC2024_1_7_hara_nakajima_kawakami_en.pdf)
- [《中国 RedGolf 利用 KEYPLUG 进行广泛目标的间谍活动和窃取信息》](https://github.com/badboycxcc/Plugx/blob/main/cta-2023-0330.pdf)
- [《MustangPanda 简史及其 PlugX 演变》](https://github.com/badboycxcc/Plugx/blob/main/JSAC2023_2_LT4.pdf)
- [《剖析 PlugX 以提取其精华》](https://github.com/badboycxcc/Plugx/blob/main/Dissecting%2BPlugX%2Bto%2BExtract%2BIts%2BCrown%2BJewels.pdf)
- [《下一代 PlugX/ShadowPad？深入研究新兴的中国 Nexus 模块化木马 Pangolin8RAT（幻灯片）》](https://github.com/badboycxcc/Plugx/blob/main/AS-22-LeonSilvia-NextGenPlugXShadowPad.pdf)
- [《ShadowPad：中国间谍活动私售恶意软件的杰作1》](https://github.com/badboycxcc/Plugx/blob/main/D1T1%20-%20%20ShadowPad%20-%20A%20Masterpiece%20of%20Privately%20Sold%20Malware%20in%20Chinese%20Espionage%20-%20Yi-Jhen%20Hsieh%20%26%20Joey%20Chen.pdf)
- [《ShadowPad：中国间谍活动私售恶意软件的杰作2》](https://github.com/badboycxcc/Plugx/blob/main/SentinelOne_-SentinelLabs_ShadowPad_WP_V2.pdf)
- [《ShadowPad APT 后门及其与 PlugX 的关系研究》](https://github.com/badboycxcc/Plugx/blob/main/Study_of_the_ShadowPad_APT_backdoor_and_its_relation_to_PlugX_en.pdf)
- [《分析报告 (TLP:WHITE) PlugX 变体分析 (PlugX 版本 7.0)》](https://github.com/badboycxcc/Plugx/blob/main/tr-12-circl-plugx-analysis-v1.pdf)



## 视频文件
- https://www.youtube.com/watch?v=-7Swd1ZetiQ
- https://www.youtube.com/watch?v=r1zAVX_HnJg


## 图片
### 来源：https://nao-sec.org/2024/06/building-caspers-shadow.html
**构建器**
![image](https://github.com/user-attachments/assets/9174b4c3-d2d7-436b-83c7-6e699de01a60)
![image](https://github.com/user-attachments/assets/191661aa-ba71-45c4-b724-29023d70ab6f)
![image](https://github.com/user-attachments/assets/5ba6af06-5573-4558-97e6-206529fd0d38)
![image](https://github.com/user-attachments/assets/e75c38e0-8f43-414a-ab4b-c7feaa5d8043)
![image](https://github.com/user-attachments/assets/8a5c6dcc-4c04-4681-947d-38b90841f818)
![image](https://github.com/user-attachments/assets/7abdc0c7-cb39-4d59-9b05-fba01e751fb5)




### 来源：https://hunt.io/blog/legacy-threat-plugx-builder-controller-discovered-in-open-directory
**构建器**
![image](https://github.com/user-attachments/assets/8b8a05fc-3495-4e8d-8ce9-93da19c7f89c)
![image](https://github.com/user-attachments/assets/bac32282-3582-4b70-ad44-b373cff87f77)
![image](https://github.com/user-attachments/assets/fd40036e-9779-4ede-a89e-4ae419968842)
![image](https://github.com/user-attachments/assets/004f11a8-e5b4-4f52-a40f-df5289b8b12c)
![image](https://github.com/user-attachments/assets/a4c4be0f-9491-4da5-8c31-228b35a31d0a)


**控制端**
![image](https://github.com/user-attachments/assets/1acc5c80-bab9-42df-883b-7d5004f44c01)

