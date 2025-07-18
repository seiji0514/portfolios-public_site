# ユーザーガイド

## 目次
1. [はじめに](#はじめに)
2. [ログイン・ログアウト](#ログインログアウト)
3. [ゲームの遊び方](#ゲームの遊び方)
4. [成績の確認](#成績の確認)
5. [設定](#設定)
6. [よくある質問](#よくある質問)
7. [トラブルシューティング](#トラブルシューティング)

## はじめに

### システム概要
脳トレゲームシステムは、認知機能の向上を目的とした様々なゲームを提供するWebアプリケーションです。

### 対応ブラウザ
- Google Chrome (推奨)
- Microsoft Edge
- Firefox
- Safari

### 推奨環境
- 画面解像度: 1024x768以上
- インターネット接続: 安定した接続
- JavaScript: 有効

## ログイン・ログアウト

### 初回ログイン
1. ブラウザで `http://localhost:5500/version2/index_limited.html` にアクセス
2. 管理者から提供されたユーザー名とパスワードを入力
3. 「ログイン」ボタンをクリック

### 通常のログイン
1. ユーザー名（メールアドレス）を入力
2. パスワードを入力
3. 「ログイン」ボタンをクリック

### ログアウト
1. 画面右上の「ログアウト」ボタンをクリック
2. または、ブラウザを閉じる

### パスワードを忘れた場合
管理者に連絡してください。

## ゲームの遊び方

### ゲーム一覧
ログイン後、利用可能なゲームが一覧表示されます。

### ゲームの種類

#### 1. 記憶ゲーム
**目的**: 記憶力の向上
**遊び方**:
1. カードが表示される
2. カードの位置を覚える
3. カードが裏返される
4. 同じカードを2枚選んでマッチング
5. すべてのカードをマッチングするとクリア

**コツ**:
- カードの位置を系統的に覚える
- 一度に覚えるカード数を制限する

#### 2. 反応速度ゲーム
**目的**: 反応速度の向上
**遊び方**:
1. 画面に色や形が表示される
2. 指示に従って素早くクリック
3. 正確性と速度を両立させる

**コツ**:
- 集中力を保つ
- 焦らずに正確に操作する

#### 3. 計算ゲーム
**目的**: 計算能力の向上
**遊び方**:
1. 計算問題が表示される
2. 制限時間内に正解を入力
3. 連続正解でボーナスポイント

**コツ**:
- 暗算の練習になる
- 時間配分を考える

#### 4. パズルゲーム
**目的**: 論理的思考力の向上
**遊び方**:
1. パズルが表示される
2. ルールに従ってピースを移動
3. 目標の形に完成させる

**コツ**:
- 全体を見渡してから始める
- 段階的に解く

### ゲームの難易度
- **初級**: 初心者向け
- **中級**: 経験者向け
- **上級**: 上級者向け

### スコアシステム
- **基本スコア**: 正解数 × 10
- **時間ボーナス**: 早く完了するとボーナス
- **連続正解ボーナス**: 連続正解でボーナス
- **総合スコア**: 基本スコア + ボーナス

## 成績の確認

### 個人成績
1. 「成績」メニューをクリック
2. 以下の情報が表示されます：
   - 総プレイ回数
   - 平均スコア
   - 最高スコア
   - プレイ時間
   - 得意なゲーム

### 詳細履歴
1. 「詳細履歴」をクリック
2. 日付別の成績が表示されます
3. ゲーム別の成績も確認可能

### 進歩グラフ
1. 「進歩グラフ」をクリック
2. スコアの推移がグラフで表示されます
3. 改善傾向を確認できます

### ランキング
1. 「ランキング」をクリック
2. 他のユーザーとの比較が可能
3. ゲーム別のランキングも表示

## 設定

### プロフィール設定
1. 「設定」メニューをクリック
2. 以下の項目を変更可能：
   - 表示名
   - メールアドレス
   - パスワード

### ゲーム設定
1. 「ゲーム設定」をクリック
2. 以下の項目を調整可能：
   - 音声のON/OFF
   - 効果音の音量
   - 画面の明るさ
   - 文字サイズ

### 通知設定
1. 「通知設定」をクリック
2. 以下の通知を設定可能：
   - ゲーム開始通知
   - 成績更新通知
   - システムメンテナンス通知

## よくある質問

### Q1: ゲームが重い場合の対処法は？
**A**: 以下の方法を試してください：
- ブラウザを再起動
- 他のタブを閉じる
- インターネット接続を確認

### Q2: スコアが保存されない場合は？
**A**: 以下を確認してください：
- ログイン状態であること
- インターネット接続が安定していること
- ブラウザの設定でJavaScriptが有効であること

### Q3: ゲームが途中で止まる場合は？
**A**: 以下を試してください：
- ページを再読み込み
- ブラウザを再起動
- 管理者に連絡

### Q4: パスワードを変更したい場合は？
**A**: 設定画面から変更可能です：
1. 「設定」メニューをクリック
2. 「パスワード変更」をクリック
3. 現在のパスワードと新しいパスワードを入力

### Q5: ゲームの難易度を変更したい場合は？
**A**: 各ゲームの開始画面で難易度を選択できます。

## トラブルシューティング

### ログインできない
**症状**: ログインボタンをクリックしても進まない
**対処法**:
1. ユーザー名とパスワードを確認
2. 大文字・小文字を確認
3. ブラウザを再起動
4. 管理者に連絡

### ゲームが表示されない
**症状**: ゲーム一覧が表示されない
**対処法**:
1. ページを再読み込み
2. インターネット接続を確認
3. ブラウザの設定を確認

### スコアが反映されない
**症状**: ゲーム終了後、スコアが記録されない
**対処法**:
1. ログイン状態を確認
2. ページを再読み込み
3. しばらく待ってから再確認

### 画面がフリーズする
**症状**: ゲーム中に画面が反応しなくなる
**対処法**:
1. ページを再読み込み
2. ブラウザを再起動
3. 他のタブを閉じる

### 音声が聞こえない
**症状**: ゲームの音声が再生されない
**対処法**:
1. ブラウザの音声設定を確認
2. システムの音量を確認
3. 設定で音声をONにする

## セキュリティについて

### ログインセキュリティ
- パスワードは定期的に変更してください
- 他の人とパスワードを共有しないでください
- 公共のPCでは必ずログアウトしてください

### データの保護
- 個人情報は適切に管理されます
- 成績データは暗号化して保存されます
- 不正アクセスは監視されています

## サポート

### お問い合わせ
問題が解決しない場合は、以下までお問い合わせください：
- **メール**: support@example.com
- **電話**: 03-1234-5678
- **受付時間**: 平日 9:00-18:00

### お問い合わせ時の準備
以下の情報をお知らせください：
- お使いのブラウザ
- エラーメッセージ（ある場合）
- 問題が発生した状況
- お客様の連絡先

## 更新履歴

| 日付 | バージョン | 変更内容 |
|------|------------|----------|
| 2024-01-01 | 1.0.0 | 初版作成 |
| 2024-01-15 | 1.1.0 | ゲーム説明を追加 |
| 2024-02-01 | 1.2.0 | トラブルシューティングを追加 | 