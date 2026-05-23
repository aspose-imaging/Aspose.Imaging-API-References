---
title: "DataStreamSupporter-Klasse"
type: docs
weight: 1360
url: /de/python-net/aspose.imaging/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.DataStreamSupporter

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Liest den Datenstrom des Objekts. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| is_cached | bool | r | Gibt einen Wert zurück, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| cache_data() | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) durchgeführt werden. |
| save() | Speichert die Daten des Objekts im aktuellen [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [save(file_path)](#save_file_path_1) | Speichert die Daten des Objekts am angegebenen Speicherort. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Speichert die Daten des Objekts am angegebenen Speicherort. |
| [save(stream)](#save_stream_3) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save_to_stream(stream)](#save_to_stream_stream_4) | Speichert die Daten des Objekts in den angegebenen Stream. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Speichert die Daten des Objekts am angegebenen Speicherort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Objektdaten gespeichert werden. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Speichert die Daten des Objekts am angegebenen Speicherort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Objektdaten gespeichert werden. |
| over_write | bool | wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden sollen. |

### Method: save_to_stream(stream) {#save_to_stream_stream_4}


```
 save_to_stream(stream) 
```

Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden sollen. |

