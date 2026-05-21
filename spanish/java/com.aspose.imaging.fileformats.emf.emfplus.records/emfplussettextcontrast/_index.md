---
title: "EmfPlusSetTextContrast"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSetTextContrast especifica el contraste del texto según el valor de corrección gamma."
type: docs
weight: 64
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetTextContrast extends EmfPlusPropertyRecordType
```

El registro EmfPlusSetTextContrast especifica el contraste del texto según el valor de corrección gamma.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSetTextContrast(EmfPlusRecord source)](#EmfPlusSetTextContrast-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSetTextContrast`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTextContrast()](#getTextContrast--) | Obtiene o establece el valor de corrección gamma X 1000, que se aplicará a las operaciones posteriores de renderizado de texto. |
| [setTextContrast(short value)](#setTextContrast-short-) | Obtiene o establece el valor de corrección gamma X 1000, que se aplicará a las operaciones posteriores de renderizado de texto. |
### EmfPlusSetTextContrast(EmfPlusRecord source) {#EmfPlusSetTextContrast-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTextContrast(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSetTextContrast`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Obtiene o establece el valor de corrección gamma X 1000, que se aplicará a las operaciones posteriores de renderizado de texto. El rango permitido es de 1000 a 2200, que representa valores gamma de texto de 1.0 a 2.2.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Obtiene o establece el valor de corrección gamma X 1000, que se aplicará a las operaciones posteriores de renderizado de texto. El rango permitido es de 1000 a 2200, que representa valores gamma de texto de 1.0 a 2.2.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

