---
title: "EmfPlusMetafile"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusMetafileData-Objekt gibt eine Metadatei an, die ein Grafikbild enthält."
type: docs
weight: 55
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusMetafile extends EmfPlusBaseImageData
```

Das EmfPlusMetafileData-Objekt gibt eine Metadatei an, die ein Grafikbild enthält.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusMetafile()](#EmfPlusMetafile--) | Initialisiert eine neue Instanz der `EmfPlusMetafile`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Metadatei angibt, die im MetafileData‑Feld eingebettet ist. |
| [setType(int value)](#setType-int-) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Metadatei angibt, die im MetafileData‑Feld eingebettet ist. |
| [getMetafileDataSize()](#getMetafileDataSize--) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe in Byte der Metadatei‑Daten im MetafileData‑Feld angibt. |
| [setMetafileDataSize(int value)](#setMetafileDataSize-int-) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe in Byte der Metadatei‑Daten im MetafileData‑Feld angibt. |
| [getMetafileData()](#getMetafileData--) | Liest oder schreibt variable Längendaten, die die eingebettete Metadatei spezifizieren. |
| [setMetafileData(byte[] value)](#setMetafileData-byte---) | Liest oder schreibt variable Längendaten, die die eingebettete Metadatei spezifizieren. |
### EmfPlusMetafile() {#EmfPlusMetafile--}
```
public EmfPlusMetafile()
```


Initialisiert eine neue Instanz der `EmfPlusMetafile`‑Klasse.

### getType() {#getType--}
```
public int getType()
```


Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Metadatei angibt, die im MetafileData‑Feld eingebettet ist. Dieser Wert MUSS in der Aufzählung MetafileDataType (Abschnitt 2.1.1.21) definiert sein.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Metadatei angibt, die im MetafileData‑Feld eingebettet ist. Dieser Wert MUSS in der Aufzählung MetafileDataType (Abschnitt 2.1.1.21) definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getMetafileDataSize() {#getMetafileDataSize--}
```
public int getMetafileDataSize()
```


Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe in Byte der Metadatei‑Daten im MetafileData‑Feld angibt.

**Returns:**
int
### setMetafileDataSize(int value) {#setMetafileDataSize-int-}
```
public void setMetafileDataSize(int value)
```


Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe in Byte der Metadatei‑Daten im MetafileData‑Feld angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getMetafileData() {#getMetafileData--}
```
public byte[] getMetafileData()
```


Liest oder schreibt variable Längendaten, die die eingebettete Metadatei spezifizieren. Der Inhalt und das Format der Daten können je nach Metadatei‑Typ unterschiedlich sein.

Grafik‑Bilder werden durch EmfPlusImage‑Objekte (Abschnitt 2.2.1.4) angegeben. Ein EmfPlusMetafile‑Objekt MUSS im ImageData‑Feld eines EmfPlusImage‑Objekts vorhanden sein, wenn ImageTypeMetafile in dessen Type‑Feld angegeben ist. Dieses Objekt ist generisch und wird für verschiedene Datentypen verwendet, einschließlich: Ein WMF‑Metadatei [MS‑WMF]; WMF‑Metadatei, die platziert werden kann; Eine EMF‑Metadatei [MS‑EMF]; Eine EMF+‑Metadatei, die nur Grafikoperationen mit EMF+‑Einträgen spezifiziert; und Eine EMF+‑Metadatei, die Grafikoperationen mit sowohl EMF+‑ als auch EMF‑Einträgen spezifiziert. Siehe Abschnitt 2.2.2 für die Spezifikation zusätzlicher Struktur‑Objekte.

**Returns:**
byte[]
### setMetafileData(byte[] value) {#setMetafileData-byte---}
```
public void setMetafileData(byte[] value)
```


Liest oder schreibt variable Längendaten, die die eingebettete Metadatei spezifizieren. Der Inhalt und das Format der Daten können je nach Metadatei‑Typ unterschiedlich sein.

Grafik‑Bilder werden durch EmfPlusImage‑Objekte (Abschnitt 2.2.1.4) angegeben. Ein EmfPlusMetafile‑Objekt MUSS im ImageData‑Feld eines EmfPlusImage‑Objekts vorhanden sein, wenn ImageTypeMetafile in dessen Type‑Feld angegeben ist. Dieses Objekt ist generisch und wird für verschiedene Datentypen verwendet, einschließlich: Ein WMF‑Metadatei [MS‑WMF]; WMF‑Metadatei, die platziert werden kann; Eine EMF‑Metadatei [MS‑EMF]; Eine EMF+‑Metadatei, die nur Grafikoperationen mit EMF+‑Einträgen spezifiziert; und Eine EMF+‑Metadatei, die Grafikoperationen mit sowohl EMF+‑ als auch EMF‑Einträgen spezifiziert. Siehe Abschnitt 2.2.2 für die Spezifikation zusätzlicher Struktur‑Objekte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

