---
title: "EmfSaveDc"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Guarda el estado actual del contexto del dispositivo de reproducción en una pila de estados guardados por registros EMR_SAVEDC anteriores, si los hay."
type: docs
weight: 112
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

Guarda el estado actual del contexto del dispositivo de reproducción en una pila de estados guardados por registros EMR\_SAVEDC anteriores, si los hay. El estado consta de propiedades y objetos gráficos, incluyendo el mapa de bits, pincel, paleta, fuente, lápiz y región actualmente seleccionados. Se utiliza un registro EMR\_RESTOREDC para restaurar el estado. Este registro EMF no especifica parámetros.

La pila puede contener información de estado para múltiples instancias del contexto del dispositivo de reproducción. Cuando se restaura un estado, todas las instancias de estado que fueron guardadas más recientemente DEBEN ser descartadas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSaveDc`. |
| [EmfSaveDc()](#EmfSaveDc--) | Inicializa una nueva instancia de la clase `EmfSaveDc`. |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSaveDc`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


Inicializa una nueva instancia de la clase `EmfSaveDc`.

