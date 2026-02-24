# KVideo-AndroidAPP  杰哥影院 公开版

一个专为KVideo项目设计的Android WebView壳应用，旨在提供一个便捷的电视端浏览器入口。本APP是一个预构建的公开版本，您只需配置您的KVideo项目地址即可开始使用。

## 🚀 主要特性

*   **灵活配置**：APP本身不包含KVideo代码，是一个WebView壳应用。您只需填入已部署并可访问的KVideo项目地址即可。
*   **高级模式**：提供特殊入口进入高级设置，方便您🦌。
*   **体验优化**：支持重力感应方便手机用户使用。
*   **注意事项**：公开版使用随机签名，若有版本更新，直接卸载旧版本后重装即可。


## 🛠️ 如何使用

1.  **安装APP**：获取构建好的KVideo-AndroidAPP APK文件并安装到您的Android设备上。
2.  **配置视频项目地址**：首次启动APP时，系统会引导您填入您的KVideo项目部署地址。
3.  **开始观看**：配置完成后，APP将加载您的KVideo界面，您可以开始浏览和观看视频。


### 🎥 演示视频
https://private-user-images.githubusercontent.com/50967145/554288609-5b5a362e-cbcc-46ce-9b8c-e316abb4641e.mp4?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzE5NTMyMzcsIm5iZiI6MTc3MTk1MjkzNywicGF0aCI6Ii81MDk2NzE0NS81NTQyODg2MDktNWI1YTM2MmUtY2JjYy00NmNlLTliOGMtZTMxNmFiYjQ2NDFlLm1wND9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjAyMjQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwMjI0VDE3MDg1N1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTlkNGEzZGU3ZTllODEzNzRkMzU3MjdhZTQ0OWVjNWIzN2MzMmYyZTI1MzIwZTY2NzU0N2IxZTkxYzZlYTA5MTQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.7vFN_LuGRjE_sr81h-QthBheoKNTET80q6qX4L7dsVg


### 🔄 重置视频项目地址

如果您需要更换或重新配置视频项目地址，只需清除APP的储存空间即可：

*   **Android 设置** -> **应用** -> **杰哥影院 公开版** -> **储存空间** -> **清除数据/清除储存空间**


## ⚙️ 高级模式 (密码: `999`)

高级模式提供额外的观影体验，进入方法有以下两种：

1.  **组合键操作**：
    *   按 **音量键+**，然后在0.5秒内按下 **音量键-**。（反之亦可：先按音量键-，0.5秒内按音量键+）
2.  **长按图标操作**：
    *   在设备桌面长按 **杰哥影院 公开版** 图标，在弹出的菜单中选择 **"杰哥 不要"**。


## ⚠️ 重要提示与系统要求

*   **WebView 壳应用**：此APK是一个纯粹的WebView壳应用。它不包含任何KVideo的实际代码，而是作为一个浏览器，负责加载您已部署的KVideo实例。请确保您的KVideo实例已经部署且可访问。
*   **最低系统要求**：**Android 8.0 (API 26) 及以上。**
*   **白屏问题**：Android 7.0 及更低版本的WebView可能不支持本项目使用的ES2017+ JavaScript特性和现代CSS，这可能导致APP白屏。如遇白屏问题，请尝试升级设备的系统WebView组件，或直接在Android 8.0+ 的设备上使用本APP。


## 🙏 致谢

感谢以下开源项目提供了核心支持：
KVideo: https://github.com/KuekHaoYang/KVideo
