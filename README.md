# Free Market 仕様書

## 概要
- 教育用ミニフリマアプリ。出品一覧、商品詳細、チャット、マイページ、ログインを提供。
- 学習目的：フロントエンドとバックエンドの学習、Supabaseの学習

## 期間
- 要更新：2025年9月25日〜2025年10月5日

## チーム人数
- 要更新：X名

## 担当
- フロントエンド（認証、商品検索、商品追加）、バックエンド（Supabase 、DB設計））

## 使用技術
- フロントエンド: React 19, TypeScript 5
- ビルド/開発: Vite 7（@vitejs/plugin-react）
- ルーティング: React Router 7
- UI: Tailwind CSS 4（PostCSS 8, Autoprefixer）
- アイコン: lucide-react
- BaaS/認証: Supabase JS v2
- 品質: ESLint 9
- 設定ファイル: `vite.config.ts`, `tailwind.config.js`, `tsconfig*.json`

## 背景/工夫した点


## 実行画面


## 今後の展望

- チャットのリアルタイム化（Supabase Realtime/Channels）
- 認証強化（OAuth プロバイダ連携、パスワードレス、RLS の厳格化）
- 検索・フィルタリングの高度化（カテゴリ、価格帯、ソート）
- 通知機能（新着メッセージ、取引更新、出品状況）
- テスト導入（ユニット/コンポーネント/E2E）と CI 連携
- パフォーマンス最適化（コード分割、画像最適化、キャッシング）
- 国際化対応（i18n）