# AI副業ハック - AdSense対応ブログサイト

## 📁 ファイル構成

```
ai-fukugyou-hack/
├── vercel.json              # Vercel設定
├── README.md
└── public/
    ├── index.html            # トップページ
    ├── about.html            # 運営者情報（E-E-A-T強化）
    ├── contact.html          # お問い合わせ（AdSense必須）
    ├── privacy.html          # プライバシーポリシー（AdSense必須）
    ├── disclaimer.html       # 免責事項
    ├── sitemap.xml           # XMLサイトマップ
    ├── robots.txt            # クローラー制御
    └── posts/
        └── ai-side-business-start-guide.html  # サンプル記事
```

## 🚀 デプロイ手順

### Step 1: GitHubリポジトリ作成
```bash
cd ai-fukugyou-hack
git init
git add .
git commit -m "Initial commit: AI副業ハック"
git remote add origin https://github.com/YOUR_USERNAME/ai-fukugyou-hack.git
git push -u origin main
```

### Step 2: Vercelにデプロイ
1. https://vercel.com → New Project
2. GitHubリポジトリを選択
3. Framework: Other
4. Output Directory: `public`
5. Deploy!

### Step 3: 独自ドメイン設定
- 推奨: `ai-fukugyou-hack.com` / `ai-fukugyou.jp`
- Vercel → Settings → Domains で設定

## 📋 AdSense審査チェックリスト

### ✅ 完了済み
- [x] プライバシーポリシー
- [x] お問い合わせページ
- [x] 運営者情報ページ
- [x] 免責事項
- [x] XMLサイトマップ / robots.txt
- [x] 構造化データ（JSON-LD）
- [x] OGPメタタグ
- [x] レスポンシブデザイン
- [x] 広告配置エリアの事前設計

### 🔲 要対応
- [ ] 独自ドメイン取得
- [ ] 記事を10〜20本追加
- [ ] Google Analytics設定
- [ ] Google Search Console登録・サイトマップ送信
- [ ] Formspree等でお問い合わせフォーム連携
- [ ] SNSアカウントリンク設定

## 📝 記事量産の手順

### 新しい記事を追加
1. `public/posts/` に `ai-side-business-start-guide.html` をコピー
2. タイトル・内容・構造化データを書き換え
3. `index.html` の articles 配列に新記事を追加
4. `sitemap.xml` にURLを追加
5. git push → Vercel自動デプロイ

### Claude Code で記事を量産する場合
```
プロンプト例:
「public/posts/ai-side-business-start-guide.html をテンプレートとして、
 "ChatGPT 副業 始め方" のキーワードでSEO記事のHTMLを作成してください。
 2000文字以上、H2見出し5つ、広告枠3箇所を含めてください。」
```

## 🎯 SEO記事テーマリスト（検索需要順）

### 🔥 最優先（検索ボリューム大）
1. AI副業 始め方
2. ChatGPT 副業
3. AI 稼ぐ方法
4. 副業 おすすめ 2025
5. ChatGPT 稼ぎ方

### 📈 中優先（競合弱い）
6. Claude Code 副業
7. AI ライティング 副業
8. Midjourney 稼ぐ
9. AI ブログ 作り方
10. note 有料記事 売り方

### 💎 ニッチ（差別化しやすい）
11. 社労士 × AI 副業
12. 士業 AI 活用
13. AI 副業 月10万円 ロードマップ
14. ChatGPT プロンプト テンプレート 副業
15. AI ツール開発 副業

## 💰 収益化ロードマップ

| Phase | 期間 | 施策 | 月収目安 |
|-------|------|------|----------|
| 1 | 1-2ヶ月 | AdSense開始 | 1,000-5,000円 |
| 2 | 3-4ヶ月 | アフィリエイト追加 | 5,000-20,000円 |
| 3 | 5-8ヶ月 | noteコンテンツ販売 | 20,000-50,000円 |
| 4 | 9-12ヶ月 | 全チャネル最適化 | 50,000-100,000円 |

### おすすめASP
- **A8.net**: AI系サービス（ChatGPT Plus紹介等）
- **もしもアフィリエイト**: Amazon・楽天の書籍紹介
- **バリューコマース**: クラウドソーシング系
