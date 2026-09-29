# 微信路（WeixinLu）

这是基于 Android/Kotlin 的个人重制工程，包名为 `stra.werecord`。工程包含源码、Gradle Wrapper、资源和构建说明。

## 获取源码

下载仓库内的 [微信路源码包](./WeixinLu-source-Android17.zip)，解压后使用 Android Studio 打开项目根目录。

## 当前状态

- Android compileSdk / targetSdk 37，minSdk 24
- Kotlin + Java，首页采用 Material 3
- ROOT 独立应用；当前没有集成 LSPosed/Xposed Hook
- 本地消息读取、编辑、删除和数据库写回路径仍在代码中
- 聊天备份记录改为按需加载
- 崩溃日志通过系统分享菜单由用户自行选择接收方

## 构建

工程要求 JDK 17 和 Android SDK Platform 37。执行：

```sh
./gradlew assembleDebug
```

目前没有在本次源代码更新后生成新的 APK。微信兼容性和真机运行尚未验证。

## 许可与来源

原始工程来源、修改记录和第三方组件信息见 `SOURCE_NOTES.md`、`UPSTREAM_README.md` 和 `THIRD_PARTY_NOTICES.md`。本仓库持有者已确认获得发布许可。
