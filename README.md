<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/oxyuan/oxyuan/master/assets/banner-dark.svg"><img src="https://raw.githubusercontent.com/oxyuan/oxyuan/master/assets/banner-light.svg" alt="oxyuan — 写后端，也写让后端顺手的工具" width="100%"></picture>

做后端，也做工具。仓库大致两类：把反复敲的命令收进一个界面（GitJet、NetKit），把散落的资料变成能秒查的东西（uTools Arthas Docs）。偏好本地优先、无服务端、断网也能跑的写法。

## 精选项目 <sub>Selected work</sub>

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/oxyuan/gitjet">GitJet</a></h3>
<p><sub>DESKTOP GIT CLIENT · macOS / WINDOWS</sub></p>
<p>变更集、按 hunk 暂存、逐行解决三路冲突、可视化编辑历史、LSP 定义跳转。Go 写后端，React 写界面，跑在系统 WebView 里。</p>
<p><sub><code>Go</code> <code>React</code> <code>TypeScript</code> <code>CodeMirror 6</code></sub></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/oxyuan/chrome-netkit-plugin">NetKit</a></h3>
<p><sub>BROWSER EXTENSION · MANIFEST V3</sub></p>
<p>给具体网站加自己的开关：X 上的隐私遮罩与一键屏蔽。功能与开关按站点隔离，无服务端，不采集任何数据。</p>
<p><sub><code>JavaScript</code> <code>Chrome / Edge</code> <code>Privacy</code></sub></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/oxyuan/utools-arthas-docs-plugin">uTools Arthas Docs</a></h3>
<p><sub>OFFLINE DOCS · UTOOLS PLUGIN</sub></p>
<p>Arthas 4.3.5 全量 76 篇，附 4.1.3 旧版 50 篇。文档随插件打包，内网、断网都能秒开，支持版本切换与全文检索。</p>
<p><sub><code>uTools</code> <code>离线</code> <code>MIT</code></sub></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/oxyuan/slice-engine">slice-engine</a></h3>
<p><sub>TEXT SEGMENTATION · GO</sub></p>
<p>按序号 → 编码 → 符号 → 空格 → 字词的优先级定位切分位，再走合并、打分、标化、去噪。引擎可插拔，按类别优先级排序执行。</p>
<p><sub><code>Go</code> <code>Plugin</code> <code>NLP</code></sub></p>
</td>
</tr>
</table>

## 技术栈

后端主力 <code>Go</code> 与 <code>Java</code>，界面用 <code>TypeScript</code> / <code>React</code>，需要贴近系统时写 <code>Rust</code>、<code>Kotlin</code>。调试优先于猜测：日志、反编译、断点，能验证的结论才算结论。

## 其他仓库

- [**gobin**](https://github.com/oxyuan/gobin) — 单文件 Go CLI 合集：抓取文档、按行检索、批量更新分支
- [**scripts**](https://github.com/oxyuan/scripts) — 个人脚本：油猴、QuantumultX、终端小工具
- 早年的 Java 练习：[online-mall](https://github.com/oxyuan/online-mall)、[aspro](https://github.com/oxyuan/aspro)、[JavaNote](https://github.com/oxyuan/JavaNote)

---

<sub>本页由 Markdown 与两段手写 SVG 维护，不依赖第三方统计卡片。</sub>
