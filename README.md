# MISSav

由「网址一键转 App」工具生成的 Android WebView 工程。

- 目标网址：https://missav.ai/dm247/cn
- 包名：com.example.webapp

## 打包成 APK 的三种方式

1. GitHub 云构建（无需安装安卓环境）：把本文件夹内容作为仓库根目录上传到 GitHub 新仓库，
   打开 Actions 页面等待 Build APK 完成，在 Artifacts 下载 APK。每次 push 也会自动重新构建。
2. Android Studio：打开本工程，菜单 Build > Build Bundle(s)/APK(s) > Build APK(s)。
3. 命令行：安装 Android SDK 并配置 ANDROID_HOME 后，在工程根目录执行 gradle assembleDebug，
   产物在 app/build/outputs/apk/debug/。

## 修改

- 网址：app/src/main/java/com/example/webapp/MainActivity.java 中的 HOME 常量。
- 名称：app/src/main/res/values/strings.xml 的 app_name。
- 主题色：app/src/main/res/values/colors.xml 的 colorPrimary。
- 图标：app/src/main/res/drawable/ic_launcher.xml。

请仅封装你有权访问且内容合法合规的网站。
