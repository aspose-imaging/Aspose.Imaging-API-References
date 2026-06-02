---
title: "WmfBinaryRasterOperation"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Раздел перечисления BinaryRasterOperation перечисляет коды бинарных растровых операций."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfBinaryRasterOperation extends System.Enum
```

Раздел перечисления BinaryRasterOperation перечисляет коды бинарных растровых операций. Коды растровых операций определяют, как обработка метафайла объединяет биты выбранной ручки с битами в целевом битмапе.

--------------------

Каждый код растровой операции представляет логическую операцию, в которой значения пикселей выбранной ручки и целевого битмапа комбинируются. Ниже приведены два операнда, используемые в этих операциях. Операнд Значение P Выбранная ручка D Целевой битмап a Побитовое И n Побитовое НЕ (инверсия) o Побитовое ИЛИ x Побитовое исключающее ИЛИ (XOR)
## Поля

| Поле | Описание |
| --- | --- |
| [Black](#Black) | 0, Пиксель всегда равен 0. |
| [Notmergepen](#Notmergepen) | DPon, Пиксель — инверсия цвета MERGEPEN |
| [Masknotpen](#Masknotpen) | DPna, Пиксель — комбинация цвета экрана и инверсии цвета ручки. |
| [Notcopypen](#Notcopypen) | Pn, Пиксель — инверсия цвета ручки. |
| [Maskpennot](#Maskpennot) | PDna, Пиксель — комбинация общих цветов как ручки, так и инверсии экрана. |
| [Not](#Not) | Dn, Пиксель — инверсия цвета экрана. |
| [Xorpen](#Xorpen) | DPx, Пиксель — комбинация цветов в ручке или в экране, но не в обоих одновременно. |
| [Notmaskpen](#Notmaskpen) | DPan, Пиксель — инверсия цвета MASKPEN. |
| [Maskpen](#Maskpen) | DPa, Пиксель — комбинация общих цветов ручки и экрана. |
| [Notxorpen](#Notxorpen) | DPxn, Пиксель — инверсия цвета XORPEN. |
| [Nop](#Nop) | D, Пиксель остаётся без изменений. |
| [Mergenotpen](#Mergenotpen) | DPno, Пиксель — комбинация общих цветов экрана и инверсии цвета ручки. |
| [Copypen](#Copypen) | P, Pixel — это цвет пера. |
| [Mergepennot](#Mergepennot) | PDno, Pixel — комбинация цвета пера и инверсии цвета экрана. |
| [Mergepen](#Mergepen) | DPo, Pixel — комбинация цвета пера и цвета экрана. |
| [White](#White) | 1, Pixel всегда равен 1. |
### Black {#Black}
```
public static final int Black
```


0, Пиксель всегда равен 0.

### Notmergepen {#Notmergepen}
```
public static final int Notmergepen
```


DPon, Пиксель — инверсия цвета MERGEPEN

### Masknotpen {#Masknotpen}
```
public static final int Masknotpen
```


DPna, Пиксель — комбинация цвета экрана и инверсии цвета ручки.

### Notcopypen {#Notcopypen}
```
public static final int Notcopypen
```


Pn, Пиксель — инверсия цвета ручки.

### Maskpennot {#Maskpennot}
```
public static final int Maskpennot
```


PDna, Пиксель — комбинация общих цветов как ручки, так и инверсии экрана.

### Not {#Not}
```
public static final int Not
```


Dn, Пиксель — инверсия цвета экрана.

### Xorpen {#Xorpen}
```
public static final int Xorpen
```


DPx, Пиксель — комбинация цветов в ручке или в экране, но не в обоих одновременно.

### Notmaskpen {#Notmaskpen}
```
public static final int Notmaskpen
```


DPan, Пиксель — инверсия цвета MASKPEN.

### Maskpen {#Maskpen}
```
public static final int Maskpen
```


DPa, Пиксель — комбинация общих цветов ручки и экрана.

### Notxorpen {#Notxorpen}
```
public static final int Notxorpen
```


DPxn, Пиксель — инверсия цвета XORPEN.

### Nop {#Nop}
```
public static final int Nop
```


D, Пиксель остаётся без изменений.

### Mergenotpen {#Mergenotpen}
```
public static final int Mergenotpen
```


DPno, Пиксель — комбинация общих цветов экрана и инверсии цвета ручки.

### Copypen {#Copypen}
```
public static final int Copypen
```


P, Pixel — это цвет пера.

### Mergepennot {#Mergepennot}
```
public static final int Mergepennot
```


PDno, Pixel — комбинация цвета пера и инверсии цвета экрана.

### Mergepen {#Mergepen}
```
public static final int Mergepen
```


DPo, Pixel — комбинация цвета пера и цвета экрана.

### White {#White}
```
public static final int White
```


1, Pixel всегда равен 1.

