---
title: "Konfiguration"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die globale Konfiguration der Speicherverwaltung"
type: docs
weight: 10
url: /de/java/com.aspose.imaging.memorymanagement/configuration/
---
**Inheritance:**
java.lang.Object
```
public final class Configuration
```

Die globale Konfiguration der Speicherverwaltung
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liefert den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


Liefert den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße in Megabyte. Ein nicht‑positiver Wert bedeutet keine Speicherbeschränkung für interne Puffer.

**Returns:**
int - der Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße in Megabyte. Ein nicht‑positiver Wert bedeutet keine Speicherbeschränkung für interne Puffer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |

