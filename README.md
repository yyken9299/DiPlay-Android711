# DiPlay Android 7.1.1 无线测试版

[下载 APK（约 22 MB）](https://github.com/yyken9299/DiPlay-Android711/releases/download/android711-v0.2.12-test.1/DiPlay-0.2.12-android7.1.1-wireless-test.apk) · [发布页面](https://github.com/yyken9299/DiPlay-Android711/releases/tag/android711-v0.2.12-test.1)

基于 [shihabal3amri/DiPlay](https://github.com/shihabal3amri/DiPlay) v0.2.12（2fc876e）的社区适配测试版。
最低 Android 7.1 / API 25，包含 Android 7.1.1；包名 `com.shihab.diplay.android711`。

车机和 iPhone 连接另一个设备的热点或同一个路由器，双方蓝牙配对，在 DiPlay 选择“已有 Wi-Fi / 同一局域网”，填写该 Wi-Fi 的名称和密码后连接。
无需 USB 接口下载或使用无线连接。Android 7 的 USB 连接在本版本中不可用。

已通过编译、APK 签名验证、三个模块的 NewApi 兼容专项检查，以及 1,215 项测试。
尚未在目标实体车机验证；车机自身热点是否支持连接取决于固件。
桌面地图嵌入仍要求 Android 11，厂商仪表/HUD 功能仍受原固件限制。

发布附件提供 APK、修改后的对应源码 ZIP、中文安装说明、验证记录及 SHA-256 校验文件。
源码 ZIP 包含完整项目与适配改动；其中不包含运行认证文件或 Android 签名密钥。
APK 使用本地调试签名，运行认证资源来自校验过的上游公开 v0.2.12 安装包。

本仓库发布的是社区测试包，并非上游官方发布。完整源码的 GPL-3.0 许可证随附件与本仓库提供。
