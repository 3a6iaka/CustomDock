# 🚀 CustomDock
Animated glassmorphic macOS-style dock & taskbar replacement for Windows 10/11 (WPF + Win32) — a single portable `.exe` with no installer or extra files.
Анимированная стеклянная док-панель и замена панели задач для Windows 10/11 в стиле macOS (WPF + Win32) — один `.exe`-файл без установки и лишних файлов.
---
## 🇬🇧 English
### ✨ Features
- **Horizontal & Vertical Modes:** Place the dock at the bottom center or vertically along the left edge of the screen, or pick any custom position (saved between launches).
- **Full Windows Taskbar Replacement:** Hides the standard Windows taskbar cleanly (`SHAppBarMessage` + `ABS_AUTOHIDE`) so maximized windows stretch to the full screen without black gaps, and restores it automatically on exit.
- **Smooth 240 FPS Animations:** Icon magnification wave on hover, smooth auto-hide & edge reveal, gliding hover labels, and hardware-cached shadows.
- **Quick App Search:** Instant background-indexed app search with styled context menu (**Open**, **Run as administrator**, **Open file location**, **Pin / Unpin to dock**).
- **Built-in System Tray & Controls:**
  - Volume slider & mute (plus mouse-wheel volume adjustment), microphone mute, keyboard layout switcher, network settings shortcut, clock/notifications, and **Show Desktop**.
  - **Minimized & Background Apps (`^`):** Chevron button for hidden tray/minimized apps with quick restore, close, and end process actions.
- **Themes, Colors & Custom Background:**
  - 4 built-in themes: **Glass**, **Neon**, **Ocean**, **Light**.
  - Color & preset editor: customize accent, background, and border colors in `#RRGGBB` / `R, G, B` or via a popup **HSV color wheel**, create or rename presets.
  - **Custom Background (PNG / Animated GIF):** Set any PNG or animated GIF as the dock background.
- **Smart Auto-Hide & Game Detection:** Automatically hides in fullscreen games and when opening the Windows Start Menu / Search, and supports **Autostart** with administrator privileges via Task Scheduler.
- **Language Switcher:** Switch UI between **RU** and **EN** directly in Settings.
### 🚀 Usage & Build
- **Run:** Download `CustomDock.exe` from **Releases** and launch it (includes `requireAdministrator` manifest for managing system windows and taskbar).
- **Build from source:** Run `build.bat` (uses built-in Windows `.NET Framework 4.x csc.exe`, no Visual Studio required).
---
## 🇷🇺 Русский
### ✨ Возможности
- **Горизонтальное и вертикальное положение:** размещение док-панели снизу по центру или вертикально у левого края экрана, а также выбор любого места на экране (позиция сохраняется между запусками).
- **Полная замена панели задач Windows:** корректное скрытие стандартной панели (`SHAppBarMessage` + `ABS_AUTOHIDE`), чтобы развёрнутые окна тянулись до самого низа без чёрной полосы, с автоматическим возвратом панели при выходе.
- **Плавные анимации (до 240 FPS):** волна иконок при наведении, мгновенный отклик при автоскрытии, плавное перетекание подсказок и аппаратное кэширование теней.
- **Быстрый поиск приложений:** фоновая индексация программ и стилизованное контекстное меню (**Открыть**, **Запустить от имени администратора**, **Открыть расположение файла**, **Закрепить / Открепить**).
- **Встроенный системный трей и управление:**
  - Громкость (ползунок и колесо мыши), микрофон, переключение раскладки, настройки сети, часы/уведомления и кнопка **Свернуть все окна**.
  - **Свёрнутые и фоновые приложения (`^`):** стрелочка трея для быстрого разворота, закрытия или завершения процессов.
- **Темы, цвета и свой фон:**
  - 4 встроенные темы: **Стекло**, **Неон**, **Океан**, **Светлый**.
  - Редактор цветов и пресетов: настройка акцента, фона и рамки в формате `#RRGGBB` / `R, G, B` или через выпадающий **цветовой круг**, создание и переименование своих пресетов.
  - **Свой фон (PNG / анимированный GIF):** установка любого изображения или GIF-анимации в качестве фона панели.
- **Умное поведение и автозапуск:** автоматическое скрытие в полноэкранных играх и при открытии меню «Пуск», а также настройка автозапуска от имени администратора без повторных запросов UAC.
- **Смена языка:** переключение интерфейса между **RU** и **EN** прямо в настройках.
### 🚀 Запуск и сборка
- **Запуск:** скачайте `CustomDock.exe` из раздела **Releases** и запустите (вшит манифест `requireAdministrator` для управления окнами и панелью задач).
- **Сборка из исходников:** запустите `build.bat` (использует встроенный в Windows компилятор `csc.exe` из `.NET Framework 4.x`, Visual Studio не требуется).
