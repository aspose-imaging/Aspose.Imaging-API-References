---
title: "EmfPlusPalette"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusPalette задает цвета, составляющие палитру."
type: docs
weight: 57
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPalette extends EmfPlusStructureObjectType
```

Объект EmfPlusPalette задает цвета, составляющие палитру.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusPalette()](#EmfPlusPalette--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getPaletteStyleFlags()](#getPaletteStyleFlags--) | Получает или задает флаги стиля палитры. |
| [setPaletteStyleFlags(int value)](#setPaletteStyleFlags-int-) | Получает или задает флаги стиля палитры. |
| [getArgb32Entries()](#getArgb32Entries--) | Получает или задает элементы палитры. |
| [setArgb32Entries(int[] value)](#setArgb32Entries-int---) | Получает или задает элементы палитры. |
### EmfPlusPalette() {#EmfPlusPalette--}
```
public EmfPlusPalette()
```


### getPaletteStyleFlags() {#getPaletteStyleFlags--}
```
public int getPaletteStyleFlags()
```


Получает или задает флаги стиля палитры.

Значение: PaletteStyleFlags (4 байта): 32‑битное беззнаковое целое, которое указывает атрибуты данных в палитре. Это значение ДОЛЖНО состоять из флагов `EmfPlusPaletteStyleFlags`.

**Returns:**
int
### setPaletteStyleFlags(int value) {#setPaletteStyleFlags-int-}
```
public void setPaletteStyleFlags(int value)
```


Получает или задает флаги стиля палитры.

Значение: PaletteStyleFlags (4 байта): 32‑битное беззнаковое целое, которое указывает атрибуты данных в палитре. Это значение ДОЛЖНО состоять из флагов `EmfPlusPaletteStyleFlags`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Получает или задает элементы палитры.

Значение: PaletteEntries (переменно): массив из PaletteCount 32‑битных ARGB‑объектов, которые определяют данные в палитре.

**Returns:**
int[] — копия элементов палитры.
### setArgb32Entries(int[] value) {#setArgb32Entries-int---}
```
public void setArgb32Entries(int[] value)
```


Получает или задает элементы палитры.

Значение: PaletteEntries (переменно): массив из PaletteCount 32‑битных ARGB‑объектов, которые определяют данные в палитре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

