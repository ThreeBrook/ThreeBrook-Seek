# 更新记录 / Changelog

## 0.6.6

- 软件里一键更新：“关于”页检查到新版本后，点“下载并安装”，从三溪的下载服务器下载、核对校验值后自动安装，断了可以接着下；不点就不下载，也不发送你的任何数据。（从 0.6.6 起可用，这一次升级仍请在网站下载。）
- 第一次使用时先问你主要想找什么——家里的照片和视频、会议录音和录屏、工作文档——按用途帮你勾好要加的文件夹。
- 团子能回答关于软件的常见问题，也会陪你聊几句；对话不保存。闲着两分钟没人理时，它会躲到屏幕边上只露出一只眼睛，碰一下就回来（设置里可以关掉）。
- 媒体库文件损坏时自动修复，修不好时可以一键重建索引；大约每周自动保存一份加密的快照，出问题时能用来恢复。
- 安装包小了约 30 MB，装好后少占约 100 MB。

- One-click updates in the app: when the About page finds a new version, click “Download & install”. It downloads from Threebrook’s download server, checks the files, resumes if interrupted, and installs. Nothing is downloaded unless you click, and none of your data is sent. (Available from 0.6.6 on; for this upgrade, please download from the website.)
- On first launch, the app asks what you mainly want to find (family photos and videos, meeting recordings, work documents) and ticks the matching folders for you.
- Tuanzi can answer common questions about the app and chat a little; conversations aren’t saved. After two idle minutes it hides at the edge of the screen with just one eye showing, and pops back when you touch it (you can turn this off in Settings).
- If the library file gets damaged, it’s repaired automatically, and if that fails you can rebuild the index in one click. An encrypted snapshot is saved about once a week to recover from.
- The installer is about 30 MB smaller and takes about 100 MB less space once installed.

## 0.6.5

- 没有显卡的电脑建索引快了不少：修正了线程安排，普通笔记本上不再互相抢着算；照片上的文字只在缩小的照片上找，有字的照片照样能搜到，很小的字可能搜不到（设置里可以关掉）。
- 第一次打开时，按这台电脑实测的速度，告诉你照片多久能按画面搜到、连同照片上的文字多久全部建好。
- “关于”页可以检查更新：先告诉你要连哪里、只下载什么，你确认后才联网，不发送你的任何数据。
- 个人版改为家庭和个人非商业使用，可以建索引的文件数从 2 万个提高到 5 万个；工作和商业使用请用专业版。

- Much faster indexing on PCs without a graphics card: threads no longer compete with each other on ordinary laptops, and text in photos is looked for in a reduced copy of each photo. Text is still found, though very small text may be missed (you can turn this off in Settings).
- On first launch, the app measures this PC and tells you how long until your photos are searchable by content, and how long until text in photos is done too.
- Check for updates on the About page: it first tells you where it will connect and what it downloads, and goes online only after you confirm. None of your data is sent.
- The Personal edition is now for home and personal non-commercial use, and indexes up to 50,000 files instead of 20,000. Use Pro for work and commercial use.

## 0.6.4

- 从 0.6.3 及更早的版本升级：数据换了保存位置，升级后需要重新添加来源、重新建索引，照片和文档本身不受影响。
- 换了新样子：颜色和字体和官网统一。
- 新的安装程序，界面和软件一个样；装到一半出错或者点了中止，会自动恢复原样。
- 安装包小了很多：标准版从约 1 GB 降到约 0.7 GB，显卡加速版从约 3.5 GB 降到约 2.5 GB，只有两个文件。
- 扫描快了很多：第一次扫描十几万个文件，从 15 分钟左右缩短到 10 秒左右。
- 移动硬盘和 NAS 可以作为来源：断开时照常能搜，接回来自动继续建索引；移动硬盘换了盘符也能找回。网络文件夹是专业版功能。
- 没有显卡的电脑，照片默认“速度优先”，建索引更快；设置里可以改成“精度优先”。
- 按文件名找文件更准：文件名对上时，文件名结果排在前面。
- 修正：添加新来源后，有时按文件名搜不到新文件夹里的文件。
- 悬浮搜索框的快捷键可以只用一个功能键，比如 F9。
- 修正：用快捷键呼出悬浮搜索框再收起后，主窗口会跳到最前面；在设置里改深浅色或语言后，会跳回第一栏。

- Upgrading from 0.6.3 or earlier: data is now kept in a new place, so after upgrading you’ll need to add your sources again and let it re-index. Your photos and documents themselves aren’t affected.
- A fresh look: colors and fonts now match the website.
- A new installer that looks like the app. If something goes wrong or you cancel halfway, it puts everything back the way it was.
- Much smaller downloads: Standard drops from about 1 GB to about 0.7 GB, and the GPU edition from about 3.5 GB to about 2.5 GB, now in two files.
- Much faster scanning: a first scan of over 100,000 files now takes about 10 seconds instead of about 15 minutes.
- External drives and NAS folders work as sources: you can still search while they’re disconnected, indexing picks up when they’re back, and an external drive is found again even with a new drive letter. Network folders are a Pro feature.
- On PCs without a graphics card, photos default to “Speed first” for faster indexing; you can switch to “Accuracy first” in Settings.
- Better file-name search: when a file name matches, file-name results come first.
- Fixed: files in a newly added source sometimes couldn’t be found by file name.
- The quick search bar shortcut can now be a single function key, like F9.
- Fixed: after calling up the quick search bar with its shortcut and closing it, the main window jumped to the front; changing the theme or language in Settings jumped back to the first section.

## 0.6.3

- 个人版免费，最多为 2 万个文件建索引；超出的文件升级专业版后自动补上，已经建好的照常能搜。
- “全部磁盘”的文件名搜索和导出索引，个人版也能用了。
- 专业版改为一次买断，含一年免费升级。
- 新图标“放大镜里的团子”，程序改名 ThreebrookSeek.exe；安装向导有团子陪着装。
- 启动更快：资料多时打开就能搜，不再每次启动都把所有文件重新扫一遍。
- 建索引更快：视频画面每帧只算一次，同一个文件的声音只解码一次。
- 修正：升级安装时关不掉正在运行的三溪寻影、再次双击快捷方式没反应。
- 显卡运行库加载不了时自动改用处理器，并说明原因。
- 修正：悬浮搜索框偶尔停在旧画面，看不到输入框。
- 试用结束后，会议模式、代码内容、旧版 Office / WPS 按专业版功能处理；试用期间已经加入的照常能搜，激活后自动补上。

- The Personal edition is free and indexes up to 20,000 files. Files beyond that are added once you upgrade to Pro, and everything already indexed stays searchable.
- File-name search across “All drives” and exporting the index now work in Personal too.
- Pro is now a one-time purchase with a year of free updates.
- A new “Tuanzi in a magnifying glass” icon, the app is now ThreebrookSeek.exe, and Tuanzi keeps you company in the installer.
- Faster startup: large libraries are searchable right away, without rescanning every file each time the app opens.
- Faster indexing: each video frame is processed once, and each file’s audio is decoded once.
- Fixed: upgrading couldn’t close a running Threebrook Seek, and double-clicking the shortcut again did nothing.
- If the GPU runtime can’t load, the app switches to the processor and tells you why.
- Fixed: the quick search bar sometimes showed an old frame without the search box.
- After the trial, meeting mode, code contents and older Office / WPS files work as Pro features. Anything added during the trial stays searchable, and the rest is added once you activate.

## 0.6.1

- 新名字：三溪寻影（原名“超级相册”）。
- 安装包分成标准版（1 GB，一个文件）和显卡加速版。
- 修正：浏览器、WPS 等导出的部分 PDF，里面的文字（比如合同里的“违约金”）按关键词搜不到。
- “时刻”改为按出游、聚会自动归组，原来的声音片段改名“精彩片段”。
- 中文搜索更准：照片和视频画面会同时参考本机翻译成英文的查询。
- 截图后在搜索框按 Ctrl+V 直接搜；可以用一段声音找相似的声音。
- 智能合集：把一句搜索存成会自己更新的合集。
- “不是这个”：搜错了点一下，以后类似的搜索会把它往后排。
- 会议录音可以导出会议纪要初稿（专业版）。
- 建索引时随时能暂停，图库不再跳动，打字搜索更顺。
- 团子扫描文件夹时有新动作。

- New name: Threebrook Seek.
- Two installers: Standard (1 GB, one file) and GPU accelerated.
- Fixed: words in some PDFs exported from browsers and other apps couldn’t be found by keyword.
- Moments now group trips and get-togethers automatically; the old sound clips are now called Highlights.
- Paste a screenshot into the search box with Ctrl+V to search; use a sound clip to find similar sounds.
- Smart collections: save a search as a collection that keeps itself up to date.
- “Not this one”: one click pushes a wrong result down in similar searches.
- Export draft meeting minutes from recordings (Pro).
- Indexing pauses instantly, the gallery no longer jumps around while indexing, and typing in search is smoother.
- Tuanzi has new animations while scanning folders.
- In the English interface, drag-and-paste tips now say “chat apps”.

## 0.6.0

- 新名字：三溪寻影（原名“超级相册”）。
- 安装包分成标准版（1 GB，一个文件）和显卡加速版。
- “时刻”改为按出游、聚会自动归组，原来的声音片段改名“精彩片段”。
- 中文搜索更准：照片和视频画面会同时参考本机翻译成英文的查询。
- 截图后在搜索框按 Ctrl+V 直接搜；可以用一段声音找相似的声音。
- 智能合集：把一句搜索存成会自己更新的合集。
- “不是这个”：搜错了点一下，以后类似的搜索会把它往后排。
- 会议录音可以导出会议纪要初稿（专业版）。
- 建索引时随时能暂停，图库不再跳动，打字搜索更顺。
- 团子扫描文件夹时有新动作。

- New name: Threebrook Seek.
- Two installers: Standard (1 GB, one file) and GPU accelerated.
- Moments now group trips and get-togethers automatically; the old sound clips are now called Highlights.
- Paste a screenshot into the search box with Ctrl+V to search; use a sound clip to find similar sounds.
- Smart collections: save a search as a collection that keeps itself up to date.
- “Not this one”: one click pushes a wrong result down in similar searches.
- Export draft meeting minutes from recordings (Pro).
- Indexing pauses instantly, the gallery no longer jumps around while indexing, and typing in search is smoother.
- Tuanzi has new animations while scanning folders.
