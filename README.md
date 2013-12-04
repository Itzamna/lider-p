lider-prestig.ru
=======

Сайт Клуба ЦЛЖ "Лидер-Престиж"

<b>_includes</b> - папка с исполняющими заготовками

<b>_layouts</b> - папка с шаблонами

<b>breeds</b> - папка со страницами пород

<b>public</b> - папка с русскими страницами сайта

  <b>public/css</b> - папка со стилями сайта
  
  <b>public/css</b> - папка со шрифтами
  
  <b>public/images/photo</b> - папка с картинками (сюда нужно будет загружать картинки для сайта)

  <b>public/jquery</b> - папка с jquery-скриптами

  <b>public/js</b> - папка с js-скриптами

<b>shows</b> - папка со страницами выставок

about.html, archive.html, breeds.html и т.д. - страницы сайта

index.html - главная страница сайта


Includes
-------

Чтобы вставить фотографию, необходимо загрузить картинку в папку public/images/photo и внутри страницы, где хотите разместить фото поместить такой код:

{% include photo.html photo="imya-faila.jpg" height="300" %}
