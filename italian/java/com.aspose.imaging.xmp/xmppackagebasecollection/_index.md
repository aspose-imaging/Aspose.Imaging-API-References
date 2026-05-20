---
title: "XmpPackageBaseCollection"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una collezione di XmpPackage."
type: docs
weight: 20
url: /it/java/com.aspose.imaging.xmp/xmppackagebasecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class XmpPackageBaseCollection implements System.Collections.Generic.IGenericEnumerable<XmpPackage>
```

Rappresenta la raccolta di `XmpPackage`.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection--) | Inizializza una nuova istanza della classe `XmpPackageBaseCollection`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Ottiene il numero di elementi nella collezione. |
| [add(XmpPackage package_)](#add-com.aspose.imaging.xmp.XmpPackage-) | Aggiunge una nuova istanza di `XmpPackage`. |
| [remove(XmpPackage package_)](#remove-com.aspose.imaging.xmp.XmpPackage-) | Rimuove il pacchetto XMP specificato. |
| [getPackages()](#getPackages--) | Ottiene l'array di `XmpPackage`. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Ottiene `XmpPackage` tramite il suo namespaceURI. |
| [clear()](#clear--) | Cancella tutti i `XmpPackage` nella collezione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso una collezione. |
### XmpPackageBaseCollection() {#XmpPackageBaseCollection--}
```
public XmpPackageBaseCollection()
```


Inizializza una nuova istanza della classe `XmpPackageBaseCollection`.

### getCount() {#getCount--}
```
public int getCount()
```


Ottiene il numero di elementi nella collezione.

Valore: Il numero di elementi nella collezione.

**Returns:**
int
### add(XmpPackage package_) {#add-com.aspose.imaging.xmp.XmpPackage-}
```
public void add(XmpPackage package_)
```


Aggiunge una nuova istanza di `XmpPackage`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Il pacchetto XMP\_ da aggiungere. |

### remove(XmpPackage package_) {#remove-com.aspose.imaging.xmp.XmpPackage-}
```
public void remove(XmpPackage package_)
```


Rimuove il pacchetto XMP specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Il pacchetto XMP\_ da rimuovere. |

### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Ottiene l'array di `XmpPackage`.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - Restituisce un array di pacchetti XMP.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Ottiene `XmpPackage` tramite il suo namespaceURI.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| namespaceUri | java.lang.String | Il namespace URI per ottenere il pacchetto\_. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns XMP package\_ for specified namespace Uri.
### clear() {#clear--}
```
public void clear()
```


Cancella tutti i `XmpPackage` nella collezione.

### iterator() {#iterator--}
```
public System.Collections.Generic.List.Enumerator<XmpPackage> iterator()
```


Restituisce un enumeratore che itera attraverso una collezione.

**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<com.aspose.imaging.xmp.XmpPackage> - Un oggetto `System.Collections.IEnumerator` che può essere usato per iterare attraverso la collezione.
