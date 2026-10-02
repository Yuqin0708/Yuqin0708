# 嗨，我是 Rainey👋

資訊管理系畢業，目標是前後端工程師（次要方向：AI 應用工程師）。
我喜歡把想法做成真的能運作的東西：從 Vue 前端、FastAPI 後端，到模型推論服務，都自己串過。

📍 Taiwan

## 🛠 技術

| 領域 | 實際用過的工具 |
|---|---|
| 前端 | Vue 3（Composition API）、TypeScript、Pinia、Vite、Tailwind CSS、shadcn-vue、Vuetify、Quasar、Axios、WebSocket、Cytoscape.js |
| 後端 | Python、FastAPI、Streamlit |
| AI／資料 | PyTorch、torchvision、OpenAI API、Power BI、SQL |
| 工具 | Git / GitHub、pnpm / Yarn、Poetry |

## 📌 精選作品

### 🎲 [Lorrator](https://github.com/jason9294/Lorrator)（團隊專題）
基於**知識圖譜與 LLM 的 RAG TRPG 遊戲主持人代理系統**：主持人上傳劇本，系統自動建立知識圖譜與向量索引，玩家在房間中與 AI 主持人即時互動。
我負責 **前端**：
- Vue 3 + TypeScript + Pinia + shadcn-vue + Tailwind CSS
- 以單一 WebSocket 連線搭配訊息型別分派，實作 AI 即時回應與動態「輸入中」提示
- 以 Cytoscape.js（fcose 佈局）做劇本知識圖譜視覺化，調整佈局參數解決節點重疊
- 亮色／暗色主題與 Ctrl+K 節點搜尋

### 🐱 [cat-breed-classifier](https://github.com/Yuqin0708/cat-breed-classifier)
上傳貓咪照片，辨識 12 種常見品種；最高機率低於 75% 時判定為米克斯。
**Vue 3 + Vuetify → FastAPI → PyTorch ResNet50**，包含前端、後端推論 API 與訓練腳本。

### ✏️ [English-writing-bot-1](https://github.com/Yuqin0708/English-writing-bot-1)
英文寫作小老師：用 OpenAI 提供文法修正、更自然的寫法與中翻英。
**Python + Streamlit + OpenAI API（gpt-4o-mini）**，可在側邊欄輸入自己的 OpenAI API Key 線上試用。

### 💬 [rag-knowledge-base](https://github.com/Yuqin0708/rag-knowledge-base)
以自訂知識庫為基礎的問答系統（RAG）：新增知識後，系統以 OpenAI 產生向量並存入 ChromaDB，提問時檢索最相近的 3 筆知識，再由 GPT 依這些內容回答。
**Vue 3 + Vuetify + TypeScript → FastAPI → ChromaDB + OpenAI**，包含聊天頁、知識庫新增／搜尋／編輯／刪除，並附 mock server 可在沒有 API Key 時試用前端。

## 📫 聯絡
mail:hello@yuqin.dev
