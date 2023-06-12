# Справка (туториал) по основам системы контроля версий Git 

## Как инициализировать и работать с Git-ом (первостепенные команды)

**Чтобы инициализировать репозиторий необходимо в терминале прописать следующую команду:**

```
git init
```

**Чтобы git начал отслеживать файл нужно прописать следующую команду:**

```
git add .
```

**Чтобы сохранить текущее состояние файла нужно прописать следующую команду:**

```
git commit -am "message"
```

**Чтобы проверить состояние текущего каталога и отслеживаемых файлов нужно прописать следующую команду:**

```
git status
```

**Чтобы просмотретьразницу между последним сохранением и текущим состоянием файла нужно прописать слудующую команду:**

```
git diff
```

**Чтобы просмотреть журнал всех сохранений нужно прописать следующую команду:**

```
git log
```

**Чтобы посмотреть журнал всех действий с файлом нужно прописать слудующую команду:**

```
git reflog
```

**Чтобы переместиться на другую ветку нужно прописать следующую команду:**

```
git checkout <branch name>
```


# Начало работы с MarkDown (md)


## Выделение текста

 Чтобы выделить текст курсивом достаточно обрамить его одинарной звёздочкой с каждой стороны *Курсив.*

Чтобы выделить текст полужирным шрифтом достаточно обрамить его двумя звёздочками с каждой стороны **Полужирный текст**

Чтобы зачеркнуть текст нужно обрамить его двумя волнистыми линиями. ~~Дарова~~

## Списки

Чтобы создасть ненумерованные списки нужно вначале строки поставить звёздочку и пробел.  

* Элемент списка 1
* Элемент списка 2
* Элемент списка 3

Чтобы создасть нумерованные списки нужно вначале строки поставить соответствующее число или цифру и точку. После отделить номер от содержания пробелом.  

1. Первый элемент нумерованного списка
2. Второй элемент нумерованного списка


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
> 1.   This is the first list item.
> 2.   This is the second list item.
>
> > Вложенная цитата.
>
> Here's some example code:
>
>     return shell_exec("echo $input | $markdown_script");