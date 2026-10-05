# 载荷分类全量索引 · Payloads Index

> 本索引完整收录源项目 [swisskyrepo/PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) 根目录下的 **全部 64 个载荷 / 漏洞分类目录**。
> 统计口径：GitHub API 根目录列表中 `type=dir` 共 67 个，排除 `.github`、`_LEARNING_AND_SOCIALS`、`_template_vuln` 三个内部 / 元目录后得到 64 个（2026-10-05 实测）。

| # | 中文分类 | 英文原名 | 一句话用途 | 源目录 |
| --- | --- | --- | --- | --- |
| 1 | API 密钥泄露 | API Key Leaks | 扫描与利用泄露的 API Key / Token 等凭据 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/API%20Key%20Leaks) |
| 2 | 账户接管 | Account Takeover | 各类导致攻击者接管用户账户的缺陷利用 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Account%20Takeover) |
| 3 | 爆破与速率限制 | Brute Force Rate Limit | 凭据爆破与限速 / 验证码绕过手法 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Brute%20Force%20Rate%20Limit) |
| 4 | 业务逻辑漏洞 | Business Logic Errors | 破坏业务流程与信任关系的逻辑缺陷 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Business%20Logic%20Errors) |
| 5 | CORS 跨域配置错误 | CORS Misconfiguration | 错误的跨域资源共享策略导致数据泄露 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CORS%20Misconfiguration) |
| 6 | CRLF 注入 | CRLF Injection | 注入回车换行篡改响应头与响应体 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CRLF%20Injection) |
| 7 | CSS 注入 | CSS Injection | 注入样式表实现数据窃取与钓鱼 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CSS%20Injection) |
| 8 | CSV 公式注入 | CSV Injection | 导出 CSV 时注入表格公式触发客户端执行 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CSV%20Injection) |
| 9 | CVE 漏洞利用 | CVE Exploits | 重要 CVE 漏洞的公开 PoC 与利用链 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CVE%20Exploits) |
| 10 | 点击劫持 | Clickjacking | 用透明iframe诱导用户点击的界面欺骗 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Clickjacking) |
| 11 | 客户端路径穿越 | Client Side Path Traversal | 前端文件读取 / 打包机制中的路径穿越 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Client%20Side%20Path%20Traversal) |
| 12 | 命令注入 | Command Injection | 注入并拼接操作系统命令执行任意指令 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Command%20Injection) |
| 13 | 跨站请求伪造 CSRF | Cross-Site Request Forgery | 诱导已登录用户发起非预期请求 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Cross-Site%20Request%20Forgery) |
| 14 | DNS 重绑定 | DNS Rebinding | 通过 DNS 切换绕过同源策略访问内网 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/DNS%20Rebinding) |
| 15 | DOM 覆盖 | DOM Clobbering | 用 HTML 属性覆盖全局变量影响前端逻辑 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/DOM%20Clobbering) |
| 16 | 拒绝服务 DoS | Denial of Service | 耗尽目标资源导致服务不可用的手法 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Denial%20of%20Service) |
| 17 | 依赖混淆 | Dependency Confusion | 抢占内部依赖包名投毒供应链 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Dependency%20Confusion) |
| 18 | 目录穿越 | Directory Traversal | ../ 遍历读取服务器任意文件 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Directory%20Traversal) |
| 19 | 编码变换绕过 | Encoding Transformations | 各类编码 / 解码用于 WAF 与过滤绕过 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Encoding%20Transformations) |
| 20 | 外部变量修改 | External Variable Modification | 通过外部输入篡改应用内部变量 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/External%20Variable%20Modification) |
| 21 | 文件包含 LFI/RFI | File Inclusion | 本地 / 远程文件包含读取与包含恶意文件 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/File%20Inclusion) |
| 22 | GWT 反序列化 | Google Web Toolkit | Google Web Toolkit 序列化 gadget 利用 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Google%20Web%20Toolkit) |
| 23 | GraphQL 注入 | GraphQL Injection | GraphQL 接口内的注入与内省查询攻击 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/GraphQL%20Injection) |
| 24 | HTTP 参数污染 HPP | HTTP Parameter Pollution | 重复参数污染绕过过滤与鉴权 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/HTTP%20Parameter%20Pollution) |
| 25 | 无头浏览器利用 | Headless Browser | 在无头浏览器 / 沙箱中执行的绕过技术 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Headless%20Browser) |
| 26 | 隐藏参数挖掘 | Hidden Parameters | 发现未公开的隐藏接口参数 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Hidden%20Parameters) |
| 27 | 不安全反序列化 | Insecure Deserialization | 反序列化 gadget 链导致 RCE | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Deserialization) |
| 28 | 不安全直接对象引用 IDOR | Insecure Direct Object References | 越权访问 / 操作他人对象数据 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Direct%20Object%20References) |
| 29 | 不安全管理接口 | Insecure Management Interface | 暴露的后台 / 管理面板弱鉴权访问 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Management%20Interface) |
| 30 | 弱随机数 | Insecure Randomness | 可预测随机数用于 Token / 会话伪造 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Randomness) |
| 31 | 不安全源码管理 | Insecure Source Code Management | 泄露的 Git / 源码仓库信息获取 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Source%20Code%20Management) |
| 32 | JWT 令牌攻击 | JSON Web Token | JWT 弱密钥 / 算法混淆 / 未校验绕过 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/JSON%20Web%20Token) |
| 33 | Java RMI 反序列化 | Java RMI | Java RMI 服务反序列化远程利用 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Java%20RMI) |
| 34 | LDAP 注入 | LDAP Injection | 注入 LDAP 过滤器绕过认证与查询 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/LDAP%20Injection) |
| 35 | LaTeX 注入 | LaTeX Injection | 注入 LaTeX 模板实现命令执行 / 读文件 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/LaTeX%20Injection) |
| 36 | 批量赋值 | Mass Assignment | 批量传参篡改不应被修改的对象字段 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Mass%20Assignment) |
| 37 | 测试方法论与资源 | Methodology and Resources | 渗透测试流程、清单与学习资源 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Methodology%20and%20Resources) |
| 38 | NoSQL 注入 | NoSQL Injection | MongoDB 等 NoSQL 查询注入绕过 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/NoSQL%20Injection) |
| 39 | OAuth 配置错误 | OAuth Misconfiguration | OAuth 流程缺陷导致账户劫持 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/OAuth%20Misconfiguration) |
| 40 | ORM 泄漏 | ORM Leak | ORM 框架错误信息泄漏数据库结构 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/ORM%20Leak) |
| 41 | 开放重定向 | Open Redirect | 可控跳转用于钓鱼与令牌窃取 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Open%20Redirect) |
| 42 | 提示词注入 | Prompt Injection | 针对 LLM 应用的 Prompt 注入攻击 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Prompt%20Injection) |
| 43 | 原型链污染 | Prototype Pollution | 污染 Object.prototype 引发 XSS / RCE | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Prototype%20Pollution) |
| 44 | 竞态条件 | Race Condition | 并发竞争条件突破一次性 / 限额逻辑 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Race%20Condition) |
| 45 | 正则表达式 ReDoS | Regular Expression | 病态正则导致正则拒绝服务 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Regular%20Expression) |
| 46 | 请求走私 | Request Smuggling | HTTP 请求走私污染代理间请求 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Request%20Smuggling) |
| 47 | 反向代理配置错误 | Reverse Proxy Misconfigurations | 反代绕过访问受保护后端 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Reverse%20Proxy%20Misconfigurations) |
| 48 | SAML 注入 | SAML Injection | SAML 断言伪造与 XML 签名绕过 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/SAML%20Injection) |
| 49 | SQL 注入 | SQL Injection | 注入 SQL 语句拖库 / 绕登录 / 盲注 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/SQL%20Injection) |
| 50 | 服务端包含 SSI | Server Side Include Injection | SSI 注入在服务器端执行命令 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Include%20Injection) |
| 51 | 服务端请求伪造 SSRF | Server Side Request Forgery | 诱导服务器发起请求访问内网 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Request%20Forgery) |
| 52 | 服务端模板注入 SSTI | Server Side Template Injection | 模板引擎注入实现 RCE | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Template%20Injection) |
| 53 | 标签页劫持 | Tabnabbing | 利用 target=_blank 劫持原标签页 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Tabnabbing) |
| 54 | 弱类型比较 | Type Juggling | 松散类型比较绕过登录与校验 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Type%20Juggling) |
| 55 | 不安全文件上传 | Upload Insecure Files | 绕过上传校验上传可执行 Webshell | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Upload%20Insecure%20Files) |
| 56 | 虚拟主机枚举 | Virtual Hosts | 枚举虚拟主机发现隐藏站点 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Virtual%20Hosts) |
| 57 | Web 缓存欺骗 | Web Cache Deception | 骗缓存服务器缓存敏感响应 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Web%20Cache%20Deception) |
| 58 | WebSocket 安全 | Web Sockets | WebSocket 跨站与鉴权缺陷利用 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Web%20Sockets) |
| 59 | XPath 注入 | XPATH Injection | 注入 XPath 查询遍历 XML 数据 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XPATH%20Injection) |
| 60 | XS-Leak 侧信道 | XS-Leak | 跨站泄漏侧信道窃取敏感状态 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XS-Leak) |
| 61 | XSLT 注入 | XSLT Injection | XSLT 转换注入实现代码执行 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSLT%20Injection) |
| 62 | 跨站脚本 XSS | XSS Injection | 注入脚本在受害者浏览器执行 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSS%20Injection) |
| 63 | XML 外部实体注入 XXE | XXE Injection | XML 外部实体读文件 / SSRF | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XXE%20Injection) |
| 64 | Zip Slip 解压穿越 | Zip Slip | 压缩包解压路径穿越写任意文件 | [源目录](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Zip%20Slip) |

---

- 在线浏览全部载荷：<https://swisskyrepo.github.io/PayloadsAllTheThings/>
- 每个分类目录内含：README.md（漏洞原理 + 利用载荷）、Intruder（Burp 字典）、Images、Files。
- 中文分类名与用途说明为本地翻译整理，技术细节以源仓库英文原文为准。
