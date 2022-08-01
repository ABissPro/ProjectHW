# ProjectHW
# Инструкция
## Подзаголовок
### 1. Шрифт
* *курсив* создается при помощи обрамления слова (*)
* **полужирный** обрамление (**)
* ~~зачеркнутый~~ обрамление (~~)
* ***Жирный текст курсивом*** обрамление (***)
- `code` обрамление (`)
- >цитируемый текст добавлением перед цитатой (>)
- >>текст (>>)
- >>>g (>>>)
- >>>>h (>>>>)
* [текст ссылки](URL_ссылки)

 ### 2. Текст

 * Строка текста +2Enter;  TAB
 
    Еще одна строка текста под ней после пустой

* Для кода можно использовать комбинацию (```) , начиная с новой строки можно писать код. Закрыть поле ода можно используя такую же комбинацию с новой строки.

```
import java.util.Scanner;

public class Scan1 {

	public static void main(String[] args) {
			System.out.print("Введите ваш диметр, см");
			Scanner d = new Scanner (System.in);
			float diametr = d.nextFloat ();
			float diametrt = d.nextFloat ();
			float dd = 2;
			float s = (float) Math.pow(diametr, dd);
			float st = (float) Math.pow(diametrt, dd);
			float g = (float) ((3.14*s)/4);
			float gt = (float) ((3.14*st)/4);
			System.out.println ("Площадь сечения на уровне груди равна " + g + ("см"));
			System.out.println ("Площадь сечения на уровне груди равна " + gt + ("см"));
			

	}

}
``` 



 ___
ошибка

![Зелье](https://static.wikia.nocookie.net/habitrpg/images/f/fc/Pet_HatchingPotion_Zombie.png/revision/latest?cb=20210503121739)
___
![progress](https://static.wikia.nocookie.net/habitrpg/images/3/32/Progress_bar.png/revision/latest?cb=20190727093726)
___
| Заголовок 1 | Заголовок 2 |
|:-----------:|:-----------:|
| клеточка 1 | клеточка 2<br/>вторая стр|
