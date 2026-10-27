CaseCoins — Android-проєкт (WebView з вбудованою грою).

ВАРІАНТ А — Android Studio (потрібен JDK 17+, Studio Koala або новіша):
1. File → Open → папка CaseCoinsAndroid (саме та, де лежить settings.gradle).
2. Дочекайся Gradle Sync (завантажить Gradle 8.9 та SDK 35 — потрібен інтернет).
3. Build → Build APK(s) → app/build/outputs/apk/debug/app-debug.apk

ВАРІАНТ Б — без ПК, через GitHub (безкоштовно):
1. Створи репозиторій на github.com, завантаж туди ВМІСТ цієї папки (разом з .github).
2. Вкладка Actions → Build APK → Run workflow.
3. Після завершення відкрий запуск → Artifacts → app-debug-apk.
