# Third-party assets / 第三方素材许可

本页是仓库在线阅读副本。详细素材清单、程序与维护工具位于 [Release 完整下载包](https://github.com/jerryyao46-ux/medical-research-illustration-library/releases/tag/v2026.10.20-ccby)；下文标记为“包内路径”的内容，请在下载并解压后按该路径查看。第三方许可与原作者署名仍按各自条目保留。

本项目原创内容的许可与第三方素材许可分开。根目录 CC BY 4.0 **不会把已收集的插画、照片、PPT 或三维模型重新许可为 CC BY 4.0**。逐项许可、作者和修改说明是素材再利用与发布的依据；预览、格式转换、兼容 SVG 和离线 GLB 压缩块继承对应来源义务。[许可范围](LICENSE_SCOPE.md)说明项目原创内容的授权边界，[署名模板](ATTRIBUTION.md)不能替代第三方原作者的署名与许可要求。

下列分类和来源核验保留 2026-09-27 本地审查快照；该历史记录的发布状态不用于描述当前仓库。实际下载内容以对应 Release 随附清单为准。`allow` 表示当前目录记录和明确来源依据支持按条件再分发，不是所有权担保或全量逐件法律认证。

## 本次分类

| 活跃记录 | 有条件允许 `allow` | 受限 `restricted` | 待复核 `review` |
|---:|---:|---:|---:|
| 23,199 | 23,192 | 4 | 3 |

默认公开素材包只使用 `allow` 白名单。下列七项及其预览/缓存不进入默认公开包，本地原件保留：

| 素材 ID | 原因 |
|---|---|
| `medical:HPB-PMC8083757-Fig1` | CC BY-NC-SA 4.0；非商业且相同方式共享 |
| `medical:HPB-PMC11948093-Fig4` | CC BY-NC 4.0；非商业 |
| `ppt:PPT-TECH-NASA-DSN-34M` | NASA 自定义媒体使用规则，不等于通用开放素材许可 |
| `ppt:PPT-TECH-NASA-TDRS-A` | 同上 |
| `medical:WMC-004066775` | 作者为 Unknown，虽目录标 PD，公开发布前需复核具体公有领域依据 |
| `medical:WMC-010215723` | 同上 |
| `medical:WMC-042471896` | 同上 |

NC 许可仍可允许满足其条件的传播，这里排除它们是默认公开包的筛选规则，不能写成“一切传播都违法”。NASA 媒体规则同样包含允许的用途，但存在非背书、第三方内容及其他例外，不能重标 CC0。[CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)、[CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/)、[NASA 官方规则](https://www.nasa.gov/nasa-brand-center/images-and-media/)。

## 清单在不同发布形态中的范围

源码审计包的清单覆盖本地全部 23,199 条记录。许可筛选数据包中，主 assets/asset_files/notice 清单仅列实际随包的 allow 项；全量审计副本置于 `licenses/audit/`，用于核对被排除条目的原因，不包含这些受限素材的原件或预览。数据包的实时素材数量以其数据库、统计及 PUBLIC_DATA_RELEASE.json 为准。

## 逐项机器清单

- assets_redistribution_manifest.jsonl（包内路径：`licenses/assets_redistribution_manifest.jsonl`）：全部 23,199 个活跃条目，包含原许可、有效许可、作者及依据、署名、来源、修改、存在的证据路径和审查状态。
- asset_files_manifest.jsonl（包内路径：`licenses/asset_files_manifest.jsonl`）：资产及衍生文件白名单，包含主文件、预览、PPT 页、模型依赖、兼容副本和离线模型分块；`parent_asset_keys` 关联来源素材，权限取关联来源中最严格状态。
- notice_files_manifest.jsonl（包内路径：`licenses/notice_files_manifest.jsonl`）：明确挑选的原始许可/版权纯文本；同时记录原路径、可随代码包携带的 `licenses/notices/` 副本及 SHA-256。
- third_party_inventory.csv（包内路径：`licenses/third_party_inventory.csv`）：便于表格筛选的透明清单。
- redistribution_summary.json（包内路径：`licenses/redistribution_summary.json`）：来源与协议统计、非允许条目、衍生关联和依赖检查。
- official_license_checks.json（包内路径：`licenses/official_license_checks.json`）：本轮实际查阅的官方许可/来源网页、检查日期及简短结论。
- evidence_files_manifest.jsonl（包内路径：`licenses/evidence_files_manifest.jsonl`）：本地证据引用及哈希；**其存在不构成复制该证据文件的单独授权**，也不是打包白名单。

本轮只读查询两个 SQLite，未改主素材、原许可字段、原索引或原有完整 ZIP。生成器是 tools/audit_asset_licenses.py（包内路径：`tools/audit_asset_licenses.py`）。现有输出覆盖前保存到 `backups/2026-09-27-github-prep/visual_assets/`。

## 按许可履行义务

- CC BY：保留作者/来源、许可链接，注明修改；不暗示原作者背书。[官方规则](https://creativecommons.org/licenses/by/4.0/)
- CC BY-SA：同时满足适用版本的改编作品相同方式共享要求；不是把整个程序自动改成该素材的许可。[官方规则](https://creativecommons.org/licenses/by-sa/4.0/)
- MIT / ISC / BSD：保留原版权、许可与免责声明，不仅写一个 SPDX 名称。[MIT](https://opensource.org/license/mit)、[ISC](https://opensource.org/license/isc)、[BSD-3-Clause](https://opensource.org/license/bsd-3-clause)
- CC0 / Public Domain：保留可追溯来源；这些状态不代替商标、肖像、隐私或其他独立权利的判断。[CC0](https://creativecommons.org/publicdomain/zero/1.0/)
- NIDDK：媒体官方说明为 copyright-free，并请求机构署名；使用清单中的完整机构名称。[官方说明](https://www.niddk.nih.gov/news/media-library)

本项目 216 个原创建号/分点图形有原来的“几何路径原创、非上游下载、无嵌入字体”声明，本次依 [LICENSE_SCOPE.md](LICENSE_SCOPE.md)新增 CC BY 4.0 发布许可；原目录标签“本项目原创”仍保留在清单，不套用于第三方图标。

## 不能混淆的来源

- Bioicons 的图标来自多个作者和许可目录；网页程序的 LICENSE 不能覆盖全部插画。[上游项目](https://github.com/duerrsimon/bioicons)
- Health Icons 图标为 CC0，网站代码为 MIT。[官方说明](https://healthicons.org/about)
- Reactome 图标与插画为 CC BY 4.0，不能因数据库数据为 CC0 而去掉插画署名。[官方协议](https://reactome.org/license)
- Lucide 的许可文件含 ISC 与部分 Feather 图标的 MIT 声明；分发时保留整份文件中的两个版权来源。[上游 LICENSE](https://github.com/lucide-icons/lucide/blob/main/LICENSE)
- Servier 当前官网采用 CC BY 4.0，旧 PPT 内的 CC BY 3.0 声明不删除。BodyParts3D 当前官方档案许可为 CC BY 4.0，原 OBJ 中的旧 CC BY-SA 2.1 JP 头部同样保留。[Servier](https://smart.servier.com/)、[BodyParts3D](https://dbarchive.biosciencedbc.jp/en/bodyparts3d/lic.html)

## 公开打包边界

按 `public_bundle_candidate=true` 的文件白名单复制实际原件、必要组件/纹理和明确衍生文件，并附逐项署名清单及 `notice_files_manifest` 指定的许可文本。公开版浏览数据和 SQLite 还须过滤对应的 `restricted/review` 行，避免留下失效入口或把受限图片埋进缓存。

不要整体复制 `03_来源与许可/`、上游仓库原始 ZIP、隔离目录、历史下载缓存、网页全文、论文全文或私人的绘图项目。某个活跃图标允许再分发，并不证明其来源压缩包里的全部未入库内容也允许。网页快照是核对证据，不自动成为可公开再分发素材。不能只修改 manifest 却把原完整库 ZIP 原样公开。

审查以当前逐项目录、现存证据和列明的官方来源级核验为基础；没有声称重新核验所有第三方所有权、图中人物许可或临床内容。Wikimedia 等聚合来源的具体文件页与许可依然重要。[Wikimedia 再利用说明](https://commons.wikimedia.org/wiki/Commons:Reusing_content_outside_Wikimedia)

## 来源分类快照

| 库与来源 | allow | restricted | review |
|---|---:|---:|---:|
| medical:Annals of Medicine and Surgery / Europe PMC Open Access | 1 | 0 | 0 |
| medical:Bioicons | 2822 | 0 | 0 |
| medical:BodyParts3D / DBCLS | 2221 | 0 | 0 |
| medical:Cancer Research UK / Wikimedia Commons | 4 | 0 | 0 |
| medical:Cureus / Europe PMC Open Access | 1 | 0 | 0 |
| medical:DBCLS TogoTV | 437 | 0 | 0 |
| medical:Europe PMC Open Access / Radiomics | 11 | 0 | 0 |
| medical:Europe PMC Open Access / Surgery | 72 | 0 | 0 |
| medical:Europe PMC Open Access / Telesurgery | 3 | 0 | 0 |
| medical:Frontiers in Medicine / Europe PMC Open Access | 1 | 0 | 0 |
| medical:Frontiers in Surgery / Europe PMC Open Access | 1 | 0 | 0 |
| medical:Health Icons | 1076 | 0 | 0 |
| medical:Human Reference Atlas / HuBMAP | 86 | 0 | 0 |
| medical:Human Reference Atlas 2D FTU / HuBMAP | 28 | 0 | 0 |
| medical:IBSI | 41 | 0 | 0 |
| medical:International Journal of Surgery (London, England) / Europe PMC Open Access | 1 | 0 | 0 |
| medical:Journal of Minimal Access Surgery / Europe PMC Open Access | 0 | 1 | 0 |
| medical:Kenney Cube Pets | 24 | 0 | 0 |
| medical:Medicine / Europe PMC Open Access | 1 | 0 | 0 |
| medical:NIDDK Media Library | 857 | 0 | 0 |
| medical:NIH BioArt | 854 | 0 | 0 |
| medical:OpenMoji | 240 | 0 | 0 |
| medical:PhyloPic | 74 | 0 | 0 |
| medical:Reactome | 2569 | 0 | 0 |
| medical:Rfam | 4218 | 0 | 0 |
| medical:SPARC / Pennsieve | 17 | 0 | 0 |
| medical:SciDraw | 606 | 0 | 0 |
| medical:Servier SMART | 49 | 0 | 0 |
| medical:Springer Nature / Europe PMC Open Access | 5 | 0 | 0 |
| medical:The Cancer Imaging Archive (TCIA) | 1 | 0 | 0 |
| medical:WikiPathways | 2203 | 0 | 0 |
| medical:Wikimedia Commons | 16 | 0 | 0 |
| medical:Wikimedia Commons / Specialty medical illustrations | 681 | 0 | 3 |
| medical:World Journal of Emergency Surgery : WJES / Europe PMC Open Access | 1 | 0 | 0 |
| medical:World Journal of Gastrointestinal Surgery / Europe PMC Open Access | 0 | 1 | 0 |
| medical:World Journal of Surgical Oncology / Europe PMC Open Access | 2 | 0 | 0 |
| medical:dVRK official CAD | 2 | 0 | 0 |
| medical:dVRK official models | 57 | 0 | 0 |
| medical:dVRK official models / local static URDF assembly | 3 | 0 | 0 |
| ppt:Affinity network symbols | 15 | 0 | 0 |
| ppt:Bootstrap Icons | 1042 | 0 | 0 |
| ppt:CRESCENT Community Fault Model | 3 | 0 | 0 |
| ppt:Lucide Icons | 28 | 0 | 0 |
| ppt:NASA 3D Resources | 0 | 2 | 0 |
| ppt:Tabler Icons | 2580 | 0 | 0 |
| ppt:UN OCHA Humanitarian Icons v2 | 12 | 0 | 0 |
| ppt:Wikimedia Commons | 10 | 0 | 0 |
| ppt:项目编号组件 | 216 | 0 | 0 |
