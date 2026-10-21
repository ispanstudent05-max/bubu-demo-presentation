# 補補 七個功能情境展示

這是獨立 HTML 簡報，不屬於補補產品程式，也沒有上傳到共用 GitHub。

## 播放

直接雙擊 index.html 即可，用瀏覽器開啟，不必 npm install 或啟動伺服器。圖片、Logo、用品圖示及 Chiron GoRound TC 字體已內嵌，可離線使用。將補補操作網站放左側、簡報視窗放右側，建議簡報寬度640～900px。頁面內容較高時可捲動，不會縮小到難以閱讀。

方向鍵 ← →、PageUp / PageDown 切頁；Home / End 到首末頁。底部選單可直接跳功能。N 開關講稿（正式講解預設隱藏）。通知四張圖可點擊放大，左右切圖，Esc 關閉。瀏覽器列印可列印全部14頁，或另存PDF；印製版依紙張可能重新分頁，主要交付仍為HTML。

內容順序依 Demo.docx 最後版本：F2 → F1 → F3 → F4 → F5 → F6 → F7；七個功能保留原編號，不重新編號。14頁包含研究開場、F1估算示例、F4四張圖及通知限制、收尾及可選備答。F1公式頁與最後備答可依現場時間略過。

## 個人帳號部署

只需把 index.html 上傳至你自己的獨立靜態網站或新建的個人儲存庫。所有素材已內嵌，不必上傳 assets、slides-content.json、驗證截圖或本說明。若使用 Vercel 靜態部署，可不設 Framework 與 Build Command，將 index.html 放發布根目錄；依平台目前介面確認部署設定。這份檔案不會初始化、清除或修改補補的 localStorage；也不包含任何登入資訊、API金鑰或資料備份。

本次沒有替你建立個人儲存庫、部署、Commit、Push、Merge，亦未修改共用專案檔案。

## 來源與範圍

- 主要文字：使用者提供的 /Users/mei/Downloads/Demo.docx。問卷35/47、32/47與訪談A/D為文件敘述，未另行查核原始資料。
- 視覺：補補專案 tokens、Logo、用品圖示與 Chiron GoRound TC 字體（由Google Fonts取得子集）；網站 https://home-restock-app.vercel.app/ 。
- 四張原始Figma畫面：https://www.figma.com/design/7Am2bN1HLIYG2vwiJkbMKu?node-id=2896-2157 。節點分別為2896:2159、2896:2231、2896:2483、2898:2161；未修改原始Figma。
- 通知規則：專案 nativeNotifications、ShoppingView、notificationDemoEligibility 與 docs/NATIVE_NOTIFICATIONS.md。
- 瀏覽器通知說明：https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API 與 https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorkerRegistration/showNotification 。通知由作業系統呈現，網址與瀏覽器識別等不由網頁任意控制；icon支援與顯示外觀依平台而異，不能承諾使用Logo就能取代所有瀏覽器圖示。

請同時閱讀 CONTENT_REVIEW.md，避免把文件舊數值與目前展示資料混用。
