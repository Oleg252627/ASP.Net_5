# ASP.Net_5
<h1>Продолжить работу над библиотекой, добавить контроллеры по управлению пользователями и ролям</h1>
<p>Продолжить работу над библиотекой, добавить контроллеры по управлению пользователями и ролям(объединить работу с пользователями из предыдущих дз с предыдущей(с книгами))
Если не применяли, применить атрибуты к свойствам моделей
(Display, Requried, DateType - если надо, и т.д. аттрибуты применяемый к атрибутам модели в файле 5.Метаданные.docx), 
соответственно использовать хелпер Html для генерации полей ввода(Html.EditorFor) и label'ов(Html.LabelFor) формы. 
Валидацию данных проводить на сервере (ModelState.IsValid)
Для генерации таблиц использовать хелперы, желательно cs файлы(методы расширения HtmlHelper), как в примере.

+в хелпере проверять наличие атрибтуа scaffoldColumn, если есть, проверить значение свойства Scaffold в атрибуте, если false - не отображать данный столбец</p>