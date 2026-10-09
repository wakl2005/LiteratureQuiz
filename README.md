# 文学常识每日一练 App

## 构建方法

1. 安装 [Android Studio](https://developer.android.com/studio)
2. 打开 Android Studio → `Open` → 选择本项目文件夹
3. 等待 Gradle 同步完成
4. 点击 `Build` → `Build APK`
5. APK 文件在 `app/build/outputs/apk/debug/app-debug.apk`

## 安装到手机

将 APK 文件传到手机安装即可。

## 配置

修改 `MainActivity.java` 中的 URL 可以加载不同页面：
```java
webView.loadUrl("https://wakl2005.github.io/my-small-web/sql-daily/");
```
