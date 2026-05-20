---
title: "EmfPlusObject"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusObject-Datensatz gibt ein Objekt zur Verwendung in Grafikoperationen an."
type: docs
weight: 42
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusObject extends EmfPlusObjectRecordType
```

Der EmfPlusObject-Datensatz gibt ein Objekt für die Verwendung in Grafikoperationen an. Die Objektdefinition kann sich über mehrere Datensätze erstrecken, was durch den Wert des Flags-Feldes angezeigt wird.

Der EmfPlusObject-Datensatz ist generisch; er wird für alle Objekttypen verwendet. Werte, die für bestimmte Objekttypen spezifisch sind, befinden sich im ObjectData-Feld. Ein konzeptuelles Modell zur Verwaltung von Grafikobjekten wird in Managing Graphics Objects (Abschnitt 3.1.2) beschrieben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusObject(EmfPlusRecord source)](#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusObject`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isContinuable()](#isContinuable--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz fortsetzbar ist. |
| [setContinuable(boolean value)](#setContinuable-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz fortsetzbar ist. |
| [getObjectType()](#getObjectType--) | Ruft den Typ des Objekts ab oder legt ihn fest. |
| [setObjectType(byte value)](#setObjectType-byte-) | Ruft den Typ des Objekts ab oder legt ihn fest. |
| [getObjectId()](#getObjectId--) | Liest oder setzt die Objektkennung. |
| [setObjectId(byte value)](#setObjectId-byte-) | Liest oder setzt die Objektkennung. |
| [getTotalObjectSize()](#getTotalObjectSize--) | Ruft die Gesamtegröße des Objekts ab oder legt sie fest. |
| [setTotalObjectSize(int value)](#setTotalObjectSize-int-) | Ruft die Gesamtegröße des Objekts ab oder legt sie fest. |
| [getObjectData()](#getObjectData--) | Ruft ein Byte-Array ab oder legt es fest, das Daten für den im Flags-Feld angegebenen Objekttyp enthält. |
| [setObjectData(EmfPlusGraphicsObjectType value)](#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-) | Ruft ein Byte-Array ab oder legt es fest, das Daten für den im Flags-Feld angegebenen Objekttyp enthält. |
### EmfPlusObject(EmfPlusRecord source) {#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusObject(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusObject`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### isContinuable() {#isContinuable--}
```
public boolean isContinuable()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz fortsetzbar ist. Gibt an, dass die Objektdefinition im nächsten EmfPlusObject-Datensatz fortgesetzt wird. Dieses Flag wird im letzten Datensatz, der das Objekt definiert, niemals gesetzt.

Wert: `true`, wenn diese Instanz komprimiert ist; andernfalls `false`.

**Returns:**
boolean
### setContinuable(boolean value) {#setContinuable-boolean-}
```
public void setContinuable(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz fortsetzbar ist. Gibt an, dass die Objektdefinition im nächsten EmfPlusObject-Datensatz fortgesetzt wird. Dieses Flag wird im letzten Datensatz, der das Objekt definiert, niemals gesetzt.

Wert: `true`, wenn diese Instanz komprimiert ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getObjectType() {#getObjectType--}
```
public byte getObjectType()
```


Ruft den Typ des Objekts ab oder legt ihn fest.

Wert: Der Typ des Objekts.

**Returns:**
byte
### setObjectType(byte value) {#setObjectType-byte-}
```
public void setObjectType(byte value)
```


Ruft den Typ des Objekts ab oder legt ihn fest.

Wert: Der Typ des Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ruft die Objektkennung ab oder legt sie fest. Der Index in der EMF+ Object Table, der dem durch diesen Datensatz erstellten Objekt zugeordnet wird. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ruft die Objektkennung ab oder legt sie fest. Der Index in der EMF+ Object Table, der dem durch diesen Datensatz erstellten Objekt zugeordnet wird. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich.

Wert: Die Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getTotalObjectSize() {#getTotalObjectSize--}
```
public int getTotalObjectSize()
```


Ruft die Gesamtegröße des Objekts ab oder legt sie fest. Wenn der Datensatz fortsetzbar ist und das Weiter‑Bit gesetzt ist, ist dieses Feld vorhanden. Fortsetzende Objekte haben mehrere EMF+-Datensätze, beginnend mit EmfPlusContineudObjectRecord. Jeder EmfPlusContinuedObjectRecord enthält eine TotalObjectSize. Sobald die angegebene Anzahl von Bytes (TotalObjectSize) gelesen wurde, wird der nächste EMF+-Datensatz nicht mehr als Teil des fortsetzenden Objekts behandelt.

Wert: Die Gesamtegröße des Objekts.

**Returns:**
int
### setTotalObjectSize(int value) {#setTotalObjectSize-int-}
```
public void setTotalObjectSize(int value)
```


Ruft die Gesamtegröße des Objekts ab oder legt sie fest. Wenn der Datensatz fortsetzbar ist und das Weiter‑Bit gesetzt ist, ist dieses Feld vorhanden. Fortsetzende Objekte haben mehrere EMF+-Datensätze, beginnend mit EmfPlusContineudObjectRecord. Jeder EmfPlusContinuedObjectRecord enthält eine TotalObjectSize. Sobald die angegebene Anzahl von Bytes (TotalObjectSize) gelesen wurde, wird der nächste EMF+-Datensatz nicht mehr als Teil des fortsetzenden Objekts behandelt.

Wert: Die Gesamtegröße des Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getObjectData() {#getObjectData--}
```
public EmfPlusGraphicsObjectType getObjectData()
```


Ruft ein Byte-Array ab oder legt es fest, das Daten für den im Flags-Feld angegebenen Objekttyp enthält. Inhalt und Format der Daten können je nach Objekttyp variieren. Siehe die einzelnen Objektdefinitionen in Abschnitt 2.2.1 für weitere Informationen.

Wert: Die Objektdaten.

**Returns:**
[EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
### setObjectData(EmfPlusGraphicsObjectType value) {#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-}
```
public void setObjectData(EmfPlusGraphicsObjectType value)
```


Ruft ein Byte-Array ab oder legt es fest, das Daten für den im Flags-Feld angegebenen Objekttyp enthält. Inhalt und Format der Daten können je nach Objekttyp variieren. Siehe die einzelnen Objektdefinitionen in Abschnitt 2.2.1 für weitere Informationen.

Wert: Die Objektdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype) |  |

