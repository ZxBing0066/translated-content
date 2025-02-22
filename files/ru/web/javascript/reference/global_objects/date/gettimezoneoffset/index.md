---
title: Date.prototype.getTimezoneOffset()
slug: Web/JavaScript/Reference/Global_Objects/Date/getTimezoneOffset
tags:
  - Date
  - JavaScript
  - Method
  - Prototype
  - Reference
translation_of: Web/JavaScript/Reference/Global_Objects/Date/getTimezoneOffset
---
{{JSRef("Global_Objects", "Date")}}

## Сводка

Метод **`getTimezoneOffset()`** возвращает смещение часового пояса относительно часового пояса UTC в минутах для текущей локали.

## Синтаксис

```
dateObj.getTimezoneOffset()
```

### Параметры

Нет.

### Возвращаемое значение

Возвращает смещение часового пояса, являющееся разностью в минутах между временем UTC и местным временем. Обратите внимание, что это значит, что смещение будет положительным для местного часового пояса, находящегося западнее часового пояса UTC и отрицательным — восточнее. Например, если ваш часовой пояс равен UTC+10 (австралийское восточное поясное время), будет возвращено значение -600. Наличие летнего и зимнего времени не даёт этому смещению быть постоянным, даже в пределах одного часового пояса.

## Примеры

### Пример: использование метода `getTimezoneOffset()`

```js
var x = new Date();
var currentTimeZoneOffsetInHours = x.getTimezoneOffset() / 60;
```

## Спецификации

{{Specifications}}

## Совместимость с браузерами

{{Compat}}
