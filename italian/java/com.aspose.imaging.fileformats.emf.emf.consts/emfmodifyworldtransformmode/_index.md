---
title: "EmfModifyWorldTransformMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione ModifyWorldTransformMode definisce i modi per utilizzare i dati di trasformazione specificati per modificare la trasformazione dallo spazio mondiale allo spazio pagina attualmente definita nel contesto del dispositivo di riproduzione."
type: docs
weight: 33
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfModifyWorldTransformMode extends System.Enum
```

L'enumerazione ModifyWorldTransformMode definisce i modi per utilizzare i dati di trasformazione specificati per modificare la trasformazione dallo spazio mondiale allo spazio pagina attualmente definita nel contesto del dispositivo di riproduzione.
## Campi

| Campo | Descrizione |
| --- | --- |
| [MWT_IDENTITY](#MWT-IDENTITY) | Reimposta la trasformazione corrente usando la matrice identità. |
| [MWT_LEFTMULTIPLY](#MWT-LEFTMULTIPLY) | Moltiplica la trasformazione corrente. |
| [MWT_RIGHTMULTIPLY](#MWT-RIGHTMULTIPLY) | Moltiplica la trasformazione corrente. |
| [MWT_SET](#MWT-SET) | Esegue la funzione di un record EMR\_SETWORLDTRANSFORM (sezione 2.3.12.2). |
### MWT_IDENTITY {#MWT-IDENTITY}
```
public static final int MWT_IDENTITY
```


Reimposta la trasformazione corrente usando la matrice identità. In questa modalità, i dati di trasformazione specificati vengono ignorati

### MWT_LEFTMULTIPLY {#MWT-LEFTMULTIPLY}
```
public static final int MWT_LEFTMULTIPLY
```


Moltiplica la trasformazione corrente. In questa modalità, i dati di trasformazione specificati sono il moltiplicando sinistro, e la trasformazione attualmente definita nel contesto del dispositivo di riproduzione è il moltiplicando destro

### MWT_RIGHTMULTIPLY {#MWT-RIGHTMULTIPLY}
```
public static final int MWT_RIGHTMULTIPLY
```


Moltiplica la trasformazione corrente. In questa modalità, i dati di trasformazione specificati sono il moltiplicando destro, e la trasformazione attualmente definita nel contesto del dispositivo di riproduzione è il moltiplicando sinistro

### MWT_SET {#MWT-SET}
```
public static final int MWT_SET
```


Esegue la funzione di un record EMR\_SETWORLDTRANSFORM (sezione 2.3.12.2).

