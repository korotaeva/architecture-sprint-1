# architecture-sprint-1

Домашнее задание 1

Использован фреймворк  Module Federation, тк приложение 
- написано на  React 
- используете Webpack, те нужны дополнительные инструменты. 
- нужна ленивая загрузка компонентов.
Проект Mesto (соцсеть для обмена фотографиями) можно разделить на несколько микрофронтендов

        auth (аутентификация и регистрация)  
                - Login 
                - Register
 
        profile (управление профилями) - 
                - EditAvatarPopup
                - EditProfilePopup

        photo (управление карточками) - 
                - AddPlacePopup 
                - ImagePopup
                - Card

        host (роутинг и общая логика) - 
                - App 
                - Header 
                - Footer
                - Main
                - ProtectedRoute
                - InfoTooltip

        shared (общие компоненты) 
                -  PopupWithForm


/auth-microfrontend
  /src
    /components
      Login.js               // Компонент входа пользователя
      Register.js            // Компонент регистрации пользователя
    /styles
      login.css              // Стили для компонента входа
      register.css           // Стили для компонента регистрации
    /utils
      auth.js                // Утилиты для аутентификации
    index.js                 // Точка входа микрофронтенда
  package.json               // Зависимости и скрипты микрофронтенда
  webpack.config.js
/profile-microfrontend
 /src
    /components
      EditAvatarPopup.js             
      EditProfilePopup.js            
    /styles
      .css              // Стили для компонента
      .css           // Стили для компонента 
    /utils
      .js               
    index.js                 // Точка входа микрофронтенда
  package.json               // Зависимости и скрипты микрофронтенда
  webpack.config.js
/photo-microfrontend
 /src
    /components            
      AddPlacePopup.js   
      ImagePopup.js   
      Card.js            
    /styles
      .css              // Стили для компонента
      .css           // Стили для компонента 
    /utils
      .js               
    index.js                 // Точка входа микрофронтенда
  package.json               // Зависимости и скрипты микрофронтенда
  webpack.config.js

/host-microfrontend
 /src
    /components  
      App      
      Header.js   
      Footer.js   
      Main.js  
      ProtectedRoute.js   
      InfoTooltip.js       
    /styles
      .css              // Стили для компонента
      .css           // Стили для компонента 
    /utils
      .js               
    index.js                 // Точка входа микрофронтенда
  package.json               // Зависимости и скрипты микрофронтенда
  webpack.config.js

shared-microfrontend
 /src
    /components  
      PopupWithFormp.js       
    /styles
      .css              // Стили для компонента
      .css           // Стили для компонента 
    /utils
      .js               
    index.js                 // Точка входа микрофронтенда
  package.json               // Зависимости и скрипты микрофронтенда
  webpack.config.js

  

Задание 2

https://drive.google.com/file/d/1EhzJVmVgamG5FTYeeOOpeBymFgrQo8Gt/view?usp=sharing
