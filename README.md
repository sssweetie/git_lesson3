# git_lesson3

**git clone** - клонирование репозитория
ОСНОВНЫЕ ТЕРМИНЫ

Репозиторий — каталог файловой системы, в котором находятся: файлы конфигурации, файлы журналов операций, выполняемых над репозиторием, индекс расположения файлов и хранилище, содержащее сами контролируемые файлы.

Локальный репозиторий — репозиторий, расположенный на локальном компьютере разработчика в каталоге. Именно в нём происходит разработка и фиксация изменений, которые отправляются на удаленный репозиторий.

Удаленный репозиторий — репозиторий, находящийся на удаленном сервере. Это общий репозиторий, в который приходят все изменения, и из которого забираются все обновления.

Коммит (Commit) — зафиксированное состояние репозитория. У коммита есть метаданные: идентификатор, имя автора, дата создания, комментарий.

Ветка (Branch) — это отдельная история изменений (коммитов) в рамках одного репозитория. Git поощряет создание отдельных веток для каждой решаемой задачи, благодаря чему и достигается эффективная параллельная работа — каждый разработчик может работать со своей историей и не бояться, что изменения в чужом коде повлияют на его работу

Слияние (Merge) — слияние изменений из какой-либо ветки репозитория с любой веткой этого же репозитория.

Клонирование (Clone) — скачивание репозитория с удаленного сервера на локальный компьютер в определённый каталог для дальнейшей работы с этим каталогом как с репозиторием.

Пул (Pull) — получение последних изменений с удалённого сервера репозитория.

Пуш (Push) — отправка всех неотправленных коммитов на удалённый сервер репозитория.

ПРИВЕТСТВУЮ ОБУЧАЮЩИХСЯ И ПРЕПОДАВАТЕЛЕЙ GeekBrains!!!


Ученье -свет, неученье потёмки !!! Век живи, век учись и дураком помрёшь!!!



GitHub-Flavored Markdown
Краткое руководство

Абзацы создаются при помощи пустой строки. Если вокруг текста сверху и снизу есть пустые строки, то текст превращается в абзац.

Чтобы сделать перенос строки вместо абзаца,
нужно поставить два пробела в конце предыдущей строки.

Заголовки отмечаются диезом # в начале строки, от одного до шести. Например:

Это образец заголовка первого уровня
Это образец заголовка второго уровня
Это образец заголовка третьего уровня
это образец заголовка четвертого уровня
и так далее...
В декоративных целях заголовки можно «закрывать» с обратной стороны.

Списки
Для разметки неупорядоченных списков можно использовать или *, или -, или +:

это первый элемент неупорядоченного списка
это второй элемент неупорядоченного списка
это третий элемент неупорядоченного списка ...
Вложенные пункты создаются четырьмя пробелами перед маркером пункта:

элемент 1
элемент 2
вложенный элемент 2.1
вложенный элемент 2.2
элемент ...
Упорядоченный список:

элемент 1
элемент 2
элемент 3
вложенный
вложенный
вложенный
элемент 3
это первый элемент упорядоченного списка
это второй элемент упорядоченного списка
это вложенный элемент
это тоже вложенный элемент
это третий элемент упорядоченного списка
Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.
На самом деле не важно как в коде пронумерованы пункты, главное, чтобы перед элементом списка стояла цифра (любая) с точкой. Можно сделать и так:

элемент 1
элемент 2
элемент 3
элемент 4
Список с абзацами:

Это образец первого абзаца. Lorem ipsum dolor sit amet, consectetur adipisicing elit.

Это образец второго абзаца. Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.

Это образец третьего абзаца. Ea, quis, alias nobis porro quos laborum minus sed fuga odio dolore natus quas cum enim necessitatibus magni provident non saepe sequi?

Это образец четвёртого абзаца. (Четыре пробела в начале или один tab).

Пять абзац

Цитаты
Цитаты оформляются как в емейлах, с помощью символа >.

This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак > ставится перед каждым элементом цитаты, будь то абзац, заголовок или пустая строка:

This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе вложенные цитаты:

This is a header.
This is the first list item.
This is the second list item.
Вложенная цитата.

Here's some example code:

return shell_exec("echo $input | $markdown_script");
Исходный код
В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве Ё) до и после кода. Также можно указать язык исходного кода.

<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count" class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0 комментариев</span>
        <span class="comment-count-placeholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">
        <span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
        </span>
        <span class="caret"></span>
      </a>
    </li>
  </ul>
</nav>
Самое приятное, что в коде не нужно заменять угловые скобки < > и амперсанд & на их html-сущности.

Инлайн код
Для вставки кода внутри предложений нужно заключать этот код в апострофы (на букве Ё). Пример: <html class="ie no-js">.

Если внутри кода есть апостроф, то код надо обрамить двойными апострофами: There is a literal backtick (`) here.

Горизонтальная черта
hr создается тремя звездочками или тремя дефисами.

Ссылки
Это встроенная ссылка с title элементом. Это — без title.

А вот пример нескольких ссылок с разметкой как у сносок. Прокатит и короткая запись без указания id.

Вынос длинных урлов из предложения способствует сохранению читабельности исходника. Сноски можно располагать в любом месте документа.

Emphasis
Выделять слова можно при помощи * и _. Одним символ для наклонного текста, два символа для жирного текста, три — для наклонного и жирного одновременно.

Например, это italic и это тоже italic. А вот так уже strong, и так тоже strong. А так жирный и наклонный одновременно.

Зачеркивание
В GFM добавлено зачеркивание текста: две тильды ~ до и после текста.

Зачеркнуто

Картинки
Картинка без alt текста



Картинка с альтом и тайтлом:

Запомнить просто: синтаксис как у ссылок, только перед открывающей квадратной скобкой ставится восклицательный знак.

Картинки «сноски»:

![Картинка][image1] ![Картинка][image2] ![Картинка][image3]

Картинки-ссылки:

Использование HTML внутри Markdown
Mожно смешивать Markdown и HTML. Если на какие-то элементы нужно поставить классы или атрибуты, смело используем HTML:

Выделять слова можно при помощи * и _ . Например, это italic и это тоже italic. А вот так уже strong, и так тоже strong.

Можно и наоборот, внутри HTML-тегов использовать Маркдаун.

Пример Маркдауна внутри HTML
Выделять слова можно при помощи * и _ . Например, это italic и это тоже italic. А вот так уже strong, и так тоже strong.

Таблицы
В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.

First Header	Second Header
Content Cell	Content Cell
Content Cell	Content Cell
Для красоты можно и по бокам линии нарисовать:

First Header	Second Header
Content Cell	Content Cell
Content Cell	Content Cell
Можно управлять выравниванием столбцов при помощи двоеточия.

Left-Aligned	Center Aligned	Right Aligned
col 3 is	some wordy text	$1600
col 2 is	centered	$12
zebra stripes	are neat	$1
Внутри таблиц можно использовать ссылки, наклонный, жирный или зачеркнутый текст.

Для всего остального есть обычный HTML )))

Особая благодарность преподавателю, опять читающего этот бред )))
