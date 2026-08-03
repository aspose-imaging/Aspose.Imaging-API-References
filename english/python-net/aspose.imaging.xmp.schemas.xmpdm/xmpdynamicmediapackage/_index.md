---
title: XmpDynamicMediaPackage Class
type: docs
weight: 70
url: /python-net/aspose.imaging.xmp.schemas.xmpdm/xmpdynamicmediapackage/
---

**Summary:** Represents XMP Dynamic Media namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpdm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpdm.XmpDynamicMediaPackage

**Inheritance:** XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpDynamicMediaPackage()](#XmpDynamicMediaPackage__1) | Initializes a new instance of the [XmpDynamicMediaPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/xmpdynamicmediapackage/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Gets the XMP key count. |
| keys | System.Collections.Generic.ICollection`1[[System.String]] | r | Gets the keys in XMP package. |
| namespace_uri | string | r | Gets the namespace URI. |
| prefix | string | r | Gets the prefix. |
| xml_namespace | string | r | Gets the XML namespace. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Adds string property. |
| [add_value(key, value)](#add_value_key_value_2) | Adds string property. |
| clear() | Clears this instance. |
| [contains_key(key)](#contains_key_key_3) | Determines whether this collection specified key. |
| [get_prop_value(key)](#get_prop_value_key_4) | Gets the first XMP attribute or element value with by specified _key_. |
| [remove(key)](#remove_key_5) | Removes the first element or attribute value with the specified key. |
| [set_abs_peak_audio_file_path(uri)](#set_abs_peak_audio_file_path_uri_6) | Sets the absolute peak audio file path. |
| [set_alblum(album)](#set_alblum_album_7) | Sets the alblum. |
| [set_alt_tape_name(alt_tape_name)](#set_alt_tape_name_alt_tape_name_8) | Sets the alternative tape name. |
| [set_alt_time_code(timecode)](#set_alt_time_code_timecode_9) | Sets the alternative time code. |
| [set_artist(artist)](#set_artist_artist_10) | Sets the artist. |
| [set_audio_channel_type(audio_channel_type)](#set_audio_channel_type_audio_channel_type_11) | Sets the audio channel type. |
| [set_audio_sample_rate(rate)](#set_audio_sample_rate_rate_12) | Sets the audio sample rate. |
| [set_audio_sample_type(audio_sample_type)](#set_audio_sample_type_audio_sample_type_13) | Sets the audio sample type. |
| [set_camera_angle(camera_angle)](#set_camera_angle_camera_angle_14) | Sets the camera angle. |
| [set_camera_label(camera_label)](#set_camera_label_camera_label_15) | Sets the camera label. |
| [set_camera_move(camera_move)](#set_camera_move_camera_move_16) | Sets the camera move. |
| [set_client(client)](#set_client_client_17) | Sets the client. |
| [set_comment(comment)](#set_comment_comment_18) | Sets the comment. |
| [set_composer(composer)](#set_composer_composer_19) | Sets the composer. |
| [set_director(director)](#set_director_director_20) | Sets the director. |
| [set_director_photography(director_photography)](#set_director_photography_director_photography_21) | Sets the director of photography. |
| [set_duration(duration)](#set_duration_duration_22) | Sets the duration. |
| [set_engineer(engineer)](#set_engineer_engineer_23) | Sets the engineer. |
| [set_file_data_rate(rate)](#set_file_data_rate_rate_24) | Sets the file data rate. |
| [set_genre(genre)](#set_genre_genre_25) | Sets the genre. |
| [set_good(good)](#set_good_good_26) | Sets the good. |
| [set_instrument(instrument)](#set_instrument_instrument_27) | Sets the instrument. |
| [set_intro_time(intro_time)](#set_intro_time_intro_time_28) | Sets the intro time. |
| [set_key(key)](#set_key_key_29) | Sets the audio’s musical key. |
| [set_log_comment(comment)](#set_log_comment_comment_30) | Sets the user's log comment. |
| [set_prop_value(key, value)](#set_prop_value_key_value_31) | Sets the first XMP attribute or element value with by specified _key_. |
| [set_value(key, value)](#set_value_key_value_32) | Sets the value. |
| [set_value(key, value)](#set_value_key_value_33) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_34) | Sets the XMP type value. |
| [try_get_value(key, value)](#try_get_value_key_value_35) | Gets the value by the _key_. |


### Constructor: XmpDynamicMediaPackage() {#XmpDynamicMediaPackage__1}


```
 XmpDynamicMediaPackage() 
```

Initializes a new instance of the [XmpDynamicMediaPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/xmpdynamicmediapackage/) class.

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Adds string property.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | string | The string value. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Adds string property.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | System.Object | The string value. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Determines whether this collection specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key to be checked. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True** if the  contains the specified key; otherwise, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Gets the first XMP attribute or element value with by specified _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |

**Returns**

| Type | Description |
| :- | :- |
| [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | Returns the [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) by the specified key. |


### Method: remove(key) {#remove_key_5}


```
 remove(key) 
```

Removes the first element or attribute value with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with removed value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if the value with the specified key was removed. |


### Method: set_abs_peak_audio_file_path(uri) {#set_abs_peak_audio_file_path_uri_6}


```
 set_abs_peak_audio_file_path(uri) 
```

Sets the absolute peak audio file path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| uri | string | The absolute path to the file’s peak audio file. |

### Method: set_alblum(album) {#set_alblum_album_7}


```
 set_alblum(album) 
```

Sets the alblum.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| album | string | The album. |

### Method: set_alt_tape_name(alt_tape_name) {#set_alt_tape_name_alt_tape_name_8}


```
 set_alt_tape_name(alt_tape_name) 
```

Sets the alternative tape name.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| alt_tape_name | string | Alternative tape name. |

### Method: set_alt_time_code(timecode) {#set_alt_time_code_timecode_9}


```
 set_alt_time_code(timecode) 
```

Sets the alternative time code.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| timecode | [Timecode](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/) | Time code. |

### Method: set_artist(artist) {#set_artist_artist_10}


```
 set_artist(artist) 
```

Sets the artist.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| artist | string | The artist. |

### Method: set_audio_channel_type(audio_channel_type) {#set_audio_channel_type_audio_channel_type_11}


```
 set_audio_channel_type(audio_channel_type) 
```

Sets the audio channel type.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| audio_channel_type | [AudioChannelType](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/audiochanneltype/) | Audio channel type. |

### Method: set_audio_sample_rate(rate) {#set_audio_sample_rate_rate_12}


```
 set_audio_sample_rate(rate) 
```

Sets the audio sample rate.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rate | int | The audio sample rate. |

### Method: set_audio_sample_type(audio_sample_type) {#set_audio_sample_type_audio_sample_type_13}


```
 set_audio_sample_type(audio_sample_type) 
```

Sets the audio sample type.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| audio_sample_type | [AudioSampleType](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/audiosampletype/) | The audio sample type. |

### Method: set_camera_angle(camera_angle) {#set_camera_angle_camera_angle_14}


```
 set_camera_angle(camera_angle) 
```

Sets the camera angle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| camera_angle | string | The camera angle. |

### Method: set_camera_label(camera_label) {#set_camera_label_camera_label_15}


```
 set_camera_label(camera_label) 
```

Sets the camera label.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| camera_label | string | The camera label. |

### Method: set_camera_move(camera_move) {#set_camera_move_camera_move_16}


```
 set_camera_move(camera_move) 
```

Sets the camera move.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| camera_move | string | The camera move. |

### Method: set_client(client) {#set_client_client_17}


```
 set_client(client) 
```

Sets the client.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| client | string | The client. |

### Method: set_comment(comment) {#set_comment_comment_18}


```
 set_comment(comment) 
```

Sets the comment.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| comment | string | The comment. |

### Method: set_composer(composer) {#set_composer_composer_19}


```
 set_composer(composer) 
```

Sets the composer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| composer | string | The composer. |

### Method: set_director(director) {#set_director_director_20}


```
 set_director(director) 
```

Sets the director.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| director | string | The director. |

### Method: set_director_photography(director_photography) {#set_director_photography_director_photography_21}


```
 set_director_photography(director_photography) 
```

Sets the director of photography.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| director_photography | string | The director of photography. |

### Method: set_duration(duration) {#set_duration_duration_22}


```
 set_duration(duration) 
```

Sets the duration.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| duration | [Time](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/time/) | The duration. |

### Method: set_engineer(engineer) {#set_engineer_engineer_23}


```
 set_engineer(engineer) 
```

Sets the engineer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| engineer | string | The engineer. |

### Method: set_file_data_rate(rate) {#set_file_data_rate_rate_24}


```
 set_file_data_rate(rate) 
```

Sets the file data rate.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rate | [Rational](/imaging/python-net/aspose.imaging.xmp.types.derived/rational/) | The file data rate in megabytes per second. |

### Method: set_genre(genre) {#set_genre_genre_25}


```
 set_genre(genre) 
```

Sets the genre.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| genre | string | The genre. |

### Method: set_good(good) {#set_good_good_26}


```
 set_good(good) 
```

Sets the good.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| good | bool | if set to <c>true</c> a shot is a keeper. |

### Method: set_instrument(instrument) {#set_instrument_instrument_27}


```
 set_instrument(instrument) 
```

Sets the instrument.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| instrument | string | The instrument. |

### Method: set_intro_time(intro_time) {#set_intro_time_intro_time_28}


```
 set_intro_time(intro_time) 
```

Sets the intro time.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| intro_time | [Time](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/time/) | The intro time. |

### Method: set_key(key) {#set_key_key_29}


```
 set_key(key) 
```

Sets the audio’s musical key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The audio’s musical key. One of: C, C#, D, D#, E, F, F#, G, G#, A, A#, and B. |

### Method: set_log_comment(comment) {#set_log_comment_comment_30}


```
 set_log_comment(comment) 
```

Sets the user's log comment.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| comment | string | The comment. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_31}


```
 set_prop_value(key, value) 
```

Sets the first XMP attribute or element value with by specified _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | The [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) value. |

### Method: set_value(key, value) {#set_value_key_value_32}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | The value to add to. |

### Method: set_value(key, value) {#set_value_key_value_33}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | The value to add to. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_34}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

### Method: try_get_value(key, value) {#try_get_value_key_value_35}


```
 try_get_value(key, value) 
```

Gets the value by the _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The XMP element key. |
| value | [XmpValue[]](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | The XMP value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True**, if the  contains the _key_; otherwise, **False**. |


