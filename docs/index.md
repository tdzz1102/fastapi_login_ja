# 概要

**ソースコード: [https://github.com/MushroomMaula/fastapi_login](https://github.com/MushroomMaula/fastapi_login)**

fastapi-login は、FastAPI に便利な、使いやすいユーザー認証機能を提供します。

## 特徴

- シンプルな認証依存関係を提供します
- リクエストのヘッダーとクーキーとしてのトークンのサポート
- 独自の依存関係を作成するため、ミドルウェアとして使用可能
- ユーザーが認証されない場合のコールバックサポート
- OAuth2 スコープサポート
- OpenAPI サポート

## 目標
``fastapi-login`` のアイデアは、使いやすい、セットアップしやすい認証システムをルートに提供することです。
可能な限りベアボーンでカスタマイズ可能でありながら。 したがって、デフォルトのデータベース ユーザー モデルや
ログイン/登録ルートはパッケージで提供されます。

それが必要な場合は、次のようなすぐに使用できる機能を提供する他のパッケージがあります。
[fastapi-users](https://github.com/frankie567/fastapi-users)。