<div align="center">

# 🐱 PurrSheet

**Уютная таблица для котов и людей.**
Формулы, шаблоны, двуязычный интерфейс, экспорт в Excel и CSV — и всё это в одном `.exe`.

[![Latest release](https://img.shields.io/github/v/release/matvey2222222222/PurrSheet?color=A78BFA&label=release&style=for-the-badge)](https://github.com/matvey2222222222/PurrSheet/releases)
[![Downloads](https://img.shields.io/github/downloads/matvey2222222222/PurrSheet/total?color=A78BFA&label=downloads&style=for-the-badge)](https://github.com/matvey2222222222/PurrSheet/releases)
[![Visitors](https://api.visitorbadge.io/api/visitors?path=matvey2222222222%2FPurrSheet&label=views&countColor=%23A78BFA&style=for-the-badge)](https://github.com/matvey2222222222/PurrSheet)
[![Stars](https://img.shields.io/github/stars/matvey2222222222/PurrSheet?color=A78BFA&style=for-the-badge)](https://github.com/matvey2222222222/PurrSheet/stargazers)

[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-A78BFA?style=flat-square)](#-установка)
[![Made by MeowSoftware](https://img.shields.io/badge/made%20by-MeowSoftware-A78BFA?style=flat-square)](#-о-разработчике)
[![No Python required](https://img.shields.io/badge/Python-not%20required-22c55e?style=flat-square)](#-установка)
[![Language](https://img.shields.io/badge/interface-EN%20%7C%20RU-A78BFA?style=flat-square)](#-языки)

</div>

---

## ✨ О PurrSheet

**PurrSheet** — лёгкий и красивый редактор таблиц для повседневных задач: бюджет, учёба, инвентарь, планы на неделю, игровая статистика. Никаких аккаунтов, облаков и подписок — просто открой и работай.

> Разработано компанией **MeowSoftware**.

---

## 🖼️ Скриншот

<div align="center">

![PurrSheet — главное окно](screenshot.png)

*Главное окно PurrSheet: тёмная тема, шаблоны, строка формул, таблица на весь экран.*

</div>

---

## 🚀 Возможности

| | |
|---|---|
| 🧮 **Формулы** | `SUM`, `AVERAGE`, `MIN`, `MAX`, `COUNT`, арифметика, диапазоны `A1:A10` |
| 📊 **Экспорт / импорт** | Microsoft Excel (`.xlsx`) и CSV (`UTF-8 BOM`) |
| 💾 **Проекты** | Собственный формат `.purr` — сохраняет данные, формулы, цвета и стили |
| 🎨 **Оформление** | Цвет фона, цвет текста, жирный шрифт |
| 🔤 **Масштаб текста** | Шрифт в ячейке автоматически подстраивается под высоту строки |
| 📐 **Гибкая вёрстка** | Ручной ресайз столбцов/строк или автоподгонка под окно |
| 🌐 **Два языка** | Английский и русский, переключение прямо в приложении |
| 📦 **Шаблоны** | Готовые (бюджет, учёба, инвентарь, план) и свои собственные |
| 🐾 **Ошибки формул** | `#DIV/0!`, `#CIRC!`, `#ERROR!` — как в Excel |
| 🛡️ **Защита от потери данных** | Предупреждение о несохранённых изменениях при закрытии |

---

## 💾 Установка

> **Python НЕ требуется.** Всё уже внутри `.exe` — PySide6, openpyxl и все зависимости упакованы в один установщик.

### Windows 10 / 11

1. Откройте страницу [**Releases**](https://github.com/matvey2222222222/PurrSheet/releases).
2. Скачайте **`PurrSheet-Setup.exe`** (установщик).
3. Запустите установщик и следуйте шагам мастера.
4. Готово — ярлык **PurrSheet** появится в меню «Пуск».

Никаких `pip install`, никаких консольных команд. Просто скачал → установил → открыл.

---

## 🧭 Как пользоваться

1. Открой программу — стартует на весь экран.
2. Выбери шаблон из списка или нажми **✨ Свой шаблон**.
3. Введи значение или формулу в строку **`fx`** сверху — например `=SUM(B2:B5)`.
4. Тяни границы столбцов и строк — текст сам подстроится.
5. Сохрани проект (`File → Save Project`), экспортни в Excel или CSV.

### Шпаргалка по формулам

| Что | Пример |
|---|---|
| Арифметика | `=A1+B1*2` |
| Степень | `=A1**2` |
| Сумма диапазона | `=SUM(A1:A10)` |
| Среднее | `=AVERAGE(B2:B5)` |
| Мин / Макс | `=MIN(A1:A3)+MAX(B1:B3)` |
| Количество | `=COUNT(A1:A100)` |

---

## 🌐 Языки

Интерфейс приложения полностью переведён на:

- 🇬🇧 **English**
- 🇷🇺 **Русский**

Сменить язык можно в любой момент: **Настройки → Язык / Settings → Language**. Выбор сохраняется.

---

## 🐞 Нашли баг или ошибку?

**Напишите нам в [Issues](https://github.com/matvey2222222222/PurrSheet/issues)!**

Мы стараемся делать PurrSheet стабильным и удобным, но всё же возможны баги. Если вы столкнулись с ошибкой, странным поведением или чем-то, что не работает как ожидалось — создайте issue с описанием:

- что вы делали;
- что ожидали увидеть;
- что получилось на самом деле;
- версию PurrSheet и версию Windows.

Каждое сообщение помогает сделать приложение лучше. Спасибо! 🐾

---

## 👨‍💻 О разработчике

**PurrSheet** разработан компанией **MeowSoftware**.

---

## 📜 Лицензия

Проект распространяется под **Apache License 2.0**. См. [LICENSE](LICENSE) и [NOTICE](NOTICE).

> **Attribution required.** Любой форк обязан сохранить файл `NOTICE` и указать в своей документации ссылку на оригинал: [github.com/matvey2222222222/PurrSheet](https://github.com/matvey2222222222/PurrSheet).

---

<div align="center">

**Сделано с ❤ и 🐾 компанией MeowSoftware**

[🐱 Скачать PurrSheet](https://github.com/matvey2222222222/PurrSheet/releases)

</div>
