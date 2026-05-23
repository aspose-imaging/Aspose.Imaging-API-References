---
title: "TiffBigEndianStreamWriter Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamwriter/
---

**Summary:** Tiff stream writer for big-endian streams.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffBigEndianStreamWriter

**Inheritance:** TiffStreamWriter

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffBigEndianStreamWriter(writer)](#TiffBigEndianStreamWriter_writer_1) | Initialisiert eine neue Instanz der [TiffBigEndianStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamwriter/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| position | int | r/w | Liest oder setzt die Streamposition. |
| sync_root | System.Object | r | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [write(data)](#write_data_1) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_2) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_3) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_4) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_5) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_6) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_7) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_8) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_9) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_10) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_11) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_12) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_13) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_14) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_15) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_16) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_17) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_18) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_19) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_20) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_21) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_22) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_23) | Schreibt die angegebenen Daten. |
| [write(data)](#write_data_24) | Schreibt die angegebenen Daten. |
| [write(data, offset, data_length)](#write_data_offset_data_length_25) | Schreibt die angegebenen Daten. |
| [write_byte(data)](#write_byte_data_26) | Schreibt die angegebenen Daten. |
| [write_bytes(data)](#write_bytes_data_27) | Schreibt die angegebenen Daten. |
| [write_double(data)](#write_double_data_28) | Schreibt einen einzelnen double-Wert in den Stream. |
| [write_doubles(data)](#write_doubles_data_29) | Schreibt ein Array von double-Werten in den Stream. |
| [write_float(data)](#write_float_data_30) | Schreibt einen einzelnen float-Wert in den Stream. |
| [write_floats(data)](#write_floats_data_31) | Schreibt ein Array von float-Werten in den Stream. |
| [write_int(data)](#write_int_data_32) | Schreibt ein Array von Ganzzahlwerten in den Stream. |
| [write_ints(data)](#write_ints_data_33) | Schreibt ein Array von Ganzzahlwerten in den Stream. |
| [write_long(data)](#write_long_data_34) | Schreibt ein Array von signierten Long-Werten in den Stream. |
| [write_longs(data)](#write_longs_data_35) | Schreibt ein Array von signierten Long-Werten in den Stream. |
| [write_rational(data)](#write_rational_data_36) | Schreibt einen einzelnen rationalen Zahlenwert in den Stream. |
| [write_rationals(data)](#write_rationals_data_37) | Schreibt ein Array von unsignierten rationalen Werten in den Stream. |
| [write_s_byte(data)](#write_s_byte_data_38) | Schreibt einen einzelnen signierten Byte-Wert in den Stream. |
| [write_s_bytes(data)](#write_s_bytes_data_39) | Schreibt ein Array von signierten Byte-Werten in den Stream. |
| [write_s_rational(data)](#write_s_rational_data_40) | Schreibt einen einzelnen signierten rationalen Zahlenwert in den Stream. |
| [write_s_rationals(data)](#write_s_rationals_data_41) | Schreibt ein Array von signierten rationalen Werten in den Stream. |
| [write_short(data)](#write_short_data_42) | Schreibt einen einzelnen Short-Wert in den Stream. |
| [write_shorts(data)](#write_shorts_data_43) | Schreibt ein Array von Short-Werten in den Stream. |
| [write_uint(data)](#write_uint_data_44) | Schreibt einen einzelnen unsignierten Ganzzahlwert in den Stream. |
| [write_uints(data)](#write_uints_data_45) | Schreibt ein Array von unsignierten Ganzzahlwerten in den Stream. |
| [write_ulong(data)](#write_ulong_data_46) | Schreibt ein Array von unsignierten Long-Werten in den Stream. |
| [write_ulongs(data)](#write_ulongs_data_47) | Schreibt ein Array von unsignierten Long-Werten in den Stream. |
| [write_ushort(data)](#write_ushort_data_48) | Schreibt einen einzelnen unsignierten Short-Wert in den Stream. |
| [write_ushorts(data)](#write_ushorts_data_49) | Schreibt ein Array von unsignierten Short-Werten in den Stream. |


### Constructor: TiffBigEndianStreamWriter(writer) {#TiffBigEndianStreamWriter_writer_1}


```
 TiffBigEndianStreamWriter(writer) 
```

Initialisiert eine neue Instanz der [TiffBigEndianStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamwriter/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| writer | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der Stream-Schreiber. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.Byte | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_2}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | float | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_3}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | float[] | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_4}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | float | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_5}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | float[] | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_6}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_7}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_8}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_9}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_10}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.SByte | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_11}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.SByte | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_12}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_13}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_14}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_15}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_16}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.Byte | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_17}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_18}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_19}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_20}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_21}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_22}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_23}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Die zu schreibenden Daten. |

### Method: write(data) {#write_data_24}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Die zu schreibenden Daten. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_25}


```
 write(data, offset, data_length) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.Byte | Die zu schreibenden Daten. |
| offset | int | Der Datenoffset. |
| data_length | int | Länge der Daten zum Schreiben. |

### Method: write_byte(data) {#write_byte_data_26}


```
 write_byte(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.Byte | Die zu schreibenden Daten. |

### Method: write_bytes(data) {#write_bytes_data_27}


```
 write_bytes(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.Byte | Die zu schreibenden Daten. |

### Method: write_double(data) {#write_double_data_28}


```
 write_double(data) 
```

Schreibt einen einzelnen double-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | float | Der zu schreibende Wert. |

### Method: write_doubles(data) {#write_doubles_data_29}


```
 write_doubles(data) 
```

Schreibt ein Array von double-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | float[] | Das zu schreibende Array. |

### Method: write_float(data) {#write_float_data_30}


```
 write_float(data) 
```

Schreibt einen einzelnen float-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | float | Der zu schreibende Wert. |

### Method: write_floats(data) {#write_floats_data_31}


```
 write_floats(data) 
```

Schreibt ein Array von float-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | float[] | Das zu schreibende Array. |

### Method: write_int(data) {#write_int_data_32}


```
 write_int(data) 
```

Schreibt ein Array von Ganzzahlwerten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Das zu schreibende Array. |

### Method: write_ints(data) {#write_ints_data_33}


```
 write_ints(data) 
```

Schreibt ein Array von Ganzzahlwerten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Das zu schreibende Array. |

### Method: write_long(data) {#write_long_data_34}


```
 write_long(data) 
```

Schreibt ein Array von signierten Long-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Das zu schreibende Array. |

### Method: write_longs(data) {#write_longs_data_35}


```
 write_longs(data) 
```

Schreibt ein Array von signierten Long-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Das zu schreibende Array. |

### Method: write_rational(data) {#write_rational_data_36}


```
 write_rational(data) 
```

Schreibt einen einzelnen rationalen Zahlenwert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Der zu schreibende Wert. |

### Method: write_rationals(data) {#write_rationals_data_37}


```
 write_rationals(data) 
```

Schreibt ein Array von unsignierten rationalen Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Das zu schreibende Array. |

### Method: write_s_byte(data) {#write_s_byte_data_38}


```
 write_s_byte(data) 
```

Schreibt einen einzelnen signierten Byte-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.SByte | Der zu schreibende Wert. |

### Method: write_s_bytes(data) {#write_s_bytes_data_39}


```
 write_s_bytes(data) 
```

Schreibt ein Array von signierten Byte-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.SByte | Das zu schreibende Array. |

### Method: write_s_rational(data) {#write_s_rational_data_40}


```
 write_s_rational(data) 
```

Schreibt einen einzelnen signierten rationalen Zahlenwert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Der zu schreibende Wert. |

### Method: write_s_rationals(data) {#write_s_rationals_data_41}


```
 write_s_rationals(data) 
```

Schreibt ein Array von signierten rationalen Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Das zu schreibende Array. |

### Method: write_short(data) {#write_short_data_42}


```
 write_short(data) 
```

Schreibt einen einzelnen Short-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Der zu schreibende Wert. |

### Method: write_shorts(data) {#write_shorts_data_43}


```
 write_shorts(data) 
```

Schreibt ein Array von Short-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Das zu schreibende Array. |

### Method: write_uint(data) {#write_uint_data_44}


```
 write_uint(data) 
```

Schreibt einen einzelnen unsignierten Ganzzahlwert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Der zu schreibende Wert. |

### Method: write_uints(data) {#write_uints_data_45}


```
 write_uints(data) 
```

Schreibt ein Array von unsignierten Ganzzahlwerten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Das zu schreibende Array. |

### Method: write_ulong(data) {#write_ulong_data_46}


```
 write_ulong(data) 
```

Schreibt ein Array von unsignierten Long-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Das zu schreibende Array. |

### Method: write_ulongs(data) {#write_ulongs_data_47}


```
 write_ulongs(data) 
```

Schreibt ein Array von unsignierten Long-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Das zu schreibende Array. |

### Method: write_ushort(data) {#write_ushort_data_48}


```
 write_ushort(data) 
```

Schreibt einen einzelnen unsignierten Short-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int | Der zu schreibende Wert. |

### Method: write_ushorts(data) {#write_ushorts_data_49}


```
 write_ushorts(data) 
```

Schreibt ein Array von unsignierten Short-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | int[] | Das zu schreibende Array. |

