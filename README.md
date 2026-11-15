# Наркобезумие (Fabric 1.20.1)
Нужны: JDK 17 и Gradle 8.6+.
Сборка:  gradle build  ->  build/libs/narkobezumie-1.0.0.jar (без -sources). Нужен Fabric API.

Моб: /summon mymod:igor  или яйцо призыва в творческом режиме.
Здоровье и урон: IgorEntity.java (MAX_HEALTH, ATTACK_DAMAGE).
Своя музыка: положите tense_music.ogg в assets/mymod/sounds/ и в sounds.json замените
"minecraft:records/11" на "mymod:tense_music".
Чтобы Игорь появился снова: удалите файл data/mymod_igor.dat в папке мира.
Песня смерти: assets/mymod/sounds/death_song.ogg (первые 10 сек), играет на экране смерти.

Миста Вааай: напишите в чат «почему он синий» -> через 10 секунд появится моб (20 HP, урон 1),
играет тема из assets/mymod/sounds/mista_theme.ogg, после смерти падает иглобрюх.
Команда: /summon mymod:mista

Яйцо с лицом (mymod:egg_face): оружие, урон 2 HP, лежит в сундуках мира (шанс 15%, ModItems.CHEST_CHANCE).
Выдать: /give @s mymod:egg_face
Выдать: /give @s mymod:egg_face

Сборка в облаке: загрузите папку проекта в репозиторий GitHub, во вкладке Actions запустится сборка,
готовый .jar скачайте из Artifacts (narkobezumie-jar).
