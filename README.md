# React TypeScript アプリケーション

## 環境構築
- Docker
- React 18 (TypeScript)

## 開発環境の起動方法
1. Reactプロジェクトの作成
   ```bash
   docker compose run --rm app npx create-react-app . --template typescript
   ```

2. 開発環境の起動
   ```bash
   docker compose up -d
   ```

3. `http://localhost:3000` にアクセス

4. 開発環境の停止
   ```bash
   docker compose down
   ```

## 技術スタック
- React 18
- TypeScript
- Docker

## ファイル構成
- `react` ディレクトリ: Reactプロジェクトのファイル
- `compose.yml`: Dockerコンテナの設定
- `.docker/Dockerfile`: Dockerイメージの設定
