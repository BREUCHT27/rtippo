# Жучок
Я разрабатываю игру на c#, которая называется "Жучок". Человек с игровым именем запускает игру и выбирает ее формат, где уточняет количество ботов (1–5  ботов может играть с игроком) и режим игры. Есть стандартный режим, в котором надо самым первым собрать жука по правилам карточной версии, и расширенный режим, в котором игра продолжается после сборки жука (он исчезает со своего места, и игроку начисляются очки за него, каждая часть жука приносит по баллу). Перед началом игры игроку разрешается выбрать себе имя, у ботов имена заданы по умолчанию (Пример: "Бот1").

Игровые принадлежности:
1)одна виртуальная игральная кость с числами от 1 до 6 или специальная кость «жучок», стороны которой означают части тела жука и соответствуют числам по порядку: Т (туловище), Г (голова), Л (лапки), Гл (глаза), У (усики) и X (хвост);
2)схематичный рисунок жука в качестве шаблона (будет подсказкой каждого этапа построения жука), показывающего его различные части;
3) Место для сборки жука на игровом поле, где тот будет появляться в процессе игры.

Правила игры:
В каждом раунде игрок кидает кость один раз. Каждый участник должен начать с броска Т (или 1): это дает ему право получить туловище –, затем он может бросать кость по остальным частям тела жучка, присоединяемых к туловищу.
Чтобы присоединить к туловищу голову, необходимо выбросить Г (или 2), и лишь затем к ней можно присоединять усики (У или 5) и глаза (Гл или 4). Каждый глаз или усик требует отдельного броска.
Выпадение Л (или 3) позволяет игроку получить сразу три лапки с одной стороны туловища. Для других трех лапок необходимо еще раз выбросить Л (или 3).

Цель игры (стандартный режим):
Каждый игрок старается, бросая кость, завершить рисунок жучка. Первый собравший получает 13 очков, соответствующих количеству частей тела жучка (туловище, голова, хвост, два усика, два глаза и шесть лапок), и становится победителем.

Цель игры (расширенный режим):
Одна игра расширенного режима состоит из серии игр стандартного режима, каждый участник игры получает по одному очку за каждую полученную часть тела жучка и совокупный счет переносится из раунда в раунд. Победителем становится игрок, набравший предварительно определенное число очков.

Рисунок этапного построения жука:

![image](https://github.com/BREUCHT27/rtippo/assets/119112204/71d83d82-85c7-4970-8bae-73d17471f923)
![image](https://github.com/BREUCHT27/rtippo/assets/119112204/7324a0c4-a2ef-4332-b7a1-13d8a1094948)
![image](https://github.com/BREUCHT27/rtippo/assets/119112204/a9f75699-1a24-45fa-9ef8-459f4e7dac8a)








