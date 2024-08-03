# example-snowflake

Snowflake に python から接続し、SQL を投げ、結果を pandas で受け取る例。

## 準備

ファイル`credentials/account.json`を作成し、ユーザー名・アカウント識別子・パスワードを保存する。

<span style="font-size: 20rem">⚠️</span> このファイルはコミットしないこと！！

- フォーマットは、`credentials/example-account.json`を参照。
- アカウント識別子の見つけ方: [link](https://docs.snowflake.com/en/user-guide/admin-account-identifier#finding-the-organization-and-account-name-for-an-account)
