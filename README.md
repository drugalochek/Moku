# 🏝️ Moku

<p align="center">
  <a href="https://github.com/drugalochek/Moku/releases/download/Release/Moku-Setup-2.6.13-x64.exe">
    <img src="https://img.shields.io/badge/СКАЧАТЬ_MOKU_2.6.13-Windows_x64-2563EB?style=for-the-badge&logo=windows&logoColor=white" alt="Скачать Moku 2.6.13 для Windows x64">
  </a>
</p>

<p align="center">
  <strong><a href="#ru">🇷🇺 Русский</a>　│　<a href="#en">🇬🇧 English</a></strong><br>
  Интерактивный остров для Windows: время, погода, музыка, анимации и инструменты для скриншотов · An interactive Windows desktop island
</p>

<p align="center">
  <em>Время, погода, управление музыкой, живые анимации и скриншоты с разметкой в одном компактном приложении.</em>
</p>


## 📸 Скриншоты / Screenshots

<p align="center">
  <img src="Screenshots/Desktop%20Screenshot%202026.11.12%20-%2017.14.32.71.png" alt="Moku на рабочем столе" width="48%">
  <img src="Screenshots/Desktop%20Screenshot%202026.11.12%20-%2017.16.19.07.png" alt="Раскрытая панель Moku" width="48%">
</p>


---

<a id="ru"></a>

## 🇷🇺 Русский

**Moku 2.6.13** — интерактивный остров для Windows 10 и Windows 11. Он объединяет часы, погоду, системную информацию о воспроизведении музыки и инструменты для создания и разметки скриншотов. В компактном режиме Moku занимает минимум места, а при раскрытии предоставляет дополнительные сведения и элементы управления.

### ✨ Возможности

| Функция | Что умеет |
|---|---|
| 🕒 **Время** | Показывает текущее время прямо на острове. |
| 🌦️ **Погода** | Отображает погодный значок и температуру. Данные получает через Open-Meteo, обновляет примерно раз в 15 минут и сохраняет последнее успешное значение в кэш. |
| 🎵 **Медиа** | Следит за системной медиасессией Windows и показывает информацию о воспроизводимом контенте. |
| 🫧 **Жидкий остров** | Во время воспроизведения музыки нижний край острова превращается в анимированную волну цвета акцента. |
| 👀 **Живые глазки** | Следят за курсором, моргают, покачиваются под музыку и могут засыпать, если долго ничего не происходит. |
| 📸 **Скриншоты** | Позволяет выделить область экрана или сделать снимок всего экрана. |
| ✏️ **Разметка снимков** | После выделения области доступны перо, стрелка, рамка, маркер, выбор цвета и толщины. |
| 🎨 **Настройки внешнего вида** | Можно выбрать положение острова, вертикальный отступ, размер и цвет акцента. |
| 🌐 **Два языка** | Интерфейс поддерживает English и Русский. |
| 🖥️ **Системный трей** | Приложение может оставаться в фоне после закрытия окна. |

### 🎮 Управление

- **Клик по острову** или **Alt + Space** — раскрыть или свернуть остров.
- **Esc** или клик за пределами острова — свернуть его.
- **Двойной клик по значку в трее** — открыть Moku.
- **Правый клик по значку в трее** — открыть меню с действиями приложения.
- В настройках можно выбрать расположение: слева, по центру или справа, а также настроить отступ сверху.

### 📸 Инструмент скриншотов

1. Выбери плитку **«Область»** и выдели нужную часть экрана.
2. На панели разметки выбери инструмент: перо, стрелку, рамку или маркер.
3. Настрой цвет и толщину линий.
4. Используй горячие клавиши:
   - `Enter` или `Ctrl + C` — скопировать результат;
   - `Ctrl + S` — сохранить PNG;
   - `Ctrl + Z` — отменить последнее действие;
   - `Esc` — закрыть редактор.
5. Плитка **«Экран»** делает снимок всего экрана и отправляет его в буфер обмена.

### ⚙️ Настройки и данные

Настройки приложения хранятся в:

```text
%APPDATA%\\Moku\\settings.json
```

Кэш погоды:

```text
%APPDATA%\\Moku\\weather-cache.json
```

Лог приложения:

```text
%APPDATA%\\Moku\\moku.log
```

### 🧩 Технологии

- Windows Desktop
- C# / .NET 8
- WPF
- Windows Media Session API
- Open-Meteo Weather API

### 📦 Установка

1. Нажми [**Скачать Moku 2.6.13 для Windows x64**](https://github.com/drugalochek/Moku/releases/download/Release/Moku-Setup-2.6.13-x64.exe).
2. Запусти `Moku-Setup-2.6.13-x64.exe` и следуй инструкциям мастера установки.
3. Если нужна другая версия, открой [**все релизы Moku**](https://github.com/drugalochek/Moku/releases).

> Установщик предназначен для Windows x64. Для получения погоды требуется подключение к интернету.

<p align="right"><a href="#en">Перейти к English ↓</a></p>

---

<a id="en"></a>

## 🇬🇧 English

**Moku 2.6.13** is an interactive desktop island for Windows 10 and Windows 11. It brings together a clock, weather, system media information, and screenshot capture and annotation tools. Moku stays compact when collapsed and reveals additional information and controls when expanded.

### ✨ Features

| Feature | Description |
|---|---|
| 🕒 **Clock** | Displays the current time on the island. |
| 🌦️ **Weather** | Shows a weather icon and temperature using Open-Meteo. Refreshes about every 15 minutes and keeps the last successful value cached. |
| 🎵 **Media** | Tracks the active Windows media session and displays playback information. |
| 🫧 **Liquid island** | While music is playing, the island's lower edge becomes an animated accent-coloured wave. |
| 👀 **Animated eyes** | Follow the cursor, blink, move with music and can fall asleep after inactivity. |
| 📸 **Screenshots** | Capture a selected screen area or the entire screen. |
| ✏️ **Screenshot annotation** | Annotate captures with a pen, arrows, rectangles and a highlighter. Choose colours and line thickness. |
| 🎨 **Appearance** | Configure island alignment, vertical offset, size and accent colour. |
| 🌐 **Bilingual UI** | English and Russian interface languages. |
| 🖥️ **System tray** | Moku can keep running in the background when its window is closed. |

### 🎮 Controls

- Click the island or press **Alt + Space** to expand or collapse it.
- Press **Esc** or click outside the island to collapse it.
- Double-click the tray icon to open Moku.
- Right-click the tray icon to access the application menu.
- Choose left, centre or right alignment and adjust the top offset in Settings.

### 📸 Screenshot tools

1. Select **Area** and drag to choose a screen region.
2. Annotate it with the pen, arrow, rectangle or highlighter.
3. Adjust the colour and line thickness.
4. Keyboard shortcuts:
   - `Enter` or `Ctrl + C` — copy;
   - `Ctrl + S` — save as PNG;
   - `Ctrl + Z` — undo;
   - `Esc` — close the editor.
5. **Screen** captures the entire screen and copies it to the clipboard.

### ⚙️ Settings and local data

Settings are stored in `%APPDATA%\\Moku\\settings.json`. Weather cache is stored in `%APPDATA%\\Moku\\weather-cache.json`, and application logs in `%APPDATA%\\Moku\\moku.log`.

### 🧩 Built with

- Windows Desktop
- C# / .NET 8
- WPF
- Windows Media Session API
- Open-Meteo Weather API

### 📦 Installation

1. Click [**Download Moku 2.6.13 for Windows x64**](https://github.com/drugalochek/Moku/releases/download/Release/Moku-Setup-2.6.13-x64.exe).
2. Run `Moku-Setup-2.6.13-x64.exe` and follow the setup wizard.
3. For other versions, visit [**all Moku releases**](https://github.com/drugalochek/Moku/releases).

> The installer is intended for Windows x64. An internet connection is required for weather updates.

<p align="right"><a href="#ru">↑ Вернуться к русскому</a></p>