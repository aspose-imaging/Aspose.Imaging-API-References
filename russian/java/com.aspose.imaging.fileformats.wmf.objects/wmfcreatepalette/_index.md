---
title: "WmfCreatePalette"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_CREATEPALETTE создает объект палитры, раздел 2.2.1.3."
type: docs
weight: 22
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePalette extends WmfGraphicObject
```

Запись META\_CREATEPALETTE создает объект Palette (раздел 2.2.1.3).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfCreatePalette()](#WmfCreatePalette--) | WMFs запись. |
## Поля

| Поле | Описание |
| --- | --- |
| [PALETTE_START](#PALETTE-START) | Тег начала палитры |
## Методы

| Метод | Описание |
| --- | --- |
| [getLogPalette()](#getLogPalette--) | Получает логическую палитру. |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Устанавливает логическую палитру. |
### WmfCreatePalette() {#WmfCreatePalette--}
```
public WmfCreatePalette()
```


WMFs запись.

### PALETTE_START {#PALETTE-START}
```
public static final int PALETTE_START
```


Тег начала палитры

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Получает логическую палитру.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) - The logical palette.
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Устанавливает логическую палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) | Логическая палитра. |

