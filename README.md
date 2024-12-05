参考サイト以下  
  
1: https://www.infra-linux.com/menu-docker4/django-mysql1-container/  
2: https://www.infra-linux.com/menu-docker4/django-mysql2-container/  
  
※ 注意使用前提として Docker Desktop 内にある Containers に何か起動されている場合は正常に動かない可能性があるので、対策方法として以下を実行してください  
ただし、Containers 内に入っているオブジェクトは無くなってしまいますので注意してください。  
    
$ docker system prune -a  
  
使用方法  
・vscodeでgit-cloneしてください  
・コマンドラインで Ctrl + Shift + p で Docker: Compose Up を検索し実行  
  
Django  
・http://localhost:8000 へアクセス  
  
Mysql 起動方法  
・vscodeのターミナルを開く  
・$ docker compose exec mysql /bin/bash  
・bash-5.1# mysql -u root -p  
  
phpMyAdmin  
・http://localhost:8081 へアクセス

MinIO  
・http://localhost:9001 へアクセス  