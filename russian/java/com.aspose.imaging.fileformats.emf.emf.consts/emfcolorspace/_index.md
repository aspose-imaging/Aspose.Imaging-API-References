---
title: "EmfColorSpace"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление ColorSpace используется для указания, когда включать и отключать проверку цвета и когда удалять преобразования."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

Перечисление ColorSpace используется для указания, когда включать и выключать проверку цвета, а также когда удалять преобразования.
## Поля

| Поле | Описание |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | Отображает цвета в цветовой диапазон целевого устройства. |
| [CS_DISABLE](#CS-DISABLE) | Отключает проверку цвета. |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | Если управление цветом включено для целевого профиля, отключает его и удаляет объединённое преобразование. |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


Отображает цвета в цветовой диапазон целевого устройства. Это включает проверку цвета. Все последующие команды рисования в контексте устройства воспроизведения будут отображать цвета так, как они выглядели бы на целевом устройстве.

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


Отключает проверку цвета.

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


Если управление цветом включено для целевого профиля, отключает его и удаляет объединённое преобразование.

