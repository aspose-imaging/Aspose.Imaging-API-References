---
title: "EmfStretchMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione StretchMode viene utilizzata per specificare come i dati di colore vengono aggiunti o rimossi dalle bitmap che sono allungate o compresse."
type: docs
weight: 43
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStretchMode extends System.Enum
```

L'enumerazione StretchMode viene utilizzata per specificare come i dati di colore vengono aggiunti o rimossi dalle bitmap che sono allungate o compresse.
## Campi

| Campo | Descrizione |
| --- | --- |
| [STRETCH_ANDSCANS](#STRETCH-ANDSCANS) | Esegue un'operazione Boolean AND utilizzando i valori di colore per i pixel eliminati ed esistenti. |
| [STRETCH_ORSCANS](#STRETCH-ORSCANS) | Esegue un'operazione Boolean OR utilizzando i valori di colore per i pixel eliminati ed esistenti. |
| [STRETCH_DELETESCANS](#STRETCH-DELETESCANS) | Elimina i pixel. |
| [STRETCH_HALFTONE](#STRETCH-HALFTONE) | Mappa i pixel dal rettangolo di origine in blocchi di pixel nel rettangolo di destinazione. |
### STRETCH_ANDSCANS {#STRETCH-ANDSCANS}
```
public static final int STRETCH_ANDSCANS
```


Esegue un'operazione Boolean AND utilizzando i valori di colore per i pixel eliminati ed esistenti. Se il bitmap è un bitmap monocromatico, questa modalità preserva i pixel neri a scapito di quelli bianchi.

### STRETCH_ORSCANS {#STRETCH-ORSCANS}
```
public static final int STRETCH_ORSCANS
```


Esegue un'operazione Boolean OR utilizzando i valori di colore per i pixel eliminati ed esistenti. Se il bitmap è un bitmap monocromatico, questa modalità preserva i pixel bianchi a scapito di quelli neri.

### STRETCH_DELETESCANS {#STRETCH-DELETESCANS}
```
public static final int STRETCH_DELETESCANS
```


Elimina i pixel. Questa modalità elimina tutte le linee di pixel eliminate senza cercare di preservarne le informazioni.

### STRETCH_HALFTONE {#STRETCH-HALFTONE}
```
public static final int STRETCH_HALFTONE
```


Mappa i pixel dal rettangolo di origine in blocchi di pixel nel rettangolo di destinazione. Il colore medio sul blocco di pixel di destinazione approssima il colore dei pixel di origine.

