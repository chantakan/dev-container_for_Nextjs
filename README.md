# Next.js + TypeScript + Tailwind CSS DevContainer Template

## 🚀 概要
このプロジェクトは、DevContainerを使用したNext.js、TypeScript、Tailwind CSSの開発環境テンプレートです。VSCodeのDevContainer機能を使用することで、チーム全体で統一された開発環境を簡単に構築できます。

## 📋 前提条件
- Docker Desktop
- Visual Studio Code
- VSCode Dev Containers 拡張機能

## 🛠️ セットアップ手順

1. リポジトリのクローン
```bash
git clone <your-repo-url>
cd <your-project-name>
```

2. VSCodeでプロジェクトを開く
```bash
code .
```

3. DevContainerで開く
   - `F1`キーもしくは`Ctrl + Shift + P`を押してコマンドパレットを開く
   - `Dev Containers: Reopen in Container`を選択

4. 環境構築の完了待ち
   - コンテナのビルド
   - 依存関係のインストール
   - VSCode拡張機能のインストール

## 🎯 機能
- ⚡️ Next.js
- 🔷 TypeScript
- 🎨 Tailwind CSS
- 📝 ESLint
- 🎁 VSCode設定の自動化
- 🔄 ホットリロード対応
- 🐳 Docker環境

## 📁 プロジェクト構成
```
.
├── .devcontainer/
│   ├── devcontainer.json  # DevContainer設定
│   └── Dockerfile         # Dockerイメージ定義
└── my-project/           # Next.jsプロジェクト
    ├── app/              # アプリケーションコード
    ├── public/           # 静的ファイル
    └── ...              # その他の設定ファイル
```

## 💻 開発サーバーの起動
コンテナ内で以下のコマンドを実行:
```bash
npm run dev
```
→ http://localhost:3000 でアクセス可能

## 🔧 環境のカスタマイズ
- `.devcontainer/devcontainer.json`: VSCode拡張機能や設定の追加
- `.devcontainer/Dockerfile`: 追加パッケージのインストールなど
- `next.config.ts`: Next.jsの設定カスタマイズ
- `tailwind.config.ts`: Tailwind CSSの設定調整

## 📜 利用可能なスクリプト
```bash
npm run dev    # 開発サーバー起動
npm run build  # プロダクションビルド
npm run start  # プロダクションサーバー起動
npm run lint   # リント実行
```

## 🤝 コントリビューション
1. このリポジトリをフォーク
2. 新しいブランチを作成
3. 変更をコミット
4. プルリクエストを作成

## 📝 ライセンス
[MITライセンス](LICENSE)