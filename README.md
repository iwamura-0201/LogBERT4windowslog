# LogBERT4windowslog

LogBERTをWindowsイベントログ用に改変したもの

## 環境構築
```bash
# パッケージのインストール
uv sync
# 仮想環境の起動
source .venv/bin/activate
# 関連パッケージの追加
uv add -r requirements.txt
```

## 動作方法
- 基本的なものは src/recover.ipynb に記述
- 実験は基本的に main.py から動かしていたので、こちらも適宜参照  (ファイル名等若干変更しているので、そのままでは動かないかも)
