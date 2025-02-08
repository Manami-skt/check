# お問い合わせフォーム
# 環境構築
Dockerビルド
1. ディレクトリ作成
2. docker-compose.yml　記述
3. default.conf 記述
4. Dockerfile 記述
5. php.ini 記述
6. my.cnf 記述
7. docker compose up -d --build

Laravel環境構築
1. docker compose exec php bash
2. composer creare-project "laravel=8.*" . --prefer--dist
3. .envの環境変数を変更
4. php artisan key:generate
5. php artisan migrate
6. 

# 使用技術
・PHP 8.4.1
・Laravel 8
・MySQL 8.0.26

# URL
・開発環境： http://localhost/
・phpMyAdmin： http://localhost:8080/
