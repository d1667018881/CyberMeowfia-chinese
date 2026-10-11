<p align="center">
  <img src="https://nebusec.ai/nebusec-social.png" alt="Nebula Security" width="640" />
</p>

<p align="center">
  官网：<a href="https://nebusec.ai">nebusec.ai</a>
  &nbsp;·&nbsp;
  Twitter <a href="https://x.com/nebusecurity">@nebusecurity</a>
  &nbsp;·&nbsp;
  <a href="https://nebusec.ai/buglist">漏洞列表（1000+）</a>
</p>

## 最新研究成果

- **加涡轮之前，先检查你的机油**：CVE-2026-7899——当 V8 优化引擎积碳时<br>
  [Chrome V8] 📖 [技术文章](https://nebusec.ai/research/cve-2026-43501-route-of-root/) · 🐦 [Twitter](https://x.com/nebusecurity/status/2093126422194004242)
- **Route of Root**：把一个"仅 DoS"的漏洞升级为 LPE，并绕过现有补丁，在 kernelCTF 中赢得 10500 美元<br>
  [Linux 内核] 📖 [技术文章](https://nebusec.ai/research/cve-2026-43501-route-of-root/) · 🐦 [Twitter](https://x.com/nebusecurity/status/2089856283977691200) · 🔗 [源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-43501-kernelCTF)
- **IonStack 第三篇**：用 GhostLock 攻破 Android 17<br>
  [Linux 内核] 📖 [技术文章](https://nebusec.ai/research/ionstack-part-3) · 🐦 [Twitter](https://x.com/nebusecurity/status/2084417335314841719) · 🔗 [源码](https://github.com/NebuSec/CyberMeowfia/tree/main/IonStack/CVE-2026-43499)
- **IonStack 第一篇**：Ion 编译器中的不健全 IonBanana Peel——穿透 Firefox 的 SpiderMonkey JIT<br>
  [Firefox SpiderMonkey] 📖 [技术文章](https://nebusec.ai/research/ionstack-part-1-cve-2026-10702/) · 🐦 [Twitter](https://x.com/nebusecurity/status/2074663573742338256) · 🔗 [源码](https://github.com/NebuSec/CyberMeowfia/tree/main/IonStack/CVE-2026-10702)
- **IonStack 第二篇**：GhostLock——存在于所有 Linux 发行版中长达 15 年的栈上 UAF 漏洞<br>
  [Linux 内核] 📖 [技术文章](https://nebusec.ai/research/ionstack-part-2) · 🐦 [Twitter](https://x.com/nebusecurity/status/2081894761284415674) · 🔗 [源码](https://github.com/NebuSec/CyberMeowfia/tree/main/IonStack/CVE-2026-43499)
- **Longinus**：一洞两界——利用单个漏洞穿透 Chrome 渲染器与 V8 沙箱，CVE-2026-6307<br>
  [Chrome V8] 📖 [技术文章](https://nebusec.ai/research/v8-cve-2026-6307-writeup) · 🐦 [Twitter](https://x.com/nebusecurity/status/2071587218205086149)
- **Nginx-QuicBurst**：首个针对通用配置、带 ASLR 绕过的公开 Nginx RCE，CVE-2026-42530<br>
  [Nginx] 🐦 [Twitter](https://x.com/nebusecurity/status/2067623683427045541) · 🔗 [源码](https://github.com/NebuSec/CyberMeowfia/tree/main/Nginx-QuicBurst)
- **Nginx-PoolSlip**：首个带 ASLR 绕过的公开 Nginx RCE，CVE-2026-9256<br>
  [Nginx] 🐦 [Twitter](https://x.com/nebusecurity/status/2057071579876753643) · 🔗 [源码](https://github.com/NebuSec/CyberMeowfia/tree/main/Nginx-PoolSlip)
- **V8 中遗漏的写屏障如何演变为 Chrome 的 RCE 漏洞**：CVE-2026-5865<br>
  [Chrome V8] 📖 [技术文章](https://nebusec.ai/research/v8-maglev-incorrect-phis-untagging) · 🐦 [Twitter](https://x.com/nebusecurity/status/2052842241828561208) · 🔗 [源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Chrome-CVE-2026-5865)
- **从 Netfilter 漏洞到 kernelCTF**：利用 CVE-2026-23274 攻破 Linux 内核并赢取 10500 美元奖金<br>
  [Linux 内核] 📖 [技术文章](https://nebusec.ai/research/cve-2026-23274-cos) · 🐦 [Twitter](https://x.com/nebusecurity/status/2044499901082702065) · 🔗 [源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-23274-kernelCTF)

## N-day 研究
- CVE-2026-64560：Linux 与 Android 上的 LPE · 🔗 [源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Ndays/Android-CVE-2026-64560)
- CVE-2026-43074：Linux 与 Android 上的 LPE · 🔗 [源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Ndays/Android-CVE-2026-43074)

## 其他安全研究
CVE-2026-31678：Linux 内核 LPE 🔗 [Fedora 44 (6.19.10-300) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-31678-Fedora-6.19.10-300)
CVE-2026-43042：Linux 内核 LPE 🔗 [Debian 13 (6.12.101) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-43042-Debian-6.12.101)
CVE-2026-52912：Linux 内核 LPE 🔗 [Fedora 44 (6.19.10-300) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-52912-Fedora-6.19.10-300)
CVE-2026-52923：Linux 内核 LPE 🔗 [RHEL 10 (6.12.0-211.7.3.el10_2) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-52923-RHEL-6.12.0-211.7.3.el10_2)
CVE-2026-52929：Linux 内核 LPE 🔗 [Ubuntu 26.04 (7.0.0-28) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-52929-Ubuntu-7.0.0-28)
CVE-2026-52933：Linux 内核 LPE 🔗 [Fedora 44 (6.19.10-300) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-52933-Fedora-6.19.10-300)
CVE-2026-68162：Linux 内核 LPE 🔗 [Ubuntu 26.04 (7.0.0-28) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-68162-Ubuntu-7.0.0-28)
CVE-2026-72137：Linux 内核 LPE 🔗 [Ubuntu 26.04 (7.0.0-28) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-72137-ubuntu-7.0.0-28)
CVE-2026-72255：Linux 内核 LPE 🔗 [Ubuntu 26.04 (7.0.0-28) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-72255-Ubuntu-7.0.0-28)
CVE-2026-74480：Linux 内核 LPE 🔗 [RHEL 10 (6.12.0-211.7.3.el10_2) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-74480-RHEL-6.12.0-211.7.3.el10_2)
CVE-2026-74581：Linux 内核 LPE 🔗 [Debian 13 (6.12.101) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-74581-Debian-6.12.101)
CVE-2026-80714：Linux 内核 LPE 🔗 [Debian 13 (6.12.101) 源码](https://github.com/NebuSec/CyberMeowfia/tree/main/security-research/Linux-CVE-2026-80714-Debian-6.12.101)
