# template_react

Docker Dev Container を前提にした **React + Vite** の開発用テンプレートです。コンテナ内では **Node.js 22**（`.devcontainer/devcontainer.json` の `node` feature）が利用されます。

## 前提

- [Docker](https://docs.docker.com/get-docker/) が動作していること
- [Cursor](https://cursor.com/) または VS Code と **Dev Containers** 拡張機能

ローカルに Node.js を入れている場合は、コンテナを使わずに同じ手順で開発できます。

## Dev Container で開く

1. このフォルダを Cursor / VS Code で開く
2. コマンドパレット（`Ctrl+Shift+P` / Mac は `Cmd+Shift+P`）を開く
3. **Dev Containers: Reopen in Container** を実行する

初回はイメージの取得・ビルドに時間がかかることがあります。

## セットアップ

```bash
npm install
```

## 開発サーバー

```bash
npm run dev
```

ブラウザで表示される URL（既定は `http://localhost:5173`）を開きます。終了するときは、そのターミナルで **Ctrl+C** を押します。

## その他のコマンド

| コマンド | 説明 |
| -------- | ---- |
| `npm run build` | 本番用ビルド（`dist/` に出力） |
| `npm run preview` | ビルド結果のローカルプレビュー |
| `npm run lint` | ESLint |

## スタック

- React 19
- Vite 8
- ESLint 9
