# QRCSV

QRCSVは、CSVデータをQRコードにエンコードするためのフォーマットです。

## デモ
このプロジェクトには、ウェブベースのQRコードリーダーとジェネレーターが含まれています。

## 機能
- QRコードからCSVデータを読み取る
- CSVデータからQRコードを生成する

## 使い方
QRコードからCSVデータを読み取るには:
1. ウェブページを開きます
2. カメラをQRコードに向けます
3. CSVデータがテーブル形式で表示されます

CSVデータからQRコードを生成するには:
1. HTMLにQRコードのスクリプトを読み込みます:
   ```html
   <script type="module" src="https://code4fukui.github.io/qr-code/qr-code.js"></script>
   ```
2. `<qr-code>`タグの間にCSVデータを挿入します:
   ```html
   <qr-code>CSV,HCR_1
   身長,176.0
   体重,64.7
   標準体重,68.1
   </qr-code>
   ```

## ライセンス
MIT License — 詳細は[LICENSE](LICENSE)を参照してください。
