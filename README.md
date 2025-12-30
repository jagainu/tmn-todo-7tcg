# tmn-todo-240102

> **Status**: 🎨 DESIGNING

## 概要

シンプルで使いやすいToDoアプリケーション。タスクの追加、編集、削除、完了状態の変更ができます。

## 機能

- [ ] タスク追加
- [ ] タスク編集
- [ ] タスク削除
- [ ] タスク完了/未完了トグル
- [ ] タスクリスト表示

## 画面

| パス | 画面名 | 説明 |
|------|--------|------|
| `/` | タスクリストページ | すべてのタスクを表示し、新規タスク追加、タスク操作を行うメインページ |
| `/completed` | 完了タスクページ | 完了したタスクを一覧表示するページ |

## データ

### Task

| フィールド | 型 | 説明 |
|-----------|-----|------|
| id | string | タスクの一意の識別子 |
| title | string | タスクのタイトル |
| description | string | タスクの詳細説明 |
| isCompleted | boolean | タスクの完了状態 |
| createdAt | string | タスク作成日時 |
| updatedAt | string | タスク更新日時 |

## 認証

なし

---

## Tech Stack

- Framework: Next.js 14 (App Router)
- Styling: Tailwind CSS + shadcn/ui
- Database: Vercel KV
- Hosting: Vercel
