
## About ##
Маленька книжка Go ([The Little Go Book](http://openmymind.net/The-Little-Go-Book/))   безкоштовна вступна книга Go.

Автор книжки [Karl Seguin](http://openmymind.net), автор таких книжок:

* [Scaling Viki](http://openmymind.net/scaling-viki/)
* [The Little Redis Book](http://openmymind.net/2012/1/23/The-Little-Redis-Book/)
* [The Little MongoDB Book](http://openmymind.net/2011/3/28/The-Little-MongoDB-Book/)
* [Foundations of Programming](http://openmymind.net/FoundationsOfProgramming.pdf)

Переклад в процесі.

## Ліцензія ##
Ця книжка вільно розповсюджується по ліцензії  [Attribution-NonCommercial-ShareAlike 4.0 International](<http://creativecommons.org/licenses/by-nc-sa/4.0/>).

## Інші переклади ##

* [Spanish](https://github.com/raulexposito/the-little-go-book/tree/master/es) by Raúl Expósito
* [Chinese](https://github.com/songleo/the-little-go-book_ZH_CN) by [songleo](https://github.com/songleo)
* [Vietnamese](https://github.com/quangnh89/the-little-go-book/blob/master/vi/readme.md) by [Quang Nguyễn](https://github.com/quangnh89)

## Формати ##
Ця книжка написана в форматі [Markdown](http://daringfireball.net/projects/markdown/) і може бути конвертована в PDF користуючись [Pandoc](http://johnmacfarlane.net/pandoc/).

Темплейт TeX використовує [Lena Herrmann's JavaScript highlighter](http://lenaherrmann.net/2010/05/20/javascript-syntax-highlighting-in-the-latex-listings-package).

Kindle і ePub формати можна зібрати з допомогою [Pandoc](http://johnmacfarlane.net/pandoc/).

## Generating books ##
Packages listed below are for Ubuntu. If you use another OS or distribution names would be similar.
Під час роботи з Windows Pandoc рекомендує встановлення MiKTeX. Після встановлення MiKTeX потребується синхронізація репозиторіїв щоб працювало встановлення пакетів.

### PDF

#### Dependencies

Packages:

* `pandoc`
* `texlive-xetex`
* `texlive-latex-extra`
* `texlive-latex-recommended`

You should have [some fonts](https://github.com/karlseguin/the-little-redis-book/blob/master/common/pdf-template.tex#L11) installed too.
Or you could change them to other ones if you want. Consider that fonts could cause [building troubles](https://github.com/karlseguin/the-little-redis-book/issues/26).

#### Сбірка PDF

Run `make ua/go.pdf`.

### ePub

#### Dependencies

Packages:

* `pandoc`

#### Building

Run `make ua/go.epub`.

### Mobi

#### Dependencies

Packages:

* `pandoc`

You should have [KindleGen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211) installed too.

#### Building

Run `make en/go.mobi`.

## Title Image ##
A PSD of the title image is included. The font used is [Comfortaa](http://www.dafont.com/comfortaa.font).
