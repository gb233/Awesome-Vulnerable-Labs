# Awesome Vulnerable Labs (CN) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English](README.md) | 中文

> 面向中文读者的漏洞靶场/实验室/在线演示/挑战平台清单，用于授权范围内学习与测试。

## Contents
- [覆盖范围亮点](#覆盖范围亮点)
- [使用说明](#使用说明)
- [Web 应用靶场](#web-应用靶场)
- [API / 微服务靶场](#api--微服务靶场)
- [AI / LLM 安全靶场](#ai--llm-安全靶场)
- [区块链 / Web3 / 智能合约靶场](#区块链--web3--智能合约靶场)
- [移动应用靶场](#移动应用靶场)
- [云 / 容器 / K8s 靶场](#云--容器--k8s-靶场)
- [内网 / Active Directory (AD) 靶场](#内网--active-directory-ad-靶场)
- [系统 / 二进制 / 逆向](#系统--二进制--逆向)
- [IoT / 工控 / ICS 靶场](#iot--工控--ics-靶场)
- [CTF / 在线挑战平台](#ctf--在线挑战平台)
- [安全厂商 Demo / 漏洞演示站](#安全厂商-demo--漏洞演示站)
- [综合实验室 / 课程式靶场](#综合实验室--课程式靶场)
- [安全基准测试 / 数据集](#安全基准测试--数据集)
- [旧版本软件与辅助资源](#旧版本软件与辅助资源)
- [收录标准](#收录标准)
- [免责声明](#免责声明)
- [Contributing](#contributing)

## 覆盖范围亮点
- 覆盖 Web/API、AI/LLM/MCP、Web3/区块链等攻防场景。
- 覆盖 Android/iOS/Windows/macOS 平台与 PHP/Java/Node.js/Python 等技术栈。
- 覆盖云/K8s、AD、IoT/ICS、CTF 与其它细分方向。
- 持续维护更新的相关资源集合。

## 使用说明
- 本清单收录“可用于漏洞学习/练习”的资源形态，包括开源可部署靶场、在线演示站点、云实验室、课程式实验环境与 CTF 挑战平台。
- 请仅在合法授权范围内使用；对在线演示类站点请避免压力测试或破坏性操作。
- 条目描述以中文为主，允许保留英文名称/别名，便于检索与对照资料。

## Web 应用靶场

### 开源可部署
- [BadStore](https://www.vulnhub.com/entry/badstore-123,41/) - 电商场景 Web 漏洞练习靶场。
- [Butterfly Security Project](http://thebutterflytmp.sourceforge.net/) - PHP/Web 漏洞教学环境。
- [bWAPP](http://sourceforge.net/projects/bwapp/files/bee-box/) - 含常见漏洞的 Web 靶场（bee-box）。
- [BWVS](https://github.com/bugku/BWVS) - Web 漏洞渗透测试靶场。
- [Vulnerable Nginx](https://github.com/detectify/vulnerable-nginx) - Nginx 漏洞演示环境。
- [WAVSEP](https://github.com/sectooladdict/wavsep) - Web 漏洞扫描测试床。
- [Commix Testbed](https://github.com/stasinopoulos/commix-testbed) - 命令注入练习页面集合。
- [Damn Vulnerable Node Application (DVNA)](https://github.com/appsecco/dvna) - Node.js Web 漏洞靶场。
- [AspGoat](https://github.com/Soham7-dev/AspGoat) - 故意不安全的 ASP.NET Core Web 应用，用于学习与练习 Web 安全。
- [Damn Vulnerable Java (DVJA)](https://github.com/appsecco/dvja) - Damn Vulnerable Java (EE) 漏洞练习应用。
- [SQL Injection Training App](https://github.com/appsecco/sqlinjection-training-app) - 用于学习 SQL 注入检测与利用的 PHP 练习应用。
- [Damn Vulnerable Web Sockets](https://github.com/interference-security/DVWS) - WebSocket 漏洞练习应用。
- [DIWA - Deliberately Insecure Web Application](https://github.com/snsttr/diwa) - 故意不安全的 Web 应用练习项目。
- [Extreme Vulnerable Node Application (XVNA)](https://github.com/vegabird/xvna) - Node.js 漏洞练习应用。
- [GameOver](https://sourceforge.net/projects/null-gameover/) - Web 安全基础训练靶场。
- [Hackazon](https://github.com/rapid7/hackazon) - 现代化电商 Web 漏洞靶场。
- [BodgeIt Store](https://github.com/psiinon/bodgeit) - Java 漏洞练习商店应用。
- [LAMPSecurity](http://sourceforge.net/projects/lampsecurity/) - LAMP 体系 Web 漏洞靶场/VM。
- [OWASP Mutillidae II](https://github.com/webpwnized/mutillidae) - OWASP Web 漏洞靶场。
- [OSS – OopsSec Store](https://github.com/kOaDT/oss-oopssec-store) - Next.js 漏洞电商应用。
- [OWASP Bricks](https://sourceforge.net/projects/owaspbricks/) - PHP/MySQL Web 漏洞练习平台。
- [OWASP BWA](http://code.google.com/p/owaspbwa/) - 收录多套 Web 漏洞应用的 VM。
- [DVWA](https://github.com/digininja/DVWA) - 经典 PHP Web 漏洞靶场。
- [GOVWA](https://github.com/0c34/govwa) - Go 语言编写的 Web 漏洞练习应用。
- [OWASP Hackademic](https://github.com/Hackademic/hackademic/) - Web 安全学习靶场。
- [OWASP Juice Shop](https://github.com/juice-shop/juice-shop) - OWASP 官方开源 Web 靶场。
- [OWASP Security Shepherd](https://www.owasp.org/index.php/OWASP_Security_Shepherd) - Web 安全训练平台（开源）。
- [OWASP Security Shepherd (GitHub)](https://github.com/OWASP/SecurityShepherd) - OWASP Security Shepherd 源码。
- [OWASP WebGoat 8](https://github.com/webgoat/webgoat) - OWASP WebGoat 8 漏洞训练平台。
- [OWASP WrongSecrets](https://github.com/commjoen/wrongsecrets) - 错误密钥管理场景靶场。
- [Peruggia](https://sourceforge.net/projects/peruggia/) - Web 攻击练习环境。
- [Pikachu](https://github.com/zhuifengshaonianhanlu/pikachu) - 中文常用 Web 漏洞靶场。
- [Webug4.0](https://github.com/wangai3176/webug4.0) - 中文 Web 漏洞靶场（SQLi/XSS/上传等）。
- [PuzzleMall](https://code.google.com/p/puzzlemall/) - Session 相关漏洞练习应用。
- [SentinelTestbed](https://github.com/dobin/SentinelTestbed) - 脆弱 Web 站点测试床。
- [SocketToMe](http://digi.ninja/projects/sockettome.php) - 含隐藏漏洞的小游戏式 Web 应用。
- [sqli-labs](https://github.com/Audi-1/sqli-labs) - SQL 注入专项靶场。
- [NoSQL Injection Lab](https://github.com/digininja/nosqlilab) - NoSQL 注入练习实验室。
- [Sqlilabs](https://github.com/himadriganguly/sqlilabs) - SQL 注入练习集合。
- [LFI Labs](https://github.com/paralax/lfi-labs) - 本地文件包含漏洞练习项目。
- [upload-labs](https://github.com/c0ny1/upload-labs) - 文件上传漏洞靶场。
- [VulnApp](https://www.nth-dimension.org.uk/blog.php?id=88) - ASP.NET 漏洞示例应用。
- [VulnLab](https://github.com/Yavuzlar/VulnLab) - Docker 化 Web 漏洞实验室。
- [WackoPicko](https://github.com/adamdoupe/WackoPicko) - 用于漏洞扫描器测试的 Web 靶场。
- [WebGoat.NET](https://github.com/jerryhoff/WebGoat.NET/) - .NET 版 WebGoat。
- [WebSecurity Dojo](https://www.mavensecurity.com/web_security_dojo/) - 自包含 Web 安全训练环境。
- [XVWA](https://github.com/s4n7h0/xvwa) - PHP/MySQL Web 漏洞靶场。
- [tegal1337/0l4bs](https://github.com/tegal1337/0l4bs) - XSS 专项练习靶场。
- [tegal1337/br0w](https://github.com/tegal1337/br0w) - 浏览器安全练习靶场。
- [xss-labs](https://github.com/do0dl3/xss-labs) - XSS 漏洞练习靶场。
- [OWASP NodeGoat](https://github.com/OWASP/NodeGoat) - Node.js OWASP Top 10 训练应用。
- [OWASP RailsGoat](https://github.com/OWASP/railsgoat) - Rails 漏洞训练应用。
- [PyGoat](https://gitlab.com/varun.manoj/pygoat) - Django 漏洞训练应用。
- [DVLA](https://gitlab.com/dpopkin/DVLA) - Laravel 漏洞练习应用。
- [vulnerable-sso](https://github.com/dogangcr/vulnerable-sso) - SSO 漏洞练习 Web 应用。
- [UnSAFE Bank](https://github.com/lucideus-repo/UnSAFE_Bank) - 覆盖 Web/Android/iOS 的脆弱应用。

- [Virtual Hacking Lab](https://sourceforge.net/projects/virtualhacking/) - 漏洞练习应用/靶场。
- [Vulnado](https://github.com/ScaleSec/vulnado) - 用于安全编码工作坊的故意脆弱 Java 应用。
- [Vulnerable Node Express](https://github.com/kaakaww/vuln_node_express) - SQL 注入与 XSS 漏洞练习应用。
- [Vulnerable OTP App](https://github.com/mddanish/Vulnerable-OTP-Application) - 漏洞练习应用/靶场。
- [Vulnerable SAML App](https://github.com/yogisec/VulnerableSAMLApp) - 漏洞练习应用/靶场。
- [VulnerableXsltConsoleApplication](https://github.com/ctxis/VulnerableXsltConsoleApplication) - 控制台应用示例，展示与 Web 相关的 XSLT 转换漏洞场景。
- [WAVSEP - Web Application Vulnerability Scanner Evaluation Project](https://github.com/zaproxy/wavsep) - 漏洞练习应用/靶场。
- [WIVET- Web Input Vector Extractor Teaser](https://github.com/bedirhan/wivet) - 漏洞练习应用/靶场。
- [Wayfarer](https://github.com/samuraiwtf/wayfarer) - 漏洞练习应用/靶场。
- [WebGoatPHP](https://www.owasp.org/index.php/WebGoatPHP) - 漏洞练习应用/靶场。
- [WebGoat](https://webgoat.github.io/WebGoat/) - 漏洞练习应用/靶场。
- [Weird Proxies - Labs](https://github.com/GrrrDog/weird_proxies/tree/master/labs) - 漏洞练习应用/靶场。
- [XXE](http://xxe.sourceforge.net/) - 漏洞练习应用/靶场。
- [Zero Health](https://github.com/aligorithm/Zero-Health) - 带 AI 聊天机器人的脆弱医疗平台，用于安全学习。
- [bWAPP](http://www.itsecgames.com/) - 漏洞练习应用/靶场。
- [insecure-deserialisation-net-poc](https://github.com/omerlh/insecure-deserialisation-net-poc) - 存在不安全反序列化的轻量 Web 服务器。
- [jwtdemo](https://github.com/Sjord/jwtdemo/) - JWT 令牌攻防练习项目。
- [play-webgoat](https://github.com/playframework/play-webgoat) - 漏洞练习应用/靶场。
- [twitterlike](https://github.com/sakti/twitterlike) - 漏洞练习应用/靶场。
- [vuln-node.js-express.js-app](https://github.com/SirAppSec/vuln-node.js-express.js-app) - 非常脆弱的 Node.js/Express Web 与 API 应用，用于安全测试。
- [vulnerable-api](https://github.com/mattvaldes/vulnerable-api) - 漏洞练习应用/靶场。
- [ypreyAPINodeJS](https://yrprey.com) - 基于 OWASP API Top 10 的 NodeJS 脆弱框架。

### 仅在线演示
- [CTFchallenge](https://ctfchallenge.com/) - 由多子域组成的 Web 漏洞练习平台。
- [Firing Range](https://public-firing-range.appspot.com/) - Google 提供的 Web 测试靶场。
- [DOM Clobbering XSS (CXSS)](https://domgo.at/cxss/intro) - DOM XSS 教学与演示页面。
- [hackxor](https://hackxor.sourceforge.net/cgi-bin/index.pl) - Web 漏洞闯关式练习站点。
- [Pentest-Ground](https://pentest-ground.com/) - 在线 Web 漏洞练习平台。
- [Duck Store](https://duck-store.escape.tech/) - 在线 Web 漏洞演示应用。
- [Cyber Scavenger Hunt](https://cyberscavengerhunt.com) - 用于学习网站/应用渗透测试的简易闯关任务。
- [Damn Vulnerable AI Bank (DVAIB)](https://www.dvaib.com) - 面向提示注入/越狱的 AI 安全实战训练平台。
- [Defend the Web](https://defendtheweb.net/) - 原 HackThis 的在线攻防练习平台。
- [HackXpert](https://labs.hackxpert.com/) - 在线漏洞练习/演示平台。
- [HackYourselfFirst](https://hack-yourself-first.com/) - 在线漏洞练习/演示平台。
- [Hacking Lab](https://www.hacking-lab.com/events/) - 在线漏洞练习/演示平台。
- [Root Me](https://www.root-me.org) - 非营利的黑客学习与挑战平台。
- [Solyd - Introdução ao Hacking e Pentest](http://solyd.com.br/treinamentos/introducao-ao-hacking-e-pentest) - 葡语安全入门课程与在线实验。

### 商业（含试用/训练平台）
- [PentesterLab](https://pentesterlab.com/) - Web 安全课程与练习平台。
- [PentesterLab - Web for Pentester](https://www.pentesterlab.com/exercises/web_for_pentester) - PentesterLab Web 练习课程。
- [Web-Security Academy](https://portswigger.net/web-security) - PortSwigger 提供的 Web 安全学习与实验平台。

## API / 微服务靶场

### 开源可部署
- [Damn Vulnerable Web Services (DVWS)](https://github.com/snoopysecurity/dvws) - Web 服务漏洞练习平台。
- [Damn Vulnerable C# API (DVCSharp-API)](https://github.com/appsecco/dvcsharp-api) - Damn Vulnerable C# API 练习项目。
- [OWASP crAPI](https://github.com/OWASP/crAPI) - OWASP API 漏洞练习平台。
- [VAmPI](https://github.com/erev0s/VAmPI) - Flask 编写的 API 漏洞靶场。
- [REST API Goat](https://github.com/optiv/rest-api-goat) - OWASP API Top 10 练习靶场。
- [vAPI](https://github.com/roottusk/vapi) - OWASP API 场景练习项目。
- [Vulnerable App for API Security](https://github.com/Erdemstar/VulnerableApp4APISecurity) - .NET API 漏洞练习项目。
- [Websheep](https://github.com/marmicode/websheep) - REST API 漏洞练习平台。
- [Pixi](https://github.com/DevSlop/Pixi) - 含不安全 API 的 MEAN 练习应用。
- [Tiredful-API](https://github.com/payatu/Tiredful-API) - Django/DRF API 漏洞练习项目。
- [Vulnerable REST API (OWASP 2023)](https://github.com/bnematzadeh/vulnerable-rest-api) - OWASP API Top 10 2023 练习项目。
- [Damn Vulnerable RESTaurant API Game](https://github.com/Nazacod/Damn-Vulnerable-RESTaurant-API-Game) - API 漏洞闯关式练习。
- [c{api}tal](https://github.com/Checkmarx/capital) - 基于 OWASP API Top 10 的 API 靶场。
- [dvws-node](https://github.com/snoopysecurity/dvws-node) - 含 API 组件的漏洞服务平台。
- [VulnerableLightApp](https://github.com/Aif4thah/VulnerableLightApp) - 教学用漏洞 API 示例。
- [Damn Vulnerable GraphQL Application (DVGA)](https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application) - GraphQL 漏洞练习应用。
- [GraphQL Security Labs](https://github.com/dcodx/graphql-security-labs) - GraphQL 安全练习实验室。
- [poc-graphql](https://github.com/righettod/poc-graphql) - GraphQL 漏洞 PoC/练习项目。
- [gRPC Goat](https://github.com/rootxjs/grpc-goat) - gRPC 漏洞练习靶场。
- [grpc-lab](https://github.com/nxenon/grpc-lab) - gRPC 漏洞练习实验室。
- [grpc-web-playground](https://github.com/bnematzadeh/grpc-web-playground) - gRPC-Web 漏洞练习应用。
- [vuln-grpc-kotlin](https://github.com/kaakaww/vuln-grpc-kotlin) - Kotlin gRPC 漏洞示例。
- [DamnVulnerableMicroServices](https://github.com/ne0z/DamnVulnerableMicroServices) - 漏洞微服务练习集。
- [VRPlayground](https://github.com/f5devcentral/VRPlayground) - 微服务漏洞练习集。
- [cargo-cats](https://github.com/Contrast-Security-OSS/cargo-cats) - 漏洞微服务演练应用。
- [java-microservice-sample-apps](https://github.com/Contrast-Security-OSS/java-microservice-sample-apps) - 漏洞微服务样例集合。
- [secDevLabs](https://github.com/globocom/secDevLabs) - 多应用漏洞实验室（含 API）。
- [Damn Vulnerable RESTaurant (theowni)](https://github.com/theowni/Damn-Vulnerable-RESTaurant-API-Game) - Web API 漏洞闯关式练习项目。

### 在线实验室 / 课程平台
- [APIsec University](https://www.apisecuniversity.com/) - API 安全训练课程与实验资源。
- [Application Security OWASP Top 10 API](https://application.security/free/owasp-top-10-API) - OWASP API Top 10 训练课程。
- [Escape GraphQL Security Academy](https://escape.tech/academy/) - GraphQL 漏洞学习平台。
- [PortSwigger API Testing Path](https://portswigger.net/web-security/learning-paths/api-testing) - Web Security Academy API 学习路径。
- [PortSwigger GraphQL Labs](https://portswigger.net/web-security/learning-paths/graphql-api-vulnerabilities) - GraphQL 漏洞实验路径。
- [Gin & Juice Shop](https://ginandjuice.shop/) - GraphQL 漏洞练习在线靶场。

## AI / LLM 安全靶场

### 在线挑战/平台
- [Gandalf](https://gandalf.lakera.ai/) - Prompt Injection 入门闯关。
- [Prompt Airlines](https://promptairlines.com/) - Prompt Injection 主题 CTF。
- [GPT Prompt Attack](https://gpa.43z.one/) - 最短提示词攻破挑战。
- [GPT Game](https://gpt.43z.one/) - 指令约束挑战游戏。
- [HackAPrompt](https://www.hackaprompt.com/) - AI 红队/Prompt Injection 平台。
- [SaTML LLM CTF](https://ctf.spylab.ai/) - LLM CTF 在线平台。
- [PortSwigger LLM Attacks Labs](https://portswigger.net/web-security/llm-attacks) - LLM 攻击实验室。
- [DVAIB - Damn Vulnerable AI Bank](https://dvaib.com/) - AI 安全练习平台。

### 开源可部署
- [LLMGoat](https://github.com/SECFORCE/LLMGoat) - OWASP LLM Top 10 练习靶场。
- [AI Goat](https://github.com/dhammon/ai-goat) - 本地 LLM CTF 挑战集。
- [AI Red Teaming Playground Labs (Microsoft)](https://github.com/microsoft/AI-Red-Teaming-Playground-Labs) - 微软提供的 AI 红队演练实验室与练习材料。
- [AIGoat](https://github.com/orcasecurity-research/AIGoat) - 可部署的 AI 安全实验环境。
- [Damn Vulnerable LLM Agent (ReversecLabs)](https://github.com/ReversecLabs/damn-vulnerable-llm-agent) - 基于 ReAct/LangChain 的 LLM Agent 注入演练项目（支持 Streamlit/Docker）。
- [LLM Vulnerable Recruitment App (ReversecLabs)](https://github.com/ReversecLabs/llm-vulnerable-recruitment-app) - 招聘场景 LLM 漏洞练习应用。
- [Vulnerable MCP Servers Lab](https://github.com/appsecco/vulnerable-mcp-servers-lab) - 用于学习渗透 MCP Server 的漏洞服务器集合。
- [Vulnerable MCP](https://github.com/akto-api-security/vuln-mcp) - 漏洞 MCP Server 示例。
- [Builder-Breaker Lab](https://github.com/Harry-Ashley/Builder-Breaker-Lab) - 基于 PyRIT 的 AI 红队实验室（验证 Microsoft AI Red Team Taxonomy）。
- [Folly](https://github.com/user1342/Folly) - LLM Prompt Injection/Jailbreaking 练习 Playground。
- [La Guerre des Prompts (Devfest 2025)](https://github.com/pi-2r/devfest2025-La-Guerre-des-Prompts-attaques-et-defenses-au-royaume-des-LLM) - Devfest 2025 Prompt Injection 攻防实践项目。
- [Damn Vulnerable MCP](https://github.com/harishsg993010/damn-vulnerable-MCP-server) - MCP 漏洞教学项目，含 10 个挑战。
- [DamnVulnerableLLMProject](https://github.com/harishsg993010/DamnVulnerableLLMProject) - LLM 漏洞练习项目。
- [satml-llm-ctf](https://github.com/ethz-spylab/satml-llm-ctf) - LLM CTF 平台源码。
- [Prompt-Injection-Playground](https://github.com/svenmorgenrothio/Prompt-Injection-Playground) - Prompt Injection 练习 Playground。

## 区块链 / Web3 / 智能合约靶场

### 开源可部署
- [GOAT Casino](https://github.com/nccgroup/GOATCasino) - 可部署的区块链/智能合约漏洞练习项目。
- [Ethernaut (OpenZeppelin)](https://github.com/OpenZeppelin/ethernaut) - Ethernaut 关卡与合约源码。
- [Paradigm CTF](https://github.com/paradigm-operations/paradigm-ctf-2021) - Paradigm 出品的区块链 CTF 题目集。
- [Blocksec CTFs](https://github.com/blockthreat/blocksec-ctfs) - BlockSec 区块链 CTF 题目集。
- [DeFiVulnLabs](https://github.com/SunWeb3Sec/DeFiVulnLabs) - DeFi 漏洞练习与合约挑战集。
- [SmartSecRiddles](https://github.com/marjon-call/SmartSecRiddles) - 智能合约安全谜题/挑战集合。
- [Damn Vulnerable DeFi](https://github.com/OpenZeppelin/damn-vulnerable-defi) - DeFi 漏洞闯关练习。

### 在线挑战/平台
- [Capture the Ether](https://capturetheether.com/) - 以太坊智能合约安全挑战平台。
- [The Ethernaut](https://ethernaut.openzeppelin.com/) - 以太坊智能合约漏洞闯关平台。
- [Etherhack](https://etherhack.positive.com/) - 智能合约安全挑战平台。
- [ciphershastra CTF](https://ciphershastra.com/) - 区块链/密码学方向 CTF 平台。
- [Defi Hack](https://www.defihack.xyz/) - DeFi 安全挑战平台。
- [Gacha Lab (BSC Testnet)](https://gachalab.inspex.co/) - BSC 测试网智能合约安全实验平台。
- [Only Pwner](https://onlypwner.xyz/) - 区块链安全挑战平台。
- [QuillCTF](https://quillctf.super.site/) - 面向智能合约的学习与挑战平台。
- [Vulnmachines - Blockchain hacking](https://vulnmachines.com) - 区块链漏洞练习与挑战平台。
- [Damn Vulnerable DeFi (Site)](https://www.damnvulnerabledefi.xyz/) - DeFi 漏洞闯关练习官网。

### 资源/题库
- [ctf-blockchain](https://github.com/minaminao/ctf-blockchain) - 区块链 CTF 题目与资料汇总。

## 移动应用靶场

### 开源可部署（含 APK/源码）
- [EVABS](https://github.com/abhi-r3v0/EVABS) - 极度脆弱的 Android 漏洞实验室。
- [Goatlin](https://github.com/Checkmarx/Goatlin/) - 移动端漏洞练习应用。
- [Vuln-Bank](https://github.com/Commando-X/vuln-bank) - 用于练习 Web/API/AI 集成应用安全测试的脆弱银行应用。
- [VyAPI](https://github.com/appsecco/VyAPI) - 云端后端的脆弱混合 Android 应用。
- [Damn Vulnerable FirefoxOS App (DVFA)](https://github.com/arroway/dvfa) - FirefoxOS 漏洞应用。
- [Damn Vulnerable iOS App (DVIA)](https://damnvulnerableiosapp.com/) - iOS 漏洞应用。
- [ExploitMe Mobile Android Labs](https://securitycompass.github.io/AndroidLabs/) - Android 安全练习应用。
- [ExploitMe Mobile iPhone Labs](https://securitycompass.github.io/iPhoneLabs/) - iPhone 安全练习应用。
- [OWASP iGoat (GitHub)](https://github.com/OWASP/igoat) - iOS 渗透测试学习工具。
- [OWASP Goatdroid](https://github.com/jackMannino/OWASP-GoatDroid-Project) - Android 安全训练环境。
- [OWASP MSTG Hacking Playground](https://github.com/OWASP/MSTG-Hacking-Playground) - OWASP MSTG 移动漏洞练习集。
- [DIVA](https://github.com/payatu/diva-android) - 经典 Android 漏洞训练应用。
- [InsecureBankv2](https://github.com/dineshshetty/Android-InsecureBankv2) - Android 银行类漏洞靶场。
- [InsecureShop](https://github.com/optiv/InsecureShop) - Kotlin 漏洞练习应用。
- [AndroGoat](https://github.com/satishpatnayak/AndroGoat) - OWASP 风格 Android 训练应用。
- [Vuldroid](https://github.com/jaiswalakshansh/Vuldroid) - Android 漏洞示例应用。
- [DVIA-v2](https://github.com/prateek147/DVIA-v2) - Swift 版 iOS 漏洞应用。
- [OWASP iGoat-Swift](https://github.com/OWASP/iGoat-Swift) - Swift 版 iOS 训练应用。
- [DVHMA](https://github.com/logicalhacking/DVHMA) - Cordova 混合应用漏洞靶场。
- [OWASP MAS Crackmes](https://github.com/OWASP/mas-crackmes) - 移动逆向 Crackme 集合。
- [OWASP MSTG Android Crackmes](https://github.com/OWASP/owasp-mstg/tree/master/Crackmes/Android) - OWASP MSTG 提供的 Android Crackme 练习集。
- [InjuredAndroid](https://github.com/B3nac/InjuredAndroid) - CTF 风格的 Android 漏洞练习应用。
- [Damn Vulnerable Bank](https://github.com/rewanthtammana/Damn-Vulnerable-Bank) - Android 漏洞银行应用。
- [OVAA](https://github.com/oversecured/ovaa) - Oversecured Android 漏洞应用。
- [Android Security Testing (hpAndro1337)](https://github.com/RavikumarRamesh/hpAndro1337) - Kotlin 编写的 Android 漏洞练习应用。
- [Frida Labs](https://github.com/DERE-ad2001/Frida-Labs) - Android Frida 利用练习挑战集。
- [Oversecured Vulnerable iOS App](https://github.com/oversecured/OversecuredVulnerableiOSApp) - iOS 漏洞练习应用合集。

## 云 / 容器 / K8s 靶场

### 开源可部署
- [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat) - AWS 漏洞场景演练工具。
- [Damn Vulnerable Cloud Application](https://github.com/m6a-UdS/dvca.git) - 云应用漏洞练习靶场。
- [Unguard](https://github.com/dynatrace-oss/unguard) - 云原生微服务漏洞演示应用。
- [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat) - Kubernetes 安全练习环境。
- [Simulator](https://github.com/controlplaneio/simulator) - Kubernetes 安全训练平台（侧重防护演练）。
- [gRPC Goat](https://github.com/rootxjs/grpc-goat) - gRPC 安全练习靶场。
- [Metarget](https://github.com/Metarget/metarget) - 云原生攻防靶场自动化构建框架。
- [VulApps](https://github.com/Medicean/VulApps) - Docker 化漏洞环境集合。
- [Vulhub](https://github.com/vulhub/vulhub) - CVE/组件漏洞复现集合（Docker）。
- [Vulfocus](https://github.com/fofapro/vulfocus) - 漏洞环境管理与复现平台。
- [VulnRange](https://gitee.com/wgpsec/VulnRange) - 多靶场/漏洞环境管理平台。
- [vulstudy](https://gitee.com/gid1314/vulstudy) - Docker 化多靶场集合。
- [pentest_lab](https://github.com/oliverwiegers/pentest_lab) - Docker Compose 本地渗透实验室。
- [kube-goat](https://github.com/ksoclabs/kube-goat) - Kubernetes 漏洞练习环境。
- [k8s-labs](https://github.com/ProfessionallyEvil/k8s-labs) - Kubernetes 漏洞练习集。
- [minik8s-ctf](https://github.com/quarkslab/minik8s-ctf) - Kubernetes 入门 CTF。
- [k8s-ctf-rocks](https://github.com/NodyHub/k8s-ctf-rocks) - Kubernetes CTF 训练集。
- [kubernetes-ctf](https://github.com/thedojoseries/kubernetes-ctf) - Kubernetes CTF 演练项目。
- [kube-ctf](https://github.com/DownUnderCTF/kube-ctf) - Kubernetes CTF 基础设施。
- [kubernetes-ctf-samples](https://github.com/kyohmizu/kubernetes-ctf-samples) - Kubernetes CTF 示例题集。
- [OWASP EKS Goat](https://owasp.org/www-project-eks-goat) - AWS EKS 漏洞练习实验室。
- [OWASP GKE Goat](https://owasp.org/www-project-gke-goat/) - GKE 漏洞练习实验室。
- [OWASP Vulnerable Container Hub](https://github.com/owasp/vulnerable-container-hub) - 可构建的漏洞容器集合。
- [TerraGoat](https://github.com/bridgecrewio/terragoat) - Terraform 云配置漏洞练习。
- [CfnGoat](https://github.com/bridgecrewio/cfngoat) - CloudFormation 漏洞模板练习。
- [CDKGoat](https://github.com/bridgecrewio/cdkgoat) - AWS CDK 漏洞练习项目。
- [KustomizeGoat](https://github.com/bridgecrewio/kustomizegoat) - Kustomize 漏洞配置练习。
- [TerraformGoat](https://github.com/HXSecurity/TerraformGoat) - 多云 Terraform 漏洞练习。
- [tfgoat-aws](https://github.com/flatt-security/tfgoat-aws) - AWS Terraform 漏洞练习。
- [AWSGoat](https://github.com/ine-labs/AWSGoat) - AWS 漏洞场景练习。
- [CloudCommotion](https://github.com/SecurityRunners/cloudcommotion) - 基于 Terraform 的云端攻击/误配置模拟环境。
- [AzureGoat](https://github.com/ine-labs/AzureGoat) - Azure 漏洞场景练习。
- [Azure Goat (XMGoat)](https://github.com/XMCyber/XMGoat) - 含多种误配置的 Azure 脆弱环境。
- [GCPGoat](https://github.com/ine-labs/GCPGoat) - GCP 漏洞场景练习。
- [sadcloud](https://github.com/nccgroup/sadcloud) - AWS 不安全配置自动化练习。
- [IAM Vulnerable](https://github.com/BishopFox/iam-vulnerable) - AWS IAM 提权练习场景。
- [OWASP Serverless-Goat](https://github.com/OWASP/Serverless-Goat) - Serverless 漏洞练习项目。
- [OWASP DVSA](https://github.com/OWASP/DVSA) - Serverless 漏洞应用。
- [DVFaaS](https://github.com/we45/DVFaaS-Damn-Vulnerable-Functions-as-a-Service) - 可自部署的 AWS Lambda 漏洞函数练习项目。
- [Lambhack](https://github.com/wickett/lambhack) - AWS Lambda 脆弱 Serverless 应用。
- [CI/CD Goat](https://github.com/cider-security-research/cicd-goat) - CI/CD 安全练习环境。
- [GitHub Actions Goat](https://github.com/step-security/github-actions-goat) - GitHub Actions 漏洞练习环境。
- [GHA-Hazmat](https://github.com/woodruffw/gha-hazmat) - 可利用的 GitHub Actions 工作流/动作示例集。
- [CONVEX](https://github.com/Azure/CONVEX) - Azure CTF 环境与基础设施。
- [caponeme](https://github.com/avishayil/caponeme) - Capital One 云安全事件复现环境。
- [CNAPPgoat](https://github.com/ermetic-research/cnappgoat) - 多云 CNAPP 漏洞演练环境。
- [TerraGoat (5toCode)](https://github.com/5toCode/github-terragoat) - Terraform 漏洞配置练习项目。
- [GCP GOAT](https://github.com/JOSHUAJEBARAJ/GCP-GOAT) - GCP 漏洞环境练习项目。
- [GCP CTF Workshop](https://github.com/n0jam/gcp-ctf-workshop) - BSides NY 2024 的 GCP 漏洞训练环境。
- [EKS Goat](https://github.com/OWASP/www-project-eks-goat) - AWS EKS 安全实验室与练习。
- [Kubernetes Infrastructure Pentest Lab](https://github.com/raesene/kube_security_lab) - Kubernetes 基础设施渗透测试实操实验。
- [Scriptease](https://github.com/alexcolb/scriptease) - 无后端的脆弱 JavaScript SPA，演示多种客户端漏洞（XSS、开放重定向等）。
- [Security Labs & POCs](https://github.com/DataDog/security-labs-pocs) - 可自部署的云安全漏洞练习环境。
- [crAPI](https://owasp.org/www-project-crapi/) - OWASP crAPI：用于 API 安全练习的故意脆弱 API。

### 在线挑战/平台
- [CloudFoxable](https://cloudfoxable.bishopfox.com/) - 云安全闯关式练习平台。
- [flAWS](http://flaws.cloud/) - AWS 配置错误挑战赛。
- [flAWS2](http://flaws2.cloud/) - AWS/Serverless 进阶挑战。
- [K8s Lan Party](https://k8slanparty.com/) - Kubernetes 漏洞/误配置攻防 CTF。
- [EKS Cluster Games](https://eksclustergames.com/) - 基于 EKS 误配置的挑战集。
- [Thunder CTF Cloud](https://thunder-ctf.cloud/) - GCP 云安全攻防练习平台。
- [AWS CTF Challenge](https://bigiamchallenge.com/) - 面向 AWS 的 CTF 挑战。
- [AWS Security Workshop](https://wellarchitectedlabs.com/security/) - 交互式 AWS 安全最佳实践工作坊。
- [Azure AD CTF Challenge](https://www.brokenazure.cloud/) - 面向 Azure AD 的 CTF 挑战。
- [Azure Infrastructure Workshop](https://github.com/mandiant/Azure_Workshop) - 交互式 Azure 安全最佳实践工作坊。
- [EntraGoat](https://github.com/Semperis/EntraGoat) - 故意脆弱的 Microsoft Entra ID 环境，用于身份安全实战训练。
- [PwnedLabs](https://pwnedlabs.io/) - 云安全在线实验平台。

## 内网 / Active Directory (AD) 靶场

### 开源可部署
- [GOAD (Game Of Active Directory)](https://github.com/Orange-Cyberdefense/GOAD) - 完整的可部署 AD 攻防靶场。
- [adlab](https://github.com/jckhmr/adlab) - Vagrant/Ansible 构建 AD 实验室。
- [Vulnerable-AD-Lab](https://github.com/M507/Vulnerable-AD-Lab) - 自动化搭建脆弱 AD 环境。
- [ad-training-lab](https://github.com/brmkit/ad-training-lab) - Proxmox 自动化 AD 训练靶场。
- [Vulnerable-Active-Directory-Lab](https://github.com/reatva/Vulnerable-Active-Directory-Lab) - OSCP 风格 AD 靶场实践。
- [ADCSGoat](https://github.com/jakehildreth/ADCSGoat) - AD CS 漏洞练习靶场。

### 漏洞注入/生成器
- [vulnerable-AD](https://github.com/safebuffer/vulnerable-AD) - 将现有 AD 环境“注入漏洞”。
- [VulnADLab-Framework](https://github.com/titus-sec/VulnADLab-Framework) - 随机构建脆弱 AD 靶场。
- [BadBlood](https://github.com/davidprowe/BadBlood) - Active Directory 测试数据生成器。

### 检测/紫队靶场
- [DetectionLab](https://github.com/clong/DetectionLab) - AD + 日志采集的防守型实验室。
- [DetectionLabELK](https://github.com/cyberdefenders/DetectionLabELK) - ELK 版 DetectionLab。
- [Lab4PurpleSec](https://github.com/0xMR007/Lab4PurpleSec) - GOAD + DMZ 的紫队实验室。
- [PurpleCloud](https://github.com/iknowjason/PurpleCloud) - 云端/混合身份紫队实验室。

## 系统 / 二进制 / 逆向

### 开源可部署
- [Metasploitable2](https://sourceforge.net/projects/metasploitable/files/Metasploitable2/) - 系统级漏洞练习虚拟机。
- [VulnStack（红日靶场）](http://vulnstack.qiyuanxuetang.net/vuln/) - 内网渗透与域环境实战靶场。
- [NETinVM](https://informatica.uv.es/~carlos/docencia/netinvm/) - 网络与系统安全教学环境。
- [DVTA (Damn Vulnerable Thick Client App)](https://github.com/srini0x00/dvta) - C#/.NET 厚客户端漏洞练习应用。
- [BetaFast](https://github.com/NetSPI/BetaFast) - 在《桌面应用入门》博客系列中用作示例的易受攻击厚客户端应用。
- [GRFICS](https://github.com/djformby/GRFICS) - 工控网络仿真与安全实验平台。
- [GRFICSv2](https://github.com/Fortiphyd/GRFICSv2) - GRFICS 第二代实验环境。
- [GRFICSv3](https://github.com/mrideout/GRFICSv3) - GRFICS 第三代实验环境。
- [Metasploitable3](https://github.com/rapid7/metasploitable3) - 新一代 Metasploitable 漏洞 VM。
- [Vulnerable Kext](https://github.com/ant4g0nist/Vulnerable-Kext) - iOS/macOS 内核扩展漏洞练习。
- [VuCSA](https://github.com/Warxim/vucsa) - Java 客户端/服务端漏洞练习应用。
- [HEVD](https://github.com/hacksysteam/HackSysExtremeVulnerableDriver) - Windows 内核驱动漏洞练习。
- [Fuzzgoat](https://github.com/fuzzstati0n/fuzzgoat) - 用于模糊测试的脆弱 C 程序。
- [Vulnserver](https://github.com/stephenbradshaw/vulnserver) - 漏洞服务器用于软件利用练习。
- [Damn Vulnerable C Program](https://github.com/hardik05/Damn_Vulnerable_C_Program) - 常见漏洞示例 C 程序。
- [exploit_me](https://github.com/bkerler/exploit_me) - ARM/ARM64 漏洞利用练习项目。

### 在线挑战
- [Reversing.kr](http://reversing.kr/) - 逆向工程在线挑战平台。
- [Pwnable.kr](http://pwnable.kr/) - 二进制漏洞挑战平台。
- [Pwnable.tw](http://pwnable.tw/) - Pwn/二进制挑战平台。
- [PwnAdventure](https://pwnadventure.com) - 带漏洞的在线游戏挑战。
- [Under the Wire](https://underthewire.tech/) - PowerShell 闯关式安全训练平台。

## IoT / 工控 / ICS 靶场

### 开源可部署
- [OWASP IoTGoat](https://github.com/OWASP/IoTGoat) - IoT 固件漏洞练习靶场。
- [IoT-vulhub](https://github.com/Vu1nT0tal/IoT-vulhub) - IoT 固件漏洞复现环境，提供多种固件模拟方式的 Docker Compose。
- [FirmAE](https://github.com/pr0v3rbs/FirmAE) - 固件仿真分析工具。
- [BLE CTF](https://github.com/hackgnar/ble_ctf) - BLE 安全练习 CTF 项目。
- [DVID (Damn Vulnerable IoT Device)](https://github.com/Vulcainreo/DVID) - 可构建的 IoT 漏洞设备项目。
- [Damn-Vuln-IoT-SoC](https://github.com/damn-vuln-iot-soc/damn-vuln-iot-soc) - 硬件/SoC 漏洞训练平台。
- [ICSGoat](https://github.com/ine-labs/ICSGoat) - ICS/SCADA 漏洞演练靶场。
- [ICSSIM](https://github.com/AlirezaDehlaghi/ICSSIM) - ICS 安全实验模拟平台。
- [Digital Bond Basecamp](https://github.com/digitalbond/Basecamp) - PLC/ICS 漏洞演练与脚本集合。
- [ICS-SCADA Vulnerable Virtual Lab](https://github.com/TheWardonianEffect/ICS-SCADA-Vulnerable-Virtual-Lab) - SCADA/工控漏洞实验室。
- [ICS Pentest Lab Example](https://github.com/yigitcantunay35/ICS_Pentest_Lab_Example) - ICS 渗透实验环境示例。
- [DVRF](https://github.com/praetorian-inc/DVRF) - 路由器固件漏洞练习项目。
- [Raspwn OS](https://github.com/alphacharlie/raspwn/) - Raspberry Pi 脆弱系统镜像。

### 在线平台
- [ICS Range](https://www.icsrange.com/) - 工控/OT 在线训练平台。
- [Cloud Range (OT/ICS)](https://www.cloudrangecyber.com/critical-infrastructure) - 关键基础设施安全训练平台。
- [Labshock](https://www.labshocksecurity.com/) - OT/ICS 安全实验平台。
- [Fortiphyd Logic](https://learn.fortiphyd.com/) - 工控/赛博物理安全训练平台。

## CTF / 在线挑战平台

### 开源可部署（CTF 平台/框架）
- [CTFd](https://github.com/isislab/CTFd) - CTF 平台开源框架。
- [Mellivora](https://github.com/Nakiami/mellivora) - PHP 编写的 CTF 引擎。
- [NightShade](https://github.com/UnrealAkama/NightShade) - 轻量 CTF 框架。
- [CTF Challenges (Probely)](https://github.com/Probely/CTF-Challenges) - 安全 CTF 题目集合。

### 开源可部署（题库/数据集）
- [InterCode-CTF](https://intercode-benchmark.github.io/) - picoCTF 题目集（约 100 题，偏高中难度），覆盖密码学/Web/PWN/逆向/取证/杂项。
- [NYU CTF Bench](https://nyu-llm-ctf.github.io/) - CSAW 2017-2023 题目集（约 200 题），难度从入门到困难，覆盖密码学/Web/PWN/逆向/取证/杂项。
- [CyBench](https://cybench.github.io/) - 来自 HackTheBox、Sekai CTF、Glacier、HKCert（2022-2024）的 40 个任务，按首次解题时间（FST）标注难度。
- [pwn.college CTF Archive](https://github.com/pwncollege/ctf-archive) - 可运行的 CTF 题目集合，常用于研究语料。

### 在线挑战平台（中国）
- [NSSCTF](https://www.nssctf.cn/index) - 中国 CTF 刷题与比赛平台。
- [BUUCTF / BUUOJ](https://buuoj.cn/) - 中国常用 CTF 平台。
- [CTFshow](https://ctf.show/) - Web/CTF 练习平台。
- [CTFHub](https://www.ctfhub.com/#/index) - CTF 训练平台与靶场。
- [攻防世界（XCTF）](https://adworld.xctf.org.cn/home/index) - XCTF 线上训练与比赛平台。
- [Bugku](https://ctf.bugku.com/) - CTF 题库与比赛平台。
- [看雪CTF](https://ctf.kanxue.com/) - 逆向与安全挑战平台。
- [合天网安 CTF](https://www.hetianlab.com/) - 中国在线 CTF 练习平台。

### 在线挑战平台（国际）
- [Embedded Security CTF](https://microcorruption.com) - 嵌入式安全挑战平台。
- [EnigmaGroup](http://www.enigmagroup.org/) - 在线安全挑战平台。
- [Escape](http://escape.alf.nu/) - XSS 主题挑战。
- [Hack The Box](https://www.hackthebox.com/) - 攻防靶机与挑战平台。
- [TryHackMe](https://tryhackme.com/) - 路径化安全训练平台。
- [Hack This Site](http://www.hackthissite.org/) - 经典在线黑客挑战平台。
- [HackThis](http://www.hackthis.co.uk/) - 在线安全挑战平台。
- [Hack.me](https://hack.me) - 在线漏洞应用与挑战平台。
- [Hacking-Lab](https://www.hacking-lab.com) - 在线安全训练平台。
- [Hacker Test](http://www.hackertest.net/) - 在线安全挑战平台。
- [Hax.Tor](http://hax.tor.hu/) - 安全挑战站点。
- [OverTheWire](http://www.overthewire.org/wargames/) - 经典 wargame 系列。
- [Hack arrrg](https://hack.arrrg.de/) - 在线安全挑战平台。
- [Netgarage Wargame](https://io.netgarage.org/) - Wargame 挑战站点。
- [Root Me](http://www.root-me.org/?lang=en) - 多方向安全挑战平台。
- [RootTheBox](https://github.com/moloch--/RootTheBox) - RootTheBox 练习平台。
- [Smash The Stack](http://www.smashthestack.org/) - Wargame 挑战平台。
- [TheBlackSheep and Erik](http://www.bright-shadows.net/) - 多方向安全挑战平台。
- [ThisIsLegal](http://thisislegal.com/) - 综合挑战与教程站点。
- [Try2Hack](http://www.try2hack.nl/) - 经典安全挑战站点。
- [XSS Challenges](http://xss-quiz.int21h.jp/) - XSS 在线挑战集。
- [XSS Game](https://xss-game.appspot.com/) - XSS 训练游戏。
- [XSS: ProgPHP](http://xss.progphp.com/) - XSS 挑战站点。
- [alert(1) to win](https://alf.nu/) - XSS 主题挑战平台。
- [PicoCTF](https://picoctf.com/) - 青少年向 CTF 平台。
- [CTF Learn](http://ctflearn.com/) - 用户贡献题库的 CTF 平台。
- [w3challs](https://w3challs.com/) - Web 安全挑战平台。
- [WeChall](https://www.wechall.net/) - Wargame/挑战平台与社区。
- [RingZer0 Team](https://ringzer0team.com/) - 在线 CTF 平台。
- [HellBound Hackers](http://www.hellboundhackers.org/) - 综合挑战平台。
- [Komodo Consulting](http://ctf.komodosec.com) - 应用安全挑战。
- [pwn.college](https://pwn.college/) - 系统/二进制方向在线训练平台。
- [Webhacking.kr](https://webhacking.kr/) - Web 安全在线挑战平台。
- [Hacker101 CTF](https://ctf.hacker101.com/) - HackerOne 官方练习平台。
- [CMD Challenge](https://cmdchallenge.com/) - 命令行挑战练习平台。
- [Exploit Education](https://exploit.education/) - 二进制与系统漏洞练习平台。
- [The Cryptopals Crypto Challenges](https://cryptopals.com/) - 密码学挑战合集。
- [CryptoHack](https://cryptohack.org/) - 密码学专项练习平台。
- [247CTF](https://247ctf.com/) - 在线 CTF 练习平台。
- [247CTF Dashboard](https://247ctf.com/dashboard) - 247CTF 练习控制台入口。
- [Lord of SQL Injection](https://los.rubiya.kr/) - SQL 注入闯关平台。
- [HackMyVM](https://hackmyvm.eu/) - 靶机与挑战平台。

## 安全厂商 Demo / 漏洞演示站

### 厂商公开演示
- [Acunetix acuforum](https://testasp.vulnweb.com/) - Acunetix 漏洞演示论坛站。
- [Acunetix acublog](https://testaspnet.vulnweb.com/) - Acunetix 漏洞演示博客站。
- [Acunetix acuart](https://testphp.vulnweb.com/) - Acunetix PHP 漏洞演示站。
- [Acunetix REST API](http://rest.vulnweb.com/) - Acunetix REST API 漏洞演示站。
- [Acunetix SecurityTweets](http://testhtml5.vulnweb.com) - Acunetix HTML5 漏洞演示站。
- [Fortify Zero Bank](http://zero.webappsecurity.com) - Fortify 漏洞演示银行站。
- [Fortify IWA.NET](https://github.com/fortify/IWA-DotNet) - Fortify .NET 漏洞示例应用。
- [Fortify IWA.JAVA](https://github.com/fortify/IWA-Java) - Fortify Java 漏洞示例应用。
- [IBM altoromutual](http://demo.testfire.net/) - IBM 漏洞演示站。
- [Mavituna testsparker (ASP.NET)](http://aspnet.testsparker.com) - Netsparker 漏洞演示站（ASP.NET）。
- [Mavituna testsparker (PHP)](http://php.testsparker.com) - Netsparker 漏洞演示站（PHP）。
- [Mavituna testsparker (Angular)](http://angular.testsparker.com) - Netsparker 漏洞演示站（Angular）。

## 综合实验室 / 课程式靶场

### 开源可部署
- [MCIR (Magical Code Injection Rainbow)](https://github.com/SpiderLabs/MCIR) - 可配置漏洞测试床框架。
- [CryptOMG](https://github.com/SpiderLabs/CryptOMG) - 密码学漏洞测试床。
- [SocengLab](https://github.com/dalpan/Pretexta) - 社工模拟训练平台。
- [CiLocks](https://github.com/tegal1337/CiLocks) - 漏洞练习项目。
- [IHA089 Labs](https://github.com/IHA089/IHA089-LABS) - 覆盖常见漏洞（SQLi/XSS/爆破等）的练习实验室集合。
- [OWASP Mantra](https://sourceforge.net/projects/getmantra/) - 浏览器集成式安全工具框架。
- [OWASP VulnCodeLab](https://owasp.org/www-project-vulncodelab/) - 安全编码与代码审计训练平台。
- [OWASP SamuraiWTF](https://www.samuraiwtf.org/) - Web 安全训练 VM/工具集。
- [OWASP SKF labs](https://github.com/blabla1337/skf-labs) - OWASP SKF Docker 实验示例集。
- [Google Security Testbeds](https://github.com/google/security-testbeds) - 漏洞扫描测试床资源集合。
- [DVXTE](https://github.com/davevs/dvxte) - Docker 打包多漏洞应用的训练环境，便于重置。
- [Digital Forensics Lab](https://github.com/frankwxu/digital-forensics-lab) - 数字取证实训实验室（教学用途）。
- [log-snare](https://github.com/sea-erkin/log-snare) - 日志安全分析与检测练习项目。
- [DamnVulnerableCryptoApp](https://github.com/DamnVulnerableCryptoApp/DamnVulnerableCryptoApp) - 不安全密码学实现练习应用。

### 代码审计 / 安全编码训练
- [java-sec-code](https://github.com/JoyChou93/java-sec-code) - Java 漏洞代码与安全编码示例。
- [Hello-Java-Sec](https://github.com/j3ers3/Hello-Java-Sec) - Java 安全学习与漏洞示例。
- [JavaSecLab](https://github.com/whgojp/JavaSecLab) - 综合 Java 漏洞平台（漏洞代码/修复示例/SINK 点）。
- [JavaVulnerableLab](https://github.com/CSPF-Founder/JavaVulnerableLab) - Java 漏洞练习平台。
- [Java Goof](https://github.com/snyk-labs/java-goof) - Java 漏洞应用与依赖演示。
- [OWASP VulnerableApp](https://github.com/SasanLabs/VulnerableApp) - Java/Spring 漏洞训练应用。
- [python_security](https://github.com/gbleaney/python_security) - Python 安全 API 与利用示例清单。
- [Vulnerable Code Snippets](https://github.com/yeswehack/vulnerable-code-snippets) - 多类漏洞代码片段集（Docker 化隔离练习）。
- [VulnPlanet](https://github.com/yevh/VulnPlanet) - 含修复方案的多领域漏洞代码片段集（Web/API/移动/IaC 等）。
- [Vulnerable Codes](https://vulnerable.codes/) - 基于真实案例的漏洞源码分析练习平台。

### 在线实验室 / 课程平台
- [Blue Team Labs Online](https://blueteamlabs.online/) - 蓝队调查/取证/威胁狩猎训练平台。
- [Google Gruyere](http://google-gruyere.appspot.com/) - Web 漏洞学习演示平台。
- [Forensic Practical](http://www.forensickb.com/2008/01/forensic-practical.html) - 取证与恶意代码分析实践。
- [Gh0st Lab](http://www.gh0st.net/) - 安全研究与挑战社区。
- [HackQuest](http://www.hackquest.com/) - 安全学习相关的资源与服务入口。
- [Security Treasure Hunt](http://www.securitytreasurehunt.com/) - 抓包分析挑战。
- [Maxkersten Binary Analysis](https://maxkersten.nl/binary-analysis-course/) - 二进制分析课程。
- [INE](https://ine.com/) - 实战型安全培训平台。
- [Hacksplaining](https://www.hacksplaining.com/) - 常见漏洞交互式课程。
- [Google Phishing Quiz](https://phishingquiz.withgoogle.com) - 钓鱼识别在线测验。
- [LabEx](https://labex.io/skilltrees/cybersecurity) - 在线实验与技能树平台。
- [Arizona Cyber Warfare Range](http://azcwr.org/az-cyber-warfare-ranges) - 网络攻防训练范围平台。
- [Hack The Box Academy](https://academy.hackthebox.com/) - HTB 课程与实验平台。
- [Offensive Security Proving Grounds](https://www.offensive-security.com/labs/individual/) - Offensive Security 训练靶场。
- [VulnHub](https://vulnhub.com/) - 可下载靶机与挑战集合。
- [PwnTillDawn Online Battlefield](https://online.pwntilldawn.com/) - 在线渗透训练靶场。
- [CyberDefenders](https://cyberdefenders.org/) - 蓝队实战训练平台。
- [LetsDefend](https://letsdefend.io/) - SOC/蓝队训练平台。
- [RangeForce](https://www.rangeforce.com/) - 企业级蓝队训练平台。
- [Immersive Labs](https://www.immersivelabs.com/) - 企业级安全训练平台。

### 商业（含试用/训练平台）
- [春秋云境](https://yunjing.ichunqiu.com/) - 中国渗透与场景化训练平台。
- [玄机靶场](https://xj.edisec.net/) - 中国在线实训平台。
- [墨者学院靶场](https://www.mozhe.cn/bug) - 在线实战靶场与课程。
- [封神台](https://hack.zkaq.cn/battle) - 在线攻防训练平台。
- [东塔在线靶场](https://labs.do-ta.com/index/course/index) - 课程式在线靶场。
- [MS08067 实战型训练平台](http://bachang.ms08067.com) - 在线实战训练平台。

### 环境/基础设施工具
- [Vagrant](https://www.vagrantup.com/) - 可复用的开发/实验环境管理工具。
- [SmartOS](https://smartos.org/) - 开源虚拟化系统。
- [vSphere Hypervisor](https://www.vmware.com/products/vsphere-hypervisor/) - 商业虚拟化平台。
- [GNS3](http://sourceforge.net/projects/gns-3/) - 网络仿真与实验工具。
- [XAMPP](https://www.apachefriends.org/index.html) - 本地 Web 服务栈。

## 安全基准测试 / 数据集

### 基准测试 / 评测套件
- [Kalm Benchmark](https://github.com/dynatrace-oss/Kalm-Benchmark) - Kubernetes 安全扫描器评测与分析平台，含多类脆弱清单与对比仪表盘。
- [OWASP BenchmarkJava](https://github.com/OWASP-Benchmark/BenchmarkJava) - OWASP 基准测试套件，用于验证漏洞检测工具的速度与准确性（可运行 Java Web 应用）。
- [OWASP BenchmarkUtils](https://github.com/OWASP-Benchmark/BenchmarkUtils) - OWASP Benchmark 工具集，提供评分卡生成与爬取工具。
- [OWASP BenchmarkPython](https://github.com/OWASP-Benchmark/BenchmarkPython) - 面向 Python 工具的 OWASP Benchmark 测试套件。
- [Open Prompt Injection](https://github.com/liu00222/Open-Prompt-Injection) - LLM Prompt Injection 攻防基准测试。
- [PINT Benchmark](https://github.com/lakeraai/pint-benchmark) - Prompt Injection 检测系统基准测试。
- [leaky-repo](https://github.com/Plazmaz/leaky-repo) - 密钥泄露扫描基准仓库。
- [Terrabuck](https://github.com/SymbioticSec/terrabuck) - 面向安全工具评测的脆弱 IaC 模板集合。
- [javascript-cwe-codeql](https://github.com/StackOverflowIsBetterThanAnyAI/javascript-cwe-codeql) - 用于 SAST 基准测试的 JavaScript 漏洞代码片段集。
- [ZagBench](https://github.com/Zag-Research/ZagBench) - 动态语言的基准测试套件。
- [python-benchmark-tasks](https://github.com/saiajith-muduthanapelli/python-benchmark-tasks) - Python 基准测试任务集合。

## 旧版本软件与辅助资源

### 漏洞资料库与旧版本下载
- [Old Version](http://www.oldversion.com/) - 旧版本软件下载站。
- [Exploit-DB](https://www.exploit-db.com/) - 漏洞利用与 Exploit 数据库。
- [PortableApps](http://www.PortableApps.com/) - 便携软件资源库。

### 导航/资源合集
- [Hello CTF 快速开始](https://hello-ctf.com/hc-start/) - 中国 CTF/靶场导航入口。
- [CTFtime](https://ctftime.org/) - CTF 赛事日历与排行平台。
- [Sploitcraft](https://github.com/R3DRUN3/sploitcraft) - 攻击指南、演示与 PoC 集合。
- [LLM Attacks](https://github.com/llm-attacks/llm-attacks) - LLM 攻击样本与方法集合。
- [渊龙Sec 安全团队导航](https://dh.aabyss.cn/) - 安全资源导航。
- [OWASP Vulnerable Web Applications Directory](https://owasp.org/www-project-vulnerable-web-applications-directory/) - OWASP 漏洞应用目录。
- [Vulhub 官方站](https://vulhub.org) - 漏洞环境集合与文档入口。
- [WeChall 活跃挑战站点](https://www.wechall.net/active_sites) - CTF/闯关站点索引。
- [CTF Sites Directory](https://ctfsites.github.io/) - 永久在线 CTF 平台目录。
- [SudoNinjaBook 云安全靶场目录](https://sudoninja.gitbook.io/sudoninjabook/security-area/cloud-security/vulnerable-cloud-labs) - 云安全靶场索引。
- [Awesome Mobile CTF](https://github.com/xtiankisutsa/awesome-mobile-CTF) - 移动安全靶场/题库索引。
- [Awesome Cloud Security Labs](https://github.com/iknowjason/Awesome-CloudSec-Labs) - 云安全靶场索引。
- [Awesome DVA](https://github.com/rarecoil/awesome-dva) - 可下载靶场/VM 索引。
- [Awesome Damn Vulnerable Applications](https://github.com/yogikortisa/awesome-damn-vulnerable-applications) - DVA 清单合集。
- [Awesome AI Security](https://github.com/ottosulin/awesome-ai-security) - AI 安全资源索引。
- [Awesome LLMSecOps](https://github.com/wearetyomsmnv/Awesome-LLMSecOps) - LLM 安全实践与平台清单。


## 收录标准
- **相关性**：与漏洞学习、渗透测试练习、攻防演练教学直接相关（vulnerable-by-design 或明确提供练习环境）。
- **可用性**：提供可访问的在线演示链接，或提供明确的自部署方式（文档/镜像/源码）。
- **描述完整**：至少包含名称、链接、一句话描述、标签。
- **信息透明**：尽量标注收费/交付方式；无法确认时可省略。
- **表达克制**：描述保持客观、中性、简短。

## 免责声明
- 本清单仅用于安全研究与教育目的；请仅在获得明确授权的系统与环境中进行测试。
- 对第三方在线演示站点，请遵守其使用条款，避免影响服务可用性。
- 维护者与贡献者不对任何不当使用造成的后果负责。

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md).
