---
title: "TiffAlphaStorage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gibt den Alpha‑Speicher für TIFF-Dokumente an."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.tiff.enums/tiffalphastorage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TiffAlphaStorage extends System.Enum
```

Gibt den Alpha‑Speicher für TIFF-Dokumente an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Unspecified](#Unspecified) | Der Alpha-Wert ist nicht angegeben und wird in der TIFF-Datei gespeichert. |
| [Associated](#Associated) | Der Alpha-Wert wird in vormultiplizierter Form gespeichert. |
| [Unassociated](#Unassociated) | Der Alpha-Wert wird in nicht assoziierter Form gespeichert. |
### Unspecified {#Unspecified}
```
public static final int Unspecified
```


Der Alpha-Wert ist nicht angegeben und wird in der TIFF-Datei gespeichert.

### Associated {#Associated}
```
public static final int Associated
```


Der Alpha-Wert wird in vormultiplizierter Form gespeichert. Wenn Alpha wiederhergestellt wird, kann es zu Rundungseffekten kommen und der wiederhergestellte Wert kann vom Original abweichen.

### Unassociated {#Unassociated}
```
public static final int Unassociated
```


Der Alphawert wird in nicht assoziierter Form gespeichert. Das bedeutet, dass der wiederhergestellte Alphawert genau derselbe ist wie er im tiff gespeichert wurde.

