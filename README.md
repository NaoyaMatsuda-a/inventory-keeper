# inventory-keeper
小規模向け在庫管理アプリ

小規模事業者向けの在庫管理システムです。  
商品登録・在庫数の更新・レポート出力ができます。

## 使用技術

- フロントエンド：React
- バックエンド：Spring Boot (Java)
- データベース：MySQL
- レポート：Python（CSV/PDF）
- クラウド：AWS（EC2, RDS, S3）

## MVP機能

- ユーザー認証（ログイン）
- 商品の登録・編集・削除
- 在庫数の更新（入出庫対応）
- 商品一覧の表示と在庫数フィルター

## セットアップ（仮）

```bash
git clone https://github.com/yourname/inventory-keeper.git
cd backend
./mvnw spring-boot:run
