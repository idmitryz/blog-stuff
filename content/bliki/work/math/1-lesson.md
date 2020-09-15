---
title: 1-lesson
date: 2020-09-15
---

# Лекция 1. Множества. Аксиомы. Числовые множества. Функции. Уравнения. Как учить математику?

## 1.1. Множества и основания математики

*(Слайд 1. С чего начинается математика?)*

**[Метаматематика]**

С чего начинается математика? На этот вопрос ответить непросто, так как он немного философский, метаматематический. Существуют так называемые основания математики. Они о том, на чем строится вся математика. Сегодня никто точно не сможет сказать какая теория претендует на основания в полной мере. В основном в современной математике пользуются языком теории множеств, строящейся на основе математической логики, о которой я расскажу в дальнейшем, а также теории категорий, о которой я расскажу совсем чуть-чуть.

*(Слайд 2. Лего и другие конструкторы.)*

**[Основания математики]**

Представьте конструктор, например Лего, как набор деталей, из которых вы можете сконструировать что захотите, у вас нет ограничений, только правила, по которым вы будете что-то строить. Так вот основания математики имеют различные варианты конструкторов (разные Лего) -- теорий, но каждый радикально отличается от другого, и, кроме этого, имеет свои собственные правила и способы построения. Теорию множеств можно назвать самым популярным конструктором.

*(Слайд 3. Детальки какого-то механизма)*

Для начала просто рассмотрим внешний вид нашего конструктора, под названием теория множеств. Наш конструктор состоит из деталей -- множеств. Что такое множество? Многие считают, что полного определения для этого понятия не существует, оно является неопределяемым, однако его можно понять и прочувствовать.

*(Слайд 4. Картинка, отображающая понятие абстрактного)*

**[Абстракция, Абстрагирование]**

Для начала попробуем научиться мыслить абстрактно, то есть убирать в мыслях все лишнее, оставляя только то, что мы рассматриваем, и что нам интересно.

*(Слайд 5. Пустой черный слайд)*

Человеческий разум способен на многое. Мы можем у себя в голове представлять что угодно, придумывать, размышлять. Обращаюсь к вашим способностям. Представьте пустое пространство, что-то вроде черного пустого помещения, ничего неимеющего, как пространство в каком-нибудь 3d редакторе. Это всего лишь абстракция, не математика, просто удобный способ попытаться понять что такое множество.

*(Слайд 6. Белая коробка в черном пространстве)*

**[Пустое множество, Обозначение пустого множества]**

Теперь предсавьте как из неоткуда появляется пустая белая коробка.
Пустая коробка -- это пустое множество, в нем ничего нет, но все же это что-то, какой-то объект.

*(Слайд 7. Кладём бильярдный шар)*

Теперь положим туда что-нибудь. Например бильярдный шар. Теперь это множество с одним элементом, в нашем случае с бильярдным шаром. 

*(Слайд 8. Вытаскиваем шар)*

Вытащим этот шар. Теперь наша коробка-множество пустая. 

*(Слайд 9. Кладём планеты)*

Давайте положим туда все планеты солнечной системы. Можете мысленно представить как Земля, Марс, Юпитер и так далее вместе входят в коробку. Теперь наше множество состоит из планет Солнечной системы. Хорошо, мы умудрились засунуть планеты в коробку в своей голове, надеюсь вы это хорошо представили. 

*(Слайд 10. Пустая коробка)*

Избавимся от планет. Можно засунуть в нашу коробку что угодно, любые объекты, и при этом они не обязательно должны иметь какие-то общие свойства.

*(Слайд 11. Вилка и солнце)*
Например, множество, состоящее из двух элементов: вилка и Солнце. Элементы множества могут быть какими захотите. 

*(Слайд 12. Пустая коробка)*
**[Множество, Элементы множества]**
Но я привел в пример только физические/реальные объекты. Однако в нашу абстрактную коробочку можно складывать математические объекты: числа, операции, функции, пространства, другие множества!

*(Слайд 13. Обозначения)*
**[Обозначения множеств, Обозначения элементов]**
Для удобства множество обозначают каким-нибудь символом. Обычно это латинские заглавные буквы: A, B, C... Однако мы могли бы назвать наше множество как захочется, например, "белая коробка", или символом #, или цветом, но все же удобнее работать с привычными нам буквами, ведь все время записывать "белая коробка" это долго, да и в белую трехмерную коробку вы на вряд ли поместите четырехмерную фигуру (на самом деле в математике даже так можно, но это уже отдельный разговор и не относится к нашей метафоре). В общем множества обычно обозначают буквами. Объекты, которые входят в множество можно также обозначать какими-нибудь символамами, главное чтобы мы знали о нашем соглашении по названиям рассматриваемых объектов. 
Например, это могут быть буквы, или числа, или цвета, как нам будет удобно, так и обозначим. Это как наклейка на объект, наклейка на белую коробку (множество А, множество B, ...) и на элементы внутри нее (буква а, число 1, операция +).

*(Слайд 14. Нотация)*
Итак, множества могут обозначаться, например, следующим образом:
А = {а, 1, +}
B = {a, a, a} = {a}
Во множестве повторяющейся элемент можно записывать один раз, нам важен один экземпляр какого-либо объекта, повторение не даёт ничего. Однако можно пользоваться такой структурой, как мультмножество. В такой структуре уже будет {а, а, а} ≠ {а}.


*(Слайд 15. Символ бесконечности)*
**[Конечные множества. Бесконечность]**
Давайте вернёмся к нашей белой коробке. Пусть она будет снова пустой. Теперь засунем туда бесконечное количество элементов. Но что может быть бесконечным в нашем мире, если даже предполагается конечное количество атомов во Вселенной? Да, их сверх много, но количество конечно ограничено. Вселенная бесконечна? Ну это уже совсем философия. Но мы точно знаем что числа бесконечны, количество возможных текстов выбранного языка бесконечно, можно представить бесконечное количество планет, или шаров, а может время бесконечно? Возможно можно придумать ещё примеры. Хотя тут чувствуется некоторый подвох. Как это, атомов конечное количество, а чисел бесконечно. Так вот полностью никто не знает что такое бесконечность, однако с ней успешно работают, также, как и с множествами, при этом можно даже узнать, что одна бесконечность больше другой. Как это можно быть? 

*(Слайд 16. Бесконечное количество шаров в коробку)*
**[Счётные множества]**
Допустим, мы засовываем бесконечное количество шаров в нашу белую коробку, она вполне вместительна для этого, бесконечно вместительна. Это количество можно посчитать, вытаскивая их по очереди: 1, 2, 3 ... Множество, элементы которого можно как бы бесконечно посчитать, называют счетными. Важно запомнить этот термин, так как он используется везде в математике. 

*(Слайд 17. Несчетность по помощи шаров)*
**[Несчётное множество. Мощность/Кардинальность]**
Пусть наша коробка снова пустая. Засунем туда два шара, но между ними будет бесконечное количество шаров, то есть между начальным и замыкающим шаром имеется бесконечное количество шаров, будто эту бесконечность зажали между двумя шарами. Значит есть начальный шар и следующий за ним, второй по порядку, второй - это не тот замыкающий. Пусть между начальным и вторым шаром имеется также бесконечное количество шаров, и второй по порядку становится замыкающим тоже, но относительно уже другой бесконечности, заключённой между начальным и вторым шаром первой бесконечности. Вух, прочитайте эти строки ещё раз, повнимательнее. Продолжим этот процесс угадайте до какой степени? До бесконечности. То есть между любыми двумя шарами есть бесконечность бесконечностей (надеюсь за такие слова меня не побьют философы). Вот такую систему вы уже не посчитаете, появляется сплошная бесконечная среда. Количество элементов этой штуки несчетно, но само слово "количество" уже вызывает противоречия, поэтому есть специальный обобщающий термин "мощность", который также называют "кардинальным числом" и обозначают как card или | |. Например, мощность множества К колоды игральных карт равна 52 и этот факт записывается как card K = 52, или |K| = 52.

## 1.2. Функции/Отображения

## 1.3. Числовые множества

## 1.4. Аксиомы и структуры. Немного теории категорий.

## 1.5. Уравнения

## 1.6. Как учить и понимать математику?

## 1.7. Упражнения
- 1.1.

## 1.8. Проверка знаний
- термины
- похожие задачки из упражнений