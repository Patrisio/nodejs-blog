# nodejs-blog - devconnector
Чтобы запустить проект, вам необходимо:

1. Добавить default.json в папку config со следующим кодом
```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

2. Установить все зависимости для серверной части
```
npm i
```

3. Установить все зависимости для клиентской части
```
cd client
npm i
```

4. Запустить сборку express и react с корневого каталога
```
npm run dev
```

5. Проверить, что проект запустился в браузере по адрусу http://localhost:5000/
