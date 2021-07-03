# Приоритизация гипотез и анализ A/B-теста для интернет-магазина

---

## Задача

---
Используя данные интернет-магазина, приоритизировать гипотезы по увеличению выручки. Произвести оценку результатов A/B-тестирования различными методами для принятия решения по гипотезе.

## Данные

---

Данные были представлены в трех файлах:

1. Данные по гипотезам:

 - краткое описание гипотезы;
 - охват пользователей по 10-балльной шкале;
 - влияние на пользователей по 10-балльной шкале;
 - уверенность в гипотезе по 10-балльной шкале;
 - затраты ресурсов на проверку гипотезы по 10-балльной шкале. 


2. Данные о заказах:

 - идентификатор заказа;
 - идентификатор пользователя, совершившего заказ;
 - дата заказа;
 - выручка с заказа;
 - группа A/B-теста, в которую попал заказ.


3. Данные о посещениях сайта интернет-магазина:

 - дата;
 - группа A/B-теста;
 - количество пользователей в указанную дату в указанной группе A/B-теста.

## Используемые библиотеки

---

- pandas
- numpy
- scipy 
- matplotlib
- seaborn 
- plotly
- datetime 