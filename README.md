# 微信路

包名 `stra.werecord`。当前源码 **2.1.5-private / versionCode11**，位于 `WeixinLu-source-Android17.zip`。

修复2.1.4在窗口获得焦点时错误解包DecorView Context导致的启动崩溃，改为直接使用宿主Activity的Window。保留透明胶囊悬浮底栏与局部采样模糊；普通好友详情和更多菜单增加查看消息，按联系人ID打开现有分页会话。保留搜索内存修复、统计聚合缓存、编辑模式隐藏，以及数据库写入和删除实现。

GitHub Actions：JDK17、Android API36，执行测试和实际编译。完整源码含版权和依赖许可，签名密钥单独保管。真机玻璃流畅度、账户字段及大数据量搜索仍需设备验证。
