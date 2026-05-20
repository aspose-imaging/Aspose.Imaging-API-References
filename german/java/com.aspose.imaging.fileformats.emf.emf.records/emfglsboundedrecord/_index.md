---
title: "EmfGlsBoundedRecord"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_GLSBOUNDEDRECORD‑Datensatz gibt eine OpenGL‑Funktion mit einem Begrenzungsrechteck für die Ausgabe an."
type: docs
weight: 63
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsBoundedRecord extends EmfOpenGlRecordType
```

Der EMR\_GLSBOUNDEDRECORD-Datensatz gibt eine OpenGL-Funktion mit einem Begrenzungsrechteck für die Ausgabe an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfGlsBoundedRecord(EmfRecord source)](#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfGlsBoundedRecord`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Ruft ein WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das ein Begrenzungsrechteck in Geräte‑Einheiten für die durch Ausführen der OpenGL‑Funktion erzeugte Ausgabe definiert. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ruft ein WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das ein Begrenzungsrechteck in Geräte‑Einheiten für die durch Ausführen der OpenGL‑Funktion erzeugte Ausgabe definiert. |
| [getCbData()](#getCbData--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt. |
| [setCbData(int value)](#setCbData-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt. |
| [getData()](#getData--) | Liest oder setzt ein optionales Byte‑Array der Länge cbData, das Daten für die OpenGL‑Funktion angibt. |
| [setData(byte[] value)](#setData-byte---) | Liest oder setzt ein optionales Byte‑Array der Länge cbData, das Daten für die OpenGL‑Funktion angibt. |
### EmfGlsBoundedRecord(EmfRecord source) {#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsBoundedRecord(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfGlsBoundedRecord`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ruft ein WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das ein Begrenzungsrechteck in Geräte‑Einheiten für die durch Ausführen der OpenGL‑Funktion erzeugte Ausgabe definiert.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ruft ein WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das ein Begrenzungsrechteck in Geräte‑Einheiten für die durch Ausführen der OpenGL‑Funktion erzeugte Ausgabe definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt. Wenn dieser Wert null ist, werden keine Daten an diesen Datensatz angehängt.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt. Wenn dieser Wert null ist, werden keine Daten an diesen Datensatz angehängt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Liest oder setzt ein optionales Byte‑Array der Länge cbData, das Daten für die OpenGL‑Funktion angibt.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Liest oder setzt ein optionales Byte‑Array der Länge cbData, das Daten für die OpenGL‑Funktion angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

