---
title: "OnBeforeUserFormSave"
translation: "extending-modx/plugins/system-events/onbeforeuserformsave"
---

## Событие: OnBeforeUserFormSave

Запускается после отправки формы, но до сохранения пользователя в менеджере.

Служба: 1 - Parser Service Events
Group: Users

## Параметры события

| Имя  | Описание                                                     |
| ---- | ------------------------------------------------------------ |
| mode | Либо 'upd' или 'new', в зависимости от обстоятельств.        |
| user | Ссылка на объект modUser.                                    |
| id   | Идентификатор пользователя. Будет 0 для новых пользователей. |

## Смотри также

- [System Events](extending-modx/plugins/system-events "System Events")
- [Plugins](extending-modx/plugins "Plugins")
