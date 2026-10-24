<div align="center">

<a href="https://seek.threebrook.com/"><img src="https://seek.threebrook.com/seek-icon.svg" alt="三溪寻影" width="96"></a>

<h1>三溪寻影</h1>

<h3>画面、声音、文字，一句话都找得到。</h3>

<p>在你自己电脑上运行的 AI 媒体搜索。照你记得的样子说一句话，<br>直接找到那张照片、视频里的那几秒、录音里的那句话、文档里的那一页。</p>

<a href="https://github.com/ThreeBrook/ThreeBrook-Seek/releases/download/v0.6.6/ThreebrookSeek-Setup-0.6.6.exe"><img src="https://img.shields.io/badge/%E4%B8%8B%E8%BD%BD%E6%A0%87%E5%87%86%E7%89%88-0.6.6_%C2%B7_686_MB-2f9e9a?style=for-the-badge&logo=windows11&logoColor=white" alt="下载标准版"></a> <a href="#下载"><img src="https://img.shields.io/badge/%E6%98%BE%E5%8D%A1%E5%8A%A0%E9%80%9F%E7%89%88-NVIDIA-4a5a59?style=for-the-badge&logo=nvidia&logoColor=white" alt="显卡加速版"></a> <a href="https://seek.threebrook.com/"><img src="https://img.shields.io/badge/%E5%AE%98%E7%BD%91-seek.threebrook.com-6b7b7a?style=for-the-badge" alt="官网"></a>

<img src="https://img.shields.io/github/v/release/ThreeBrook/ThreeBrook-Seek?label=%E6%9C%80%E6%96%B0%E7%89%88&color=2f9e9a" alt="release"> <img src="https://img.shields.io/github/downloads/ThreeBrook/ThreeBrook-Seek/total?label=%E4%B8%8B%E8%BD%BD%E6%AC%A1%E6%95%B0&color=2f9e9a" alt="downloads"> <img src="https://img.shields.io/badge/Windows-10_%2F_11_%C2%B7_64--bit-2f9e9a?style=flat" alt="Windows 10 / 11"> <img src="https://img.shields.io/badge/%E9%9A%90%E7%A7%81-%E6%9C%AC%E6%9C%BA%E5%A4%84%E7%90%86_%C2%B7_%E4%B8%8D%E4%B8%8A%E4%BC%A0-2f9e9a?style=flat" alt="privacy">

[功能](#一句话直接找到) · [下载](#下载) · [个人版与专业版](#个人版与专业版) · [常见问题](#常见问题) · [讨论区](https://github.com/ThreeBrook/ThreeBrook-Seek/discussions) · **中文** | [English](README.en.md)

<img src="docs/images/search-zh.webp" alt="搜“海边”：海边的照片和视频排在一起，视频标出 00:03–00:13 那一段，右边写着为什么找到它" width="900">

</div>

## 一句话，直接找到

不用记文件名，不用先整理、打标签。像跟人描述一样说出你记得的样子：

<table>
<tr>
<td width="50%"><img src="docs/images/lecture-zh.webp" alt="搜“老师讲条件概率的那段”：讲课视频排第一，右边列出讲话内容、关键词、声音都对得上"></td>
<td width="50%"><img src="docs/images/doc-zh.webp" alt="搜“租房合同里押金怎么退”：右边直接显示合同里讲押金的条款"></td>
</tr>
<tr>
<td><b>🔊 说过的话也能搜</b><br>“老师讲条件概率的那段”——录音和视频里的讲话会转成文字，点一下从那句话开始播。</td>
<td><b>📄 文档里的那一条</b><br>“租房合同里押金怎么退”——按意思找到合同，右边直接显示讲押金的条款。</td>
</tr>
<tr>
<td><img src="https://seek.threebrook.com/shots/player.webp" alt="播放页：进度条上亮起来的一段就是命中的位置"></td>
<td><img src="https://seek.threebrook.com/shots/ocr.webp" alt="照片里的型号 STM32F407 和 3.3V 被识别出来并框出"></td>
</tr>
<tr>
<td><b>🎬 直接跳到那几秒</b><br>视频按片段建索引，进度条上亮起来的就是命中的那一段，通常精确到几秒。</td>
<td><b>🔍 照片里的字也算数</b><br>截图、白板、票据、电路板上的型号和参数，都能搜到并框出来，还能直接复制。</td>
</tr>
</table>

### 三条溪，汇成一个搜索框

“三溪”是我们团队所在的小镇，镇上三条溪在中间汇到一起。三溪寻影把你资料里的三种东西汇到同一个搜索框里：

| 🖼️ 画面 | 🔊 声音 | 📄 文字 |
| --- | --- | --- |
| 照片、视频画面、PDF 和 PPT 的页面。按看到的内容找，不用记文件名，也不用先打标签。 | 录音和视频里说过的话会转成文字，掌声、笑声、海浪、烟花这些声音也认得。 | Word、Excel、PDF、网页、电子书、邮件，还有截图和照片里的字。意思相近也能找到。 |

<details>
<summary><b>支持哪些文件</b></summary>

| 类型 | 格式 |
| --- | --- |
| 照片 | JPG、PNG、HEIC / HEIF、WebP、AVIF、GIF、BMP、TIFF，相机 RAW（DNG、CR2、CR3、NEF、ARW、RAF、ORF、RW2） |
| 视频 | MP4、MOV、MKV、AVI、WMV、M4V、WebM、3GP、MTS / M2TS、MPG、FLV、RMVB 等 |
| 录音 | MP3、WAV、M4A、AAC、FLAC、OGG、Opus、WMA、AMR、APE 等 |
| 文档 | PDF、Word（DOCX）、PowerPoint（PPTX）、Excel（XLSX）、CSV、TXT / Markdown、网页、EPUB、RTF、ODF、邮件（EML / MSG）、字幕、Jupyter 笔记本 |
| 专业版另有 | 代码与工程文件按内容搜索；旧版 DOC / PPT / XLS 和 WPS 文件（借本机 Office / WPS 转换） |

</details>

### 不只是搜索

| | |
| --- | --- |
| 🖼️ **以图搜图、以声搜声** | 拖一张图进来、粘贴截图，或者选一段声音，找出相似的照片、视频画面和录音。 |
| ⚡ **悬浮搜索框** | 在任何地方按快捷键呼出，文件名搜索覆盖全部磁盘，打字就出结果。 |
| 📅 **图库、时刻、智能合集** | 按时间浏览，出游和聚会自动归成一个“时刻”；一次搜索可以存成会自动更新的合集；还有那年今天。 |
| 🧹 **重复与相似照片** | 连拍、存了好几份的照片一眼看出来，自己决定留哪张。 |
| 🔒 **私密文件夹** | 用 Windows Hello 解锁才显示，平时不出现在搜索和图库里。 |
| ✂️ **找到之后** | 结果直接拖进微信或资源管理器；复制图片、复制画面、导出视频片段；选取照片和录音里的文字。 |
| 🌗 **中英文、深浅色** | 界面中英文切换，跟随系统深浅色。 |
| 🐾 **团子** | 一只住在桌面上的小宠物，会陪你一起找东西（不喜欢可以关掉）。 |

<p align="center"><img src="docs/images/dark-zh.webp" alt="深色界面：搜“跨年夜的烟花”，跨年夜视频标出 00:06–00:14 那一段" width="820"></p>

### 你的文件，只在你的电脑上

- **不上传。** AI 模型随软件装在本机，建索引、搜索都在你的电脑上完成，断网也照常用。
- **不收集。** 没有统计、没有广告、没有账号。只有你在“关于”页确认“检查更新”时，才会读取官网上的一个版本号文件；有新版本时你再点“下载并安装”，才会下载新版安装程序。都不带你的任何数据。
- **加密保存。** 索引、缩略图、识别出的文字都加密存放，只有你这台电脑上的这个 Windows 用户能打开。
- **敏感功能默认关闭。** 人脸分组、地点解析要你单独同意才会开启。
- **不碰原文件。** 只读取，不移动、不修改、不重命名你的照片和文档。

## 下载

最新版 **0.6.6** · [这一版更新了什么](CHANGELOG.md) · [所有版本](https://github.com/ThreeBrook/ThreeBrook-Seek/releases)

| | 下载 | 适合 |
| --- | --- | --- |
| **标准版**<br>推荐 | [ThreebrookSeek-Setup-0.6.6.exe](https://github.com/ThreeBrook/ThreeBrook-Seek/releases/download/v0.6.6/ThreebrookSeek-Setup-0.6.6.exe)（686 MB） | 任何 Windows 电脑。一个文件，下载后双击安装。 |
| **显卡加速版** | [ThreebrookSeek-Setup-GPU-0.6.6.exe](https://github.com/ThreeBrook/ThreeBrook-Seek/releases/download/v0.6.6/ThreebrookSeek-Setup-GPU-0.6.6.exe)（1.9 GB）<br>[ThreebrookSeek-Setup-GPU-0.6.6-2.bin](https://github.com/ThreeBrook/ThreeBrook-Seek/releases/download/v0.6.6/ThreebrookSeek-Setup-GPU-0.6.6-2.bin)（455 MB） | 有 NVIDIA 显卡的电脑，建索引快几倍。**两个文件下载到同一个文件夹**，再运行 .exe。 |

- **系统**：Windows 10 / 11（64 位）。安装后约占 1.2 GB（标准版）或 4 GB（显卡加速版），另加索引。
- **安装**：不需要管理员权限，不需要联网；装到一半出错或者点了中止，会自动恢复原样。
- **校验**：每个版本的 SHA-256 写在[发布页](https://github.com/ThreeBrook/ThreeBrook-Seek/releases)里，PowerShell 里用 `Get-FileHash <文件名>` 核对。也可以从[官网下载页](https://seek.threebrook.com/download)下载。

## 个人版与专业版

| | 个人版 | 专业版 |
| --- | :---: | :---: |
| 价格 | **免费** | 一次买断，没有订阅 |
| 适合 | 家庭和个人非商业使用 | 工作和商业使用 |
| 可建索引的文件数 | 5 万个 | 不限 |
| 一句话搜照片、视频、录音、文档 | ✓ | ✓ |
| 以图搜图、以声搜声、悬浮搜索框、文件名搜索 | ✓ | ✓ |
| 图库、时刻、智能合集、人物、私密文件夹 | ✓ | ✓ |
| NAS / 网络文件夹作为来源 | | ✓ |
| 会议模式：录音对齐演示文稿、纪要初稿 | | ✓ |
| 代码与工程文件、旧版 Office / WPS 按内容搜索 | | ✓ |
| 本机 MCP 接口（给 AI 助手用） | | ✓ |
| 新版本 | ✓ | 一年内发布的新版本 |

每次安装都有 **14 天专业版试用**，激活和试用都在本机完成。[了解专业版 →](https://seek.threebrook.com/buy)

## 常见问题

<details><summary><b>需要联网吗？</b></summary>

不需要。安装、建索引、搜索都在本机完成，断网也照常用。只有你在“关于”页点“检查更新”并确认之后，才会读取官网上的一个版本号文件；有新版本时再点“下载并安装”，才会下载新版安装程序。

</details>

<details><summary><b>没有显卡能用吗？要多久建好索引？</b></summary>

能。第一次打开时会按你这台电脑实测的速度，告诉你照片多久能按画面搜到、连同照片上的文字多久全部建好。建索引在后台进行，期间随时可以搜，关机后下次接着做。有 NVIDIA 显卡的话用显卡加速版，快几倍。

</details>

<details><summary><b>会改动、上传我的照片吗？索引存在哪里？</b></summary>

不会改动，也不会上传。三溪寻影只读取你选定的文件夹。索引默认存在 `%LOCALAPPDATA%\ThreebrookSeek`，可以在设置里换到别的磁盘，全部加密保存。

</details>

<details><summary><b>个人版有时间限制吗？</b></summary>

没有，个人版一直免费，用于家庭和个人非商业用途，最多为 5 万个文件建立索引。安装后的前 14 天可以试用专业版的全部功能，到期自动回到个人版，已经建好的索引都保留。

</details>

<details><summary><b>支持移动硬盘和 NAS 吗？</b></summary>

移动硬盘可以直接加为来源，拔下后照样能搜，接回来接着建索引，换了盘符也能认出来。NAS 和网络文件夹是专业版功能。

</details>

<details><summary><b>有 Mac 版或手机版吗？</b></summary>

目前只有 Windows 版。想要其他平台，欢迎到[讨论区](https://github.com/ThreeBrook/ThreeBrook-Seek/discussions)告诉我们。

</details>

<details><summary><b>怎么卸载？</b></summary>

Windows 设置 → 应用 → 三溪寻影 → 卸载。卸载时可以勾选“同时删除索引数据”；不勾就保留，重新安装后不用重建索引。你的照片和文档本身不受影响。

</details>

## 反馈与讨论

- 💬 **用法、想法、建议** → [讨论区](https://github.com/ThreeBrook/ThreeBrook-Seek/discussions)
- 🐞 **出错、崩溃、搜不到** → [新建 Issue](https://github.com/ThreeBrook/ThreeBrook-Seek/issues/new)，写上 Windows 版本、标准版还是显卡加速版、怎么操作出现的。运行日志在 `%LOCALAPPDATA%\ThreebrookSeek\app.log`，贴出来之前请去掉你不想公开的文件名和路径。
- ✉️ **购买、激活、退款，或不方便公开的问题** → support@threebrook.com

## 关于这个仓库

这里发布三溪寻影的安装包和更新记录，也是用户交流的地方。软件的源代码不公开，不在这里。

[发布页](https://github.com/ThreeBrook/ThreeBrook-Seek/releases)（安装包与校验值） · [CHANGELOG.md](CHANGELOG.md)（每个版本改了什么） · [官网](https://seek.threebrook.com/)

---

<div align="center">

<a href="https://threebrook.com/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://threebrook.com/lockup-dark.svg"><img src="https://threebrook.com/lockup-light.svg" alt="三溪 Threebrook" width="180"></picture></a>

**来自三溪小镇的小团队，做安静、可靠、在你自己电脑上运行的软件。**

| 🟢 本地优先 | 🌿 不收集 | ☀️ 小而可靠 |
| :---: | :---: | :---: |
| 能在你电脑上做完的事，<br>就不放到云上 | 不做统计、不放广告、不追踪，<br>我们的网站也一样 | 一个产品只把一件事<br>做好、做稳定 |

<sub>© 2026 三溪 Threebrook · 珠海三溪科技有限公司 · support@threebrook.com<br>使用本软件即表示同意随软件附带的许可协议与隐私政策。</sub>

</div>
