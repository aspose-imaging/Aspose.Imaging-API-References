---
title: "EmfSetTextAlign"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETTEXTALIGN especifica la alineación del texto."
type: docs
weight: 139
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextAlign extends EmfStateRecordType
```

El registro EMR\_SETTEXTALIGN especifica la alineación del texto.

Los registros EMR\_SMALLTEXTOUT, EMR\_EXTTEXTOUTA y EMR\_EXTTEXTOUTW utilizan valores de alineación de texto para posicionar una cadena de texto en el medio de salida. Los valores especifican la relación entre un punto de referencia y un rectángulo que delimita el texto. El punto de referencia es la posición actual o un punto pasado a un registro de salida de texto. El rectángulo que delimita el texto está formado por las celdas de caracteres en la cadena de texto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetTextAlign(EmfRecord source)](#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetTextAlign`. |
| [EmfSetTextAlign()](#EmfSetTextAlign--) | Inicializa una nueva instancia de la clase `EmfSetTextAlign`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTextAlignmentMode()](#getTextAlignmentMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica la alineación del texto mediante una máscara de banderas de alineación. |
| [setTextAlignmentMode(int value)](#setTextAlignmentMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica la alineación del texto mediante una máscara de banderas de alineación. |
### EmfSetTextAlign(EmfRecord source) {#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextAlign(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetTextAlign`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


Inicializa una nueva instancia de la clase `EmfSetTextAlign`.

### getTextAlignmentMode() {#getTextAlignmentMode--}
```
public int getTextAlignmentMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica la alineación del texto mediante una máscara de banderas de alineación. Estas son o bien `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] sección 2.1.2.3) para texto con una línea base horizontal, o `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] sección 2.1.2.4) para texto con una línea base vertical. Sólo se puede elegir un valor entre los que afectan la alineación horizontal y vertical.

**Returns:**
int
### setTextAlignmentMode(int value) {#setTextAlignmentMode-int-}
```
public void setTextAlignmentMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica la alineación del texto mediante una máscara de banderas de alineación. Estas son o bien `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] sección 2.1.2.3) para texto con una línea base horizontal, o `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] sección 2.1.2.4) para texto con una línea base vertical. Sólo se puede elegir un valor entre los que afectan la alineación horizontal y vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

