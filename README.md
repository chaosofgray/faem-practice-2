#FAEM Practice - 2

Данная программа позволяет пользователю:
- добавлять товары и информацию по ним
- удалять
- редактировать
- выводить весь список товаров
- вывести информацию по указанному товару
- работать с несколькими файлами .json, в которых хранится информация по товарам

<br/>

Добавление
-
`goods new`

После выполнения данной команды пользователю предлагается ввести информацию по товару:
- наименование товара
- производитель
- цена товара
- количество

(ID товара устанавливается автоматически)

<br/>

Удаление 
-
`goods del <ID товара>`

После выполнения данной команды удаляется информация по товару с указанным ID из установленного файла

<br/>

Редактирование
-
`goods edit <ID товара>`

После выполнения данной команды пользователь может редактировать товар с указанным ID<br/>
Требуется выбрать одно из предлагаемых полей и ввести новое значение

<br/>

Список товаров
-
`goods list`

После выполнения данной команды пользователю выводится список товаров

<br/>

Информация по указанному товару
-
`goods read <ID товара>`

После выполнения данной команды пользователю выводится информация по указанному товару

<br/>

Информация по указанному товару
-
`goods -f <filename>`

После выполнения данной команды устанавливается новый файл, с которым будет проходит
