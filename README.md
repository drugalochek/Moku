# 🏝️ Moku

<p align="center">
  <strong>🇷🇺 Русский · 🇬🇧 English</strong><br>
  Интерактивный остров для рабочего стола Windows
</p>

<p align="center">
  <em>Время, погода, музыка и маленькие живые детали прямо на рабочем столе.</em>
</p>

---

## 🇷🇺 Русский

**Moku** — небольшое desktop-приложение для Windows, которое превращает верхнюю часть рабочего стола в интерактивный остров. В свёрнутом состоянии он остаётся компактным, а при открытии показывает дополнительные элементы управления и полезную информацию.

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

### 🛠️ Сборка из исходников

Понадобится **.NET 8 SDK** и Windows.

```powershell
cd Island
dotnet run -c Release
```

Чтобы собрать автономное приложение:

```powershell
dotnet publish -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true -o publish
```

Для сборки установщика, если в репозитории присутствует соответствующий проект и скрипт:

```powershell
cd Island
build-release.bat
```

### 📦 Загрузки

Готовые сборки будут публиковаться во вкладке **Releases**. Сейчас релизный файл ещё не прикреплён.

➡️ **[Открыть релизы Moku](https://github.com/drugalochek/Moku/releases)**

### 📋 Статус проекта

README описывает функции текущей версии приложения из основного репозитория проекта. Сам репозиторий **Moku** пока подготавливается: исходный код и готовые сборки будут добавлены отдельно.

---

## 🇬🇧 English

**Moku** is a lightweight Windows desktop app that adds an interactive island to your desktop. It stays compact when collapsed and reveals extra information and controls when expanded.

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

### 🛠️ Build from source

Install the **.NET 8 SDK** on Windows, then run:

```powershell
cd Island
dotnet run -c Release
```

For a self-contained Windows x64 publish:

```powershell
dotnet publish -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true -o publish
```

### 📦 Downloads

Windows builds will be published on the **Releases** page. No release asset is attached yet.

➡️ **[View Moku releases](https://github.com/drugalochek/Moku/releases)**

---

## 📄 License

See the [LICENSE](LICENSE) file for licensing terms. Third-party components remain subject to their respective licenses.
