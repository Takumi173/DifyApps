# [Dify](https://dify.ai/)で作ったアプリ置き場
### 注意事項等
 * テスト目的であれば、公開アプリは自己責任でご自由にお試しいただいて構いません。
 * すべての実行ログはDifyサーバーに記録され、アップロードファイルもDifyサーバーで管理されます。
 * 誤ったファイルがアップロードされても、**作者はファイルは削除することができません。**
 * 出力内容は大規模言語モデルによるものであり、誤った内容が出力される可能性があります。
 * 事前予告なく仕様の変更やNotionのデータを削除する可能性があります。

### 免責事項・その他
 * 本ツールの使用によって生じたいかなる損害に対して、作者は一切の責任を負いません。
 * 本リポジトリは製薬協および所属会社と一切関係がありません。
 * 本リポジトリはMITライセンスの下に配布されます。

## TransNoter
### URLs
 * [入力先（Dify Web App）](https://udify.app/workflow/bT39YVjUcafCyD5o)（[DSL(yml)ファイル](https://github.com/Takumi173/DifyApps/blob/main/TransNoter.yml)）
 * [出力先（Notion）](https://faithful-second-0c8.notion.site/1294e9e7f43f80f19c6ec18093650408?v=9a79ac16d80f4851b96fccc8e5fcf2a9&pvs=4)

### 機能
 * DifyAppに入力したファイルまたはURLからテキストを取得し、要約と翻訳結果をNotionに送ります。
 * Webサイトによってはテキストが取得できないこともあります。

## WholeTranslation
### URLs
 * [入力先（Dify Web App）](https://udify.app/workflow/Zzw17wlR8GML01Sn)（[DSL(yml)ファイル](https://github.com/Takumi173/DifyApps/blob/main/WholeTranslation.yml)）

### 機能
 * ファイルまたはURLのテキストの全文翻訳結果を、指定のNotionページに返します。
 * TransNoterの一部として構成しています。入力画面はありますが、単体での使用は想定しません。
