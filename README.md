# 微信路

包名 `stra.werecord`，当前源码 `2.1.1-private` / versionCode 7，Android 16 / SDK 36。

完整工程保存在 `WeixinLu-source-Android17.zip`。解压后使用 JDK 17 执行 `./gradlew testDebugUnitTest assembleDebug`。GitHub Actions 对推送的完整源码运行回归测试并重新编译 APK；下载的 Actions APK 使用 runner 临时签名，交付包在本地沿用既有密钥签名。

保留 Material 3 界面、直接初始化入口、数据库聚合与统计缓存、数据库编辑和删除路径。查看模式隐藏修改入口，异常保留堆栈和复制功能。应用内项目链接指向本仓库。

设备上的 ROOT/SQLCipher 操作、微信 8.0.72 和 43 万条消息性能仍需真机验证。构建报告位于源码包内。
