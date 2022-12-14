# Git flow

Описание git flow

## Sprint

- Для каждого спринта должна быть ветка формата sprint/sprint-number.
- В рамках спринта все задачи должны быть сделаны в этой ветке.
- В конце спринта необходимо от текущей ветке создать
ветку нового спринта.

## Feature

- Каждая задача должно быть сделана в отдельной ветке.
- Ветка должна иметь название типа feature/number-description.
- Ветка должна быть создана от ветки-фичи в рамках которой она должна быть сделана
- Ветка в которой исправляется ошибка должна иметь вид fix/number-description.

## Commit

- Commit должен быть осмысленный, не должен состоять только из update, fix, code review и т.д
- Если задачи не очень маленькая то необходимо делать несколько commit-ов для возможности удобного cherry pick 

## Pull-request

- После завершения каждой задачи необходимо сделать ПР в ветку у которой была создана текущая.

- Пр должен иметь следующий вид:

```
 Title: TaskNumber-TaskTitle
 Body: Краткое описание как протестировать
```

- У ПР должен быть указан Reviewers и Assignees
