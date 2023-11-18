# Метод ввода GNU EMACS для технических писателей

## Установка

1. Установите пакет:

    ```emacs-lisp
    (use-package 'russian-techwriter-input-method)
    ```

1. Сделайте `russian-techwriter` методом ввода по умолчанию:

    ```emacs-lisp
    (setq-default default-input-method 'russian-techwriter)
    ```

1. Для использования метода включите его нажатием клавиш `[C-\]`.

## Использование

В отличие от метода ввода `russian-computer`, входящего в стандартную поставку EMACS, этот пакет предоставляет поддержку лигатур. Список поддерживаемых лигатур представлен ниже. Для вставки лигатуры необходимо нажать клавишу `[/]` (справа от `[ю]`), после чего ввести нужную последовательность символов.

## Лигатуры

### Тире

| Последовательность | Символ замены | Описание    |
|:------------------:|:-------------:|-------------|
| `[/-]`             | –             | EN DASH     |
| `[/--]`            | ‒             | FIGURE DASH |
| `[/---]`           | —             | EM DASH     |

### Кавычки

| Последовательность | Символ замены | Описание                                   |
|:------------------:|:-------------:|--------------------------------------------|
| `[/,,]`            | „             | DOUBLE LOW-9 QUOTATION MARK                |
| `[/,]`             | ‚             | SINGLE LOW-9 QUOTATION MARK                |
| `[/``]`            | ‘             | LEFT SINGLE QUOTATION MARK                 |
| `[/']`             | ’             | RIGHT SINGLE QUOTATION MARK                |
| `[/``]`            | “             | LEFT DOUBLE QUOTATION MARK                 |
| `[/'']`            | ”             | RIGHT DOUBLE QUOTATION MARK                |
| `[/<<]`            | «             | LEFT-POINTING DOUBLE ANGLE QUOTATION MARK  |
| `[/>>]`            | »             | RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK |

### Точки и пули

| Последовательность | Символ замены | Описание                            |
|:------------------:|:-------------:|-------------------------------------|
| `[/*]`             | •             | Пуля                                |
| `[/.]`             | ․             | Точка                               |
| `[/..]`            | ‥             | Двоточие                            |
| `[/...]`           | …             | Многоточие                          |

### Номера и параграфы

| Последовательность | Символ замены | Описание                            |
|:------------------:|:-------------:|-------------------------------------|
| `[/&]`             | §             | Параграф                            |
| `[/#]`             | №             | Номер                               |
| `[/no]`            | №             | - // -                              |

### Валюты и товарные символы

| Последовательность | Символ замены | Описание         |
|:------------------:|:-------------:|------------------|
| `[/c]`             | ©             | Copyright        |
| `[/tm]`            | ™             | Trademark        |
| `[/reg]`           | ®             | Reserved         |
| `[/eu]`            | €             | Euro             |
| `[/ru]`            | ₽             | Российский рубль |
| `[/ce]`            | ¢             | Cent             |
| `[/te]`            | ₸             | Казахский теньге |

### Дроби

| Последовательность | Символ замены |
|:------------------:|:-------------:|
| `[/78]`            | ⅞             |
| `[/58]`            | ⅝             |
| `[/38]`            | ⅜             |
| `[/18]`            | ⅛             |
| `[/56]`            | ⅚             |
| `[/16]`            | ⅙             |
| `[/45]`            | ⅘             |
| `[/35]`            | ⅗             |
| `[/25]`            | ⅖             |
| `[/15]`            | ⅕             |
| `[/23]`            | ⅔             |
| `[/13]`            | ⅓             |
| `[/34]`            | ¾             |
| `[/12]`            | ½             |
| `[/14]`            | ¼             |

### Римские цифры

| Последовательность | Символ замены |
|:------------------:|:-------------:|
| `[/RI]`            | Ⅰ             |
| `[/RII]`           | Ⅱ             |
| `[/RIII]`          | Ⅲ             |
| `[/RIV]`           | Ⅳ             |
| `[/RV]`            | Ⅴ             |
| `[/RVI]`           | Ⅵ             |
| `[/RVII]`          | Ⅶ             |
| `[/RVIII]`         | Ⅷ             |
| `[/RIX]`           | Ⅸ             |
| `[/RX]`            | Ⅹ             |
| `[/RXI]`           | Ⅺ             |
| `[/RXII]`          | Ⅻ             |
| `[/ri]`            | ⅰ             |
| `[/rii]`           | ⅱ             |
| `[/riii]`          | ⅲ             |
| `[/riv]`           | ⅳ             |
| `[/rv]`            | ⅴ             |
| `[/rvi]`           | ⅵ             |
| `[/rvii]`          | ⅶ             |
| `[/rviii]`         | ⅷ             |
| `[/rix]`           | ⅸ             |
| `[/rx]`            | ⅹ             |
| `[/rxi]`           | ⅺ             |
| `[/rxii]`          | ⅻ             |