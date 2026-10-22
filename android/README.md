# 刻时 Android 安装包

这是为了让不支持 PWA 安装的 Android 设备也能把「刻时」放到桌面而提供的 Android 壳。

- 包名：`com.keshi.app`
- 内容：WebView 加载 `https://zxhy197.github.io/keshi/`
- 支持：本地音乐文件选择、Web Audio、localStorage、IndexedDB
- 不包含：原生后台闹钟、系统级通知；提醒边界与 Web 版一致
- 构建：GitHub Actions `.github/workflows/android.yml`
- 产物：debug APK，可直接安装；需在手机上允许「安装未知来源应用」

它不是对 Web 应用的重写，只是安装壳。正式版本仍以 PWA 为准。
