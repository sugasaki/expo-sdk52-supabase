# expo-sdk52-supabase

このプロジェクトは [Expo](https://expo.dev) と [Supabase](https://supabase.com/) を利用したReact Nativeアプリのサンプルです。

## セットアップ手順

1. 依存パッケージのインストール

   ```bash
   pnpm install
   # または npm install / yarn install
   ```

2. 環境変数の設定

   プロジェクトルートに `.env` ファイルを作成し、以下の内容を記載してください。

   ```env
   SUPABASE_URL=your_supabase_url
   SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

   ※ `.env.sample` を参考にしてください。
   ※ `.env` ファイルは `.gitignore` で管理され、リポジトリには含めません。

3. アプリの起動

   ```bash
   npx expo start
   ```

   出力に従って、iOS/AndroidシミュレータやWebでアプリを開くことができます。

## 主な機能

- Homeタブに「ユーザー一覧を取得」ボタンあり
- ボタンを押すとSupabaseの `users` テーブルから最大5件のユーザーを取得・表示
- Supabase連携のサンプル実装

## 注意事項

- SupabaseのURLやAPIキーなどの秘匿情報は必ず `.env` ファイルで管理してください。
- `app.json` やソースコードに秘匿情報を直接記載しないでください。

## 参考リンク
- [Expo公式ドキュメント](https://docs.expo.dev/)
- [Supabase公式ドキュメント](https://supabase.com/docs)
- [react-native-dotenv](https://github.com/goatandsheep/react-native-dotenv)

---

何か問題や質問があればIssueやPRでご連絡ください。
