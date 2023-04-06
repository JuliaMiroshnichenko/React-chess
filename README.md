![chessCover](https://github.com/JuliaMiroshnichenko/React-chess/blob/master/cover.jpg)

[author: @ayunannas]

## Шахматы / Chess 

---

### Стек / Stack: 

* React
* TypeScript

---

### Этапы разработки: 

1. Инициализация React приложения
2. Создание ООПшных классов для шахмат. Инициализация клетки шахматной доски
3. Расстановка фигуры
4. Координаты доски. Х Y
5. Логика игры. Подсвечивание доступных для хода клетки
6. canMove. Движение фигур ( Ферзь, слон, ладья )
7. Движение коня и пешки
8. Перезапуск игры. Передача хода
9. Список съеденных фигур. Таймер

---

### Что осталось реализовать [в дальнейшем] : 

10. По истечении времени добавить проверку по условию if ( timer < 0 ) { } в таймер, у какого игрока обнулился, 
значит игрок проиграл, вывести на экран "Белые проиграли!" и перезапустить игру  
12. Логика движения короля 
13. Добавить условие для шаха и мата. Метод canMove - проверить, находится ли король под атакой,
определить также как, на какие позиции движется каждая из фигур. 
Смотрим ( target ), если на ( target ) идет атака от любой из фигур, то это шах, и надо подвинуть или защитить короля.
Сделать метод ( isKingUnderAttack ) и добавить < условия > 
14. Добавить условия на < мат >, < на победу > ( у каждой фигуры есть availablePoints , благодаря которым идет определение, куда может идти фигура,
если Король под атакой ( тот же метод isKingUnderAttack )),
если у короля нет свободных полей куда-либо пойти и его нечем защитить ( < высчитать > точки для соседних фигур ), 
то игра закончена, ставится мат 
15. История ходов ( записывать куда-то )
16. Реализовать на < ход вперед >, на < ход назад > ( Undo ), ( Redo )

---

### Инструкция по запуску : 

1. `npm install`
2. `npm start`

---

## Не забудьте поставить звездочку ! ! ! ★ 

