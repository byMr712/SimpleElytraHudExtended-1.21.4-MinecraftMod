> **Language:** Русский · [English](README.en.md)

# Simple Elytra Hud Extended (Minecraft 1.21.4)

![Java 21](https://img.shields.io/badge/Java-21-blue.svg)
![Minecraft](https://img.shields.io/badge/Minecraft-1.21.4-blue.svg)
![Fabric](https://img.shields.io/badge/Loader-Fabric-blue.svg)
![ModMenu](https://img.shields.io/badge/ModMenu-Supported-blue.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

> **Добавлено в этой версии:** поддержка элитр из кастомных модов. HUD теперь работает не только с ванильными элитрами (`minecraft:elytra`), но и с любыми предметами-глидерами из модов (например, незеритовые элитры, элитры из `Elytra Reborn`, `Elytra Revamped` и аналогичных) благодаря проверке через `LivingEntity#canGlideWith`.

---

## О моде

**Elytra Hud** добавляет новый способ полёта с вашей элитрой, выводя ключевую информацию о полёте на экран в реальном времени.

---

## Галерея интерфейса

| Полет с HUD в реальном времени | Элементы интерфейса |
|:---:|:---:|
| ![Полет с активным HUD](images/elytra_hud_flying.webp) | ![Внешний вид HUD](images/elytra_hud.png) |

---

## Возможности HUD

- **Левая панель**:
  1. Текущий угол наклона (Pitch).
  2. Скорость полёта (км/ч, м/с или миль/ч).
  3. Текущие координаты игрока (X, Y, Z).
- **Центральная панель**:
  - Графическая шкала прочности элитры.
  - Индикаторы направления (стрелки набора высоты и пикирования).
- **Правая панель**:
  - Динамический компас, указывающий точное направление движения.
- **Параметры конфигурации**:
  - Видимость HUD (включение/отключение).
  - Задержка появления HUD после старта полёта.
  - Отображение прочности элитры.
  - Отображение координат.
  - Выбор единиц измерения скорости (км/ч, м/с, миль/ч).

---

## Установка

1. Скачайте последнюю версию со страницы [GitHub Releases](https://github.com/byMr712/SimpleElytraHudExtended-1.21.4-MinecraftMod/releases).
2. Требуются:
   - [Fabric API](https://modrinth.com/mod/fabric-api)
   - [YetAnotherConfigLib (YACL)](https://modrinth.com/mod/yacl)
   - [Mod Menu](https://modrinth.com/mod/modmenu) (по желанию)
3. Поместите `.jar` файл в папку `mods`.
4. Запустите игру.

---

## Сборка

1. Требуется Java 21 и Fabric Loader для Minecraft 1.21.4.
2. Для сборки выполните:
   ```bash
   ./gradlew build
   ```
3. Собранный файл находится в `build/libs/SimpleElytraHudExtended-1.21.4-byMr712.jar`.

---

## Авторы и лицензия

- Оригинальный код: [Lukasabbe](https://github.com/lukasabbe) ([Simple Elytra Hud](https://modrinth.com/mod/simpleelytrahud)).
- Модификация и расширение для 1.21.4: [Mr712](https://github.com/byMr712).
- Графика: Lemonixi.
- Идея: Smurre.
- Распространяется под лицензией [MIT License](LICENSE).