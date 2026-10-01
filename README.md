# 微信路

`stra.werecord` · `2.1.2-private` · versionCode 8 · Android SDK 36

完整源码为 `WeixinLu-source-Android17.zip`。使用 JDK 17 解压执行 `./gradlew testDebugUnitTest assembleDebug`。GitHub Actions 对源码运行回归测试并实际编译。

本版重新设计会话导航、消息记录卡片、统计排版及工作台，修复系统栏对比度和搜索区域拥挤。保留已有聚合统计与缓存、ROOT/SQLCipher 数据库修改路径、编辑模式检查和详细诊断。

Actions 原始 APK 使用临时签名；交付 APK 在本地沿用既有密钥。真机数据库操作仍需设备验证。
