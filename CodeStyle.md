# Code style

## Общие правила
- Каждый файл должен
иметь описание только одной сучности.
- Проект не должен иметь
глобальных переменных.
- Файл не должен быть больше
600 строк кода
- Строка не должна быть
больше 120 символов

## Структура файла

- Mark: - Static properties.
- Mark: - ParentName properties.
- Mark: - TypeName properties
- Mark: - Public properties
- Mark: - .... properties
- Mark: - Private properties
- Mark: - Init
- Mark: - Public methods
- Mark: - Internal methods

(рекомендация следующие типы методов выделять в расширения)

- Mark: - Private methods
- Mark: - ParentName methods
- Mark: - TypeName methods

## Название переменных и функций

- Фукции или наблюдатель,
которые сообщают что-то другой сучности должны бать
с перепиской oN, например: 
```
 func onViewTap
```
- Функции которые является обработчиками действий пользователя должны иметь
в основание название UI-элемента и окончание Action. Например: 
```
func signInButtonAction
```

- Названия сокращать нельзя
Te. Button, image view и т.д писать полностью
- Название переменной должно содержать тип и передавать сущность типа. Например: 
```
const sigInButton: Button
const imageSelectorView: SelectorView
```


## Типовые функции и переменные

- Создание UI верстки нужно инициализировать в функции setup
- Подписки на наблюдатели должна происходить в функции bind
- Переменные для паттерна делегирования должен иметь в название deleagate
