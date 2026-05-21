---
title: "EmfPlusGraphicsVersion"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusGraphicsVersion указывает версию графики операционной системы, используемую для создания EMF‑метафайла."
type: docs
weight: 44
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusGraphicsVersion extends EmfPlusStructureObjectType
```

Объект EmfPlusGraphicsVersion определяет версию графики операционной системы, используемую для создания метафайла EMF+.

Версии графики могут быть расширены поставщиком; однако, чтобы обеспечить совместимость, любые такие расширения ДОЛЖНЫ быть реализованы как в клиентах, так и в серверах EMF+ метафайлов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusGraphicsVersion()](#EmfPlusGraphicsVersion--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getMetafileSignature()](#getMetafileSignature--) | Получает MetafileSignature (20 бит): Значение, которое идентифицирует тип метафайла. |
| [setMetafileSignature(int value)](#setMetafileSignature-int-) | Получает MetafileSignature (20 бит): Значение, которое идентифицирует тип метафайла. |
| [getGraphicsVersion()](#getGraphicsVersion--) | Получает GraphicsVersion (12 бит): Версию графики операционной системы. |
| [setGraphicsVersion(int value)](#setGraphicsVersion-int-) | Получает GraphicsVersion (12 бит): Версию графики операционной системы. |
### EmfPlusGraphicsVersion() {#EmfPlusGraphicsVersion--}
```
public EmfPlusGraphicsVersion()
```


### getMetafileSignature() {#getMetafileSignature--}
```
public int getMetafileSignature()
```


Получает MetafileSignature (20 бит): Значение, которое идентифицирует тип метафайла. Значение для EMF+ метафайла равно 0xDBC01.

**Returns:**
int
### setMetafileSignature(int value) {#setMetafileSignature-int-}
```
public void setMetafileSignature(int value)
```


Получает MetafileSignature (20 бит): Значение, которое идентифицирует тип метафайла. Значение для EMF+ метафайла равно 0xDBC01.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGraphicsVersion() {#getGraphicsVersion--}
```
public int getGraphicsVersion()
```


Получает GraphicsVersion (12 бит): Версию графики операционной системы. Это значение ДОЛЖНО быть определено в перечислении `EmfPlusGraphicsVersion`.

**Returns:**
int
### setGraphicsVersion(int value) {#setGraphicsVersion-int-}
```
public void setGraphicsVersion(int value)
```


Получает GraphicsVersion (12 бит): Версию графики операционной системы. Это значение ДОЛЖНО быть определено в перечислении `EmfPlusGraphicsVersion`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

