Kilin 的音樂管理系統
一個結合 RESTful API 設計的全端音樂管理系統，整合 YouTube 播放功能與互動式前端小遊戲。

[系統連結]
前端網站: https://kilin945.github.io/gittest1140409/project/
首頁: 包含多個 AI 製作的純前端小遊戲

[專案簡介]
本專案展示了現代化的網頁應用程式架構，包含：
RESTful API 設計架構
Docker 容器化部署技術
Railway 雲端託管服務
Google OAuth 2.0 整合
互動式前端應用程式

[技術架構]
[前端技術]
開發語言: HTML、CSS、JavaScript
部署平台: GitHub Pages
特色功能:
AI 製作的互動小遊戲
響應式網頁設計
YouTube API 整合

[後端技術]
API 設計: RESTful 架構
部署方式: Docker 容器化
託管平台: Railway

[資料庫]
系統: MySQL
部署: Railway 雲端平台

[音樂系統功能]
本系統採用 RESTful 設計，可直接在前端網頁操作，透過後端 API server 管理資料庫內容。

[核心功能]
使用者管理
遊客身份登入
使用者註冊與登入
音樂庫管理
新增歌手、歌曲、專輯、使用者資料
查詢所有歌曲（含分頁功能）
音樂排行榜
建立個人播放清單
管理清單內歌曲
YouTube 整合
Google 帳號授權登入
YouTube 影片播放
自動儲存影片網址

[使用說明]
系統操作步驟
初次使用
進入音樂系統，選擇「遊客身份」登入
建立帳號
登入後，前往「新增使用者」
設定您的帳號密碼
返回登入畫面後使用新帳號登入
提示：忘記密碼可使用萬用密碼 "super"（僅供測試）
建立音樂庫
新增喜愛的歌手
新增歌曲（可參考排行榜）
使用分頁功能瀏覽更多內容
管理播放清單
建立個人播放清單
將歌曲加入播放清單

[YouTube 播放功能]
進入播放音樂介面
使用 Google 帳號登入（需先聯絡 Kilin 加入 OAuth 測試名單）
系統將自動播放 YouTube 音樂並儲存網址

[系統架構]
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│    前端      │────▶│  API 伺服器  │────▶│   資料庫     │
│(GitHub Page)│     │  (Railway)  │     │   (MySQL)   │
└─────────────┘     └─────────────┘     └─────────────┘
                           │
                           ▼
                    ┌─────────────┐
                    │ Google OAuth│
                    └─────────────┘
[注意事項]
Google OAuth 功能需要預先申請測試權限
請聯絡開發者加入測試名單

[聯絡資訊]
開發者: Kilin
Email: kilin0323@icloud.com
GitHub: https://github.com/Kilin945

本專案展示全端開發能力，包含 RESTful API 設計、雲端部署及第三方服務整合。
