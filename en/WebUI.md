# WebUI-client

  

## Description

  

This is project is for web interface of BondiFuzz application. Allows to login user, create, modify and delete Project, Fuzzers and their Versions.

  

## Deployment

  
```

git clone git@github.com:Bondifuzz/webui-client.git

cd webui-client

npm install

npm run build

```

  

After build is generated, copy build/static and build/locales directories to api-gateway. These steps are required in order for  assets and translations to be accessible for app.

**Note:** for user documentation to be shown in web application, you will need  to copy book, generated from user-manuals, to the api-gateway directory.

  

## Local development

  

```

git clone git@github.com:Bondifuzz/webui-client.git

cd webui-client

npm install

npm start

```

  

## Languages & tools

  

### JavaScript

  

- React 17.0.2 
- react-router-dom 5.3.0
- i18next 21.8.9 
  

### CSS

  

- AntDesign 4.18.5
