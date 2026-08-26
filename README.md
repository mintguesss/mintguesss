<div align="center">

# Ken Huang　黃予岑

**電腦視覺 · 機器學習 · 全端開發**

輔仁大學資訊管理學系畢業（班排前十 / 書卷獎），2026 年起就讀國立中央大學資訊管理研究所。
研究方向是電腦視覺、機器學習應用與情緒辨識；也做 NLP 與全端。
喜歡從零訓練模型、拆解難題，更喜歡把成果做成看得見、用得到的產品。

<br>

[![Portfolio](https://img.shields.io/badge/作品集-mintguesss.github.io-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mintguesss.github.io/personal_web)
[![Email](https://img.shields.io/badge/Email-a03111006@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:a03111006@gmail.com)

</div>

---

## 現在

- 🎓 **國立中央大學 資訊管理研究所** 碩一 —— 電腦視覺 / 機器學習應用 / 情緒辨識
- 🔬 **國科會大專生研究計畫**（114-2813-C-030-031-E）—— 多模態詐騙辨識管線，指導教授：廖建翔
- 🏆 育秀盃創意獎佳作 · 第 42 屆專題發表優秀組別 · 管理學院學術獎章 ×2 · 書卷獎

---

## 代表作

### 🛡️ [騙局雷達 Fraud Radar](https://github.com/Liao-s-Research-Lab/fraud-radar)

多模態詐騙偵測平台。貼文字、貼網址或上傳截圖，幾秒內給出詐騙機率與完整分析報告。
後端整合 **BERT 語意分類**、**PaddleOCR** 截圖取字、無頭瀏覽器爬取網頁，並比對警政署公告的詐騙網站清單交叉驗證。

> 延伸自國科會大專生研究計畫：針對 OCR 辨識不足，以 **NLM 降噪 + Otsu 閾值化** 預處理搭配 **CLIP 零樣本語意篩選** 改善 BERT 輸入品質，AUC-ROC **0.873 → 0.929**

`PyTorch` `BERT` `PaddleOCR` `Flask` `Next.js` `React` `Firebase`

---

### 👀 [個人助理 Personal Assistant](https://github.com/mintguesss/personal-assistant)

用筆電鏡頭即時監測坐姿、專注、情緒與飲水，在對的時機跳桌面通知。純電腦視覺、本機運行、不需穿戴裝置。
四個模型跑在同一條即時影像管線上，並針對實測痛點做工程補償：喝水改用**手勢時間模式**而非辨識容器、坐姿改用**個人化基準校正 + 多訊號投票**取代固定閾值。

`MediaPipe` `YOLOv11` `ViT` `OpenCV` `Python`

---

### 📈 [Folio Manager](https://github.com/mintguesss/Folio-manager)

個人財務 + 投資管理 Web App，可安裝為 PWA。
台股美股均以 **FIFO** 計算已實現損益，美股另存歷史匯率獨立追蹤台幣成本，避免以當日匯率換算失真；盤中依開盤時段動態節流背景同步股價，並用 Supabase RLS 做多使用者資料隔離。

`Next.js` `TypeScript` `Supabase` `Tailwind CSS` `Vercel`

---

## 其他作品

| 專案 | 一句話 | 技術 |
|---|---|---|
| 🧩 [AI 拖延症分析與任務粉碎機](https://github.com/mintguesss/TAICA_LLM) | 分析拖延成因，把大任務粉碎成最小步驟，完成後解鎖可 3D 列印的模型零件（[線上試用](https://taica-llm.onrender.com/)） | `Groq API` `Flask` `Supabase` `STL` |
| 💰 [PromptMiser](https://github.com/mintguesss/PromptMiser) | 即時計算一段文字在各家模型會用掉多少 token、哪家便宜，並壓縮冗詞給出省錢建議 | `Vue 3` `FastAPI` `tiktoken` |
| 📊 [ClaudeQuota](https://github.com/mintguesss/ClaudeQuota) | Windows 系統列小工具，即時顯示 Claude 訂閱的 5 小時與每週用量 | `Python` `Win32 API` |
| 🔐 AI 輔助 WAF 攻擊偵測系統 | Human-in-the-Loop 增量學習 + SHAP 可解釋分析，自動生成 WAF 規則建議 | `PyTAIL` `SHAP` `Transformer` |

---

## 技術棧

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![BERT](https://img.shields.io/badge/BERT-FFB300?style=flat-square&logo=huggingface&logoColor=black)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Web / Data**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

---

<div align="center">

中文（母語）　·　English（TOEIC 810）

更多專案與完整經歷 → **[作品集網站](https://mintguesss.github.io/personal_web)**

</div>
