#Список товаров
# Проверка валидации  поля «Количество» на странице Корзины - невалидные значения
#regress 

* Тестовые данные: прод  адрес сайта тест адрес сайта
  
* Предусловие:
1. Открыта главная страница 
2. В корзину добавлен один товар

* Шаги:
1. На главной странице нажать иконку "Корзина"
2. На странице Корзины в поле "Количество" ввести:  -1 
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
3. На странице Корзины в поле "Количество" ввести:  0.1
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
4. На странице Корзины в поле "Количество" ввести: 1/5
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
5. На странице Корзины в поле "Количество" ввести: 01110
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
6. На странице Корзины в поле "Количество" ввести: 5-2
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
7. На странице Корзины в поле "Количество" ввести: абв
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
8. На странице Корзины в поле "Количество" ввести: АБВ
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
9. На странице Корзины в поле "Количество" ввести: 這
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
10. На странице Корзины в поле "Количество" ввести: !»№
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
11. На странице Корзины в поле "Количество" ввести:  (пробел)
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
12. На странице Корзины в поле "Количество" ввести: 9999999999
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
13. На странице Корзины в поле "Количество" ввести: пустое значение (удалить 1)
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
14. На странице Корзины в поле "Количество" ввести: ♥ 
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
15. На странице Корзины в поле "Количество" ввести: 1A
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
16. На странице Корзины в поле "Количество" ввести: äß
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
17. На странице Корзины в поле "Количество" ввести: SELECT * FROM Users WHERE UserId = 105 OR 1=1
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.
18. На странице Корзины в поле "Количество" ввести: <script>alert(“text”);</script>
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна. 
19. На странице Корзины в поле "Количество" ввести: AbC
* Ожидаемый результат:
  Поле ввода не принимает невалидные значения. Оформление заказа невозможно. Кнопка "Перейти к оформлению" недоступна.   
    
  
Автор: Юлия Михайлова

Отчет о тестировании

Тестовый сервер

| Дата       | Время | Версия браузера Десктоп              | Результат/Баг в Трелло Десктоп | Версия браузера и ОС Тач         | Результат/Баг в Трелло Тач | Дата релиза | QA      |
| ---------- | ----- | ------------------------------------ | ------------------------------ | -------------------------------- | -------------------------- | ----------- | ------- |


Продовый сервер

| Дата       | Время | Версия браузера Десктоп              | Результат/Баг в Трелло Десктоп | Версия браузера и ОС Тач         | Результат/Баг в Трелло Тач         | Дата релиза | QA      |
| ---------- | ----- | ------------------------------------ | ------------------------------ | -------------------------------- | ---------------------------------- | ----------- | ------- |

