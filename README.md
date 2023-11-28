# HSE_ML_course

Материалы практических занятий курса "Машинное обучение", 3 курс, НИУ ВШЭ

*Лектор Мыльников Л.А., семинары групп 3, 4 (Направление "Бизнес-информатика")*

*Семинарист Проворова А.А.*

---

В приложенных документах содержатся материалы с семинаров.

### Задания к семинарам:

### Модуль 2
---
**Семинар 1(9):**

##### Ассоциативные правила 

1)Исследовать данные на наличие ассоциативных правил на файле отличном от использованного в примере (пример выполнен на файле расположенном по [ссылке](https://disk.yandex.ru/d/Qvwpjgm5lwU2yQ)) 
2) Попробовать создать различные ассоциативные правила в зависимости от выбранных метрик и их пороговых значений.
3) Интерпретировать полученные результаты 

*Дополнительные баллы*: 

1)Исследовать файл с использованием алгоритма SlopeOne 
2)Исследовать файл с использованием алгоритма PageRank алгоритма

---
**Семинар 2(10):**

##### Повышение эффективности моделей

1) Решить задачу классификации методами k-NN, SVM, Naive Bayes, Decision Tree и провести оценку качества.
   Предлагаемые файлы для работы:

   *DataSet11_2* - Необходимо выявить на основании параметров клиентов, выплатит ли он кредит вовремя, т.е. определить, выдавать ли ему кредит (скоринг-модель)

   *DataSet11_3* - Данные о режимах работы технического устройства. Предсказание температуры на выходе (будет температура выше или ниже заданного порога? Т.е произойдет или нет срабатывание защиты). BK_T25  должно быть <400 что бы не происходило срабатывания защиты!

   Файлы можно найти по [ссылке](https://disk.yandex.ru/d/FJs9p6fbMKLddA)

3) Выполнить кроссвалидацию и сравнить качество получаемых результатов с результатами полученными на предыдущем этапе 
4) Построить композицию моделей и сравнить качество модели с предыдущими результатами 

*Дополнительные баллы*: 

1) Использовать свой файл данных (НЕ СБАЛАНСИРОВАННЫЕ ДАННЫЕ!!!) 
2) Использовать другие виды кроссвалидации 
3) Использовать другие методы построения композиций моделей

---

**Семинар 3(11):**

##### Работа с текстовыми данными

Обучите модель для определения принадлежности текста к одному из заданных классов. При разборе текста
используйте Bag of words (файлы данных см. по [ссылке](https://disk.yandex.ru/d/jelxVYweTEEftA )).

*Дополнительные баллы*:

1. Использовать свой файл данных
2. Провести лемматизацию/стемминг
3. Используйте TF-IDF
4. Используйте множественную классификацию

---

**Семинар 4(12):**

##### Метод гистограмм ориентированных градиентов (HOG)

1) Исследуйте пример по определению наличия заданного объекта на изображении (в примере определяется
наличие на изображении коровы, файлы данных расположены по [ссылке](https://disk.yandex.ru/d/oxqQtX6tFKXjjw))

2) Сформировать свою выборку для обучения модели которая будет содержать 100 изображений с наличием
объекта для распознания и 100 изображений без объекта для распознования. Обучить на собранных данных
несколько моделей классификации и сравнить их эффективность.

3) Добавить в массив данных для обучения названия файлов и после обучения модели проанализировать
визуально и сделать выводы о том какие особенности имеют изображения которые определяются верно и какие
особенности имеют изображения определяющиеся с ошибками.

*Дополнительные баллы*:
1. Реализовать оценку наличия заданного объекта на изображении методом Далала-Тригса
   
---

**Семинар 5(13):**

##### Работа с текстовыми данными (часть 2)

1) Обучите модель для определения принадлежности текста к одному из заданных классов. При разборе текста
используйте разбор текста по частям речи и построение векторов(файлы данных см. по [ссылке](https://disk.yandex.ru/d/y3y3dCl-2-dN5g)).
2) Проведите апробацию модели на всех приведенных файлах.
3) Сравнить результаты и сделать выводы.

Для определения класса используйте таблицу следующего вида:

![image](https://github.com/annaprovorova/HSE_ML_course/assets/42402997/5808a837-b6ce-4665-b566-c01b2b99bfa8)

*Дополнительные баллы*:

1. Использовать свой файл данных **на другом языке**
2. Изменить набор выделяемых частей речи (ввести дополнительные)

---

**Семинар 6(14):**

##### Работа с текстовыми данными (часть 3 – прототип чат бота)

1) Изучите предложенный пример. 
2) Модифицируйте предложенный пример под свои пары вопрос-ответ и сформулируйте не менее 5 своих вопросов.
3) Исследуйте работу системы и сделайте выводы о применимости к своему набору данных способов оценки схожести и структурирования информации и текстовых данных.
  
*Дополнительные баллы*: 
1. Доработайте код таким образом чтобы у него был интерфейс через который можно было формулировать вопрос и получать ответ.
2. Сделайте бонусное зедение, подключив API любого сайта(по Вашему выбору).
   
---
---
### Модуль 1
---

**Семинар 1:**

##### Построение графиков данных (графики, гистограммы, BoxPlot диаграмы, круговые диаграммы и др.)

Взять любой интересующий вас датасет с https://www.kaggle.com/datasets или скачать [отсюда](https://disk.yandex.ru/d/ZKrrXqH5nrp2Gw )

Проанализировать данные и построить к ним графики.

Работа должна содержать не менее 5 графиков разных типов и выводы по ним. Результат работы оформить в ipynb/google collab

*Дополнительные баллы:*  
1) Свой файл данных;
2) Качественный анализ данных (описание)
3) Использование дополнительных способов визуализации
   
Дополнительное задание к семинару см. в [материалах к семинару](https://github.com/annaprovorova/HSE_ML_course/blob/main/sem%201.ipynb)

---

**Семинар 2**
##### Преобразование данных 

1) Подобрать данные с Kaggle или других источников в свободном доступе (Список источников [см. здесь](https://github.com/annaprovorova/HSE_ML_course/blob/main/%D0%98%D1%81%D1%82%D0%BE%D1%87%D0%BD%D0%B8%D0%BA%D0%B8%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.md))
2) Вычислить новые показатели
3) Оценить Accuracy

*Дополнительные баллы:*
   1) Очистка данных
   2) Другие методы решения задачи или методы оценки эффективности
  
---

**Семинар 3**

##### Интерполяция

Взять не менее 10 значений и построить по ним интерполяционные кривые по формуле Лагранжа, по формуле Ньютона, с использованием сплайнов (интерполяция кубическим сплайном).

Можно использовать [готовые датасеты](https://disk.yandex.ru/d/2od1XdMfVv3Z6Q) или взять свой с [открытых источников](https://github.com/annaprovorova/HSE_ML_course/blob/main/%D0%98%D1%81%D1%82%D0%BE%D1%87%D0%BD%D0%B8%D0%BA%D0%B8%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.md)

---

**Семинар 4**

##### Однопараметрическая экстраполяция

1) Взять файлы данных с временными рядами прошлых работ или подобрать свои (DataSet3_1, DataSet3_2, DataSet1_4).
2) Взять не менее 100 значений и разбить их на 2 выборки (80 и 20) и исследовать возможность прогнозирования с использованием одного параметра.
3) Использовать первые 80 значений для обучения моделей - методом МНК для функций y=c0+c1*x+c2*x^2 - методом kNN - ARIMA модели
4) Построить графики получаемых с использованием построенных моделей функций и нанести значения из тренировочной и тестовой выборок
  
*Дополнительные баллы:* 
1) Усложнить функцию для метода МНК;
2) Реализовать методы МНК и/или kNN и/или авторегрессии без использования библиотек;
3) Проверить выбранные для описания значения (ряд) на стационарность (тест Дики-Фуллера + другие способы проверки).

---

**Семинар 5**

##### Многопараметрическая экстраполяция

1) Взять файлы данных с временными рядами прошлых работ или подобрать свои
    - DataSet1_4 (ссылка прикреплена к заданию к семинару 1);
    - DataSet5_1 – «Динамика цен на основные социально значимые продовольственные товары в розничной сети Свердловской области» (данные сортированы по следующим столбцам:
         1) Дата мониторинга;
         2) кура охлажденная и мороженая. руб./кг;
         3) молоко цельное питьевое 2.5-3.2% жирности. руб./л.;
         4) мука пшеничная в/с. руб./кг;
         5) хлеб и булочные изделия из пшеничной муки 1 и 2 с.. руб./кг;
         6) яйцо куриное. руб./дес.;
         7) картофель. Руб./кг.;
    - DataSet5_2 – данные об аренде велосипедов (задание со школы Сириус 2022 года))
   (ссылка - https://disk.yandex.ru/d/lXRX2k0yiLwR5Q).
3) Выбрать параметры используемые для прогнозирования, взять не менее 100 значений и разбить их на 2 выборки (80 и 20)
4) Использовать первые 80 значений для обучения моделей -методом МНК (квадратичная гипотеза), методом kNN, методом SVM, методом Lasso, методом PLS
   3.1 Использовать не менее 2-х параметров для прогнозирования целевого параметра
   3.2. Добавить к параметрам из варианта 3.1 значения целевого параметра со сдвигом на один шаг в прошлое (отставание от прогнозируемого значения на один шаг)
5) Построить графики получаемых с использованием построенных моделей функций и нанести значения из тренировочной и тестовой выборок

*Дополнительные баллы:*

Реализовать прогнозирование на заданное (N) количество шагов в будущее  используя для прогнозирования каждого следующего шага (кроме первого) прогнозные значения параметров. Для прогнозирования первого значения используются реальные снятые значения. Обучение модели осуществляется как в основном задании.

---

**Семинар 6**

##### Сравнение временных рядов

1) Взять файлы данных из предложенных наборов (3-4 нормативных и 3-4 ненормативных сигнала, https://disk.yandex.ru/d/l9hS2owRKUMdoQ )

Файлы содержание в названии h… - нормативная работа подшипника (сигналы с четырех датчиков вибрации) 
Файлы содержание в названии b… - не нормативная работа подшипника (сигналы с четырех датчиков вибрации)). 

2) Взять не менее 100 значений

3) Посчитать для всех сочетаний значения коэффициентов корреляции (Пирсона, Спирмена, Кендала) и сделать соответствующие выводы

4) Посчитать значение DTW для всех сочетаний, сравнить со значениями коэффициентов корреляции, сделать выводы
  
5) Посчитать спектральную плотность сигнала

6) Разложить временные ряды на составляющие

*Дополнительные баллы:*

1. Провести оценки коэффициентов корреляции и DTW для спектральной плотности сигнала 
2. Спрогнозировать составляющие полученные при разложении методом STL с использованием методов с предыдущего семинара, восстановить прогнозные значения, построить графики исходного и прогнозного временных рядов

**ВАЖНО!!! Обязательно посмотрите материалы Л.А. Мыльникова к семинару в SmartLMS**

---

**Семинар 7**

#### Проверка адекватности моделей

1) Проверить адекватность полученных ранее (на практике 5) моделей -построить графики исходных и полученных данных - построить скрипичные диаграммы исходных и полученных данных -получить значения MAE, RMSE, MAPE, MASE -проверить адекватность полученных моделей с помощью критерия , Фишера, Стьюдента 

2) Произвести выбор модели на основе полученных результатов χ2
  
*Дополнительные баллы:* 

1. Построить функции распределения исходных данных 

2. Использовать дополнительные критерии/тесты проверки адекватности моделей

---

**Семинар 8**

#### Переход от задачи регрессии к задаче классификации

1) Построить регрессионную модель
   - взять файл DataSet1_3 (см. первую практическую работу) и спрогнозировать значение стоимости акций компании Google
   - или взять свой файл данных
2) Свести задачу регрессии к задаче классификации для этого
   -для задачи со стоимостью акций на основе двух соседних значений  ввести два класса 0 (если цена падает) и 1 (если цена растет)
3) Построить модели классификации для предсказания
   -роста или спада значений акций
5) Сравнить качество моделей по критериям (Confusion Matrix, ROC кривая, Accuracy, Precision, Recall, F-мера, Log Loss)
  
*Дополнительные баллы:* 

1) Использовать свой файл данных 
2) Рассмотреть не менее 3-х дополнительных моделей классификации и обосновать выбор одной из них

---

# Важная информация!

Как расчитывается оценка?

**Оценка за 1-й модуль** = округление до целого $(0.2 * Score_{1} + 0.4 * Score_{2} + 0.2 * Score_{3})$

$Score_{1}$ - текущее тестирование после каждого лекционного занятия. Принимает значение от 0 до 10 путем сложения набранных баллов за каждый тест теста. Балл за каждый тест = 10/6 ставится в случае, если получены верные ответы на все вопросы. В противном случае за результат теста присваивается значение 0.1 или 0 если студент не пытался его написать.

$Score_{2}$ – выполнение заданий на практиках. Принимает значение от 0 до 10 путем сложения баллов за каждое задание. Балл за каждое задание = 10/8 и ставится в случае, если задание выполнено верно, были заданы вопросы и даны верные ответы преподавателю. В противном случае за выполнение задания присваивается нулевое значение. При сдаче задания после простановки оценки за первый модуль за каждое задание присваивается 0,6 балла (получившееся в результате корректировки оценка за 1-й модуль идет в расчет итоговой оценки за второй модуль).

$Score_{3}$ – тест по первому модулю. Принимает значение от 0 до 10. Тест проводится в форме тестирования и состоит из 20 вопросов: 10 вопросов по теории и 10 вычислительных. Число баллов зависит от числа правильных ответов. За каждый вопрос при полностью правильном ответе можно получить 0.5 балла.

**Оценка за 2-й модуль** = округление до целого $(0.1 * Score_{1} + 0.25 * Score_{2} + 0.2 * Score_{3} + 0.25* Score_{4}+0.2* Score_{add})$

$Score_{1}$ - текущее тестирование после каждого лекционного занятия. Принимает значение от 0 до 10 путем сложения набранных баллов за каждый тест теста. Балл за каждый тест = 10/6 ставится в случае, если получены верные ответы на все вопросы. В противном случае за результат теста присваивается значение 0.1 или 0 если студент не пытался его написать.

$Score_{2}$ – выполнение заданий на практиках. Принимает значение от 0 до 10 путем сложения баллов за каждое задание. Балл за каждое задание = 10/8 и ставится в случае, если задание выполнено верно, были заданы вопросы и даны верные ответы преподавателю. В противном случае за выполнение задания присваивается нулевое значение. При сдаче задания после простановки оценки за первый модуль за каждое задание присваивается 0,6 балла (получившееся в результате корректировки оценка за 1-й модуль идет в расчет итоговой оценки за второй модуль).

$Score_{3}$ – тест по первому модулю. Принимает значение от 0 до 10. Тест проводится в форме тестирования и состоит из 20 вопросов: 10 вопросов по теории и 10 вычислительных. Число баллов зависит от числа правильных ответов. За каждый вопрос при полностью правильном ответе можно получить 0.5 балла.

$Score_{4}$ – Оценка за первый модуль (0-8) * 1,25 (масштабируем оценку от 0 до 10).

 
$Score_{add}$ – дополнительные баллы. Можно набрать от 0, 4, 7, 10 баллов. 10 баллов можно получить за участие в конкурсе/олимпиаде по машинному обучению, 7 – если подготовлена статья или тезисы отправлены и приняты в печать, до 4-х баллов – за выполнение дополнительных заданий к практикам.
