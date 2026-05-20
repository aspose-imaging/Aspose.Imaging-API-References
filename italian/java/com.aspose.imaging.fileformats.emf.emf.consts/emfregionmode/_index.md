---
title: "EmfRegionMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione RegionMode definisce valori utilizzati con EMR_SELECTCLIPPATH e EMR_EXTSELECTCLIPRGN per specificare il percorso corrente o una nuova regione che viene combinata con la regione di ritaglio corrente."
type: docs
weight: 39
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRegionMode extends System.Enum
```

L'enumerazione RegionMode definisce i valori che vengono utilizzati con EMR\_SELECTCLIPPATH e EMR\_EXTSELECTCLIPRGN, specificando il percorso corrente o una nuova regione che viene combinata con la regione di ritaglio corrente.
## Campi

| Campo | Descrizione |
| --- | --- |
| [RGN_AND](#RGN-AND) | La nuova regione di ritaglio include l'intersezione (aree sovrapposte) della regione di ritaglio corrente e del percorso corrente (o nuova regione). |
| [RGN_OR](#RGN-OR) | La nuova regione di ritaglio include l'unione (aree combinate) della regione di ritaglio corrente e del percorso corrente (o nuova regione). |
| [RGN_XOR](#RGN-XOR) | La nuova regione di ritaglio include l'unione della regione di ritaglio corrente e del percorso corrente (o nuova regione) ma senza le aree sovrapposte |
| [RGN_DIFF](#RGN-DIFF) | La nuova regione di ritaglio include le aree della regione di ritaglio corrente escludendo quelle del percorso corrente (o nuova regione). |
| [RGN_COPY](#RGN-COPY) | La nuova regione di ritaglio è il percorso corrente (o la nuova regione). |
### RGN_AND {#RGN-AND}
```
public static final int RGN_AND
```


La nuova regione di ritaglio include l'intersezione (aree sovrapposte) della regione di ritaglio corrente e del percorso corrente (o nuova regione).

### RGN_OR {#RGN-OR}
```
public static final int RGN_OR
```


La nuova regione di ritaglio include l'unione (aree combinate) della regione di ritaglio corrente e del percorso corrente (o nuova regione).

### RGN_XOR {#RGN-XOR}
```
public static final int RGN_XOR
```


La nuova regione di ritaglio include l'unione della regione di ritaglio corrente e del percorso corrente (o nuova regione) ma senza le aree sovrapposte

### RGN_DIFF {#RGN-DIFF}
```
public static final int RGN_DIFF
```


La nuova regione di ritaglio include le aree della regione di ritaglio corrente escludendo quelle del percorso corrente (o nuova regione).

### RGN_COPY {#RGN-COPY}
```
public static final int RGN_COPY
```


La nuova regione di ritaglio è il percorso corrente (o la nuova regione).

