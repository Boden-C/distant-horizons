<img src="https://gitlab.com/distant-horizons-team/distant-horizons-core/-/raw/main/_Misc%20Files/logo%20files/new/SVG/Distant-Horizons-M.svg" height="256px">

# LOD файлы для Distant Horizons
LOD-файлы многих популярных карт для Distant Horizons alpha 2.1+

## Куда помещать
**Одиночная игра:**
- Верхний мир: `.minecraft/saves/ИМЯ_МИРА/data/DistantHorizons.sqlite`
- Нижний мир: `.minecraft/saves/ИМЯ_МИРА/DIM-1/data/DistantHorizons.sqlite`
- Энд: `.minecraft/saves/ИМЯ_МИРА/DIM1/data/DistantHorizons.sqlite`
- Пользовательские измерения: `.minecraft/saves/ИМЯ_МИРА/ПАПКА_ИЗМЕРЕНИЯ/data/DistantHorizons.sqlite`

**Многопользовательская игра:**
- `.minecraft/Distant_Horizons_server_data/ИМЯ_СЕРВЕРА/`

## Загрузки
| Мир | Версия Мира | Версия DH | Загрузка | Комментарии | Версия Загрузки |
| --- | --- | --- | --- | --- | --- |
| [Wynncraft](https://wynncraft.com/) | 2.1 Bonfire | a2.1+ | [СКАЧАТЬ](../..//releases/tag/wynn1.2) | Основано на [файлах Throwneb](https://forums.wynncraft.com/threads/distant-horizons-v2-lod-files-for-wynncraft-map.315647/), обновленных до DH a2.1, используйте их пост для инструкций | wynn1.2
| [Drehmal](https://www.drehmal.net/) | 2.2 Apotheosis | a2.1+ | [СКАЧАТЬ](https://drive.usercontent.google.com/download?id=1Sb9k6IC0z-qu6gNy28mX8cEyvjd_ovQr&export=download&authuser=0) | Предоставлено Kofi на Discord-сервере Drehmal | внешний
| [Middle Earth](https://www.mcmiddleearth.com/) | Июль 2024 | a2.1+ | [СКАЧАТЬ](https://www.mcmiddleearth.com/community/resources/distant-horizons-base.170/download) | [Инструкции](https://www.mcmiddleearth.com/community/resources/distant-horizons-lods.171/) Предоставлено Feuerdrache0 | внешний

<br><br><br>

# Файлы Bobby/Загрузка Мира

## Куда помещать
`.minecraft/.bobby/ИМЯ`

## Как скачать мир
Bobby сохраняет целые файлы чанков `.mca`, что означает, что полная папка Bobby функционирует как полный мир для скачивания.
1. Создайте пустой пустотный мир (используйте пользовательский пресет)
2. Перейдите в `.minecraft/saves/ИМЯ_МИРА/`
- Верхний мир находится в `ИМЯ_МИРА/region`
- Нижний мир находится в `ИМЯ_МИРА/DIM-1/region`
- Энд находится в `ИМЯ_МИРА/DIM1/region`
- Пользовательские измерения находятся в `ИМЯ_МИРА/ПАПКА_ИЗМЕРЕНИЯ/region`
2. В папке .bobby и соответствующем имени вы увидите измерения. Скопируйте их в соответствующие папки region.
Вы должны копировать файлы `.mca` туда, где находятся файлы `.mca`. (Для Wynncraft вам, скорее всего, понадобится скопировать только верхний мир.)

## Загрузки
| Мир | Версия Мира | Загрузка | Комментарии | Версия Загрузки |
| --- | --- | --- | --- | --- |
| [Wynncraft](https://wynncraft.com/) | Постоянно обновляется | [Скачать через DownGit](https://downgit.github.io/#/home?url=https://github.com/Wynncraft-Overhaul/majestic-overhaul/tree/immersive/.bobby/play.wynncraft.com/0/minecraft) | Olinus поддерживает модпак [Wynncraft Majestic Overhaul](https://github.com/Wynncraft-Overhaul/majestic-overhaul), который содержит обновленные [файлы Bobby](https://github.com/Wynncraft-Overhaul/majestic-overhaul/tree/immersive/.bobby/play.wynncraft.com/0/minecraft). К сожалению, GitHub не поддерживает загрузку каталогов, поэтому здесь используется сторонний сервис. Если он перестанет работать, скачайте весь модпак [здесь](https://github.com/Wynncraft-Overhaul/majestic-overhaul/archive/refs/heads/immersive.zip). | внешний

<br>

# Вклад

Вклад приветствуется и поощряется! Если у вас есть LOD-файлы для SMP, пользовательских карт, серверов или чего-то популярного, создайте [issue](../../issues), и я добавлю их.
