---
layout: default
title: Obsidian Vault Sync
---

# Obsidian Vault Sync

Obsidian Vault Sync は、運用者本人の Obsidian Vault を Windows と Linux の間で同期するための個人用設定です。一般向けの同期サービスや、Obsidian 公式のサービスではありません。

Linux 上の rclone が Google Drive API を利用し、指定した Google Drive フォルダと端末内の Vault を双方向に同期します。Windows 側は Google ドライブの同期機能を使用します。

同期にはファイルの一覧取得、読み取り、作成、更新、削除を使用します。同時編集による競合は両方の版を保存し、Linux の同期処理による置き換え・削除前のファイルはバックアップへ退避します。

詳しいデータの扱いは [プライバシーポリシー](privacy.html) を参照してください。

運用者: Fizor。問い合わせ先: [GitHub Issues](https://github.com/Fizor-drm/obsidian-vault-sync/issues)。秘密情報や Vault の内容は投稿しないでください。
