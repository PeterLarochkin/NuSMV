## Система

Дано квадратное поле 4х4. В каждой ячейке поля есть лампочка. Три игрока по очереди переключают лампочки (переключить: если была выключена, то зажечь, иначе выключить).
Первый игрок выбирает лампочку и переключает её и все соседние по вертикали и горизонтали, если они есть. После первого игрока ходит второй.
Второй игрок выбирает лампочку и переключает её и все соседние по вертикали, горизонтали и диагонали, если они есть. После второго игрока ходит третий.
Третий игрок выбирает лампочку и переключает её, а также две соседние слева и две соседние справа, если они есть. Кроме того, третий игрок решает, какой из первых двух игроков ходит следующим.

Начальная раскладка: все лампочки выключены.

### Свойства

1. Игроки могут зажечь все лампочки.
2. Игроки могут зажечь все лампочки так, чтобы правая верхняя лампочка до последнего хода всегда была выключена.
3. Игроки могут зажечь все лампочки, даже если третий игрок всегда выбирает первого следующим.
4. Как бы игроки ни выбирали лампочки до текущего момента, они обязательно имеют возможность продолжить выбирать лампочки так, чтобы зажечь их все.