# Code Rules for MVP

Общие правила можно 
посмотреть в файле [Code Rules](https://github.com/oneGo-inc/BaseDocumentation/blob/main/CodeStyle.md)
 
## Краткое описание MVP

### View
- Класс отвечающий за верстку, отображение и обработку UI. 
- Не должна содержать бизнес логику.
- Знает о presenter через абстракцию

### Presenter
- Класс отвечающий за бизнес логику
- Работает с сервисами, моделью, подготавливает данные для
view
- Знает о view через абстракцию.

### Configure 
- Собирает MVP модуль
- Через функцию build можно передавать данные в presenter
