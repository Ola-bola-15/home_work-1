# home_work-1
Приложение электронной почты, кроме прочего, состоит из следующих элементов: «Страница входа», «Главная страница», кнопки «Отправить письмо», «Удалить письмо», разделы «Удаленные», «Отправленные», «Входящие». В новом релизе был добавлен раздел «Черновики» и исправлена ошибка, при которой удаленное письмо попадало в раздел «Отправленные». 

1. Приведите примеры: 
- интеграционного теста приложения электронной почты; 
Ответ: Проверить связь между отправкой письма и его нахождением в разделе «Отправленные», удалением письма из «Входящих», проверить есть ли оно в разделе «Удаленные».

    **Тест-кейс:** https://docs.google.com/document/d/1q4Dktx2z0xoTB0YoSjd1r_1gk7Ansklv/edit?usp=sharing&ouid=100021507745040838112&rtpof=true&sd=true

- дымового теста приложения электронной почты; 
Ответ: Отправить готовое письмо в раздел «Черновики» и проверить добавилось ли оно туда.

    **Тест-кейс:** https://docs.google.com/document/d/1c4DpBh9g90My1ZHfolnYUGo47d_n28Yy/edit?usp=sharing&ouid=100021507745040838112&rtpof=true&sd=true

- ре-теста приложения электронной почты; 
Ответ: Удалить письмо, оно попало в «Отправленные». Провести проверку по тест-кейсу, проверить повторяется ли ошибка.

     **Тест-кейс:** https://docs.google.com/document/d/1fGS46BoCll3MMRxjqRsCTDG0Ay41YraD/edit?usp=sharing&ouid=100021507745040838112&rtpof=true&sd=true

- нефункционального теста приложения электронной почты. 
Ответ: Поверить скорость работы приложения в будний день с 8.00 до 12.00 и ночью с 01.00 до 03.00.

  **Тест-кейс:** https://docs.google.com/document/d/1CHgoUkzC365lAX7q0XP9ywSyLM1gP8se/edit?usp=sharing&ouid=100021507745040838112&rtpof=true&sd=true

_____
2. Необходимо ли провести регрессионное тестирование приложения электронной почты, в случае если (ответить отдельно для каждого случая, мотивируя свой ответ): 
  - добавлен раздел «Спам»; 
   
    **Ответ:** Нет, т.к. регрессионное тестирование проводится на уже исправленные ошибки. Надо провести: функциональное тестирование  (чтобы проверить, точно ли в эту папку попадают нежелательные письма),  нефункциональное (будут ли в папку «Спам» попадать все входящие письма) и дымовое (после отправления письма в папку «Спам», окажется ли оно там).

- раздел «Удаленные» переименован в раздел «Корзина»;
 
    **Ответ:** Нет, т.к. изменения произошли только в названии папки, а не в самом ее коде, функционал не изменился.

 - на «Странице входа» устранен ранее обнаруженный дефект. 
  
    **Ответ:** Да, надо проверить, как после устранения дефекта поведется себя приложение. Проверить еще раз задачу, где был баг.

____________
3. Какой вид тестирования желательно провести в первую очередь на новом билде (релизе) приложения? 
 
**Ответ:** Дымовое тестирование.
________________
4. В результате добавления раздела «Черновик» перестала корректно работать кнопка «Удалить письмо». Какой вид тестирования позволит обнаружить нам данный дефект?
 
**Ответ:** Тестирование совместимости.
