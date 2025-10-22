APIKey Tool v1.0.5 - 使用说明
====================================

快速开始
--------
1. 确保以下文件在同一目录：
   - 可执行文件（apikey-tool-*）
   - ApiInfo2.0.db（数据库）
   - web/（资源文件夹）

2. 赋予执行权限（Linux/macOS）：
   chmod +x apikey-tool-*

3. 运行程序：
   - Linux: ./apikey-tool-linux
   - macOS: ./apikey-tool-mac 或 ./apikey-tool-mac-arm64
   - Windows: 双击 apikey-tool.exe

4. 浏览器会自动打开 http://127.0.0.1:63464


macOS 安全提示
--------------
如果遇到"无法打开，因为它来自身份不明的开发者"：

方法1：移除隔离属性
xattr -d com.apple.quarantine apikey-tool-mac*

方法2：系统设置
右键点击可执行文件 → 打开 → 点击"打开"


功能说明
--------
✅ API密钥测试（微信/钉钉/飞书等）
✅ Token自动获取和管理
✅ 地图API测试（高德/百度/腾讯）
✅ 开发文档快速访问
✅ 代理支持


访问地址
--------
主页:       http://127.0.0.1:63464
开发文档:   http://127.0.0.1:63464/dev-docs
地图测试:   http://127.0.0.1:63464/map-test


免责声明
--------
⚠️ 本工具仅供学习、测试和合法的API开发使用
• 请确保拥有相关API的合法使用权限
• 请遵守各平台的服务条款和API调用限制
• 使用者需对自己的行为承担全部法律责任
