# 朱育奎個人網站

這是一個使用React、Express和PostgreSQL構建的個人介紹網站，展示我的專業技能、工作經驗和項目。

## 網站特色

- 響應式設計，適合不同尺寸的設備（手機、平板、桌面）
- 莫蘭迪色系風格，提供視覺舒適性
- 分區展示個人資訊、技能、工作經驗、項目和聯繫方式
- 訪客可以通過表單發送聯繫訊息
- 後端使用PostgreSQL數據庫存儲訪客訊息

## 技術棧

### 前端
- React
- TypeScript
- Tailwind CSS
- Shadcn UI 組件
- React Query
- React Hook Form

### 後端
- Express.js
- PostgreSQL
- Drizzle ORM
- Zod 驗證

## 功能模塊

1. **自我介紹**：個人頭像、簡介和聯繫資訊
2. **技能展示**：直觀地展示各類專業技能和熟練度
3. **工作經驗**：詳細列出工作經歷和職責描述
4. **項目展示**：視覺化展示已完成的項目和作品
5. **聯繫表單**：訪客可以填寫表單發送訊息

## 網站結構

```
/
├── client/            # 前端代碼
│   ├── src/           # 源代碼
│   │   ├── components/  # 組件
│   │   ├── pages/       # 頁面
│   │   ├── hooks/       # 自定義鉤子
│   │   └── lib/         # 工具函數
├── server/            # 後端代碼
│   ├── routes.ts      # API路由
│   ├── storage.ts     # 數據存儲邏輯
│   └── db.ts          # 數據庫連接
├── shared/            # 前後端共享代碼
│   └── schema.ts      # 數據模型和驗證
├── dist/              # 構建產物
│   └── public/        # 靜態文件
└── README.md          # 項目說明
```

## 部署說明

### 靜態部署
如果您只需要靜態版本的網站（不包含數據庫功能），可以直接使用`website_files.zip`中的文件，將其解壓後上傳到任何網絡託管服務。

### 完整功能部署
如需完整功能（包括數據庫）：

1. 確保環境中安裝了Node.js和PostgreSQL
2. 設置數據庫連接環境變量：`DATABASE_URL`
3. 安裝依賴：`npm install`
4. 執行數據庫遷移：`npm run db:push`
5. 啟動服務：`npm start`

## 聯繫方式

- 電子郵件：yukuizhu9@gmail.com
- 電話：0968-118956
- 社交媒體：Facebook、Instagram

---

© 2025 朱育奎. 版權所有.