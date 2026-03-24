# dsa

Python でデータ構造とアルゴリズムの基礎を学ぶためのリポジトリです。主な教材は Jupyter Notebook です。

## 使い方

1. Python 3.11 系を用意する（`.python-version` を参照してもよい）。
2. 仮想環境を作り、`pip install -r requirements.txt` で Jupyter を入れる。
3. `notebooks/00_overview.ipynb` から開く。

## ノートの構成

| ファイル | 内容 |
|----------|------|
| `notebooks/00_overview.ipynb` | 全体像・スコープ・進捗・各 Phase へのリンク |
| `notebooks/phase0_foundation.ipynb` 〜 `phase5_integration.ipynb` | 各 Phase 専用（末尾に **感想** テンプレあり） |

命名は `00_overview` と `phaseN_*` で並びが分かるようにしてある。

## 任意

- 長いコードは `src/` に切り出す。
- テストを書く場合は `tests/` を使う（ツールは未固定。必要なら `pytest` を追加する）。
