<div align="center">

# Ken Huang　黃予岑

**Computer Vision · Machine Learning · LLM Agent · Full-stack**

輔大資管畢業，2026 年起就讀中央大學資管所<br>
Research —— 多模態詐騙偵測、即時電腦視覺，訓練與調校模型<br>
Engineering —— PyTorch 模型部署、可驗證的 LLM Agent，Flask / Next.js 前後端

<br>

<a href="https://mintguesss.github.io/personal_web"><img src="https://img.shields.io/badge/Website-mintguesss.github.io-3B5BDB?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=1A1D23" height="46"></a>

</div>

---

## 🛡️ [Fraud Radar 騙局雷達](https://github.com/Liao-s-Research-Lab/fraud-radar)

多模態詐騙偵測平台。貼文字、貼網址或上傳截圖，幾秒內給出詐騙機率與完整分析報告。
後端整合 **BERT** 語意分類、**PaddleOCR** 截圖取字、無頭瀏覽器爬取網頁，並比對警政署公告的詐騙網站清單交叉驗證。

> 同時延伸至國科會大專生研究計畫〈結合 AI 整合技術以提升詐騙辨識精確度〉：針對 OCR 辨識不足，以 **NLM denoising + Otsu thresholding** 預處理搭配 **CLIP zero-shot** 語意篩選改善 BERT 輸入品質，AUC-ROC **0.873 → 0.929**

`PyTorch` `BERT` `PaddleOCR` `CLIP` `Flask` `Next.js` `React` `Firebase`

---

## 🎓 [Aidit 修業規劃 Agent](https://github.com/mintguesss/aidit)

會查證、會說「不知道」的畢業審查與選課 Agent。[線上展示](https://aidit-weld.vercel.app)
在畢業審查場域，答錯的代價遠高於不答：學分由確定性引擎計算，模型只負責理解意圖；規定沒寫清楚的地方不硬算，改列待確認並告訴你該問誰。

- 算學分、排課、原文回查的模組完全不呼叫模型，**CI 做相依分析**強制隔離
- 每條結論附規定原文引句，對不上就降級為待確認
- 35 案 golden set **錯答 0**；真實成績單 **10/10**，同一模型直接算 20 次只對 9 次
- 提示注入攔截率 **100%**、誤攔率 0%

`Next.js` `TypeScript` `Supabase` `Claude API` `LLM Agent`

---

## 👀 [Personal Assistant 個人助理](https://github.com/mintguesss/personal-assistant)

用筆電鏡頭即時監測坐姿、專注、情緒與飲水，並即時以桌面通知提示。純電腦視覺、本機運行、不需穿戴裝置。

- **MediaPipe** —— pose / face landmarks，判斷坐姿與是否在座
- **YOLOv11** —— 手部動作偵測，判斷飲水行為
- **ViT** —— 臉部情緒分類
- 四個模型共用同一條 **OpenCV** real-time pipeline

`MediaPipe` `YOLOv11` `ViT` `OpenCV` `Python`

---

## 📈 [Folio Manager](https://github.com/mintguesss/Folio-manager)

個人財務 + 投資管理 Web App，可安裝為 PWA。

- 台股美股均以 **FIFO** 計算已實現損益
- 美股另存歷史匯率獨立追蹤台幣成本，避免以當日匯率換算失真
- 記帳端涵蓋日常開銷、出國旅費與朋友間分帳
- 盤中依開盤時段動態節流背景同步股價
- **Supabase RLS** 做多使用者資料隔離

`Next.js` `TypeScript` `Supabase` `Tailwind CSS` `Vercel`

---

## Other Projects

| Project | What it does | Stack |
|---|---|---|
| 💰 [PromptMiser](https://github.com/mintguesss/PromptMiser) | 即時計算一段文字在各家模型會用掉多少 token、哪家便宜，並壓縮冗詞給出省錢建議 | `Vue 3` `FastAPI` `tiktoken` |
| 🎙️ [nobook](https://github.com/mintguesss/nobook) | 課堂即時轉錄與筆記：手機錄音、筆電本地跑 ASR + LLM，課還沒下就有能照抄的筆記，不呼叫雲端 API | `faster-whisper` `llama.cpp` `FastAPI` |
| 📊 [ClaudeQuota](https://github.com/mintguesss/ClaudeQuota) | Windows 系統列小工具，即時顯示 Claude 訂閱的 5 小時與每週用量 | `Python` `Win32 API` |
| 🧹 [Clean-Contributors](https://github.com/mintguesss/Clean-Contributors) | Claude Code plugin，把不想要的帳號移出 GitHub repo 的 Contributors 名單 | `Shell` `PowerShell` `GitHub API` |

---

<div align="center">

More projects & background → **[Website](https://mintguesss.github.io/personal_web)**

</div>
