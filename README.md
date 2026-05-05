# Bot Flow Builder — Android APK auto-build

## Как получить APK (5 минут, без Android Studio):

1. Создай новый репозиторий на GitHub (можно приватный).
2. Загрузи в него ВСЁ содержимое этого архива (кнопка "uploading an existing file" → перетащи папки).
   ⚠️ Папка `.github` должна попасть как есть (с точкой в начале).
3. Открой вкладку **Actions** в репозитории. Если спросит — нажми "I understand my workflows, go ahead and enable them".
4. Workflow **Build Android APK** запустится автоматически. Жди ~5–8 минут.
5. Когда появится зелёная галочка → кликни на run → скачай APK из раздела **Artifacts** (`bot-flow-builder-apk`).
   Или открой раздел **Releases** — там будет тег `latest` с APK.
6. Перекинь .apk на телефон, разреши установку из неизвестных источников и установи.

## Чтобы обновить приложение
Просто замени `mobile/www/index.html` новой версией HTML и закоммить — APK пересоберётся сам.
