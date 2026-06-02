---
title: "Classe SplitStreamContainer"
type: docs
weight: 7330
url: /fr/python-net/aspose.imaging/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SplitStreamContainer

**Inheritance:** StreamContainer

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | Initialise une nouvelle instance de la classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | Initialise une nouvelle instance de la classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | Initialise une nouvelle instance de la classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Spécifie le nombre d'octets de lecture et d'écriture lors d'une lecture séquentielle. |
| can_read | bool | r | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| can_seek | bool | r | Obtient une valeur indiquant si le flux prend en charge le déplacement. |
| can_write | bool | r | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| is_stream_disposed_on_close | bool | r | Obtient une valeur indiquant si ce flux est libéré à la fermeture. |
| length | int | r/w | Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à la  par la position de départ du flux passée au constructeur de StreamContainer. |
| position | int | r/w | Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer. |
| flux | _io.BufferedRandom | r | Obtient le flux de données. |
| sync_root | System.Object | r | Obtient un objet pouvant être utilisé pour synchroniser l'accès à la ressource synchronisée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_stream(stream, dispose_stream)](#create_from_stream_stream_dispose_stream_1) | Initialise une nouvelle instance de la classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |
| [create_from_stream_container(stream, dispose_stream)](#create_from_stream_container_stream_dispose_stream_2) | Initialise une nouvelle instance de la classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |
| flush() | Vide tous les tampons de ce flux et provoque l'écriture de toutes les données tamponnées sur le dispositif sous-jacent. |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_3) | Insère le conteneur de flux à la position spécifiée. |
| [read(buffer, offset, count)](#read_buffer_offset_count_4) | Lit une séquence d'octets du flux actuel et avance la position dans le flux du nombre d'octets lus. |
| [read(bytes)](#read_bytes_5) | Lit des octets pour remplir le tampon d'octets spécifié. |
| [read_byte()](#read_byte__6) | Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte. |
| [save(destination_stream)](#save_destination_stream_7) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_8) | Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_9) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(file_path)](#save_file_path_10) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_11) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_12) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_13) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_14) | Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_15) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_16) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_17) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [seek(offset, origin)](#seek_offset_origin_18) | Définit la position dans le flux actuel. |
| seek_begin() | Définit la position du flux au début du flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer. |
| [to_bytes()](#to_bytes__19) | Convertit les données du flux en tableau d'entiers. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_20) | Convertit les données du flux en tableau d'entiers. |
| [write(buffer, offset, count)](#write_buffer_offset_count_21) | Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| [write(bytes)](#write_bytes_22) | Écrit tous les octets spécifiés dans le flux. |
| [write_byte(value)](#write_byte_value_23) | Écrit un octet à la position actuelle du flux et avance la position dans le flux d'un octet. |
| [write_to(stream_container)](#write_to_stream_container_24) | Copie les données contenues vers un autre [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_25) | Copie les données contenues vers un autre [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

Initialise une nouvelle instance de la classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Initialise une nouvelle instance de la classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux de données. |
| dispose_stream | bool | si défini sur <c>true</c> le flux sera libéré lorsque le conteneur sera libéré. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Initialise une nouvelle instance de la classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le flux de données. |
| dispose_stream | bool | si défini sur <c>true</c> le flux sera libéré lorsque le conteneur sera libéré. |

### Method: create_from_stream(stream, dispose_stream)  [static] {#create_from_stream_stream_dispose_stream_1}


```
 create_from_stream(stream, dispose_stream) 
```

Initialise une nouvelle instance de la classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux de données. |
| dispose_stream | bool | si défini sur <c>true</c> le flux sera libéré lorsque le conteneur sera libéré. |

**Returns**

| Type | Description |
| :- | :- |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) |  |


### Method: create_from_stream_container(stream, dispose_stream)  [static] {#create_from_stream_container_stream_dispose_stream_2}


```
 create_from_stream_container(stream, dispose_stream) 
```

Initialise une nouvelle instance de la classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux. |
| dispose_stream | bool | si défini sur <c>true</c> libère le flux. |

**Returns**

| Type | Description |
| :- | :- |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) |  |


### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_3}


```
 insert(position, stream, dispose_stream) 
```

Insère le conteneur de flux à la position spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position où insérer. |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux à insérer. |
| dispose_stream | bool | si défini sur <c>true</c> libère le flux. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_4}


```
 read(buffer, offset, count) 
```

Lit une séquence d'octets du flux actuel et avance la position dans le flux du nombre d'octets lus.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tampon | System.Byte | Un tableau d'octets. Lorsque cette méthode retourne, le tampon contient le tableau d'octets spécifié avec les valeurs entre _offset_ et (_offset_ + _count_ - 1) remplacées par les octets lus depuis la source actuelle. |
| offset | int | Le décalage d'octet basé sur zéro dans _buffer_ à partir duquel commencer à stocker les données lues depuis le flux actuel. |
| count | int | Le nombre maximal d'octets à lire depuis le flux actuel. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le nombre total d'octets lus dans le tampon. Cela peut être inférieur au nombre d'octets demandé si autant d'octets ne sont pas disponibles actuellement, ou zéro (0) si la fin du flux a été atteinte. |


### Method: read(bytes) {#read_bytes_5}


```
 read(bytes) 
```

Lit des octets pour remplir le tampon d'octets spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | System.Byte | Les octets à remplir. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le nombre d'octets lus. Cette valeur peut être inférieure au nombre d'octets dans le tampon s'il n'y a pas assez d'octets dans le flux. |


### Method: read_byte() {#read_byte__6}


```
 read_byte() 
```

Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte.

**Returns**

| Type | Description |
| :- | :- |
| int | L'octet non signé converti en Int32, ou -1 si à la fin du flux. |


### Method: save(destination_stream) {#save_destination_stream_7}


```
 save(destination_stream) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_8}


```
 save(destination_stream, buffer_size) 
```

Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |
| buffer_size | int | Le tampon. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_9}


```
 save(destination_stream, buffer_size, length) 
```

Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |
| buffer_size | int | La taille du tampon. |
| length | int | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur [SplitStreamContainer.length](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |

### Method: save(file_path) {#save_file_path_10}


```
 save(file_path) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier dans lequel enregistrer les données du flux. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_11}


```
 save(file_path, buffer_size) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier dans lequel enregistrer les données du flux. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) est utilisée. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_12}


```
 save(file_path, buffer_size, length) 
```

Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier dans lequel enregistrer les données du flux. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) est utilisée. |
| length | int | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_13}


```
 save_to_stream(destination_stream) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_14}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |
| buffer_size | int | Le tampon. |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_15}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) est utilisée. |
| length | int | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_16}


```
 save_with_buf_size(file_path, buffer_size) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier dans lequel enregistrer les données du flux. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) est utilisée. |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_17}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier dans lequel enregistrer les données du flux. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) est utilisée. |
| length | int | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_18}


```
 seek(offset, origin) 
```

Définit la position dans le flux actuel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| offset | int | Un décalage d'octet relatif au paramètre _origin_. Cette valeur représente le décalage depuis la position de départ du flux passée au constructeur de StreamContainer. |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Une valeur de type SeekOrigin indiquant le point de référence utilisé pour obtenir la nouvelle position. |

**Returns**

| Type | Description |
| :- | :- |
| int | La nouvelle position dans le flux actuel. |


### Method: to_bytes() {#to_bytes__19}


```
 to_bytes() 
```

Convertit les données du flux en tableau d'entiers.

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Les données du flux converties en tableau d'entiers. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_20}


```
 to_bytes(position, bytes_count) 
```

Convertit les données du flux en tableau d'entiers.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à partir de laquelle commencer la lecture des octets. |
| bytes_count | int | Le nombre d'octets à lire. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Les données du flux converties en tableau d'entiers. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_21}


```
 write(buffer, offset, count) 
```

Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tampon | System.Byte | Un tableau d'octets. Cette méthode copie _count_ octets de _buffer_ vers le flux actuel. |
| offset | int | Le décalage d'octet basé sur zéro dans _buffer_ à partir duquel commencer à copier les octets vers le flux actuel. |
| count | int | Le nombre d'octets à écrire dans le flux actuel. |

### Method: write(bytes) {#write_bytes_22}


```
 write(bytes) 
```

Écrit tous les octets spécifiés dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | System.Byte | Les octets à écrire. |

### Method: write_byte(value) {#write_byte_value_23}


```
 write_byte(value) 
```

Écrit un octet à la position actuelle du flux et avance la position dans le flux d'un octet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | System.Byte | L'octet à écrire dans le flux. |

### Method: write_to(stream_container) {#write_to_stream_container_24}


```
 write_to(stream_container) 
```

Copie les données contenues vers un autre [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux vers lequel copier. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_25}


```
 write_to(stream_container, length) 
```

Copie les données contenues vers un autre [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux vers lequel copier. |
| length | int | Le nombre d'octets à écrire. |

