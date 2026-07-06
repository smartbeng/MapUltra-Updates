# MapUltra 0.8

- 修复关于页检查更新按钮在 macOS 下不可见的问题，改为稳定的蓝色实心按钮并加入像素级可见性自测。
- 修复主页地图总览图在大窗口和高分辨率下仍显示过小的问题，改为按舞台区域自适应铺满。
- 统一 macOS 应用程序入口、菜单栏、Windows 标题栏和任务栏使用 MapUltra 品牌图标。
- 加强 macOS PKG 安装完成判断：安装后确认 /Applications/MapUltra.app、Info.plist、主程序和 MapUltra.icns 均可见，并注册 LaunchServices 后再显示完成。
