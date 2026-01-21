# PDF Slide Studio

PDFスライドを複数形式に変換するWebツール。完全にクライアント側で処理されるため、ファイルのアップロードは不要です。

🔗 **[デモサイト](https://toshiki-yasuda.github.io/pdf-slide-studio/)**

## ✨ 機能

- **PDF → 画像変換**: 高解像度PNGとしてZIP形式で一括ダウンロード
- **PDF → PowerPoint**: PPTXファイルとして出力
- **PDF → GIF**: アニメーションGIFとして出力
- **PDF → 長画像**: 縦長の1枚画像として出力（SNS用など）

## 🚀 特徴

- **モバイル対応**: スマートフォン・タブレットでも快適に動作
- **プライバシー重視**: すべての処理はブラウザ内で完結、サーバーへのアップロードなし
- **シンプルUI**: ドラッグ&ドロップまたはタップで簡単操作
- **高品質出力**: 2倍スケールでレンダリング

## 📱 使い方

1. [デモサイト](https://toshiki-yasuda.github.io/pdf-slide-studio/)にアクセス
1. PDFファイルを選択またはドラッグ&ドロップ
1. 処理完了後、希望の形式でダウンロード

## 🛠 技術スタック

- **PDF.js**: PDFのレンダリング
- **JSZip**: ZIP圧縮
- **PptxGenJS**: PowerPoint生成
- **GIF.js**: GIFアニメーション生成
- **Tailwind CSS**: スタイリング、
- **Lucide Icons**: アイコン

## 📂 ファイル構成

```
pdf-slide-studio/
├── index.html    # メインアプリケーション（単一ファイル）
└── README.md     # このファイル
```

## 🌐 ローカルで実行

```bash
# リポジトリをクローン
git clone https://github.com/Toshiki-Yasuda/pdf-slide-studio.git

# ディレクトリに移動
cd pdf-slide-studio

# 任意のローカルサーバーで実行
# Python 3の場合
python -m http.server 8000

# Node.jsの場合
npx http-server
```

ブラウザで `http://localhost:8000` にアクセス

## 📄 ライセンス

MIT License

## 👤 作者

Made with ❤️ by [Toshiki Yasuda](https://github.com/Toshiki-Yasuda)

-----

**AY Consulting** - 愛とAIで、あなたの変革を支援します 
