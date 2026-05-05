# Bot Flow Builder — Android (Capacitor)

Этот каталог упаковывает HTML-приложение из `mobile/www/` в нативный Android APK.

## Автосборка APK через GitHub Actions

После push в репозиторий запускается workflow `.github/workflows/android-apk.yml`, который:
1. Ставит Node + JDK 17 + Android SDK
2. Устанавливает Capacitor зависимости
3. Создаёт Android-проект (`npx cap add android`)
4. Собирает debug APK
5. Загружает APK как **artifact** во вкладке Actions → последний run → Artifacts → `app-debug-apk`

Скачать APK: GitHub → вкладка **Actions** → последний зелёный run → раздел **Artifacts**.

## Локально (опционально)
```bash
cd mobile
npm install
npx cap add android
npx cap sync android
npx cap open android   # требует Android Studio
```

## Обновление контента
Замени файл `mobile/www/index.html` — при следующем push GitHub Actions соберёт новый APK.
