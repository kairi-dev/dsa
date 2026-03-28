# dsa

DSA初学者向けの学習リポジトリ（Python + Jupyter）。

## 学習導線

1. 概念学習: `learn/00_overview.ipynb`
2. 演習: `practice/00_overview.ipynb`

## 構成

- `learn/`: 概念をステップバイステップで学ぶ（実務での使いどころ付き）
- `practice/`: 各Phaseごとに
  - `ex1`: 選択式
  - `ex2`: 穴埋め式

## セットアップ（uv）

```bash
uv sync
uv run python -m ipykernel install --user --name dsa --display-name "Python (dsa)"
uv run jupyter lab
```

## 依存関係

- 依存関係は `pyproject.toml` で管理する。
- 追加ライブラリは `uv add <package>` で入れる。
