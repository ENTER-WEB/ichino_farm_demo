# 苺希ファーム / ICHIGO FARM — デモサイト（パスワード保護）

クライアント確認用のデモサイトです。`index.html` は staticrypt によりクライアントサイドで暗号化されています（AES-CBC + PBKDF2 + HMAC）。閲覧には共有されたパスワードが必要です。

- 画像は `assets/` 配下に配置
- 検索エンジン非掲載（`robots.txt` で Disallow）
