# WebUI-client

  

## Описание

  

Это проект веб-интерфейса приложения BondiFuzz. Позволяет пользователям авторизоваться, создавать, изменять и удалять Проекты, Фаззеры и их Версии.

  

## Развертывание

  
```

git clone git@github.com:Bondifuzz/webui-client.git

cd webui-client

npm install

npm run build

```

  
После того, как билд получен, необходимо скопировать директории build/static и  build/locales в api-gateway. Это необходимо для того, чтобы графические элементы и файлы переводов были доступны веб приложению.

**Внимание:**  чтобы пользовательская документация отображалась в веб приложении, скопируйте сгенерированную директорию (book) из user-manuals  в api-gateway.

  

## Локальная разработка
  

```

git clone git@github.com:Bondifuzz/webui-client.git

cd webui-client

npm install

npm start

```

  

## Технологии


### JavaScript
  

- React 17.0.2 
- react-router-dom 5.3.0
- i18next 21.8.9 
  

### CSS


- AntDesign 4.18.5
