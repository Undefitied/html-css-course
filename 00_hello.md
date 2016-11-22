#Знакомство с HTML и CSS

HTML - язык разметки. CSS - язык стилей. Один без другого не имеет большого смысла, а другой без первого существовать не может.
Если проводить аналогию с HTML и CSS на реальный мир, то первое, что приходит в голову - строительство дома.
В этом случаи HTMl - кирпичи, из которых строиться основная конструкция, а CSS - все элементы декора - краска, отделка и прочее.

Оба языка не являются языками программирование и, соотвтетственно, имеют простой синтаксис и легкую архитектуру. 
HTML состоит из двух элементов:
1) Тег
2) Атрибут

## Теги
Теги бывают двух видов - обычные и самозакрывающиеся.
Обычные теги открываются и закрываются и внутри имеют содержимое.
Пример:
`html
<div>
  Это текст, который находиться внутри блока
  <div>А это текст, который находится внутри блока и этот блока тоже находится внутри блока.</div>
</div>
`
> В данном примере название тега - div, он открывается `<div>...Содержимое...</div>` и закрывается.
> Обратите внимание, что в html не имеет значение количество "пустых символов" - то есть количество пробелов и переносов строк.
> Если вы поставить 10 переносов или 1050 пробелов или любое количество, то отобразиться всего 1 пробел