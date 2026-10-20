# 第三方软件与运行依赖

本页是仓库在线阅读副本。详细素材清单、程序与维护工具位于 [Release 完整下载包](https://github.com/jerryyao46-ux/medical-research-illustration-library/releases/tag/v2026.10.20-ccby)；下文标记为“包内路径”的内容，请在下载并解压后按该路径查看。第三方许可与原作者署名仍按各自条目保留。

日常浏览所需的第三方浏览引擎已经随代码提供，不从 CDN 下载。素材与软件许可分开管理，素材请看 [THIRD_PARTY_ASSETS.md](THIRD_PARTY_ASSETS.md)。

| 软件 | 锁定版本 | 使用方式 | 许可及保留位置 |
|---|---|---|---|
| Three.js，含 OrbitControls、GLTFLoader、OBJLoader | 0.186.0 | `医学科研绘图素材库/08_浏览器/vendor/atlas-engine.js` 内置运行时 | MIT；同目录 `THREE-LICENSE.txt`、`atlas-engine.js.LEGAL.txt` |
| esbuild | 0.25.12 | 构建上述引擎时使用；浏览时无需安装 | MIT；同目录 `ESBUILD-LICENSE.txt` |
| Python | 3.10+，具体重建脚本另列 | 用户自行安装，用于导入、查询及维护；不捆绑解释器 | Python Software Foundation License；[官方许可](https://docs.python.org/3/license.html) |

引擎的官方包来源、完整性值和产物 SHA-256 在 vendor/provenance.json（包内路径：`医学科研绘图素材库/08_浏览器/vendor/provenance.json`） 中。可选 Pillow、pypdfium2、NumPy、LibreOffice、Node.js 和 Playwright 不随本源码包捆绑，具体用途、安装命令和对应许可链接见 依赖与安装（包内路径：`docs/INSTALL.md`）。不用某项维护功能就不必安装该项依赖。

Tabler、Lucide、Bootstrap 等图标虽然使用 MIT/ISC 等软件常见许可，在本项目中仍按逐个素材列入素材清单；须保留其上游作者和完整版权声明，不能仅留下本项目原创内容的 CC BY 4.0 声明。
