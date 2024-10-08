# キャッチアップ用テンプレート集

フレームワーク・ランタイム・BAAS など、新しい技術が出たときに、勉強用の app をまとめたリポジトリ。
どの技術が来ても、下記のアプリを作ることで、技術習得を効率化することを目的にする。
フレームワークごとの違い（開発のしやすさ・課題・ペイン）をいち早く理解することが可能。

## 作成するもの

- EC プラットフォーム

  - ユーザー認証: ユーザー登録、ログイン、ログアウト
  - 商品カタログ: 商品の一覧表示、詳細表示、検索、フィルタリング（商品データの管理と表示）
  - カート機能: 商品の追加、削除、数量変更、カートの保存（セッション管理またはデータベースに保存）
  - 注文処理: 注文確認、支払い処理（サードパーティの決済ゲートウェイ統合）
  - 注文履歴: ユーザーの注文履歴表示、注文詳細
  - 商品管理: 管理者用の商品追加、編集、削除（管理者専用のダッシュボード）
  - レビュー機能: 商品レビューの投稿と表示（ユーザーからのフィードバック収集）
  - おすすめ商品: ユーザーの行動に基づいた商品レコメンデーション
  - セール/クーポン機能: 割引やクーポンの適用

- マーケティングツール
  - キャンペーン管理: キャンペーンの作成、編集、削除（キャンペーンの詳細情報管理）
  - メール配信: メールテンプレート作成、メールリスト管理、メール送信（メール送信機能）
  - レポートと分析: キャンペーンのパフォーマンス分析、レポート作成（データの可視化）
  - リード管理: リードの追加、管理、フォローアップ（リードの情報管理）
  - A/B テスト機能: メールの A/B テスト実施、結果分析
  - ソーシャルメディア統合: ソーシャルメディアへの投稿、分析（外部 API の統合）
  - 顧客セグメンテーション: 顧客グループの作成、ターゲティング（詳細な顧客管理）
- チャットツール
- ブログツール

## 使い方

- 0 から作るもよし！
- 既存のテンプレートからリポジトリを分けて、一部を変えるもよし！
  - 例: 認証機能だけ新技術を入れたい。
    - Supabase Auth → Clerk にしたいなど。

## Other
- https://www.freepublicapis.com