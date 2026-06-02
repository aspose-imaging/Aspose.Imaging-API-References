---
title: "Configurazione"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La configurazione globale della gestione della memoria"
type: docs
weight: 10
url: /it/java/com.aspose.imaging.memorymanagement/configuration/
---
**Inheritance:**
java.lang.Object
```
public final class Configuration
```

La configurazione globale della gestione della memoria
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBufferSizeHint()](#getBufferSizeHint--) | Restituisce il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Imposta il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni. |
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


Restituisce il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni.

Valore: L'indicazione della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Returns:**
int - l'indicazione della dimensione del buffer che definisce la dimensione massima consentita per tutti i buffer interni.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


Imposta il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni.

Valore: L'indicazione della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | l'indicazione della dimensione del buffer che definisce la dimensione massima consentita per tutti i buffer interni. |

