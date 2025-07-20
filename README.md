# TOEFL iBT 評価基準リポジトリ

このリポジトリは、TOEFL
iBTのスピーキングとライティングタスクのための日本語評価基準とスコアリングガイドラインを提供します。

## 概要

TOEFL
iBT受験者および指導者向けの評価リソースです。各タスクの採点基準、評価手順、フィードバックテンプレートが含まれています。

## ディレクトリ構成

```txt
.
├── speaking/    # スピーキングタスク評価基準（4問）
│   ├── q1.md   # Independent Speaking Task
│   ├── q2.md   # Integrated Speaking Task (Reading + Listening)
│   ├── q3.md   # Integrated Speaking Task (Listening)
│   └── q4.md   # Integrated Speaking Task (Academic Lecture)
└── writing/     # ライティングタスク評価基準（2問）
    ├── q1.md   # Integrated Writing Task
    └── q2.md   # Writing for an Academic Discussion Task
```

## 使用方法

1. 各タスクのマークダウンファイルを参照してください
2. 評価基準と採点手順に従って評価を行います
3. 提供されているフィードバックテンプレートを活用してください

## 開発

### 必要条件

- Node.js
- pnpm

### セットアップ

```bash
pnpm install
```

### フォーマット

```bash
# コードフォーマット
pnpm format

# フォーマットチェック
pnpm format:check
```
