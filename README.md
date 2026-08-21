# Study Tracker / 学習記録トラッカー

A small Python project that records a study session in memory and reports the session count. Its original sequence of code changes and commit messages was replayed as 14 commits to show the project's step-by-step development while learning Git.

学習セッションをメモリ上に記録し、セッション数を表示する小さな Python プロジェクトです。Git を学びながら試行錯誤した開発過程を示すため、元のコード変更とコミットメッセージの順序を 14 個のコミットとして再現しています。

## Run / 実行方法

Requires Python 3. No third-party packages are needed.

Python 3 が必要です。外部パッケージは使用していません。

```bash
python3 main.py
```

Expected output / 実行結果:

```text
[{'subject': 'Python', 'minutes': 30}]
Total sessions: 1
```

## Learning focus / 学習ポイント

- Python lists and dictionaries / Python のリストと辞書
- Adding and counting records / レコードの追加と件数取得
- Small, incremental Git commits / 小さな単位での Git コミット
- Preserving visible development history / 開発履歴の保持

## Current limitations / 現在の制限

- The session values are currently fixed in the source code. / セッションの値はソースコード内に固定されています。
- Data is not persisted after the program exits. / プログラム終了後にデータは保存されません。
- There is no interactive input or automated test suite yet. / 対話入力と自動テストはまだありません。

## Provenance / 制作情報

The source code and incremental commit sequence are Kanata Araki's learning work. The bilingual README organization and editing were prepared with AI assistance. No open-source license is granted.

ソースコードと段階的なコミットの流れは、荒木奏多の学習成果です。このバイリンガル README の構成と編集には AI の支援を利用しています。オープンソースライセンスは付与していません。
