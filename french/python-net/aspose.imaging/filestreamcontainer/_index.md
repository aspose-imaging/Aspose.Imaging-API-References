---
title: "Classe FileStreamContainer"
type: docs
weight: 4810
url: /fr/python-net/aspose.imaging/filestreamcontainer/
---

**Summary:** Helper for file stream processing.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FileStreamContainer

**Inheritance:** StreamContainer

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Spécifie le nombre d'octets de lecture et d'écriture lors d'une lecture séquentielle. |
| can_read | bool | r | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| can_seek | bool | r | Obtient une valeur indiquant si le flux prend en charge le déplacement. |
| can_write | bool | r | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| file_path | string | r | Obtient le chemin du fichier. |
| is_created | bool | r | Obtient une valeur indiquant si le flux a été créé explicitement. |
| is_stream_disposed_on_close | bool | r | Obtient une valeur indiquant si ce flux est libéré à la fermeture. |
| is_temporal | bool | r/w | Obtient ou définit une valeur indiquant si le flux est temporel. |
| length | int | r/w | Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à la  par la position de départ du flux passée au constructeur de StreamContainer. |
| position | int | r/w | Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer. |
| flux | _io.BufferedRandom | r | Obtient le flux de données. |
| sync_root | System.Object | r | Obtient un objet pouvant être utilisé pour synchroniser l'accès à la ressource synchronisée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_1) | Crée un nouveau flux de fichier. |
| flush() | Vide tous les tampons de ce flux et provoque l'écriture de toutes les données tamponnées sur le dispositif sous-jacent. |
| [open_file_stream(file_location)](#open_file_stream_file_location_2) | Ouvre un flux de fichier existant. Si le flux de fichier n'existe pas, l'exception appropriée est levée. |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | Lit une séquence d'octets du flux actuel et avance la position dans le flux du nombre d'octets lus. |
| [read(bytes)](#read_bytes_4) | Lit des octets pour remplir le tampon d'octets spécifié. |
| [read_byte()](#read_byte__5) | Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte. |
| [save(destination_stream)](#save_destination_stream_6) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(file_path)](#save_file_path_9) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_12) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_13) | Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_14) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_15) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_16) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [seek(offset, origin)](#seek_offset_origin_17) | Définit la position dans le flux actuel. |
| seek_begin() | Définit la position du flux au début du flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer. |
| [to_bytes()](#to_bytes__18) | Convertit les données du flux en tableau d'entiers. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_19) | Convertit les données du flux en tableau d'entiers. |
| [write(buffer, offset, count)](#write_buffer_offset_count_20) | Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| [write(bytes)](#write_bytes_21) | Écrit tous les octets spécifiés dans le flux. |
| [write_byte(value)](#write_byte_value_22) | Écrit un octet à la position actuelle du flux et avance la position dans le flux d'un octet. |
| [write_to(stream_container)](#write_to_stream_container_23) | Copie les données contenues vers un autre [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_24) | Copie les données contenues vers un autre [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |


### Method: create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_1}


```
 create_file_stream(file_location, is_temporal) 
```

Crée un nouveau flux de fichier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_location | string | L'emplacement du fichier. |
| is_temporal | bool | Si défini sur <c>true</c>, le conteneur de flux de fichier est temporel. |

**Returns**

| Type | Description |
| :- | :- |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Le conteneur de flux de fichier. |


### Method: open_file_stream(file_location)  [static] {#open_file_stream_file_location_2}


```
 open_file_stream(file_location) 
```

Ouvre un flux de fichier existant. Si le flux de fichier n'existe pas, l'exception appropriée est levée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_location | string | L'emplacement du fichier. |

**Returns**

| Type | Description |
| :- | :- |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Le conteneur de flux de fichier. |


### Method: read(buffer, offset, count) {#read_buffer_offset_count_3}


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


### Method: read(bytes) {#read_bytes_4}


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


### Method: read_byte() {#read_byte__5}


```
 read_byte() 
```

Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte.

**Returns**

| Type | Description |
| :- | :- |
| int | L'octet non signé converti en Int32, ou -1 si à la fin du flux. |


### Method: save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |
| buffer_size | int | Le tampon. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) est utilisée. |
| length | int | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier dans lequel enregistrer les données du flux. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier dans lequel enregistrer les données du flux. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) est utilisée. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


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

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_12}


```
 save_to_stream(destination_stream) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) et la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_13}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux dans lequel enregistrer les données. |
| buffer_size | int | Le tampon. |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_14}


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

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_15}


```
 save_with_buf_size(file_path, buffer_size) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier dans lequel enregistrer les données du flux. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) est utilisée. |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_16}


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

### Method: seek(offset, origin) {#seek_offset_origin_17}


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


### Method: to_bytes() {#to_bytes__18}


```
 to_bytes() 
```

Convertit les données du flux en tableau d'entiers.

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Les données du flux converties en tableau d'entiers. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_19}


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


### Method: write(buffer, offset, count) {#write_buffer_offset_count_20}


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

### Method: write(bytes) {#write_bytes_21}


```
 write(bytes) 
```

Écrit tous les octets spécifiés dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | System.Byte | Les octets à écrire. |

### Method: write_byte(value) {#write_byte_value_22}


```
 write_byte(value) 
```

Écrit un octet à la position actuelle du flux et avance la position dans le flux d'un octet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | System.Byte | L'octet à écrire dans le flux. |

### Method: write_to(stream_container) {#write_to_stream_container_23}


```
 write_to(stream_container) 
```

Copie les données contenues vers un autre [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux vers lequel copier. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_24}


```
 write_to(stream_container, length) 
```

Copie les données contenues vers un autre [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux vers lequel copier. |
| length | int | Le nombre d'octets à écrire. |

