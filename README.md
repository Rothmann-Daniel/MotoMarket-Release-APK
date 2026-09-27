# 🏍️ MotoMarket

Полнофункциональное Android-приложение для **продажи, аренды и сервисного обслуживания мотоциклов и экипировки** с системой тест-драйвов, корзиной, заказами и панелью администратора. Построено на современном стеке Android с полной поддержкой **5 языков** и автоматическими **email-уведомлениями**.

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)
![Material 3](https://img.shields.io/badge/Material%203-757575?style=for-the-badge&logo=materialdesign&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---
[![Скачать PDF](https://img.shields.io/badge/📄_Presentation_MotoMarket_PDF-D32F2F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/Rothmann-Daniel/MotoMarket-Release-APK/raw/main/docs/MotoMarket_saas_VietKeys_PDF.pdf)
--

## 📖 О проекте

MotoMarket — это многофункциональная платформа для мотосалона, объединяющая в одном приложении:

- 🛒 **Продажу** мотоциклов и экипировки
- 🛣️ **Аренду** мотоциклов и экипировки
- 🏁 **Тест-драйв** с онлайн-записью
- 🛠️ **Сервисное обслуживание** (выезд мастера или визит в центр)
- 👑 **Панель администратора** для управления всем контентом
- 📧 **Email-уведомления** на 5 языках

Проект ориентирован на реальный бизнес: клиенты видят каталог, оформляют заказы, подают заявки, а администратор управляет всем через встроенную панель.

## ✨ Возможности

### 🏍️ Продажа мотоциклов и экипировки

- Каталог мотоциклов с фотографиями, характеристиками, ценой и пробегом
- Каталог экипировки с фильтрацией по типу, размеру, бренду
- Фильтры по производителю, категории, году, цвету
- Поиск по названию, бренду, цвету
- Детальная карточка: фото, цена, характеристики, описание
- Быстрый контакт с продавцом
- Корзина с управлением количеством
- Оформление заказа с выбором **доставки** или **самовывоза**
- Email-уведомления по заказам экипировки

### 🛣️ Аренда мотоциклов

- Каталог мотоциклов, доступных для аренды
- Фильтрация по производителю и категории
- Управление статусами: **доступно / забронировано / в аренде / на сервисе**
- Выбор периода аренды с расчётом стоимости
- Запрос дополнительной экипировки к заказу
- Указание адреса доставки и примечаний
- Загрузка документов (паспорт, виза, права, страховка)
- Согласие с договором аренды
- **Email-уведомления** пользователю и администратору с вложениями документов

### 🎒 Аренда экипировки

- Каталог экипировки для аренды
- Распределение единиц по статусам: **доступно / в аренде / сервис / списано**
- Учёт количества по каждому статусу
- Перемещение единиц между статусами в один клик
- Возврат в доступные

### 🏁 Тест-драйв

- Заявка на тест-драйв с выбором даты и времени
- Проверка документов (права, паспорт, страховка)
- Выбор даты и времени через Material Date/Time Picker
- Указание адреса и контактных данных
- **Email-уведомления** пользователю и администратору
- Управление заявками в админ-панели

### 🛠️ Сервисное обслуживание

- Заявка на ТО с выбором типа: **выезд мастера** или **сервисный центр**
- Указание адреса (с координатами для мастера) или выбор центра из списка
- Выбор даты и времени визита
- Описание перечня работ
- **Email-уведомления** пользователю и администратору
- Управление заявками: подтверждение, отмена с причиной, удаление
- Автоматические HTML-письма с поддержкой **5 языков**


### 🔐 Панель администратора

**📖 Управление мотоциклами на продажу:**

- Добавление, редактирование, удаление
- Скрытие / показ
- Отметка «продано» / возврат в продажу
- Загрузка фотографий в Base64

**🎒 Управление экипировкой на продажу:**

- Полный CRUD
- Управление складом (количество)
- Скрытие / показ, отметка «продано»

**🏍 Управление арендой мотоциклов:**

- CRUD по мотоциклам в аренде
- Управление статусами и доступностью
- Изменение тарифов

**🎒 Управление арендой экипировки:**

- CRUD, распределение по статусам
- Перемещение единиц между статусами
- Управление общим количеством

**📦 Заказы экипировки:**

- Список с фильтрацией по статусу (Pending / Confirmed / Shipped / Completed / Cancelled)
- Поиск по имени, email, телефону, номеру заказа
- Подтверждение, отправка, завершение, отмена с причиной
- Удаление заказов

**🏁 Заявки на тест-драйв:**

- Список с группировкой по статусам
- Подтверждение, завершение, отмена с причиной
- Удаление заявок
- Поиск по имени, email, мотоциклу

**🛠️ Заявки на сервис:**

- Список заявок по статусам
- Подтверждение, отмена с причиной, удаление
- Просмотр адреса на карте
- Отображение комментария администратора

**📧 Просмотр email-уведомлений:**

- Все уведомления отправляются автоматически
- Вложение документов клиента к письму админа (по аренде)

### 👤 Пользователь

- Регистрация и авторизация через **Firebase Authentication**
- Профиль с заполнением ФИО, телефона, документов
- Просмотр каталогов и фильтрация
- Корзина и оформление заказов
- Подача заявок на тест-драйв и сервис
- Просмотр истории заказов
- Загрузка фотографий документов
- Автоматическое определение языка интерфейса

---

## 🛠️ Технологии

### Core

- **Kotlin** — основной язык разработки
- **Jetpack Compose** — декларативный UI
- **Material 3** — дизайн-система
- **Coroutines / Flow** — асинхронная работа с данными
- **ViewModel + StateFlow** — управление состоянием UI
- **Navigation Compose** — навигация между экранами

### Backend

- **Firebase Authentication** — авторизация и управление пользователями
- **Firebase Firestore** — облачное хранилище данных
- **Firebase Storage** — хранение изображений

### Email

- **JavaMail (Jakarta Mail)** — отправка email через SMTP
- **Gmail SMTP (SSL, TLSv1.2)** — транспорт для уведомлений
- **HTML-шаблоны** с inline-стилями
- **Вложения документов** (JPEG) к админским письмам

### Прочее

- **Gradle Kotlin DSL** — конфигурация сборки
- **GitHub Actions** — CI для сборки и проверок
- **BuildConfig** — хранение SMTP-кредов

---

## 🏗️ Архитектура

Проект следует паттерну **MVVM** с разделением по функциональным модулям:

```
app/
└── src/
    └── main/
        └── java/
            └── com.danielrothmann.motomarket/
                ├── auth/                  # Авторизация и регистрация
                ├── bike/                  # Мотоциклы: модели, производители, категории
                ├── bottommenu/            # Нижнее меню
                ├── company/               # Настройки компании (адреса, email)
                ├── data/model/            # Модели данных
                ├── navigation/            # Навигация между экранами
                ├── order/                 # Заказы аренды + EmailHelper
                ├── profile/               # Профиль и админ-проверки
                ├── rent/                  # Аренда мотоциклов и экипировки
                ├── service/               # Сервисное обслуживание + ServiceEmailHelper
                ├── shop/                  # Продажа: мотоциклы, экипировка, корзина
                ├── ui/components/         # Переиспользуемые компоненты
                └── utils/                 # Утилиты (AppColors, ImageUtils, NumberFormatter)
```

---

## 📧 Email-уведомления

Приложение автоматически отправляет **HTML-письма** пользователям и администраторам при изменении статусов заказов и заявок. Письма оформлены в фирменном стиле MotoMarket и поддерживают **5 языков** — язык определяется по локали устройства пользователя (`userLocale`).

### Поддерживаемые языки

| Код | Язык | Флаг |
|:---:|:---:|:---:|
| `ru` | Русский | 🇷🇺 |
| `en` | English | 🇬🇧 |
| `de` | Deutsch | 🇩🇪 |
| `es` | Español | 🇪🇸 |
| `zh` | 中文 | 🇨🇳 |

> Если локаль не входит в список — письмо отправляется на **английском** (fallback).


### 🏍️ Аренда мотоциклов (`EmailHelper`)

| Событие | Получатель | Язык |
|---------|-----------|------|
| Новый заказ на аренду (+ вложения документов) | 👑 Администраторы | 🇷🇺 Русский |
| Заявка принята (авто-отбивка) | 👤 Пользователь | по локали |
| Заказ подтверждён администратором | 👤 Пользователь | по локали |
| Заказ отменён с причиной | 👤 Пользователь | по локали |

**Что в письме пользователю:**

- Модель, год и цвет мотоцикла
- Период аренды (дата начала / окончания / количество дней)
- Итоговая стоимость
- Адрес доставки
- Запрошенная экипировка
- В письме-подтверждении — чек-лист «Что взять с собой»

**Что в письме администраторам:**

- Данные клиента (ФИО, email, телефон, язык)
- Детали аренды и сумма
- Адрес доставки и примечание
- Статус документов клиента
- **Вложения**: фотографии паспорта, визы, прав, страховки (JPEG)
- Отметка о согласии с договором

### 🛠️ Сервисное обслуживание (`ServiceEmailHelper`)

| Событие | Получатель | Язык |
|---------|-----------|------|
| Новая заявка на ТО | 👑 Администраторы | 🇷🇺 Русский |
| Заявка принята (авто-отбивка) | 👤 Пользователь | по локали |
| Заявка подтверждена администратором | 👤 Пользователь | по локали |
| Заявка отменена с причиной | 👤 Пользователь | по локали |

**Что в письме пользователю:**

- Тип обслуживания (🏠 выезд мастера / 🏪 сервисный центр)
- Адрес или название и адрес центра
- Дата и время записи
- Описание перечня работ
- Комментарий администратора (при подтверждении)

**Что в письме администраторам:**

- Данные клиента
- Тип обслуживания и место (со ссылкой на Google Maps)
- Дата и время
- Перечень работ

### ⚙️ Настройка SMTP

Оба хелпера читают креды из `BuildConfig`:

```properties
# develop.properties (в .gitignore)
SMTP_EMAIL=your_email@gmail.com
SMTP_PASSWORD=your_app_password
```

> ⚠️ Пароль — **app password** Google, а не обычный пароль аккаунта.  
> Проверка конфигурации: `EmailHelper.isConfigured` / `ServiceEmailHelper.isConfigured`. Если креды пусты — отправка не выполняется, приложение продолжает работать.

### 🧱 Архитектура email-модуля

```
order/EmailHelper.kt            service/ServiceEmailHelper.kt
├── Strings                     ├── Strings
│   ├── ReceivedStrings         │   ├── ReceivedStrings
│   ├── ConfirmStrings          │   ├── ConfirmedStrings
│   └── CancelStrings           │   └── CancelledStrings
├── createSession()             ├── createSession()
├── sendEmail { }               ├── sendEmail { }
├── sendOrderToAdmins()         ├── sendServiceRequestToAdmins()
├── sendOrderReceivedToUser()   ├── sendServiceRequestReceivedToUser()
├── sendConfirmationToUser()    ├── sendServiceConfirmationToUser()
└── sendCancellationToUser()    └── sendServiceCancellationToUser()
```

**Особенности:**

- `suspend`-функции на `Dispatchers.IO`
- HTML на inline-стилях (совместимо с Gmail, Outlook, Apple Mail)
- `MimeMultipart("alternative")` для HTML-писем
- `MimeMultipart("mixed")` для писем с вложениями
- Отдельные `SimpleDateFormat` под каждую локаль
- Локализация через вложенные `data class` для каждого типа письма

---

## 🌐 Локализация

Приложение полностью поддерживает **русский** и **английский** языки интерфейса, а email-уведомления — **5 языков**.

**Структура:**

- `res/values/strings.xml` — русский
- `res/values-en/strings.xml` — английский
- `AppColors` — единая палитра (вынесена из хардкода)

Все строки UI вынесены в ресурсы, хардкод в коде отсутствует.

---

## 🚀 Запуск проекта

### Требования

- Android Studio Hedgehog или новее
- JDK 17+
- Android SDK 26+
- Устройство или эмулятор с Android 8.0 (API 26) и выше
- Аккаунт Firebase и файл `google-services.json`
- Google-аккаунт с **app password** для SMTP (для email-уведомлений)

### Шаги

1. Клонируй репозиторий:

```bash
git clone https://github.com/Rothmann-Daniel/MotoMarket.git
cd MotoMarket
```

2. Открой проект в **Android Studio**

3. Добавь файл `google-services.json` из Firebase Console в папку `app/`

4. Создай файл `develop.properties` в корне и добавь SMTP-креды:

```properties
SMTP_EMAIL=your_email@gmail.com
SMTP_PASSWORD=your_app_password
```

> Файл добавлен в `.gitignore` — креды не попадут в репозиторий.

5. Синхронизируй Gradle (`File → Sync Project with Gradle Files`)

6. Запусти приложение на эмуляторе или устройстве (**Run → Run 'app'**)

---

## 🔑 Тестовые аккаунты

| Роль | Email | Пароль |
|:---:|:---:|:---:|
| 👑 Администратор | `<admin@example.com>` | `ПО ЗАПРОСУ` |
| 👤 Обычный пользователь | `<test@test.com>` | `<qwerty>` |

> ⚠️ Учётные записи созданы для тестирования.

### Функционал по ролям

**👑 Администратор:**

- Полный CRUD по мотоциклам, экипировке, аренде
- Управление заказами и заявками
- Управление статусами и видимостью
- Просмотр входящих email-уведомлений
- Загрузка фотографий

**👤 Пользователь:**

- Просмотр каталогов и фильтрация
- Корзина и оформление заказов
- Заявки на тест-драйв и сервис
- Просмотр профиля и истории
- Загрузка документов

---

## 📦 Основные зависимости

```kotlin
// Jetpack Compose
implementation(platform("androidx.compose:compose-bom"))
implementation("androidx.compose.ui:ui")
implementation("androidx.compose.material3:material3")
implementation("androidx.activity:activity-compose")
implementation("androidx.navigation:navigation-compose")

// Firebase
implementation(platform("com.google.firebase:firebase-bom"))
implementation("com.google.firebase:firebase-auth-ktx")
implementation("com.google.firebase:firebase-firestore-ktx")
implementation("com.google.firebase:firebase-storage-ktx")

// Lifecycle / ViewModel
implementation("androidx.lifecycle:lifecycle-viewmodel-compose")
implementation("androidx.lifecycle:lifecycle-runtime-ktx")

// Coroutines
implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android")

// Email
implementation("com.sun.mail:android-mail:1.6.7")
implementation("com.sun.mail:android-activation:1.6.7")
```

---

## 📸 Скриншоты

<details>
<summary>📱 Посмотреть скриншоты приложения</summary>

### 🛒 Магазин и продажа

| Каталог магазина | Экипировка | Карточка аренды |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/aaa597f7-d3ef-4f08-af82-563bc967cddc" width="250"/> | <img src="https://github.com/user-attachments/assets/ce724ef7-1238-430b-a06c-c404f2dfb17c" width="250"/> | <img src="https://github.com/user-attachments/assets/7a0e1786-9f81-4b74-bcdc-1ef33000da79" width="250"/> |

| Характеристики мотоцикла | Тарифы | Корзина |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/bcc1a391-f151-4bce-8c55-94ffb2f1369e" width="250"/> | <img src="https://github.com/user-attachments/assets/1d36027b-6201-4616-a4c6-c3331d0ae983" width="250"/> | <img src="https://github.com/user-attachments/assets/d5f9339d-ee66-43ce-9af6-20de7299e7b8" width="250"/> |

### 🏁 Тест-драйв и заказы пользователя

| Запись на тест-драйв | Тест-драйв | Мои заказы |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/8f192514-794d-4cec-b894-6985bc7aa0ed" width="250"/> | <img src="https://github.com/user-attachments/assets/1db04527-759b-4aee-83b1-262128b18907" width="250"/> | <img src="https://github.com/user-attachments/assets/3b9e3b81-3ecf-468b-8758-ce7d6728cfbc" width="250"/> |

| Информация о заказе | Редактирование заказа | — |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/f0f77e25-286d-4610-a6d2-234053cf8ee8" width="250"/> | <img src="https://github.com/user-attachments/assets/1093ed54-8738-4b00-ba8b-2cccb0757872" width="250"/> | |

### 🔐 Админ-панель

| Админ-панель (RU) | Админ-панель 1 | Админ-панель 2 |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/f8fdc00c-16c1-461b-9d1e-e8effb8fa8f7" width="250"/> | <img src="https://github.com/user-attachments/assets/2b36a987-f3b8-4d43-9c06-05045cedc653" width="250"/> | <img src="https://github.com/user-attachments/assets/cf9662fa-018f-4495-9eff-1aa02e3eaa2e" width="250"/> |

| Админ с аватаром | Админ-экран | Менеджер управления |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/625c006a-8a71-4d74-9a91-d1b7a10f4a7f" width="250"/> | <img src="https://github.com/user-attachments/assets/a84fb772-c0c5-4b42-aa0c-3c87f51a2241" width="250"/> | <img src="https://github.com/user-attachments/assets/6ca416e2-af43-40ca-8abb-95856c24c4b5" width="250"/> |

### 🛠️ Сервис и заявки

| Заявка на ТО | Заявки на ТО | Заказы (админ) |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/920f13ba-48a1-4c16-9170-70022cb46eec" width="250"/> | <img src="https://github.com/user-attachments/assets/167f62df-96ec-4703-a78d-0ae8ad2bcc2a" width="250"/> | <img src="https://github.com/user-attachments/assets/f7b9b99e-6379-4ac7-a8d3-68a6e30b766b" width="250"/> |

| Заказы | — | — |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/88ec901e-c0da-4534-8a6d-f7e534e6bd64" width="250"/> | | |

</details>

<details>
<summary>📧 Посмотреть примеры email-писем</summary>

<img width="431" height="817" alt="Снимок экрана — 2026-09-15 в 17 06 56" src="https://github.com/user-attachments/assets/1c009103-cd72-4516-8277-8262847bd511" />
<img width="1719" height="909" alt="Снимок экрана — 2026-09-15 в 17 07 27" src="https://github.com/user-attachments/assets/88c8fd94-dd3b-46cf-b53b-69f3cb80edbe" />
<img width="424" height="522" alt="Снимок экрана — 2026-09-15 в 17 07 47" src="https://github.com/user-attachments/assets/4d1d1f26-8bc1-4940-923a-6fa52788db3b" />
<img width="1728" height="697" alt="Снимок экрана — 2026-09-15 в 17 07 41" src="https://github.com/user-attachments/assets/0898b4dc-d9db-40b0-a775-5aa0fd0b3e76" />
<img width="482" height="713" alt="Снимок экрана — 2026-09-15 в 17 09 10" src="https://github.com/user-attachments/assets/c4e6fff2-11b5-46c3-a942-a87c995df7c3" />
<img width="491" height="548" alt="Снимок экрана — 2026-09-15 в 17 09 20" src="https://github.com/user-attachments/assets/fc7828ca-a1e0-475f-86a5-7dc6782c34df" />
<img width="523" height="714" alt="Снимок экрана — 2026-09-15 в 17 10 26" src="https://github.com/user-attachments/assets/7af2d101-b955-4715-a1cc-9b7cdac5224e" />
<img width="453" height="654" alt="Снимок экрана — 2026-09-15 в 17 10 36" src="https://github.com/user-attachments/assets/37d03343-e2b4-4158-a6c2-ac1a4ad5e323" />

</details>

---

## 🧪 Тестирование

Планируется покрытие:

- Unit-тестами — ViewModel, репозитории, email-хелперы
- UI-тестами — основные пользовательские сценарии

Тестируемые сценарии:

- Авторизация и регистрация
- Просмотр каталога и фильтрация
- Добавление в корзину и оформление заказа
- Подача заявки на тест-драйв и сервис
- Управление статусами аренды
- Отправка email-уведомлений

---

## ⚙️ CI/CD

В проекте настроены **GitHub Actions** (`.github/workflows`) для автоматической сборки и проверок:

- Компиляция проекта
- Сборка APK
- Запуск unit-тестов (при наличии)
- Статический анализ (при наличии)

---

## 🎯 Дорожная карта

### ✅ Реализовано

- [x] Авторизация и регистрация (Firebase Auth)
- [x] Каталог мотоциклов на продажу
- [x] Каталог экипировки на продажу
- [x] Корзина и оформление заказа
- [x] Каталог аренды мотоциклов
- [x] Каталог аренды экипировки
- [x] Заявки на тест-драйв
- [x] Заявки на сервисное обслуживание
- [x] Карта с адресами пунктов выдачи
- [x] Админ-панель: CRUD по всем сущностям
- [x] Управление заказами и статусами
- [x] История аренды для пользователя
- [x] Email-уведомления на 5 языках
- [x] Вложения документов клиента в админских письмах
- [x] Локализация ru / en
- [x] Material 3 интерфейс
- [x] Вынос цветов в `AppColors`
- [x] CI/CD через GitHub Actions

### 🎯 Возможные улучшения

- [ ] Онлайн-оплата
- [ ] Push-уведомления (FCM)
- [ ] Избранное
- [ ] Аналитика и отчёты для админа
- [ ] Отзывы пользователей
- [ ] Тёмная / светлая тема
- [ ] Unit-тесты
- [ ] Больше языков интерфейса
- [ ] Экспорт данных (PDF / CSV)

---

## 💡 Ключевые преимущества

✨ **Полный цикл бизнеса** — продажа, аренда, сервис, тест-драйв  
📧 **5-язычные email-уведомления** с вложениями документов  
🌐 **Мультиязычный интерфейс** (ru / en)  
⚡ **Реактивный UI** на StateFlow  
📱 **Material 3** — современный дизайн  
🔐 **Firebase** — надёжная авторизация и хранение  
🎨 **Единая палитра** в `AppColors`  
🧪 **Production-ready код** — готов к развёртыванию  
📦 **Активное развитие** — проект обновляется

---

## 👨‍💻 Автор

**Данила Ротман** — Android Developer

- 📱 Telegram: [@danielrothmann](https://t.me/danielrothmann)
- 🌐 GitHub: [@Rothmann-Daniel](https://github.com/Rothmann-Daniel)

---

## 📄 Лицензия

Проект доступен для ознакомления и обучения. Коммерческое использование требует согласования с автором.

---

<div align="center">

**⭐ Если проект понравился, поставьте звезду!**

Made by Daniel Rothmann

</div>
