# Алексей Сильченко

Аудитор розничной сети. Автоматизирую рутину вокруг инвентаризации и аудита:
обработку выгрузок, проверку данных и обходы торгового зала с телефона.

## Проекты

### [Vyverka](https://github.com/Gefest100500/Vyverka) — Android, Kotlin
Приложение для выверки местоположений, паллет и товара в пути. Выгрузки из учётной системы
подтягиваются из GitHub, результат возвращается в Excel с подсветкой и уходит письмом.

`Kotlin` `Jetpack Compose` `CameraX` `ML Kit` `SQLite` `свой парсер и генератор XLSX`
📦 [Скачать APK](https://github.com/Gefest100500/Vyverka/releases/latest)

### [CoffeMod](https://github.com/Gefest100500/Coffeemod) — Android, Kotlin
Инвентаризация небольшой кофейни: товары и группы, сканирование штрихкодов, приход/расход,
пересчёт с черновиком, PDF-этикетки с QR, отчёты и импорт продаж из CSV. Полностью офлайн.

`Kotlin` `Compose` `CameraX` `ML Kit` `ZXing` `SQLite`
📦 [Скачать APK](https://github.com/Gefest100500/Coffeemod/releases/latest)

### [Nexus](https://github.com/Gefest100500/Nexus) — Electron, JavaScript
Хаб командировок ревизора: данные корпоративного портала по поездкам, отелям и документам
в одном окне. Без npm-зависимостей, собственный парсер XLSX.

`Electron` `JavaScript` `Node.js` `Windows` `zero dependencies`

### [Core V3.0](https://github.com/Gefest100500/Core-v3) — Python, PyQt6
Desktop-инструмент аудитора: обработка выгрузок из 1С, АСУС и Тандер Склад, анализ квантов,
свод ОС/МБП, проверка Брак/Утиль, дашборд по письмам инвентаризации, табель ревизора.
733+ автотестов.

`Python 3.13` `PyQt6` `pandas` `openpyxl` `SQLite`

## Стек

- **Мобильная разработка:** Kotlin, Jetpack Compose, CameraX, ML Kit, SQLite
- **Десктоп:** Electron, JavaScript, PyQt6
- **Автоматизация:** Python, pandas, openpyxl
- **Данные:** SQLite, Excel (чтение и генерация без сторонних библиотек), CSV
- **Инструменты:** Git, GitHub Actions, Android SDK, Gradle

## Принципы

- офлайн важнее «красиво в облаке» — данные должны работать без сети;
- интерфейс для работы руками в зале: минимум тапов, крупные элементы, честные статусы;
- чужие данные не уходят наружу: секреты вне репозитория, выгрузки — только в рабочем контуре.
