# Шаховска Игра
## Изработиле: Славко Трајковски и Предраг Стерјоски

### Краток опис:

Класична шаховска игра, која се состои од шаховница со шаховски фигури, тајмер за игра и статус на игра.

### Излед на играта

1. Главен екран

![main_window](https://github.com/slavcetrajkovski/ChessGameVP/assets/126784837/92df4fca-e05b-46b1-adb1-76990979940b)

2. Контроли

![controls](https://github.com/slavcetrajkovski/ChessGameVP/assets/126784837/ef7b6250-59e8-4c43-b27a-4d003e60801d)

Копче "Restart" кое овозможува започнување на нова игра, како и стрелки за навраќање на потег.

3. Тајмер

![timer](https://github.com/slavcetrajkovski/ChessGameVP/assets/126784837/a1884ee4-c8f7-43cc-a750-cfe7fb4b4629)

Играта не започнува се додека не се притисне копчето "Start". По неговото притискање, се овозможува движење на соодветна фигура од белата страна. Откако ќе се направи првиот потег на белите фигури, тајмерот запира и почнува да одбројува на црните фигури. Ова се случува континуирано се додека играта не заврши.

4. Статус

![state](https://github.com/slavcetrajkovski/ChessGameVP/assets/126784837/656ffecb-494f-434b-a605-d26947cc934e)

"NORMAL" статус кој што означува нормален тек на играта. Овој статус се менува во зависност од текот на играта, кој ќе го видиме во наредните слики.

### Тек на игра

1. "NORMAL"

 ![normal_main_window](https://github.com/slavcetrajkovski/ChessGameVP/assets/126784837/6095c685-9b89-48ee-a574-c1a2c5a5a809)

 Нормален тек на игра.

 2. "CHECK"

![check_main_window](https://github.com/slavcetrajkovski/ChessGameVP/assets/126784837/50cbfc61-081b-40b4-b3a5-6c430a925f01)

Статусот се менува во "CHECK", кога Кралот е во опасност но има се уште потези во игра.

3. "CHECKMATE"

![checkmate_main_window](https://github.com/slavcetrajkovski/ChessGameVP/assets/126784837/6001505e-f5ce-4d9e-a7be-418a5f9c518d)

Статусот се менува во "CHECKMATE", кога Кралот е во безизлезна ситуација, односно "Мат".



