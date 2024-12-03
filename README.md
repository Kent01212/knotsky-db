参考サイト以下

1: https://www.infra-linux.com/menu-docker4/django-mysql1-container/
2: https://www.infra-linux.com/menu-docker4/django-mysql2-container/

使用方法
・vscodeでgit-cloneしてください
・コマンドラインで Docker:compose Up を実行

DJango
・http://localhost:8000 へアクセス

Mysql 起動方法
・vscodeのターミナルを開く
・$ docker compose exec mysql /bin/bash
・bash-5.1# mysql -u root -p

MinIO
・