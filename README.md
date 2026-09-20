> **Language:** Русский · [English](README.en.md)

# Simple Elytra Hud Extended (Minecraft 1.21.4) 

> **Добавлено в этой версии:** поддержка элитр из кастомных модов. HUD теперь работает не только с ванильными элитрами (`minecraft:elytra`), но и с любыми предметами-глидерами из модов (например, незеритовые элитры, элитры из `Elytra Reborn`, `Elytra Revamped` и аналогичных) благодаря проверке через `LivingEntity#canGlideWith`.

![Flying with an elytra with the hud up](https://cdn.modrinth.com/data/cached_images/050acab9f4ab75f1117c5357e6914d76c1707a8e.png)

## Информация

Elytra Hud добавляет новый способ полёта с вашей элитрой.
Он выводит важную информацию на экран во время полёта.
Используйте этот мод для долгих перелётов, чтобы получить максимум от путешествия.

## Возможности HUD

> #### Левая часть
> У нас есть три текстовых поля, по порядку:
> 1. Ваш [угол наклона](https://minecraft.wiki/w/Elytra#Flying).
> 2. Скорость в км/ч
> 3. Координаты
> #### Середина
> В центре находится статус вашей элитры.
>
> Справа от него — стрелки вверх и вниз.
> Если вы летите вверх, она загорается; то же самое при полёте вниз.
> #### Правая часть
> Справа находится компас. Это не обычный компас, потому что он всегда указывает в направлении вашего движения.

# Конфигурация

Моду требуется [YetAnotherConfigLib](https://modrinth.com/mod/yacl) и [modmenu](https://modrinth.com/mod/modmenu).

> #### Параметры конфигурации
> Они расположены по порядку в меню конфигурации.
> - Видимость HUD — если хотите отключить отображение HUD
> - Задержка HUD — время, через которое появляется HUD
> - Статус элитры — можно отключить уровень повреждения элитры в HUD
> - Координаты элитры — при желании можно отключить координаты в HUD
> - Измерение скорости — доступны км/ч (по умолчанию), м/с или миль/ч

# Как скачать?

### С лаунчером (рекомендуется)
1. Скачайте [Modrinth launcher](https://modrinth.com/app) (более удобный) или [Prism launcher](https://prismlauncher.org/) (больше опций, но сложнее для новичков)
2. Создайте профиль для нужной версии Minecraft и убедитесь, что он на Fabric. Сначала проверьте совместимость мода с этой версией.
3. Мод можно скачать в лаунчере
   4. (Modrinth launcher) В профиле в правом углу нажмите «Add content» и найдите «Simple Elytra Hud» и нажмите «install».
   5. (Prism launcher) Зайдите в профиль, нажав «edit», затем «Mods» и «Download mods». На вкладке Modrinth напишите «Simple Elytra Hud». Отметьте для загрузки и нажмите confirm.
   6. Вам нужны modmenu и YetAnotherConfigLib. Скачайте их так же!
4. Теперь можно запускать профиль и наслаждаться!
### Без лаунчера
1. Мод можно скачать здесь на [Modrinth](https://modrinth.com/mod/simpleelytrahud/versions) или [Github](https://github.com/lukasabbe/transport-hud/releases)
2. Также понадобится [Fabric API](https://modrinth.com/mod/fabric-api/versions)
3. Также понадобятся [Mod Menu](https://modrinth.com/mod/modmenu) и [YetAnotherConfigLib](https://modrinth.com/mod/yacl) (в версиях ниже 1.6 и опциональном [cloth config](https://modrinth.com/mod/cloth-config))
4. Также понадобится [fabric](https://fabricmc.net/use/installer/), и он автоматически создаст профиль
5. Положите моды в %appdata%/.minecraft/mods
6. Теперь можно играть в Minecraft

# Открытый исходный код

Почти все мои моды с открытым исходным кодом и под лицензией MIT.
Не стесняйтесь использовать их как угодно.
Если хотите помочь разработке, загляните в [GitHub](https://github.com/lukasabbe/transport-hud)!

Если вы нашли ошибку, пожалуйста, сообщите о ней [здесь](https://github.com/lukasabbe/transport-hud/issues)!

# Вдохновение и авторы
- Мод вдохновлён [Boat HUD](https://modrinth.com/mod/boathud)
- Код написал Lukasabbe
- Графику сделал Lemonixi
- Идею предложил Smurre

Спасибо всем за скачивание мода!