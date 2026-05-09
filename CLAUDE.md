# CLAUDE.md

## プロジェクト概要

**PRESSFIELD** — Industry News Curator

業界ニュースをキュレーションして表示するシングルページWebアプリケーション。

## ファイル構成

- `index.html` — メインアプリケーション（HTML/CSS/JS をすべて含むシングルファイル）
- `README.md` — リポジトリの説明

## 開発ガイドライン

- フロントエンドはバニラHTML/CSS/JSで実装する（フレームワーク不使用）
- ダーク/ライトモード対応（CSS変数で切り替え）
- 日本語・英語の両言語に対応したフォント設定（Montserrat / Noto Sans JP）
- シングルファイル構成を維持する

## ブランチ戦略

- `main` — 本番ブランチ
- `claude/*` — Claude Code による開発ブランチ（main へ auto-merge）

## コーディング規約

- コメントは必要最小限にとどめる
- CSS変数（`:root`）でテーマカラーを管理する
- JavaScriptはシンプルに保ち、不要な抽象化を避ける
