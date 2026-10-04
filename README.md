# 🎧 Music Player

Музыкальный плеер на Spotify Web API: авторизация через Spotify, свои плейлисты, любимые треки, артисты, альбомы, поиск и полноценное управление воспроизведением прямо из браузера.

**[🔗 Демо](https://music-player-danu-it.vercel.app)**

https://user-images.githubusercontent.com/73935646/234902258-859d057b-fda5-4b38-a766-8eeffdd809d9.mp4

> Приложение в Spotify работает в режиме разработки, поэтому войти в демо могут только добавленные аккаунты, а для управления воспроизведением нужен Spotify Premium. Как всё работает, видно на видео выше.

## Возможности

**Библиотека**
- Авторизация через Spotify
- Создание, переименование и удаление плейлистов, добавление и удаление треков, изменение их порядка
- Любимые треки: добавление и удаление лайком
- Сохранённые альбомы и артисты, подписка и отписка от артистов

**Музыка**
- Страница артиста: популярные треки, альбомы, похожие исполнители
- Категории и подборки плейлистов по ним
- Поиск по трекам и альбомам
- Недавно прослушанные треки

**Плеер**
- Play / pause, перемотка, громкость
- Следующий и предыдущий трек, повтор, перемешивание
- Отображение текущего трека

**Интерфейс**
- Светлая и тёмная тема
- Сворачиваемый сайдбар

## Стек

![React](https://img.shields.io/badge/React_18-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat&logo=redux&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router_6-CA4245?style=flat&logo=react-router&logoColor=white)
![styled-components](https://img.shields.io/badge/styled--components-DB7093?style=flat&logo=styled-components&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat&logo=mui&logoColor=white)
![Spotify API](https://img.shields.io/badge/Spotify_Web_API-1DB954?style=flat&logo=spotify&logoColor=white)

- React 18 + TypeScript
- Redux Toolkit и **RTK Query**: 40+ эндпоинтов Spotify API, кэширование и автоматическая инвалидация через теги
- React Router v6
- styled-components (темизация) и MUI
- [Spotify Web API](https://developer.spotify.com/documentation/web-api)
- Деплой на Vercel

## Запуск

```bash
git clone https://github.com/donuwave/music-player-react.git
cd music-player-react
npm install
npm start
```

Для локального запуска нужно создать приложение в [Spotify Developer Dashboard](https://developer.spotify.com/dashboard), указать Redirect URI `http://localhost:3000` и подставить свой Client ID.
