1.
Для родителя текста marquee задаём overflow: hidden, чтобы не показывать лишнее по краям блока. Чтобы текст был в одну линию и не переносился на вторую строку, добавляем white-space: nowrap.
Для самой строчки marquee__text добавляем оформление текста. Лучше в такой анимации смотрится текст с заглавными буквами.

2.
Далее опишем параметры анимации marquee-moving. Время (10s) должно быть достаточно большим, чтобы текст можно было прочитать. 
Текст движется равномерно (linear). Анимация повторяется по кругу, то есть бесконечно (infinite).

3.
У нас будет два ключевых кадра: сначала текст сдвинут вправо, за край блока-родителя, а затем перемещается налево.
Такие анимации, выполненные только с помощью CSS, имеют ряд недостатков. Один из них — создаётся ощущение, словно у нас есть момент ожидания перед запуском второго круга. 
И если текста будет гораздо больше или меньше, то анимацию придётся корректировать. Но для простых ситуаций это вполне неплохой подход.