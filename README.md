# ポストジェネレーター

業務用のSNS投稿文を自動生成する個人用ツールです。

---

## 🚀 使い方（GitHub Pages）

1. GitHubでリポジトリを作成
2. `index.html` をアップロード
3. Settings → Pages → Branch: `main` → Save
4. `https://ユーザー名.github.io/リポジトリ名/` でアクセス

### スマホのホーム画面に追加
- **iPhone**: Safariで開く → 共有ボタン → 「ホーム画面に追加」
- **Android**: Chromeで開く → ⋮ → 「ホーム画面に追加」

---

## ☁️ クラウド同期（端末間同期）

Google Apps Script（GAS）を使って、PC・スマホ間でデータを同期できます。

1. `Code.gs` の内容を Apps Script に貼り付け
2. ウェブアプリとしてデプロイ（アクセス: 全員）
3. 発行されたURLを、アプリの「マスタ → クラウド同期設定」に各端末で入力

更新時刻の新しい方を優先する方式のため、どちらの端末で編集しても自動的に揃います。

---

## 🛠️ 技術仕様

- HTML / CSS / JavaScript（フレームワーク不使用）
- Claude API（AI機能）
- localStorage によるデータ保持
- Google Apps Script によるクラウド同期
- GitHub Pages でホスティング

---

## ⚙️ 設定について

業務ルール・テンプレート・マスタなどの具体的な設定は、アプリ内の「マスタ」タブから登録・編集します（このリポジトリには含めていません）。
