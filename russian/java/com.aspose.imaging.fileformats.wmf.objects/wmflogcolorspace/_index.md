---
title: "WmfLogColorSpace"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект LogColorSpace задаёт логическое цветовое пространство для контекста устройства воспроизведения, которое может быть именем цветового профиля в ASCII‑символах."
type: docs
weight: 44
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpace extends MetaObject
```

Объект LogColorSpace задаёт логическое цветовое пространство для контекста воспроизведения устройства, которое может быть именем цветового профиля в ASCII‑символах.

Поля Endpoints, GammaRed, GammaGreen и GammaBlue используются для указания логического цветового пространства. Поле Endpoints — это объект CIEXYZTriple, содержащий значения x, y и z конечных точек RGB цветового пространства. Связь между тристимульными значениями X,Y,Z и хроматичными значениями x,y,z выражается следующим образом. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) Поля GammaRed, GammaGreen и GammaBlue содержат значения в формате \"8.8 fixed point\", который представляет числа с плавающей точкой. Каждое значение состоит из нулевого 8‑битного старшего байта, за которым следует 8‑битная дробная часть; полученные 16 бит сдвигаются влево на 8 бит. Таким образом, в 32‑битах реальное значение N.F выглядит как 00000000nnnnnnnnffffffff00000000, где \"nnnnnnnn\" и \"ffffffff\" являются двоичными представлениями N и F соответственно. Например, для реального числа 10.5 nnnnnnnn будет 00001010 (двоичное 10), а ffffffff будет 00000101 (двоичное 5), и полный 32‑битный двоичный код будет 00000000000010100000010100000000, что соответствует шестнадцатеричному значению 0x0A50.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfLogColorSpace()](#WmfLogColorSpace--) |  |
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
| [getFilename()](#getFilename--) | Получает или задает необязательную строку ASCII, указывающую имя файла, содержащего цветовой профиль. |
| [setFilename(String value)](#setFilename-java.lang.String-) | Получает или задает необязательную строку ASCII, указывающую имя файла, содержащего цветовой профиль. |
### WmfLogColorSpace() {#WmfLogColorSpace--}
```
public WmfLogColorSpace()
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


Получает или задает необязательную строку ASCII, указывающую имя файла, содержащего цветовой профиль. Если имя файла указано, и поле `ColorSpaceType` установлено в LCS\_CALIBRATED\_RGB, остальные поля этой структуры ДОЛЖНЫ игнорироваться.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


Получает или задает необязательную строку ASCII, указывающую имя файла, содержащего цветовой профиль. Если имя файла указано, и поле `ColorSpaceType` установлено в LCS\_CALIBRATED\_RGB, остальные поля этой структуры ДОЛЖНЫ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

