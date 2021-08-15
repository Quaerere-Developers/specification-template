# 〇〇 API

## 1. コントローラー

| 対象              | イベント         | 条件                                  | 確認内容                  | 備考 |
| ----------------- | ---------------- | ------------------------------------- | ------------------------- | ---- |
| getUserController | ユーザ情報取得　 | email: <br/> password:                | undeifned エラー          |      |
| getUserController | ユーザ情報取得　 | email: user@email.com <br/> password: | password undeifned エラー |

## 2. サービス　

| 対象           | イベント         | 条件                                            | 確認内容                         | 備考 |
| -------------- | ---------------- | ----------------------------------------------- | -------------------------------- | ---- | --- |
| getUserService | ユーザ情報取得　 | email: user@email.com <br/> password: password  | ユーザ情報を返す                 |      |     |
| getUserService | ユーザ情報取得　 | email: user@email.com <br/> password: damyypass | ユーザ情報が存在しないためエラー |      |
|                |                  |                                                 |                                  |      |
