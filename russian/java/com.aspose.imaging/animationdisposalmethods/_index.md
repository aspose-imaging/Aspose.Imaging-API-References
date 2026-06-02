---
title: "AnimationDisposalMethods"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Указывает, как графика должна обрабатываться после отображения."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging/animationdisposalmethods/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AnimationDisposalMethods extends System.Enum
```

Указывает, как графика должна обрабатываться после отображения.
## Поля

| Поле | Описание |
| --- | --- |
| [PRESERVE](#PRESERVE) | Не удалять. |
| [BACKGROUND](#BACKGROUND) | Восстановить фон. |
| [PREVIOUS](#PREVIOUS) | Восстановить предыдущее. |
### PRESERVE {#PRESERVE}
```
public static final int PRESERVE
```


Не удалять. Графика должна оставаться на месте.

### BACKGROUND {#BACKGROUND}
```
public static final int BACKGROUND
```


Восстановить фон. Область, использованная графикой, должна быть восстановлена к фоновому цвету.

### PREVIOUS {#PREVIOUS}
```
public static final int PREVIOUS
```


Восстановить предыдущее. Декодер должен восстановить область, перезаписанную графикой, тем, что было до её отрисовки.

