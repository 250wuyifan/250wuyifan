<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:2f80ed&height=200&section=header&text=&fontSize=1" width="100%" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=2F80ED&center=true&vCenter=true&random=false&width=500&lines=%E5%98%BF%EF%BC%8C%E6%88%91%E6%98%AF+Changmen+%F0%9F%91%8B;%E5%AE%89%E5%85%A8%E7%A0%94%E7%A9%B6%E5%91%98;%E9%80%86%E5%90%91%E5%B7%A5%E7%A8%8B%E5%B8%88;AI+%E5%AE%89%E5%85%A8%E5%BB%BA%E9%80%A0%E8%80%85" alt="Typing SVG" />

<br/>

<samp>Windows 攻防研发 · AI 安全研究 · 进程注入 · 内核漏洞利用</samp>

<br/><br/>

[![GitHub](https://img.shields.io/badge/250wuyifan-%23121011.svg?style=flat-square&logo=github&logoColor=white)](https://github.com/250wuyifan)
[![Email](https://img.shields.io/badge/ProtonMail-8B89CC?style=flat-square&logo=protonmail&logoColor=white)](mailto:changmen@protonmail.com)
[![Twitter](https://img.shields.io/badge/@changmensec-%231DA1F2.svg?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/changmensec)
[![Telegram](https://img.shields.io/badge/@changmenlabs-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/changmenlabs)
[![Blog](https://img.shields.io/badge/blog.changmen.io-FF5722?style=flat-square&logo=hugo&logoColor=white)](https://blog.changmen.io)

</div>

<br/>

## `$ whoami`

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│   Changmen / 250wuyifan                                      │
│                                                              │
│   > 安全研究员 & 逆向工程师                                    │
│   > 专注于 Windows 系统内核 & AI 安全领域                      │
│   > 构建攻击工具 & 防御方案                                    │
│                                                              │
│   研究方向:                                                   │
│     [■■■■■■■■░░]  进程注入 & 线程劫持                          │
│     [■■■■■■■░░░]  BYOVD & 内核驱动滥用                        │
│     [■■■■■■░░░░]  AI/LLM 安全 & 红队测试                      │
│     [■■■■■░░░░░]  Shellcode & 反分析对抗                      │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

<br/>

## <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 代表项目

<table>
<tr>
<td width="50%">

### <img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white" /> Windows 攻防研究

| 项目 | 技术栈 |
|:--------|:-----|
| **[WaitingThreadInject](https://github.com/250wuyifan/WaitingThreadInject)** <br/> <sub>等待线程劫持 — 栈返回地址重定向实现低噪声注入</sub> | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black) `线程劫持` `ZwWriteVirtualMemory` |
| **[BYOVD-终止进程](https://github.com/250wuyifan/byovd-%E7%BB%88%E6%AD%A2%E8%BF%9B%E7%A8%8B)** <br/> <sub>利用漏洞驱动 DeviceIoControl 绕过保护终止进程</sub> | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black) `BYOVD` `IOCTL` `内核` |
| **[BeaconGuard](https://github.com/250wuyifan/BeaconGuard)** <sup>开发中</sup> <br/> <sub>Hook VirtualAlloc/Sleep 捕获 Shellcode 并恢复上下文</sub> | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black) `Detours` `反Shellcode` |
| **[APC-Injection](https://github.com/250wuyifan/APC-injection)** <br/> <sub>APC 注入 / 早鸟 APC 注入，支持 DLL 和 Shellcode</sub> | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black) `APC注入` `免杀` |

</td>
<td width="50%">

### <img src="https://img.shields.io/badge/AI-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" /> AI 安全研究

| 项目 | 技术栈 |
|:--------|:-----|
| **[AIScan](https://github.com/250wuyifan/aiscan)** <br/> <sub>自研 AI 安全扫描器 — LLM 模型测试 + MCP 代码审计</sub> | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) `LLM智能判定` `Semgrep` |
| **[MCPScan-Multi-LLM](https://github.com/250wuyifan/mcpscan-multi-llm)** <br/> <sub>MCP 协议安全扫描 — 支持多 LLM 供应商</sub> | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) `MCP` `硅基流动` |
| **[AISecLab](https://github.com/250wuyifan/AISecLab)** <br/> <sub>AI 安全靶场 — 40+ 实战靶场，覆盖 8 大攻击面</sub> | ![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white) `红队` `DVMCP` |
| **[DVMCP-Server](https://github.com/250wuyifan/damn-vulnerable-MCP-server-CN)** <br/> <sub>国内首个 MCP 协议安全挑战靶场（10关）</sub> | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) `MCP协议` `SSE` |

</td>
</tr>
</table>

<br/>

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="24"> 技术栈

<div align="center">

| 领域 | 技术 |
|:------:|:------------|
| **逆向分析** | ![IDA](https://img.shields.io/badge/IDA_Pro-4B275F?style=flat-square) ![Ghidra](https://img.shields.io/badge/Ghidra-BF0D3E?style=flat-square&logo=ghidra) ![WinDbg](https://img.shields.io/badge/WinDbg-0078D6?style=flat-square) ![x64dbg](https://img.shields.io/badge/x64dbg-1E90FF?style=flat-square) |
| **系统开发** | ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000?style=flat-square&logo=rust) ![Windows](https://img.shields.io/badge/NT内核-0078D6?style=flat-square&logo=windows&logoColor=white) |
| **AI/ML** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![LLM](https://img.shields.io/badge/LLM安全-FF6F00?style=flat-square) |
| **Web开发** | ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white) |
| **攻防技术** | ![进程注入](https://img.shields.io/badge/进程注入-DC143C?style=flat-square) ![BYOVD](https://img.shields.io/badge/BYOVD-8B0000?style=flat-square) ![ETW绕过](https://img.shields.io/badge/ETW绕过-B22222?style=flat-square) ![Inline_Hook](https://img.shields.io/badge/Inline_Hook-CD5C5C?style=flat-square) |

</div>

<br/>

## <img src="https://media.giphy.com/media/cj87CxfRtrUifF3Riz/giphy.gif" width="25"> 当前研究

```
  ✅  等待线程劫持注入链优化
  🔄  驱动层进程终止防御对抗
  🧪  Beacon 内存属性动态切换与异常恢复
  🛡️  AIScan — LLM 智能判定 + 自动化越狱/注入测试
  🔬  AI 安全靶场 — 40+ 攻击场景实战训练
  🔌  DVMCP — MCP 协议安全研究与漏洞挖掘
```

<br/>

## 📊 GitHub 统计

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=250wuyifan&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=2f80ed&icon_color=2f80ed&text_color=c9d1d9&ring_color=2f80ed&locale=cn" width="49%" />
<img src="https://streak-stats.demolab.com?user=250wuyifan&theme=github-dark-blue&hide_border=true&background=0D1117&ring=2F80ED&fire=2F80ED&currStreakLabel=2F80ED&locale=zh_Hans" width="49%" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=250wuyifan&theme=github-compact&hide_border=true&bg_color=0d1117&color=2f80ed&line=2f80ed&point=ffffff&area=true&area_color=2f80ed" width="98%" />

</div>

<br/>

## 📌 研究历程

```mermaid
timeline
    title 研究足迹
    2023 : 逆向基础 · 恶意样本动态分析
    2024 : BYOVD 研究 · 驱动滥用 PoC · 进程注入
    2025 : 等待线程劫持 · Beacon Guard
    2026 : AI 安全研究 · AIScan · AI 安全靶场 · MCP 安全
```

<br/>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=250wuyifan&theme=darkhub&no-frame=true&row=1&column=7&margin-w=10" width="98%" />

</div>

<br/>

## 🔗 联系方式

<div align="center">

| 平台 | 链接 |
|:----:|:-----|
| 📝 博客 | [blog.changmen.io](https://blog.changmen.io) |
| 🐦 推特 | [@changmensec](https://twitter.com/changmensec) |
| 📱 电报 | [@changmenlabs](https://t.me/changmenlabs) |
| 📧 邮箱 | `changmen@protonmail.com` |

</div>

<br/>

<div align="center">
<samp>

*保持好奇 · 保持进攻 · 保持锋利*

</samp>

<br/>

[![](https://visitcount.itsvg.in/api?id=250wuyifan&icon=6&color=1)](https://visitcount.itsvg.in)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2f80ed,50:161b22,100:0d1117&height=120&section=footer" width="100%" />
