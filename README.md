# Домашнее задание к занятию «4. Puppeteer 1»


## Задача 1. Puppeteer timeout

1. [Проект с лекции](https://github.com/netology-code/jsaqa-code/tree/main/7.4/puppeteer).
2. Исследуйте настройки тайм-аутов и уберите тайм-ауты из конфигурации.
3. Задайте тайм-ауты для каждого из тестов в отдельности.


## Задача 2. Puppeteer before and after hooks

1. Добавьте ещё три теста к существующим и поместите их за блоком `describe`. 
Новые тесты должны проверять заголовки на других страницах приложения.   
3. Существующие хуки не будут подходить для этих тестов, так как новые тесты будут содержать другую стартовую страницу. 
Преобразуйте код так, чтобы всё работало, и соблюдался принцип DRY (Don't Repeat Yourself).
    
<details>
  <summary>Подсказка.</summary>
  
   Хуки можно использовать в разных местах и не один раз, поместив их в логические блоги, в которых они будут работать: например, внутри блока `describe`. Выше по иерархии кода они не будут действовать, так как работает стандартный принцип зоны видимости.
  
</details>

3. Запушьте репозиторий — изменения для двух задач — и сдайте ссылку на проверку.

<br>

------------------
### ***Добавлено в соответствии с заданием:***
  Добавлены к существующим и помещены за блоком `describe` три теста, проверяющие заголовки на других страницах приложения.

------------------

<br>