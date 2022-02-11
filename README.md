# nuxt-app
## 開発手順
### 開発開始時
docker-compose up -d
docker-compose exec app bash
npm run dev
下記にアクセスする
http://localhost:3000/
その後はほっとリロードされる

### 開発終了時
ctrl + C
exit
docker compose down