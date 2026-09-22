# FlowMet — GitHub Actions

Этот проект подготовлен для сборки APK прямо через GitHub Actions.

## Как собрать APK с телефона

1. Создай новый GitHub repository.
2. Загрузи содержимое этой папки в репозиторий.
3. Открой вкладку **Actions**.
4. Выбери **Build FlowMet APK**.
5. Нажми **Run workflow**.
6. После завершения открой результат запуска и скачай artifact **FlowMet-debug**.
7. Внутри будет `app-debug.apk`.

Никакой Termux не нужен.

### Важно
Это debug APK для тестирования. Для публикации в Google Play позже добавим release-подпись и нормальный release build.
