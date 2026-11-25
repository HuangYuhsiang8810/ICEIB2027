# DIC3 IEEE conference paper draft

這份英文初稿以 DIC3 期中報告 v4 為來源，沿用 ICEIB2027-IEEE 的 IEEEtran 雙欄格式與章節結構。

## Overleaf

將 `ICEIB2027-IEEE/` 資料夾內的檔案打包成 ZIP，讓 `main.tex` 位於 ZIP 根目錄。在 Overleaf 選擇 **New Project → Upload Project** 匯入，主檔設為 `main.tex`，編譯器選 pdfLaTeX。本機可在此資料夾執行 `latexmk -pdf main.tex`。

## 投稿前待確認

- 在 `main.tex` 補上作者英文姓名、單位和聯絡資訊。
- 核對十個有向區間、M05A 歷史檔版本、模型設定與分天信賴區間，補上足以重現結果的細節。
- 加入獨立校準資料的預警結果，以及 Agent 引用與出發建議的端到端評估。
- ICEIB 官網目前規定全文 4–8 頁，投稿前請再確認格式要求。https://www.iceib.asia/
