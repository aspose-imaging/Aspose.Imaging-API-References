---
title: "EmfSetArcDirection"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETARCDIRECTION especifica la dirección de dibujo que se utilizará para la salida de arcos y rectángulos."
type: docs
weight: 118
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

El registro EMR\_SETARCDIRECTION especifica la dirección de dibujo que se usará para la salida de arcos y rectángulos.

El registro EMR\\_SETARCDIRECTION afecta la dirección en la que los siguientes registros dibujan: - EMR\\_ARC (sección 2.3.5.2) - EMR\\_ARCTO (sección 2.3.5.3) - EMR\\_CHORD (sección 2.3.5.4) - EMR\\_ELLIPSE (sección 2.3.5.5) - EMR\\_PIE (sección 2.3.5.15) - EMR\\_RECTANGLE (sección 2.3.5.34) - EMR\\_ROUNDRECT (sección 2.3.5.35)
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetArcDirection`. |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | Inicializa una nueva instancia de la clase `EmfSetArcDirection`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | Obtiene o establece un entero sin signo de 32 bits que especifica la dirección del arco. |
| [setArcDirection(int value)](#setArcDirection-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica la dirección del arco. |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetArcDirection`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


Inicializa una nueva instancia de la clase `EmfSetArcDirection`.

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


Obtiene o establece un entero sin signo de 32 bits que especifica la dirección del arco. El valor DEBE estar en la enumeración ArcDirection (sección 2.1.2). La dirección predeterminada es en sentido antihorario.

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica la dirección del arco. El valor DEBE estar en la enumeración ArcDirection (sección 2.1.2). La dirección predeterminada es en sentido antihorario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

