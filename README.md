
# Notion Blog
このリポジトリは、NotionAPIを使用して作成されたブログのサンプルプロジェクトです。このブログは、Node.js、Tailwind CSS、そしてNotionAPIを活用して構築されています。  
実際に作成したブログです→ [Notion Blog](https://notion-blog-kappa-lake.vercel.app/)

## 概要
このプロジェクトは、Notionをバックエンドとして使用し、Node.jsを通じてデータの取得と表示を行うシンプルなブログです。Tailwind CSSを使用して、ブログのデザインとスタイリングを実装しました。

## 技術スタック
- Node.js
- Tailwind
- NotionAPI

## セットアップ
以下の手順に従って、このブログプロジェクトをセットアップしてください。

- リポジトリをクローンします。
```
git clone git@github.com:ya-sny/notion-blog.git
```
- プロジェクトディレクトリに移動します。
```
cd notion-blog
```
- 依存関係をインストールします。
```
npm install
```
- .env.local ファイルを編集し、NotionのAPIキーとデータベースIDを設定します。
```
NOTION_TOKEN=your_notion_api_key
NOTION_DATABASE_ID=your_notion_database_id
```
- ブログを起動します。
```
npm run dev
```
- ブラウザで http://localhost:3000 を開いて、ブログを確認します。
