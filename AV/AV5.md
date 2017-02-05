## Элемент памяти. Бит. Байт. Слово. Нумерация бит. Объемы памяти.

**Память** — это тот компонент компьютера, в котором хранятся программы и данные.

**Элементом памяти** называется такой элемент, который сохраняет свое состояние после прекращения действия сигнала управления.

Основной единицей хранения данных в памяти является двоичный разряд, который называется **битом**. Бит может содержать 0 или 1. Эта самая маленькая единица памяти.

**Ячейка** — минимальная адресуемая единица памяти.

Память состоит из ячеек, каждая из которых может хранить некоторую порцию
информации. Каждая ячейка имеет номер, который называется **адресом**. Если адрес состоит из `m` бит, максимальное число адресуемых ячеек составит `2^m`.

В последние годы практически все производители выпускают компьютеры с **8-разрядными ячейками**, которые называются байтами.  Байты группируются в **слова**. В компьютере с **32-разрядными** словами на каждое слово приходится **4 байт**, а в компьютере с **64-разрядными** словами — **8 байт**.

Разряды нумеруются справа налево, начиная с 0.

#### Упорядочение байтов

Байты в слове могут нумероваться слева направо (как у компьютеров SPARC или мэйнфреймов IBM) или справа налево (как у компьютеров Intel).

В первой из этих систем нумерация начинается с высшего порядка, в связи с чем она относится к категории компьютеров с прямым порядком следования байтов (big endian) — в противоположность системам с обратным порядком следования байтов (little endian).