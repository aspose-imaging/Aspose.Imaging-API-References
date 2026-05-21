---
title: "EmfRegionMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración RegionMode define valores que se usan con EMR_SELECTCLIPPATH y EMR_EXTSELECTCLIPRGN especificando la ruta actual o una nueva región que se combina con la región de recorte actual."
type: docs
weight: 39
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRegionMode extends System.Enum
```

La enumeración RegionMode define valores que se usan con EMR\_SELECTCLIPPATH y EMR\_EXTSELECTCLIPRGN, especificando la ruta actual o una nueva región que se combina con la región de recorte actual.
## Campos

| Campo | Descripción |
| --- | --- |
| [RGN_AND](#RGN-AND) | La nueva región de recorte incluye la intersección (áreas superpuestas) de la región de recorte actual y la ruta actual (o nueva región). |
| [RGN_OR](#RGN-OR) | La nueva región de recorte incluye la unión (áreas combinadas) de la región de recorte actual y la ruta actual (o nueva región). |
| [RGN_XOR](#RGN-XOR) | La nueva región de recorte incluye la unión de la región de recorte actual y la ruta actual (o nueva región) pero sin las áreas superpuestas |
| [RGN_DIFF](#RGN-DIFF) | La nueva región de recorte incluye las áreas de la región de recorte actual excluyendo las de la ruta actual (o nueva región). |
| [RGN_COPY](#RGN-COPY) | La nueva región de recorte es la ruta actual (o la nueva región). |
### RGN_AND {#RGN-AND}
```
public static final int RGN_AND
```


La nueva región de recorte incluye la intersección (áreas superpuestas) de la región de recorte actual y la ruta actual (o nueva región).

### RGN_OR {#RGN-OR}
```
public static final int RGN_OR
```


La nueva región de recorte incluye la unión (áreas combinadas) de la región de recorte actual y la ruta actual (o nueva región).

### RGN_XOR {#RGN-XOR}
```
public static final int RGN_XOR
```


La nueva región de recorte incluye la unión de la región de recorte actual y la ruta actual (o nueva región) pero sin las áreas superpuestas

### RGN_DIFF {#RGN-DIFF}
```
public static final int RGN_DIFF
```


La nueva región de recorte incluye las áreas de la región de recorte actual excluyendo las de la ruta actual (o nueva región).

### RGN_COPY {#RGN-COPY}
```
public static final int RGN_COPY
```


La nueva región de recorte es la ruta actual (o la nueva región).

