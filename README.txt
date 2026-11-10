CozyStep GitHub Pages 安裝說明

1. 將本 ZIP 解壓縮，把 index.html、manifest.json、sw.js、icons 資料夾一起上傳到 GitHub Repository 的 Pages 發布目錄。請勿只上傳 index.html，或多包一層資料夾。
2. GitHub Settings > Pages，選擇發布的分支及目錄，等待部署完成。
3. 用 Android Chrome 開啟正式 HTTPS 網址，等待頁面載入完成。
4. Chrome 右上角選單 >「新增至主畫面」>「安裝」（選項名稱可能因版本而不同）。
5. 完成後回到手機桌面，點新安裝的 CozyStep 圖示。正常應以獨立 App 視窗開啟，沒有 Chrome 網址列。手機狀態列仍可能顯示。

若先前只有網頁捷徑：移除舊捷徑，從正式網址重新安裝。若系統要求解除安裝並刪除資料，請先備份原 App 資料，避免失去現有記錄。
一般 Chrome 分頁開啟網站時仍會有網址列；必須由已安裝的 App 圖示開啟。

路徑採用 ./，會依所在 Repository 自動識別，支援 /co-step/ 或其他 Repository 名稱。請固定使用同一個正式網址安裝。
本次保留原版畫面、功能及 cozystep_state 儲存鍵。資料仍保存在原本的瀏覽器本機，並未新增雲端同步或背景計步。
保留原有 CDN、圖片來源；首次使用需連網。服務工作者會快取主程式與可取得的依賴，但未快取圖片仍需網路。日後修改 sw.js 時，請同步提高 CACHE 版本號。

安裝設定已檢查，預覽已確認；最終手機安裝行為仍需部署後實機驗證。
