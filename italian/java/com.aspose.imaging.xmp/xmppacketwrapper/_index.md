---
title: "XmpPacketWrapper"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Contiene il pacchetto XMP serializzato includendo intestazione e trailer."
type: docs
weight: 21
url: /it/java/com.aspose.imaging.xmp/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), [com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class XmpPacketWrapper implements IXmlValue, IImageMetadataFormat
```

Contiene il pacchetto XMP serializzato includendo intestazione e trailer.

Un wrapper costituito da una coppia di istruzioni di elaborazione XML (PI) può essere posizionato attorno all'elemento rdf:RDF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-) | Inizializza una nuova istanza della classe `XmpPacketWrapper`. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Inizializza una nuova istanza della classe `XmpPacketWrapper`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderPi()](#getHeaderPi--) | Ottiene l'istruzione di elaborazione dell'intestazione. |
| [getMeta()](#getMeta--) | Ottiene i metadati XMP. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.imaging.xmp.XmpMeta-) | Imposta i metadati XMP. |
| [getTrailerPi()](#getTrailerPi--) | Ottiene l'istruzione di elaborazione del trailer. |
| [getPackages()](#getPackages--) | Ottiene l'array di `XmpPackage` all'interno di XMP. |
| [getPackagesCount()](#getPackagesCount--) | Ottiene la quantità di pacchetti nella struttura XMP. |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.imaging.xmp.XmpPackage-) | Aggiunge il pacchetto. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Ottiene il pacchetto per URI dello spazio dei nomi. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Determina se il pacchetto esiste nel wrapper XMP. |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.imaging.xmp.XmpPackage-) | Rimuove il pacchetto XMP. |
| [clearPackages()](#clearPackages--) | Rimuove tutti i `XmpPackage` all'interno di XMP. |
| [getXmlValue()](#getXmlValue--) | Converte il valore XMP nella rappresentazione XML. |
| [toString()](#toString--) | Restituisce una stringa XML che rappresenta l'oggetto corrente. |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Inizializza una nuova istanza della classe `XmpPacketWrapper`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | L'intestazione XMP dell'istruzione di elaborazione. |
| trailer | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Il trailer XMP dell'istruzione di elaborazione. |
| xmpMeta | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | I metadati XMP. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Inizializza una nuova istanza della classe `XmpPacketWrapper`.

### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Ottiene l'istruzione di elaborazione dell'intestazione.

**Returns:**
[XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Ottiene i metadati XMP. Opzionale.

**Returns:**
[XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) - The XMP meta. Optional.
### setMeta(XmpMeta value) {#setMeta-com.aspose.imaging.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Imposta i metadati XMP. Opzionale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | I metadati XMP. Opzionale. |

### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Ottiene l'istruzione di elaborazione del trailer.

**Returns:**
[XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) - Trailer processing instruction.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Ottiene l'array di `XmpPackage` all'interno di XMP.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - L'array di `XmpPackage` all'interno di XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Ottiene la quantità di pacchetti nella struttura XMP.

**Returns:**
int - La quantità di pacchetti all'interno della struttura XMP.
### addPackage(XmpPackage package_) {#addPackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Aggiunge il pacchetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Il pacchetto. |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Ottiene il pacchetto per URI dello spazio dei nomi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| namespaceUri | java.lang.String | L'URI dello schema del pacchetto. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Determina se il pacchetto esiste nel wrapper XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI dello schema del pacchetto. |

**Returns:**
boolean - Restituisce true se il pacchetto con lo spazio dei nomi specificato esiste nel wrapper XMP.
### removePackage(XmpPackage package_) {#removePackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Rimuove il pacchetto XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Il pacchetto. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Rimuove tutti i `XmpPackage` all'interno di XMP.

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converte il valore XMP nella rappresentazione XML.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito in XML.
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa XML che rappresenta l'oggetto corrente.

**Returns:**
java.lang.String - Una stringa XML che rappresenta l'oggetto corrente.
