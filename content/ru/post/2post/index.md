---
 title: Облегченные языки разметки
 date: 2025-04-04
---

Облегченный язык разметки - это язык разметки, разработанный таким образом, чтобы иметь минимальный синтаксис и быть более удобным для чтения человеком, чем традиционные языки разметки. Некоторые из них, такие как asciidoc и язык этой самой вики, обладают сравнительно большим количеством функций, в то время как другие, например, почтовый клиент Thunderbird, который интерпретирует сообщения электронной почты в соответствии с соглашением, более примитивны.

В чем польза облегченного языка разметки

    В качестве формата программного документа многие другие сообщества разработчиков, такие как python, уже используют облегченный язык разметки для программных документов. Обычно
разработчики используют его для создания файлов справки
        для использования в комментариях к исходному коду, которые впоследствии извлекаются для формирования справочного документа по коду.

В первом случае должен быть виджет для отображения разметки. Во втором случае документ должен быть переведен в HTML.

    Формат содержимого виджета WYSIWYG editor Редактор WYSIWYG может сохранять содержимое на упрощенном языке разметки. В этом случае упрощенный язык разметки является прозрачным для пользователей. Этот вариант рассматривается как редактор bbcode с графическим интерфейсом, который иногда используется в Интернете, но пока не был реализован в tcl.

    Непосредственно доступный конечным пользователям, этот вариант часто встречается на онлайн-форумах, таких как BBCode, и в wiki, например, в tclerswiki. Предполагается, что конечный пользователь будет изучать и составлять тексты, используя этот вики-язык.

    Какие облегченные языки разметки поддерживают инструменты tcl? До сих пор большинство инструментов облегченного языка разметки TCL либо требовали, чтобы пользователи определяли свой собственный язык разметки, как библиотека, включенная в tkoutline, либо использовали язык разметки, определенный автором инструмента, например “put-text”, используемый в tkcvs, который определяет несколько тегов, включая “
    ”, ”" и так далее. Не существует инструмента, который использовал бы хорошо узнаваемый облегченный язык разметки, такой как asciidoc или Textile .

Хорошо узнаваемый облегченный язык разметки обычно имеет множество инструментов, предназначенных для его обработки, поэтому проще создать документ на этом языке и повторно использовать его, например, как в меню “Справка”, так и на странице руководства Unix. Из-за отсутствия таких инструментов в tcl, на данный момент документы, уже написанные на хорошо распознаваемом языке разметки, не могут отображаться непосредственно в виджетах tcl.

Какие функции есть в облегченных инструментах языка разметки?

    Может отображать / распознавать жирный шрифт и курсив. Это базовая функция языка разметки, поэтому она не упоминается в таблице функций. Все инструменты поддерживают ее.
    Отображение в расширенном текстовом формате, как в httext
    Перевод в HTML, как в tclerswiki
    Редактирование в формате WYSIWYG, которого нет ни в одном инструменте языка разметки tcl
    Поддержка изображений (I), ссылок (L), таблиц (T) и заголовков (H)

Список языков

    asciidoc
    Креольский, попытка создать общую вики-разметку
    htext
    киви
    Markdown - Мультимаркетинг (MMD): надмножество Markdown
    Текстильный
    линия tkoutline






































