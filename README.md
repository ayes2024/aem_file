# AEM Fayl Arxivi

579 fayl üçün veb arxiv. Cədvəl görünüşü, axtarış, filtrlər.

## Qovluq strukturu

```
aem-fileserver/
├── server.js          # Express server
├── package.json
├── Dockerfile
├── railway.toml
├── data.json          # Excel məlumatları (579 sətir)
├── files/             # Bütün fayllar (570 fayl)
│   ├── 49084_4556.pdf
│   ├── 49083_4557.pdf
│   └── ...
└── public/
    └── index.html     # Frontend
```

## Railway-də Deploy

1. [railway.app](https://railway.app) saytına daxil olun
2. **New Project** → **Deploy from GitHub repo**
3. Bu qovluğu GitHub-a push edin
4. Railway avtomatik Dockerfile ilə build edəcək
5. Deploy tamamlandıqda URL veriləcək

## Yerli İşlətmə

```bash
npm install
node server.js
# http://localhost:3000
```
