# 無障礙功能面試問題

本文翻譯自 [Accessibility Interview Questions](https://github.com/scottaohara/accessibility_interview_questions)。

就利用以下問題展開對話吧。得知對方如何解決問題；如何解讀無障礙、具有包容性的使用者經驗，這比起是否能背誦出規格和鍵盤熱鍵好多了。

問題分類成三種：[一般](#一般)、[技術](#技術)與[設計](#設計)。這些分類可能不正確，但目前就先用這樣來分。如果你有更好的分類方式，或有任何問題，請[跟我們說](https://github.com/ymcheung/accessibility_interview_questions/issues)！理想的情況下，一名面試者應該可以回答每個類別裡的問題。


## 一般
- 無障礙功能可以讓誰受惠？
- 舉出一些足以影響無障礙的響應式/行動優先設計。
- UI 使用圖示系統 (iconography) 的時候，有哪些要注意的使用者經驗？
- 有哪些方法可以把彈出式對話框 (modal dialogue) 關閉？
- 你對修改報讀功能傳遞某些內容的方式有什麼看法？
- 你熟悉哪些桌面和行動裝置的輔助科技 (assistive technologies, ATs)？
	- 你自認對這些輔助科技有多熟悉？
- 請描述標題標籤 (heading tags) 可以用來做什麼？
- 什麼是略過連結 (skip link)？有哪些人會因此受惠？
- 請舉出一些在網站或網頁應用程式，用來測試無障礙的工具。
- 使用簡明語言 (plain language) 對於一份文件的無障礙有什麼好處？


## 技術
- 請說明連結、一般按鈕與送出按鈕的適當使用時機。
- 你會用什麼方法找出一個元素的無障礙名稱？
- 什麼是無障礙樹 (accessibility tree)？
- 為什麼 em 或 rem 比起 px 更適合來設定文字大小？
- 為什麼讓 viewport 能夠縮放很重要？
- 輔助科技會如何顯示 `title` 屬性 (attribute)？
	- `title` 應該要用在什麼種類的內容？
	- 在 `title` 裡，什麼樣的資訊是適當的？
- 請描述可能會用到 `aria-describedby` 的情境。
- 什麼是 landmark rule？好用的地方在哪？
- 你什麼時候會用到開關按鈕 (toggle button)？舉例來說：使用 `aria-pressed` 和/或 `role="switch"` 的 `button`，而不是用勾選 (checkbox) 的？
- 請描述隱藏內容的方法：
	- 對所有使用者
	- 只對螢幕報讀器的使用者
	- 對視力正常的使用者，但螢幕報讀器的使用者不隱藏
- 圖片的 `alt=""` 在哪時候有效果？
- `aria-hidden="true"` 和 `role="presentation"` 有什麼不同？
- 你會如何標示裝飾用的圖示字型 (icon font) 或 SVG？
- 使用 CSS 的 pseudo content 會有什麼問題？
- 你應該，或是建議在何時使用 <abbr>ARIA</abbr> 的 role 或 attribute，藉以解決無障礙問題？
- 請分享要找出無障礙問題是屬於開發者、瀏覽器或輔助科技的錯誤時，你的流程是什麼？
- 關於單頁式 Web 應用程式在讀取新畫面時，處理注意力的方法，你有什麼可以分享的？
- 為何不能只依賴視覺風格來傳達狀態？
- 圖片輪播 (carousel) 功能有什麼問題？


## 設計
- 請以無障礙的角度，談談扁平化 (flat) 與[擬物 (skeuomorphism)](http://whatis.techtarget.com/definition/skeuomorphism) 設計風潮的優點與缺點。
- 請解釋顏色對比 (color contrast) 的重要性。
- 除了 `:hover`，請舉出可操作項目（actionable items，例如：連結、按鈕、表單控制元件...等）的其他狀態。
- 對於把 UI 元件的視覺焦點指示 (visual focus indicator) 移除有什麼看法？
- 如果表單或表單輸入欄位要顯示一錯誤訊息，那你會想讓它出現在哪裡？
- 在介面上使用動畫會如何影響使用者經驗？
- 請簡述你會如何為報讀器的使用者製作無障礙的資訊圖表。
- 改變一般捲軸行為會有什麼問題？例如：無限捲動 (infinite scrolling) 或捲軸綁架 (scrolljacking)。
- 為何只使用顏色時，不足以讓可操作項目引起注意力，或傳達狀態？


## 有想加入的問題？
請開 issue（[中文](https://github.com/ymcheung/accessibility_interview_questions/issues)、[英文](https://github.com/scottaohara/accessibility_interview_questions/issues)），或送來 pull request（[中文](https://github.com/ymcheung/accessibility_interview_questions/pulls)、[英文](https://github.com/scottaohara/accessibility_interview_questions/pulls)），將斟酌納入您的意見。


## 感謝
謝謝所有提供意見的朋友。特別要感謝 [Eric Bailey](https://github.com/ericwbailey) 和 [Ashley Bischoff](https://github.com/handcoding)，提供許多沒有被 Github 記錄起來的貢獻。
