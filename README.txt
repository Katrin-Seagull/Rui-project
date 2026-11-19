GLaDOS AI — Android-приложение (подходит для Android 7.0+, Honor MagicOS, Huawei EMUI/HarmonyOS без Google Play)

ЧТО УЖЕ ВНУТРИ:
- Подключение к https://disquisitive.duckdns.org:48721/
- Работает без Google Play Services (GMS)
- Офлайн-кэш интерфейса и IndexedDB-хранилище чатов/профилей
- Экран офлайн-режима без белого мерцания
- Нативный мост GLaDOSNative для кнопки "Обновить приложение" без сброса пароля и локальных чатов

КАК ПОЛУЧИТЬ ГОТОВЫЙ .APK ЗА 2 МИНУТЫ БЕЗ УСТАНОВКИ ANDROID STUDIO:
1. Создайте на GitHub новый приватный репозиторий (например, glados-app).
2. Распакуйте этот архив и загрузите все файлы (включая папку .github) в репозиторий.
3. Перейдите во вкладку Actions -> Build GLaDOS APK -> Run workflow (или дождитесь автозапуска после загрузки).
4. Через ~2 минуты откройте завершённый запуск и скачайте архив GLaDOS-AI-APK из раздела Artifacts.
5. Внутри лежит готовый файл GLaDOS-AI.apk (~2-3 МБ) — отправляйте его себе и сестре в Telegram и устанавливайте.

ИЛИ ЛОКАЛЬНО НА ПК:
1. Откройте распакованную папку в Android Studio.
2. Нажмите Build -> Build Bundle(s) / APK(s) -> Build APK(s).
3. Файл появится в app/build/outputs/apk/debug/app-debug.apk.
