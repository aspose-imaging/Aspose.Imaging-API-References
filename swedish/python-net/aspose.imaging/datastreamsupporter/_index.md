---
title: "DataStreamSupporter-klass"
type: docs
weight: 1360
url: /sv/python-net/aspose.imaging/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.DataStreamSupporter

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Hämtar objektets datastream. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| is_cached | bool | r | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| save() | Sparar objektets data till den aktuella [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [save(file_path)](#save_file_path_1) | Sparar objektets data till den angivna filsökvägen. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Sparar objektets data till den angivna filsökvägen. |
| [save(stream)](#save_stream_3) | Sparar objektets data till den angivna strömmen. |
| [save_to_stream(stream)](#save_to_stream_stream_4) | Sparar objektets data till den angivna strömmen. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Sparar objektets data till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filinnehållet, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

### Method: save_to_stream(stream) {#save_to_stream_stream_4}


```
 save_to_stream(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

