---
title: "EmfExtCreateFontIndirectW"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_EXTCREATEFONTINDIRECTW define una fuente lógica para operaciones gráficas."
type: docs
weight: 51
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreateFontIndirectW extends EmfObjectCreationRecordType
```

El registro EMR\_EXTCREATEFONTINDIRECTW define una fuente lógica para operaciones gráficas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfExtCreateFontIndirectW(EmfRecord source)](#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfExtCreateFontIndirectW`. |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW--) | Inicializa una nueva instancia de la clase `EmfExtCreateFontIndirectW`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhFonts()](#getIhFonts--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de fuente lógica en la tabla de objetos EMF (sección 3.1.1.1). |
| [setIhFonts(int value)](#setIhFonts-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de fuente lógica en la tabla de objetos EMF (sección 3.1.1.1). |
| [getElw()](#getElw--) | Obtiene o establece un objeto LogFontExDv (sección 2.2.15), que especifica la fuente lógica. |
| [setElw(EmfLogFont value)](#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Obtiene o establece un objeto LogFontExDv (sección 2.2.15), que especifica la fuente lógica. |
### EmfExtCreateFontIndirectW(EmfRecord source) {#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreateFontIndirectW(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfExtCreateFontIndirectW`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW--}
```
public EmfExtCreateFontIndirectW()
```


Inicializa una nueva instancia de la clase `EmfExtCreateFontIndirectW`.

### getIhFonts() {#getIhFonts--}
```
public int getIhFonts()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de fuente lógica en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Returns:**
int
### setIhFonts(int value) {#setIhFonts-int-}
```
public void setIhFonts(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de fuente lógica en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getElw() {#getElw--}
```
public EmfLogFont getElw()
```


Obtiene o establece un objeto LogFontExDv (sección 2.2.15), que especifica la fuente lógica. Un objeto LogFont 2.2.13 PUEDE estar presente en su lugar.[90]El proceso para determinar el tipo de objeto en este campo se describe a continuación.

**Returns:**
[EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
### setElw(EmfLogFont value) {#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public void setElw(EmfLogFont value)
```


Obtiene o establece un objeto LogFontExDv (sección 2.2.15), que especifica la fuente lógica. Un objeto LogFont 2.2.13 PUEDE estar presente en su lugar.[90]El proceso para determinar el tipo de objeto en este campo se describe a continuación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) |  |

