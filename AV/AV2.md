## Знак. Символ. Алфавит. Кодирование.

**Знак** - соглашение (явное или неявное) о приписывании чему-либо какого-либо определённого смысла.

**Символ** - это знак, изображение какого-нибудь предмета или животного для обозначения качества объекта; условный знак каких-либо понятий, идей, явлений.

**Алфавит** - множество неделимых символов какого-либо формального языка (иногда называемых буквами по аналогии с алфавитами естественных языков). Из символов алфавита формального языка строятся слова, а заданием формальной грамматики — допустимые выражения языка.

Чаще всего алфавит рассматривается как непустое конечное множество. Например, алфавит `{.,-}` лежит в основе азбуки Морзе, алфавит `{0,1}` - общепринятый набор символов для представления информации в компьютерах.

### Кодирование

**Код символа** - представление символа в виде целого числа.

#### Стандарты кодирования символов

##### ASCII

**ASCII** (American Standard Code for Information Interchange — американский стандартный код для обмена информацией). Каждый ASCII символ содержит 7 бит, таким образом, всего можно закодировать **128 символов**. Коды от 0 до 1F соответствуют управляющим символам, которые не печатаются. Коды от 128 до 255 не входят в кодировку ASCIIl, на IBM PC за ними были закреплены специальные символы, которые до сих пор поддерживаются большинством компьютеров. Печатные ASCII-символы включают буквы верхнего и нижнего регистров, цифры, знаки пунктуации и некоторые математические символы.

##### Unicode

**Основная идея Unicode** — приписать каждому символу единственное постоянное **16-разрядное значение**, которое называется кодовым пунктом. Так как Unicode-символы состоят из 16 бит, всего получается **65 536 кодовых пунктов**. 

##### UTF-8

Стандарт Unicode был лучше ASCII, но со временем в нем тоже возникла нехватка кодовых пунктов. Кроме того, он требовал 16 бит для представления «чистого» ASCII-текста, что было расточительно. Для решения этих проблем была разработана новая схема кодирования UTF-8 UCS Transformation Format. Коды UTF-8 имеют переменную длину от 1 до 4 байт, и позволяют кодировать **до двух миллиардов символов**. Этот способ кодировки сейчас доминирует в World Wide Web. Одно из преимуществ UTF-8 заключается в том, что коды от 0 до 127 используются для представления ASCII-символов. Таким образом, одному символу соответствует один байт (вместо двух байтов в Unicode). Для символов, не входящих в набор ASCII, старший бит первого байта устанавливается в 1; это означает, что за ним следуют один и более дополнительных байтов. Всего используются шесть разных форматов.