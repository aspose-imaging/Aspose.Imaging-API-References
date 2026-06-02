---
title: "EmfExtTextOutOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die ExtTextOutOptions-Aufzählung spezifiziert Parameter, die verschiedene Aspekte der Textausgabe durch EMR_SMALLTEXTOUTsection 2.3.5.37‑Datensätze und in EmrText‑Objekten steuern."
type: docs
weight: 19
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfExtTextOutOptions extends System.Enum
```

Die Aufzählung ExtTextOutOptions gibt Parameter an, die verschiedene Aspekte der Textausgabe durch EMR\_SMALLTEXTOUT(section 2.3.5.37)-Datensätze und in EmrText-Objekten steuern.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ETO_OPAQUE](#ETO-OPAQUE) | Dieses Bit zeigt an, dass die aktuelle Hintergrundfarbe verwendet werden SOLLTE, um das Rechteck zu füllen. |
| [ETO_CLIPPED](#ETO-CLIPPED) | Dieses Bit zeigt an, dass der Text an das Rechteck angepasst werden SOLLTE. |
| [ETO_GLYPH_INDEX](#ETO-GLYPH-INDEX) | Dieses Bit zeigt an, dass die Codes für Zeichen in einer Ausgabetextzeichenfolge tatsächlich Indizes der Zeichen‑glyphen in einer TrueType‑Schrift sind. |
| [ETO_RTLREADING](#ETO-RTLREADING) | Dieses Bit zeigt an, dass der Text RECHTS‑NACH‑LINKS angeordnet werden MUSS, anstatt der standardmäßigen LINKS‑NACH‑RECHTS‑Reihenfolge. |
| [ETO_NO_RECT](#ETO-NO-RECT) | Dieses Bit zeigt an, dass der Datensatz kein Begrenzungsrechteck für die Textausgabe angibt. |
| [ETO_SMALL_CHARS](#ETO-SMALL-CHARS) | Dieses Bit zeigt an, dass die Codes für Zeichen in einer Ausgabetextzeichenfolge 8 Bit groß sind, abgeleitet von den niederwertigen Bytes der 16‑Bit‑Unicode‑UTF16‑LE‑Zeichencodes, wobei das höherwertige Byte als 0 angenommen wird. |
| [ETO_NUMERICSLOCAL](#ETO-NUMERICSLOCAL) | Dieses Bit zeigt an, dass zur Anzeige von Zahlen die zum Gebietsschema passenden Ziffern verwendet werden SOLLTEN. |
| [ETO_NUMERICSLATIN](#ETO-NUMERICSLATIN) | Dieses Bit zeigt an, dass zur Anzeige von Zahlen europäische Ziffern verwendet werden SOLLTEN. |
| [ETO_IGNORELANGUAGE](#ETO-IGNORELANGUAGE) | Dieses Bit zeigt an, dass keine spezielle Betriebssystemverarbeitung für die Glyphenplatzierung bei Rechts‑nach‑Links‑Zeichenketten durchgeführt werden soll; das heißt, die gesamte Glyphenpositionierung SOLLTE durch Zeichen‑ und Zustandsdatensätze im Metafile übernommen werden. |
| [ETO_PDY](#ETO-PDY) | Dieses Bit zeigt an, dass sowohl horizontale als auch vertikale Zeichenversatzwerte bereitgestellt werden SOLLTEN. |
| [ETO_REVERSE_INDEX_MAP](#ETO-REVERSE-INDEX-MAP) | Dieses Bit ist reserviert und SOLLTE NICHT verwendet werden. |
### ETO_OPAQUE {#ETO-OPAQUE}
```
public static final int ETO_OPAQUE
```


Dieses Bit zeigt an, dass die aktuelle Hintergrundfarbe verwendet werden SOLLTE, um das Rechteck zu füllen.

### ETO_CLIPPED {#ETO-CLIPPED}
```
public static final int ETO_CLIPPED
```


Dieses Bit zeigt an, dass der Text an das Rechteck angepasst werden SOLLTE.

### ETO_GLYPH_INDEX {#ETO-GLYPH-INDEX}
```
public static final int ETO_GLYPH_INDEX
```


Dieses Bit zeigt an, dass die Codes für Zeichen in einer Ausgabetextzeichenfolge tatsächlich Indizes der Zeichen‑glyphen in einer TrueType‑Schrift sind. Glyphen‑Indizes sind schriftspezifisch, daher muss die zur Wiedergabe verwendete Schrift identisch sein mit der Schrift, die zur Erzeugung der Indizes verwendet wurde.

### ETO_RTLREADING {#ETO-RTLREADING}
```
public static final int ETO_RTLREADING
```


Dieses Bit zeigt an, dass der Text RECHTS‑NACH‑LINKS angeordnet werden MUSS, anstatt der standardmäßigen LINKS‑NACH‑RECHTS‑Reihenfolge. Dies SOLLTE nur angewendet werden, wenn die in den Wiedergabegeräte‑Kontext ausgewählte Schrift entweder Hebräisch oder Arabisch ist.

### ETO_NO_RECT {#ETO-NO-RECT}
```
public static final int ETO_NO_RECT
```


Dieses Bit zeigt an, dass der Datensatz kein Begrenzungsrechteck für die Textausgabe angibt.

### ETO_SMALL_CHARS {#ETO-SMALL-CHARS}
```
public static final int ETO_SMALL_CHARS
```


Dieses Bit zeigt an, dass die Codes für Zeichen in einer Ausgabetextzeichenfolge 8 Bit groß sind, abgeleitet von den niederwertigen Bytes der 16‑Bit‑Unicode‑UTF16‑LE‑Zeichencodes, wobei das höherwertige Byte als 0 angenommen wird.

### ETO_NUMERICSLOCAL {#ETO-NUMERICSLOCAL}
```
public static final int ETO_NUMERICSLOCAL
```


Dieses Bit zeigt an, dass zur Anzeige von Zahlen die zum Gebietsschema passenden Ziffern verwendet werden SOLLTEN.

### ETO_NUMERICSLATIN {#ETO-NUMERICSLATIN}
```
public static final int ETO_NUMERICSLATIN
```


Dieses Bit zeigt an, dass zur Anzeige von Zahlen europäische Ziffern verwendet werden SOLLTEN.

### ETO_IGNORELANGUAGE {#ETO-IGNORELANGUAGE}
```
public static final int ETO_IGNORELANGUAGE
```


Dieses Bit zeigt an, dass keine spezielle Betriebssystemverarbeitung für die Glyphenplatzierung bei Rechts‑nach‑Links‑Zeichenketten durchgeführt werden soll; das heißt, die gesamte Glyphenpositionierung SOLLTE durch Zeichen‑ und Zustandsdatensätze im Metafile übernommen werden.

### ETO_PDY {#ETO-PDY}
```
public static final int ETO_PDY
```


Dieses Bit zeigt an, dass sowohl horizontale als auch vertikale Zeichenversatzwerte bereitgestellt werden SOLLTEN.

### ETO_REVERSE_INDEX_MAP {#ETO-REVERSE-INDEX-MAP}
```
public static final int ETO_REVERSE_INDEX_MAP
```


Dieses Bit ist reserviert und SOLLTE NICHT verwendet werden.

