# counter

Простой счётчик на React Native и Expo.

## Запуск

```powershell
cd c:\Cursor\counter
npm install
npm start
```

Откройте приложение в **Expo Go** на телефоне (QR-код в терминале) или нажмите `a` для Android-эмулятора / `w` для браузера.

Если телефон не подключается по Wi‑Fi, запустите с туннелем:

```powershell
npx expo start --go --tunnel
```

В терминале должно быть **Using Expo Go**, а не development build (клавиша `s` переключает режим).

## Экран

- Крупное число по центру (начальное значение — 0)
- **+** — увеличить на 1
- **Сброс** — вернуть 0
