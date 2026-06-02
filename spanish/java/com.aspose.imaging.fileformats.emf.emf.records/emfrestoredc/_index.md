---
title: "EmfRestoreDc"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_RESTOREDC restaura el contexto del dispositivo de reproducción al estado especificado."
type: docs
weight: 109
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfRestoreDc extends EmfStateRecordType
```

El registro EMR\_RESTOREDC restaura el contexto del dispositivo de reproducción al estado especificado. El contexto del dispositivo de reproducción se restaura extrayendo la información de estado de una pila que fue creada por registros EMR\_SAVEDC anteriores (sección 2.3.11).

La pila puede contener información de estado para múltiples instancias del contexto del dispositivo de reproducción. Cuando se restaura un estado, todas las instancias de estado que fueron guardadas más recientemente DEBEN ser descartadas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfRestoreDc(EmfRecord source)](#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfRestoreDc`. |
| [EmfRestoreDc()](#EmfRestoreDc--) | Inicializa una nueva instancia de la clase `EmfRestoreDc`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSavedDc()](#getSavedDc--) | Obtiene o establece un entero con signo de 32 bits que especifica el estado guardado que se debe restaurar relativo al estado actual. |
| [setSavedDc(int value)](#setSavedDc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el estado guardado que se debe restaurar relativo al estado actual. |
### EmfRestoreDc(EmfRecord source) {#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRestoreDc(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfRestoreDc`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfRestoreDc() {#EmfRestoreDc--}
```
public EmfRestoreDc()
```


Inicializa una nueva instancia de la clase `EmfRestoreDc`.

### getSavedDc() {#getSavedDc--}
```
public int getSavedDc()
```


Obtiene o establece un entero con signo de 32 bits que especifica el estado guardado que se debe restaurar relativo al estado actual. Este valor DEBE ser negativo; \\u20131 representa el estado que se guardó más recientemente en la pila, \\u20132 el anterior, etc.

**Returns:**
int
### setSavedDc(int value) {#setSavedDc-int-}
```
public void setSavedDc(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el estado guardado que se debe restaurar relativo al estado actual. Este valor DEBE ser negativo; \\u20131 representa el estado que se guardó más recientemente en la pila, \\u20132 el anterior, etc.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

