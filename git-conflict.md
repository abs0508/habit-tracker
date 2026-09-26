# Конфликт

Конфликт был в README.md в строке "Статус проекта".

В ветке docs/readme-update я поменял её на "продумываю MVP", а в ветке feature/checkins на "пишу план api". Сначала слил docs/readme-update в main, потом при слиянии feature/checkins git выдал:

CONFLICT (content): Merge conflict in README.md

Как исправил: открыл README.md, там были метки <<<<<<< ======= >>>>>>>. Удалил их и оставил одну строку, объединив оба варианта:
"Статус проекта: продумываю MVP, план api почти готов".
Потом git add README.md и отдельный коммит "исправил конфликт в README (строка со статусом)".
