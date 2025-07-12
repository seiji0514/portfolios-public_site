# Netlifyデプロイガイド

## 手順1: Netlifyアカウント作成
1. [netlify.com](https://netlify.com) にアクセス
2. **Sign up** をクリック
3. GitHubアカウントでログイン（推奨）

## 手順2: サイトデプロイ
1. Netlifyダッシュボードで **New site from Git** をクリック
2. **Deploy manually** を選択
3. `seiji-portfolio` フォルダをドラッグ&ドロップ
4. デプロイ完了まで数分待機

## 手順3: カスタムURL設定
1. デプロイ完了後、**Site settings** をクリック
2. **Domain management** を選択
3. **Change site name** でカスタムURLを設定
   - 例: `seiji-portfolio`
   - 結果: `https://seiji-portfolio.netlify.app`

## 手順4: カスタムドメイン設定（オプション）
1. **Domain management** で **Add custom domain**
2. 独自ドメインを入力
3. DNS設定を確認

## トラブルシューティング

### 404エラーが出る場合
- ファイル名の大文字小文字を確認
- パスが正しく設定されているか確認
- ブラウザのキャッシュをクリア

### 画像が表示されない場合
- 画像ファイルが正しいパスにあるか確認
- ファイル名に日本語や特殊文字が含まれていないか確認

## 更新方法
1. ローカルでファイルを編集
2. `seiji-portfolio` フォルダを再度ドラッグ&ドロップ
3. 自動的にデプロイが実行される

## メリット
- **無料**: 月100GB転送量まで無料
- **高速**: CDNによる高速配信
- **簡単**: ドラッグ&ドロップでデプロイ
- **SSL**: 自動でHTTPS対応
- **カスタムドメイン**: 無料で設定可能

## サポート
- [Netlify公式ドキュメント](https://docs.netlify.com/)
- [Netlifyコミュニティ](https://community.netlify.com/) 