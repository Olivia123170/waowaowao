# CFR 45 §92.11 — 语言援助服务与辅助措施可用性通知

45 CFR Part 92（Section 1557 实施条例）第 92.11 节原文的整理与翻译工作仓库。

**当前版本：v0.1.0**（版本号以 `VERSION` 文件为准，计划译文完成后再升位）

## 版本记录

| 版本 | 状态 | 内容 |
| --- | --- | --- |
| v0.1.0 | 当前 | 仓库骨架：归档源文件、原始文本提取、README 与目录约定。译文尚未开始。 |

版本号遵循语义化版本（`主版本.次版本.修订号`）：
- **主版本**：译文全部定稿、可作为正式交付基线时升位。
- **次版本**：新增完整章节译文，或对既有译文做实质性修订时升位。
- **修订号**：术语统一、格式微调、勘误等小改动时升位。

对应的 git 标签与 `VERSION` 文件保持同步。

## 远程仓库

- GitHub：<https://github.com/Olivia123170/waowaowao>
- 克隆：`git clone git@github.com:Olivia123170/waowaowao.git`
- 默认分支 `main`，走 SSH 认证（本机密钥已登记，无需 token）。

> 注：远程仓库名为 `waowaowao`，与本项目内容无直接关联，请勿据此推断项目用途。

## 源文件

| 项目 | 说明 |
| --- | --- |
| 文件名 | `source/CFR-2025-title45-vol1-sec92-11.pdf` |
| 出处 | 45 CFR Subtitle A, 10-1-25 Edition（Title 45, Volume 1） |
| 页数 | 2 页（原书第 422–423 页） |
| SHA-256 | `86c02cc1198e47b20fd26e2f569f6c063789cf69c5717ce66834c6f511515879` |

### 本文件包含的条款

- § 92.10(a)(2)（上半部分，承接上一页）
- **§ 92.11 Notice of availability of language assistance services and auxiliary aids and services**
  - (a) 通知义务总则
  - (b) 语言与替代格式要求（英文 + 该州最常用的 15 种语言）
  - (c) 送达方式（年度、应请求、网站显著位置、实体场所 ≥20 号无衬线字体、以及 (c)(5) 列举的 11 类电子与书面通信）
  - (d) 合规视同条款（(1) 年度退出选择权 / (2) 记录主要语言并全程提供）
- **Subpart B—Nondiscrimination Provisions**
  - § 92.101 Discrimination prohibited（(a) 总则、(b) 具体禁止情形，本节在原文第 2 页结束处截断）

## 目录结构

```
.
├── README.md                    本说明
├── .gitignore
└── source/
    ├── CFR-2025-title45-vol1-sec92-11.pdf   法规原文（只读，勿改动）
    └── extracted-text-raw.txt               原文原始文本提取（含分页标记与页眉页脚，仅供比对）
```

译文与整理稿后续放入 `translation/`。

## 约定

- `source/` 下的文件为**基线**，任何情况下不得修改；如需修订请新增文件并注明版本。
- 提交身份使用仓库**本地**配置：`Olivia <212806454@qq.com>`（本机无全局 gitconfig）。
