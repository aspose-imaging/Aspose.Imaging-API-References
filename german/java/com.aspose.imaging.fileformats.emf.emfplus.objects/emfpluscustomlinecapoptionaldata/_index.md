---
title: "EmfPlusCustomLineCapOptionalData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusCustomLineCapOptionalData-Objekt gibt optionale Füll‑ und Konturdaten für eine benutzerdefinierte Linienendkappe an."
type: docs
weight: 37
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCustomLineCapOptionalData extends EmfPlusStructureObjectType
```

Das EmfPlusCustomLineCapOptionalData-Objekt gibt optionale Füll‑ und Konturdaten für eine benutzerdefinierte Linienendkappe an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillData()](#getFillData--) | Ruft ein optionales EmfPlusFillPath‑Objekt (Abschnitt 2.2.2.17) ab oder legt es fest, das den Pfad zum Füllen eines benutzerdefinierten Grafik‑Linienendes angibt. |
| [setFillData(EmfPlusFillPath value)](#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-) | Ruft ein optionales EmfPlusFillPath‑Objekt (Abschnitt 2.2.2.17) ab oder legt es fest, das den Pfad zum Füllen eines benutzerdefinierten Grafik‑Linienendes angibt. |
| [getOutlineData()](#getOutlineData--) | Ruft ein optionales EmfPlusLinePath‑Objekt (Abschnitt 2.2.2.26) ab oder legt es fest, das den Pfad zum Umranden eines benutzerdefinierten Grafik‑Linienendes angibt. |
| [setOutlineData(EmfPlusLinePath value)](#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-) | Ruft ein optionales EmfPlusLinePath‑Objekt (Abschnitt 2.2.2.26) ab oder legt es fest, das den Pfad zum Umranden eines benutzerdefinierten Grafik‑Linienendes angibt. |
### EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData--}
```
public EmfPlusCustomLineCapOptionalData()
```


### getFillData() {#getFillData--}
```
public EmfPlusFillPath getFillData()
```


Ruft ein optionales EmfPlusFillPath‑Objekt (Abschnitt 2.2.2.17) ab oder legt es fest, das den Pfad zum Füllen eines benutzerdefinierten Grafik‑Linienendes angibt. Dieses Feld MUSS vorhanden sein, wenn das Flag CustomLineCapDataFillPath im Feld CustomLineCapDataFlags des EmfPlusCustomLineCapData‑Objekts gesetzt ist.

**Returns:**
[EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath)
### setFillData(EmfPlusFillPath value) {#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-}
```
public void setFillData(EmfPlusFillPath value)
```


Ruft ein optionales EmfPlusFillPath‑Objekt (Abschnitt 2.2.2.17) ab oder legt es fest, das den Pfad zum Füllen eines benutzerdefinierten Grafik‑Linienendes angibt. Dieses Feld MUSS vorhanden sein, wenn das Flag CustomLineCapDataFillPath im Feld CustomLineCapDataFlags des EmfPlusCustomLineCapData‑Objekts gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath) |  |

### getOutlineData() {#getOutlineData--}
```
public EmfPlusLinePath getOutlineData()
```


Ruft ein optionales EmfPlusLinePath‑Objekt (Abschnitt 2.2.2.26) ab oder legt es fest, das den Pfad zum Umranden eines benutzerdefinierten Grafik‑Linienendes angibt. Dieses Feld MUSS vorhanden sein, wenn das Flag CustomLineCapDataLinePath im Feld CustomLineCapDataFlags des EmfPlusCustomLineCapData‑Objekts gesetzt ist.

**Returns:**
[EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath)
### setOutlineData(EmfPlusLinePath value) {#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-}
```
public void setOutlineData(EmfPlusLinePath value)
```


Ruft ein optionales EmfPlusLinePath‑Objekt (Abschnitt 2.2.2.26) ab oder legt es fest, das den Pfad zum Umranden eines benutzerdefinierten Grafik‑Linienendes angibt. Dieses Feld MUSS vorhanden sein, wenn das Flag CustomLineCapDataLinePath im Feld CustomLineCapDataFlags des EmfPlusCustomLineCapData‑Objekts gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath) |  |

