# 第三方声明 / Third-Party Notices

本仓库 **PayloadsAllTheThings-zh（中文版）** 是对以下开源项目的中文二次开发与索引整理，特此致谢并如实署名。

## 1. 源项目

| 项目 | 内容 |
| --- | --- |
| 项目名 | Payloads All The Things |
| 仓库地址 | https://github.com/swisskyrepo/PayloadsAllTheThings |
| 作者 / 维护者 | Swissky（[@pentest_swissky](https://twitter.com/pentest_swissky)） |
| 默认分支 | master |
| 开源许可 | **MIT License** |
| 源许可文件 | https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/LICENSE |
| 源仓星标 | 81,472 ★（GitHub API 实测，2026-10-05） |
| 在线文档 | https://swisskyrepo.github.io/PayloadsAllTheThings/ |

源项目原文许可：

> MIT License
> Copyright (c) 2019 Swissky

## 2. 本仓库使用与改编说明

- **改编内容**：本仓库将源项目根目录下的载荷 / 漏洞分类目录翻译为中文名称，整理为中文分类索引（见 [payloads-index.md](payloads-index.md)），并撰写中文 README、使用示例与速查说明，降低中文安全测试人员的上手门槛。
- **条目统计方式与核实日期（2026-10-05）**：
  - 源仓星标：经 GitHub REST API `GET /repos/swisskyrepo/PayloadsAllTheThings` 实测为 **81,472**。
  - 载荷分类目录数：经 `GET /repos/swisskyrepo/PayloadsAllTheThings/contents/` 取根目录列表，共 **67** 个 `type=dir` 目录；排除内部 / 元目录 `.github`、`_LEARNING_AND_SOCIALS`、`_template_vuln` 共 3 个后，实际载荷 / 漏洞分类目录为 **64** 个。
  - 本 README 分类清单精选收录 **24** 条高频场景；全量 **64** 条中文索引见 [payloads-index.md](payloads-index.md)。
- **保留署名**：所有载荷技术与版权归原作者 Swissky 及源项目众多贡献者所有。本仓库未修改源项目的任何载荷内容，仅做翻译、索引与中文导读。
- **使用边界**：相关载荷与手法仅供授权安全测试、CTF 竞赛与防御研究使用，请勿用于未授权目标。

## 3. 本仓库自身许可

本仓库的中文文档、README、分类索引与 SVG 素材采用 **MIT License** 发布：

> MIT License
> Copyright (c) 2026 zieang88888

详见 [LICENSE](LICENSE)。
