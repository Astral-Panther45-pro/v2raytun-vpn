[![Platform](https://img.shields.io/badge/Platform-%20Android%20%7C%20Android%20TV%20%7C%20iOS%20%7C%20macOS%20%7C%20Windows%20%7C%20Linux-informational.svg)](https://github.com/LXST-CODE/v2RayTun/wiki/home)
[![Android](https://img.shields.io/badge/Android-7%2B-informational.svg)](https://developer.android.com/about/versions/nougat)
[![iOS](https://img.shields.io/badge/iOS-16.0%2B-informational.svg)](https://go.dev/wiki/MinimumRequirements)
[![macOS](https://img.shields.io/badge/macOS-13.0%2B-informational.svg)](https://go.dev/wiki/MinimumRequirements)
[![Windows](https://img.shields.io/badge/Windows-10%2B-informational.svg)](https://docs.flutter.dev/reference/supported-platforms)
[![Arch](https://img.shields.io/badge/Arch-x64-informational.svg)](https://go.dev/wiki/MinimumRequirements)
[![Chat on Telegram](https://img.shields.io/badge/Chat%20on-Telegram-lightgray.svg)](https://t.me/v2raytun)

# v2RayTun — Мощный кроссплатформенный прокси-клиент

**v2RayTun** — это высокопроизводительный клиент для работы с прокси, работающий на базе проверенного временем [Xray core](https://github.com/XTLS/Xray-core). Мы обеспечиваем бесшовную работу на Android, Android TV, iOS, macOS, Windows и Linux.

> Этот репозиторий — центр разработки: здесь мы ведем дорожную карту (roadmap), выпускаем релизы, разбираем баги и обсуждаем будущие фичи.

## 🚀 Получить приложение

Актуальные сборки, чейнджлоги и новости:
* [Telegram Releases](https://t.me/v2raytun/3)
* [GitHub Releases](https://github.com/LXST-CODE/v2RayTun/releases)

Официально в магазинах:
* [Google Play](https://play.google.com/store/apps/details?id=com.v2raytun.android)
* [App Store](https://apps.apple.com/us/app/v2raytun/id6476628951)

> [!NOTE]
> В App Store версия недоступна для региона RU.

## 🛠 Начало работы

> [!WARNING]
> v2RayTun — это **инструмент**, а не сервис. Приложение не предоставляет готовых конфигов, подписок или VPN-серверов. 

Чтобы начать, просто импортируйте нужные вам конфигурации или подписки в приложение.

## 📱 Поддержка платформ

У каждой системы свой подход к сборке и дистрибуции:

- [Android / Android TV](./android/)
- [iOS](./ios/)
- [macOS](./macos/)
- [Windows](./windows/)
- [Linux](./linux/)

## 📦 Система версий

Мы отказались от концепции «единой версии» для всех платформ. Каждый релизный трек развивается независимо, чтобы обеспечить максимальную стабильность для конкретной ОС.

| Трек | Платформы | Стек | Особенности |
|---|---|---|---|
| **Android** | Android, Android TV | Kotlin | Единый код, разные UI-паттерны под ТВ и смартфоны |
| **Desktop** | Windows, Linux | Flutter / Dart | Кроссплатформенная база с учетом специфики ОС |
| **iOS** | iOS, iPadOS | Swift | Нативный трек с интеграцией App Store |
| **macOS** | macOS M2+ / Intel | Swift | Раздельная оптимизация под архитектуры Apple |

## 🗺 Roadmap и фидбек

* **Roadmap:** Следите за развитием проекта в [GitHub Projects](https://github.com/users/LXST-CODE/projects/1).
* **Issues:** Нашли ошибку или есть идея для крутой фичи? Открывайте [Issues](https://github.com/LXST-CODE/v2RayTun/issues). Пожалуйста, используйте шаблоны для обращений — это ускорит обработку.

## 🌍 Языки / Languages

Основной язык документации — английский. Однако для удобства пользователей мы дополняем описание русскоязычными пояснениями там, где это необходимо.
