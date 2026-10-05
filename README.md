# PROJECTS Worklog Voice Recorder

Статическая страница для GitHub Pages. Никаких API-ключей, Google Sheet ID или рабочих данных внутри нет.

## Быстрый запуск

1. Создать публичный GitHub-репозиторий, например `projects-worklog-recorder`.
2. Положить `index.html` в корень репозитория и сделать commit/push.
3. На GitHub открыть `Settings → Pages`.
4. В `Build and deployment` выбрать:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Сохранить и дождаться адреса вида:
   `https://USERNAME.github.io/projects-worklog-recorder/`
6. Передать этот URL в PROJECTS_WEB:
   `PROJECTS_WEB_DB → Settings → worklog_voice_recorder_url`.

После этого кнопка микрофона в PROJECTS_WEB открывает эту страницу, а кнопка
`Готово — отправить RAW` возвращает текст в основную базу.

## Что хранится на GitHub

Только HTML/CSS/JS диктофона. Никакие расшифровки на GitHub не сохраняются.
