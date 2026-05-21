---
title: "EmfMetafileHeader"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_HEADER kayıt türleri, EMF metafilelerinin başlangıç noktalarını tanımlar ve metafildeki görüntünün oluşturulduğu cihazın özelliklerini belirtir."
type: docs
weight: 70
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public class EmfMetafileHeader extends EmfRecord
```

EMR\_HEADER kayıt türleri, EMF metafilelerinin başlangıç noktalarını tanımlar ve metafildeki görüntünün oluşturulduğu cihazın özelliklerini belirtir. Başlık kaydındaki bilgiler, EMF metafilelerinin belirli bir çıktı cihazından bağımsız olmasını sağlar. Size alanının değeri, bu bölümde daha önce listelenen farklı EMR\_HEADER kayıt türlerini ayırt etmek için kullanılabilir. Üç olası başlık vardır: Temel başlık, yani EmfMetafileHeader kaydı. Bu başlığın sabit‑boyutlu kısmı 88 bayttır ve bir Header nesnesi içerir. İlk uzantı başlığı, yani EmfMetafileHeaderExtension1 kaydı. Bu başlığın sabit‑boyutlu kısmı 100 bayttır ve bir Header nesnesi ve bir HeaderExtension1 nesnesi (bölüm 2.2.10) içerir. İkinci uzantı başlığı, yani EmfMetafileHeaderExtension2 kaydı. Bu başlığın sabit‑boyutlu kısmı 108 bayttır ve bir Header nesnesi, bir HeaderExtension1 nesnesi ve bir HeaderExtension2 nesnesi (bölüm 2.2.11) içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfMetafileHeader(EmfRecord record)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfMetafileHeader` sınıfı örneği başlatır. |
| [EmfMetafileHeader()](#EmfMetafileHeader--) | Yeni bir `EmfMetafileHeader` sınıfı örneği başlatır. |
| [EmfMetafileHeader(EmfMetafileHeader header)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Yeni bir `EmfMetafileHeader` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmfHeader()](#getEmfHeader--) | Bir Header nesnesi alır (bölüm 2.2.9), bu nesne metafilin içeriği ve yapısı hakkında bilgi içerir |
| [setEmfHeader(EmfHeaderObject value)](#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-) | Bir Header nesnesi ayarlar (bölüm 2.2.9), bu nesne metafilin içeriği ve yapısı hakkında bilgi içerir |
| [getEmfHeaderRecordBuffer()](#getEmfHeaderRecordBuffer--) | EMF başlık kaydının geri kalanını içeren isteğe bağlı bir bayt dizisi alır. |
| [setEmfHeaderRecordBuffer(byte[] value)](#setEmfHeaderRecordBuffer-byte---) | EMF başlık kaydının geri kalanını içeren isteğe bağlı bir bayt dizisi ayarlar. |
| [getEmfDescriptionBuffer()](#getEmfDescriptionBuffer--) | EMF açıklama tamponunu alır. EMF açıklama dizesini içeren isteğe bağlı bir bayt dizisi; bu dize EmfMetafileHeader kaydının sabit kısmıyla bitişik olmak zorunda değildir. |
| [setEmfDescriptionBuffer(byte[] value)](#setEmfDescriptionBuffer-byte---) | EMF açıklama tamponunu ayarlar. EMF açıklama dizesini içeren isteğe bağlı bir bayt dizisi; bu dize EmfMetafileHeader kaydının sabit kısmıyla bitişik olmak zorunda değildir. |
| [getEmfDescription()](#getEmfDescription--) | EMF açıklamasını alır. İsteğe bağlı, null ile sonlandırılmış, rastgele uzunlukta ve içerikte Unicode UTF16-LE dizesi. |
| [setEmfDescription(String value)](#setEmfDescription-java.lang.String-) | EMF açıklamasını ayarlar. İsteğe bağlı, null ile sonlandırılmış, rastgele uzunlukta ve içerikte Unicode UTF16-LE dizesi. |
### EmfMetafileHeader(EmfRecord record) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMetafileHeader(EmfRecord record)
```


Yeni bir `EmfMetafileHeader` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kayıt. |

### EmfMetafileHeader() {#EmfMetafileHeader--}
```
public EmfMetafileHeader()
```


Yeni bir `EmfMetafileHeader` sınıfı örneği başlatır.

### EmfMetafileHeader(EmfMetafileHeader header) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeader(EmfMetafileHeader header)
```


Yeni bir `EmfMetafileHeader` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | Başlık. |

### getEmfHeader() {#getEmfHeader--}
```
public EmfHeaderObject getEmfHeader()
```


Bir Header nesnesi alır (bölüm 2.2.9), bu nesne metafilin içeriği ve yapısı hakkında bilgi içerir

**Returns:**
[EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
### setEmfHeader(EmfHeaderObject value) {#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-}
```
public void setEmfHeader(EmfHeaderObject value)
```


Bir Header nesnesi ayarlar (bölüm 2.2.9), bu nesne metafilin içeriği ve yapısı hakkında bilgi içerir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject) |  |

### getEmfHeaderRecordBuffer() {#getEmfHeaderRecordBuffer--}
```
public byte[] getEmfHeaderRecordBuffer()
```


EMF başlık kaydının geri kalanını içeren isteğe bağlı bir bayt dizisi alır. Bu alanın boyutu 4 baytın katı OLMAK ZORUNDADIR.

**Returns:**
byte[]
### setEmfHeaderRecordBuffer(byte[] value) {#setEmfHeaderRecordBuffer-byte---}
```
public void setEmfHeaderRecordBuffer(byte[] value)
```


EMF başlık kaydının geri kalanını içeren isteğe bağlı bir bayt dizisi ayarlar. Bu alanın boyutu 4 baytın katı OLMAK ZORUNDADIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getEmfDescriptionBuffer() {#getEmfDescriptionBuffer--}
```
public byte[] getEmfDescriptionBuffer()
```


EMF açıklama tamponunu alır. EMF açıklama dizesini içeren isteğe bağlı bir bayt dizisi; bu dize EmfMetafileHeader kaydının sabit kısmıyla bitişik olmak zorunda değildir. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alan isteğe bağlıdır ve YOK SAYILMALIdır.

**Returns:**
byte[]
### setEmfDescriptionBuffer(byte[] value) {#setEmfDescriptionBuffer-byte---}
```
public void setEmfDescriptionBuffer(byte[] value)
```


EMF açıklama tamponunu ayarlar. EMF açıklama dizesini içeren isteğe bağlı bir bayt dizisi; bu dize EmfMetafileHeader kaydının sabit kısmıyla bitişik olmak zorunda değildir. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alan isteğe bağlıdır ve YOK SAYILMALIdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getEmfDescription() {#getEmfDescription--}
```
public String getEmfDescription()
```


EMF açıklamasını alır. İsteğe bağlı, null ile sonlandırılmış Unicode UTF16-LE dizesi, rastgele uzunlukta ve içerikte. Kayıttaki konumu ve karakter sayısı, EmfHeader içinde sırasıyla offDescription ve nDescription alanlarıyla belirtilir. Bu alanlardan birinin değeri sıfır ise, açıklama dizesi bulunmaz.

**Returns:**
java.lang.String
### setEmfDescription(String value) {#setEmfDescription-java.lang.String-}
```
public void setEmfDescription(String value)
```


EMF açıklamasını ayarlar. İsteğe bağlı, null ile sonlandırılmış Unicode UTF16-LE dizesi, rastgele uzunlukta ve içerikte. Kayıttaki konumu ve karakter sayısı, EmfHeader içinde sırasıyla offDescription ve nDescription alanlarıyla belirtilir. Bu alanlardan birinin değeri sıfır ise, açıklama dizesi bulunmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

