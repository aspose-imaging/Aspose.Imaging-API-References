---
title: "WmfLogColorSpaceW"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект LogColorSpaceW определяет логическое цветовое пространство, которое может быть задано файлом цветового профиля с именем, состоящим из 16‑битных символов Unicode."
type: docs
weight: 45
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpaceW extends MetaObject
```

Объект LogColorSpaceW задаёт логическое цветовое пространство, которое может быть определено файлом цветового профиля с именем, состоящим из 16‑битных символов Unicode.

Смотрите объект `WmfLogColorSpace` (раздел 2.2.2.11) для получения дополнительных сведений о интерпретации значений полей этого объекта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getSignature()](#getSignature--) | Получает или задает 32‑битное беззнаковое целое, которое указывает `signature` объектов цветового пространства; оно ДОЛЖНО быть установлено в значение 0x50534F43, которое является ASCII‑кодировкой строки \"PSOC\". |
| [setSignature(int value)](#setSignature-int-) | Получает или задает 32‑битное беззнаковое целое, которое указывает `signature` объектов цветового пространства; оно ДОЛЖНО быть установлено в значение 0x50534F43, которое является ASCII‑кодировкой строки \"PSOC\". |
| [getVersion()](#getVersion--) | Получает или задает 32‑битное беззнаковое целое, определяющее номер `version`; оно ДОЛЖНО быть 0x00000400. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее номер `version`; оно ДОЛЖНО быть 0x00000400. |
| [getSize()](#getSize--) | Получает или задает 32‑битное беззнаковое целое, определяющее `size` этого объекта в байтах. |
| [setSize(int value)](#setSize-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее `size` этого объекта в байтах. |
| [getColorSpaceType()](#getColorSpaceType--) | Получает или задает 32‑битное знаковое целое, которое указывает тип цветового пространства. |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | Получает или задает 32‑битное знаковое целое, которое указывает тип цветового пространства. |
| [getIntent()](#getIntent--) | Получает или задает 32‑битное знаковое целое, определяющее намерение отображения гаммы. |
| [setIntent(int value)](#setIntent-int-) | Получает или задает 32‑битное знаковое целое, определяющее намерение отображения гаммы. |
| [getEndpoints()](#getEndpoints--) | Получает или задает объект CIEXYZTriple (раздел 2.2.2.7), который определяет координаты CIE‑хроматичности x, y и z трёх цветов, соответствующих `endpoints` RGB для логического цветового пространства, связанного с растровым изображением. |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | Получает или задает объект CIEXYZTriple (раздел 2.2.2.7), который определяет координаты CIE‑хроматичности x, y и z трёх цветов, соответствующих `endpoints` RGB для логического цветового пространства, связанного с растровым изображением. |
| [getGammaRed()](#getGammaRed--) | Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для красного. |
| [setGammaRed(int value)](#setGammaRed-int-) | Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для красного. |
| [getGammaGreen()](#getGammaGreen--) | Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для зелёного. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для зелёного. |
| [getGammaBlue()](#getGammaBlue--) | Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для синего. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для синего. |
| [getFilename()](#getFilename--) | Получает или задает необязательную нуль‑терминированную строку Unicode UTF16-LE, которая указывает имя файла, содержащего цветовой профиль. |
| [setFilename(String value)](#setFilename-java.lang.String-) | Получает или задает необязательную нуль‑терминированную строку Unicode UTF16-LE, которая указывает имя файла, содержащего цветовой профиль. |
### WmfLogColorSpaceW() {#WmfLogColorSpaceW--}
```
public WmfLogColorSpaceW()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает `signature` объектов цветового пространства; оно ДОЛЖНО быть установлено в значение 0x50534F43, которое является ASCII‑кодировкой строки \"PSOC\".

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает `signature` объектов цветового пространства; оно ДОЛЖНО быть установлено в значение 0x50534F43, которое является ASCII‑кодировкой строки \"PSOC\".

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Получает или задает 32‑битное беззнаковое целое, определяющее номер `version`; оно ДОЛЖНО быть 0x00000400.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее номер `version`; оно ДОЛЖНО быть 0x00000400.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


Получает или задает 32‑битное беззнаковое целое, определяющее `size` этого объекта в байтах.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее `size` этого объекта в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


Получает или задает 32‑битное знаковое целое, которое указывает тип цветового пространства. Оно ДОЛЖНО быть определено в перечислении LogicalColorSpace (раздел 2.1.1.14). Если это значение равно LCS\_sRGB или LCS\_WINDOWS\_COLOR\_SPACE, необходимо использовать цветовое пространство sRGB.

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


Получает или задает 32‑битное знаковое целое, которое указывает тип цветового пространства. Оно ДОЛЖНО быть определено в перечислении LogicalColorSpace (раздел 2.1.1.14). Если это значение равно LCS\_sRGB или LCS\_WINDOWS\_COLOR\_SPACE, необходимо использовать цветовое пространство sRGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getIntent() {#getIntent--}
```
public int getIntent()
```


Получает или задает 32‑битное знаковое целое, определяющее намерение отображения гаммы. Оно ДОЛЖНО быть определено в перечислении GamutMappingIntent (раздел 2.1.1.11).

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Получает или задает 32‑битное знаковое целое, определяющее намерение отображения гаммы. Оно ДОЛЖНО быть определено в перечислении GamutMappingIntent (раздел 2.1.1.11).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


Получает или задает объект CIEXYZTriple (раздел 2.2.2.7), который определяет координаты CIE‑хроматичности x, y и z трёх цветов, соответствующих `endpoints` RGB для логического цветового пространства, связанного с растровым изображением. Если поле `ColorSpaceType` не указывает LCS\_CALIBRATED\_RGB, это поле ДОЛЖНО игнорироваться.

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


Получает или задает объект CIEXYZTriple (раздел 2.2.2.7), который определяет координаты CIE‑хроматичности x, y и z трёх цветов, соответствующих `endpoints` RGB для логического цветового пространства, связанного с растровым изображением. Если поле `ColorSpaceType` не указывает LCS\_CALIBRATED\_RGB, это поле ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для красного. Если поле `ColorSpaceType` не указывает LCS\_CALIBRATED\_RGB, это поле ДОЛЖНО игнорироваться.

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для красного. Если поле `ColorSpaceType` не указывает LCS\_CALIBRATED\_RGB, это поле ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для зелёного. Если поле `ColorSpaceType` не указывает LCS\_CALIBRATED\_RGB, это поле ДОЛЖНО игнорироваться.

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для зелёного. Если поле `ColorSpaceType` не указывает LCS\_CALIBRATED\_RGB, это поле ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для синего. Если поле `ColorSpaceType` не указывает LCS\_CALIBRATED\_RGB, это поле ДОЛЖНО игнорироваться.

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Получает или задает 32‑битное фиксированное значение, определяющее тональную кривую отклика для синего. Если поле `ColorSpaceType` не указывает LCS\_CALIBRATED\_RGB, это поле ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


Получает или задает необязательную нуль‑терминированную строку Unicode UTF16-LE, которая указывает имя файла, содержащего цветовой профиль. Если имя файла указано, и поле `ColorSpaceType` установлено в LCS\_CALIBRATED\_RGB, остальные поля этой структуры ДОЛЖНЫ игнорироваться.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


Получает или задает необязательную нуль‑терминированную строку Unicode UTF16-LE, которая указывает имя файла, содержащего цветовой профиль. Если имя файла указано, и поле `ColorSpaceType` установлено в LCS\_CALIBRATED\_RGB, остальные поля этой структуры ДОЛЖНЫ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

