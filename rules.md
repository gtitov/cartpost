---
layout: post
title: Правила публикаций
---
## Общие положения
Статья должна быть написана на языке Markdown. Это очень простой и полезный язык разметки, с синтаксисом и возможностями которого можно познакомиться [тут](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Использование языка для нашего сайта имеет некоторые особенности.
Статья должна быть названа одним словом на латинице с маленькой буквы. Название будет использовано в адресе статьи.
Статья должна иметь 3 основных части:
- **front-matter** включает сведения о шаблоне, авторе и названии публикации, отделяется тремя дефисами сверху и снизу;
```yaml
    ---
    layout: post  # шаблон у всех статей "post"
    author: Мария  # используйте своё имя в поле автор
    title: "Интервью с работодателем: Андрей Александрович Медведев"  # заключайте название в кавычки
    ---
```
- **краткое описание** приводится сразу после **front-matter**, заключается в звёздочки для наклонного отображения;
- **основное содержание** пишется на Markdown.

Статья должна выглядеть таким образом:
```markdown
    ---
    layout: post
    author: Мария
    title: "Интервью с работодателем: Андрей Александрович Медведев"
    ---
    *Андрей Александрович Медведев — заведуюший лабораторией картографии ИГ РАН*
    
    Основное содержание статьи.
```

## Важные замечания
Не используйте в статье [первый уровень заголовка](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#headers) (с одной решёткой) — он используется для отображения названия статьи.

## Работа с изображениями
Не используйте изображения с очень высоким разрешением: 1000px вполне достаточно. Синтаксис добавления изображений можно посмотреть [здесь](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images). Присылаются в архиве zip, содержащем статью и картинки в папке assets/images/posts/название-статьи.

## Работа с источниками
Cсылки на источники, используйте [сноски (footnote)](https://support.typora.io/Markdown-Reference/#footnotes), завершите статью [горизонтальной чертой](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#horizontal-rule) (тройной дефис, отделённый пустыми строчками)