---
title: "Classe DataStreamSupporter"
type: docs
weight: 1360
url: /it/python-net/aspose.imaging/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.DataStreamSupporter

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Ottiene lo stream di dati dell'oggetto. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| is_cached | bool | r | Restituisce un valore che indica se i dati dell'oggetto sono attualmente nella cache e non è necessario leggere i dati. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| cache_data() | Memorizza nella cache i dati e garantisce che non vengano caricati ulteriori dati dal [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) sottostante. |
| save() | Salva i dati dell'oggetto nel corrente [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [save(file_path)](#save_file_path_1) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(stream)](#save_stream_3) | Salva i dati dell'oggetto nello stream specificato. |
| [save_to_stream(stream)](#save_to_stream_stream_4) | Salva i dati dell'oggetto nello stream specificato. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dell'oggetto. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dell'oggetto. |
| over_write | bool | se impostato su <c>true</c> sovrascrive il contenuto del file, altrimenti verrà effettuata un'aggiunta. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Salva i dati dell'oggetto nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'oggetto. |

### Method: save_to_stream(stream) {#save_to_stream_stream_4}


```
 save_to_stream(stream) 
```

Salva i dati dell'oggetto nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'oggetto. |

