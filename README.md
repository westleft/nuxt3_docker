# Nuxt3 + Docker 環境

nuxt3 一直出現 node 版本警告，乾脆用 docker 

## 開發環境

```
docker-compose -f docker-compose.dev.yml up
```

打開 `http://localhost:3000/`

## 生產環境

```
docker-compose -f docker-compose.prod.yml up
```

打開 `http://localhost:8080/`

## 部屬 [Render](https://render.com/)

* Build Command：`npm install && npm run generate`
* Publish directory：`.output/public`

https://nuxt3-docker.onrender.com/test
