# BotFlow — Android APK builder

1. Создай новый репозиторий на GitHub.
2. Залей содержимое этого архива в корень репо (включая скрытую папку `.github`).
3. Settings → Actions → General → Workflow permissions → **Read and write permissions** → Save.
4. Подожди 5–8 минут — APK появится в Releases → **latest** или Actions → Artifacts.

В этой версии:
- Прозрачный статусбар (убрал чёрный фон сверху)
- Иконка Workflow (mesh-blur фон) и сплэш-экран
- Стрелка курсора заменена на solar:cursor-square-bold
- Усилен пинч-зум на нодах (capture-фаза pointer events)
- Лёгкий градиент над канвасом (меньше repaint при пане)
