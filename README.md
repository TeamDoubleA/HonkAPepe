# HonkAPepe
## Објаснување на проблемот : </br>
Играта се базира на познатата игра *“Урди го кртот”*.</br></br>
## *Функционалности* : </br> 
Фигура која се појавува на псевдо-случајна локација на секои ≤0.75 секунди.
Се користи интерна база(Application settings), за чување на highscore. 
Покажувач за интеракција со фигурите. Поле за приказ на најдобриот резултат (highscore), број на моментални поени како и број на моментални промашувања.
Копче за повторно играње. Стандардно копче за излез од апликацијата.

## *Опис на решение*: </br>  
Освен integers за бројач на секунди, highscore, моментални поени и промашувања, користевме Booleans за ознака дали играта е во активна состојба ("се игра") или е во состојба на мирување ("стоп"), и за ознака дали тековната рунда е прва.</br>
[Image](https://i.ibb.co/T236P2H/Honk-Apepee.jpg)

## *Опис на функција*:  **timer1_Tick** </br>
При секој тик, што е наместен на 0.75 секунди се бираат нови псевно случајни x,y координати за фигурата, и таа се иницијализира на истите.
Потоа се проверува дали играчот направил 15 или повеќе промашувања со што играта влегува во "стоп" состојба, и на полето се печати "GAME OVER".
Потоа соодветно се ажурира highscore доколку е помал од тековниот број на поени. Доколку ова е прва рунда исто така во поелто се појавува и копче за повторна игра.
Исто така кога ќе изминат 15 секунди во играта се активира easter egg во времетрање од 1 секунда.</br>

## Изработиле
  * Антонио Цековски 161241
  * Александар Тренчев 161147

