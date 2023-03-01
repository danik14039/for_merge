# Краткое руководство для работы в MarkDown

## Цитаты

Цитаты оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак `>` ставится перед каждым элементом цитаты, будь то абзац, заголовок или пустая строка:

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе вложенные цитаты:

> ## This is a header.
>
> 1. This is the first list item.
> 2. This is the second list item.
>
> > Вложенная цитата.
>
> Here's some example code:
>
>> return shell_exec("echo $input |$markdown_script");

## Инлайн код

## Ссылки
Это встроенная [ссылка с title элементом]
(http://example.com/link "Я ссылка"). Это — [без title]
(http://example.com/link).
А вот [пример][1] [нескольких][2] [ссылок][id] с
разметкой как у сносок. Прокатит и [короткая запись][]
без указания id.
[1]: http://example.com/ "Optional Title Here"
[2]: http://example.com/some
[id]: http://example.com/links (Optional Title Here)
[короткая запись]: http://example.com/short
Вынос длинных урлов из предложения способствует
сохранению читабельности исходника. Сноски можно
располагать в любом месте документа.

## Emphasis
