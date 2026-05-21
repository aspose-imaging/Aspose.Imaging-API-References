---
title: "EmfPlusRedEyeCorrectionEffect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект RedEyeCorrectionEffect указывает области изображения, к которым применяется коррекция «красных глаз»."
type: docs
weight: 67
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusredeyecorrectioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusRedEyeCorrectionEffect extends EmfPlusImageEffectsObjectType
```

Объект RedEyeCorrectionEffect указывает области изображения, к которым применяется коррекция «красных глаз».
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusRedEyeCorrectionEffect()](#EmfPlusRedEyeCorrectionEffect--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getNumberOfAreas()](#getNumberOfAreas--) | Получает или задает 32-битное знаковое целое, которое указывает количество прямоугольников в поле Areas. |
| [setNumberOfAreas(int value)](#setNumberOfAreas-int-) | Получает или задает 32-битное знаковое целое, которое указывает количество прямоугольников в поле Areas. |
| [getAreas()](#getAreas--) | Получает или задает массив объектов WMF RectL NumberOfAreas, указанных в [MS-WMF] раздел 2.2.2.19. |
| [setAreas(Rectangle[] value)](#setAreas-com.aspose.imaging.Rectangle---) | Получает или задает массив объектов WMF RectL NumberOfAreas, указанных в [MS-WMF] раздел 2.2.2.19. |
### EmfPlusRedEyeCorrectionEffect() {#EmfPlusRedEyeCorrectionEffect--}
```
public EmfPlusRedEyeCorrectionEffect()
```


### getNumberOfAreas() {#getNumberOfAreas--}
```
public int getNumberOfAreas()
```


Получает или задает 32-битное знаковое целое, которое указывает количество прямоугольников в поле Areas.

Значение: количество областей.

**Returns:**
int
### setNumberOfAreas(int value) {#setNumberOfAreas-int-}
```
public void setNumberOfAreas(int value)
```


Получает или задает 32-битное знаковое целое, которое указывает количество прямоугольников в поле Areas.

Значение: количество областей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAreas() {#getAreas--}
```
public Rectangle[] getAreas()
```


Получает или задает массив объектов NumberOfAreas WMF RectL, указанных в разделе [MS-WMF] 2.2.2.19. Каждый прямоугольник определяет область растрового изображения, к которой эффект коррекции красных глаз SHOULD быть применён.

Value: Области.

**Returns:**
com.aspose.imaging.Rectangle[]
### setAreas(Rectangle[] value) {#setAreas-com.aspose.imaging.Rectangle---}
```
public void setAreas(Rectangle[] value)
```


Получает или задает массив объектов NumberOfAreas WMF RectL, указанных в разделе [MS-WMF] 2.2.2.19. Каждый прямоугольник определяет область растрового изображения, к которой эффект коррекции красных глаз SHOULD быть применён.

Value: Области.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

