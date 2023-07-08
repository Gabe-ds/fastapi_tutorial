# fastapi_tutorial

## 開発環境

- Pyenv
- Poetry
- Black

## 環境構築

### Pythonのバージョン指定

```bash
pyenv local 3.11.2
```

### 依存環境のインストール

```bash
poetry install
```

## 実行

```bash
poetry run uvicorn main:app --reload
```

## フォーマッター

```bash
poetry run black .
```
