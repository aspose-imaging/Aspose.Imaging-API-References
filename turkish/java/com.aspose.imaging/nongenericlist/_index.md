---
title: "NonGenericList"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Genel olmayan nesne listesi"
type: docs
weight: 76
url: /tr/java/com.aspose.imaging/nongenericlist/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.util.List
```
public class NonGenericList implements List
```

Genel olmayan nesne listesi
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [NonGenericList(List list)](#NonGenericList-java.util.List-) | `NonGenericList` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getList()](#getList--) |  |
| [addItem(Object value)](#addItem-java.lang.Object-) | `System.Collections.IList`'e bir öğe ekler. |
| [clear()](#clear--) | `System.Collections.IList`'den tüm öğeleri kaldırır. |
| [contains(Object value)](#contains-java.lang.Object-) | `System.Collections.IList`'in belirli bir değeri içerip içermediğini belirler. |
| [indexOf(Object value)](#indexOf-java.lang.Object-) | `System.Collections.IList` içindeki belirli bir öğenin indeksini belirler. |
| [insertItem(int index, Object value)](#insertItem-int-java.lang.Object-) | Belirtilen indekste bir öğeyi `System.Collections.IList`'e ekler. |
| [get(int index)](#get-int-) | Belirtilen indeksteki öğeyi alır. |
| [set(int index, Object value)](#set-int-java.lang.Object-) | Belirtilen indeksteki öğeyi ayarlar. |
| [removeItem(Object value)](#removeItem-java.lang.Object-) | `System.Collections.IList`'ten belirli bir nesnenin ilk oluşumunu kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki `System.Collections.IList` öğesini kaldırır. |
| [size()](#size--) | `System.Collections.ICollection` içinde bulunan öğe sayısını alır. |
| [isEmpty()](#isEmpty--) |  |
| [toArray()](#toArray--) |  |
| [add(Object o)](#add-java.lang.Object-) |  |
| [remove(Object o)](#remove-java.lang.Object-) |  |
| [containsAll(Collection c)](#containsAll-java.util.Collection-) |  |
| [addAll(Collection c)](#addAll-java.util.Collection-) |  |
| [addAll(int index, Collection c)](#addAll-int-java.util.Collection-) |  |
| [removeAll(Collection c)](#removeAll-java.util.Collection-) |  |
| [retainAll(Collection c)](#retainAll-java.util.Collection-) |  |
| [add(int index, Object element)](#add-int-java.lang.Object-) |  |
| [remove(int index)](#remove-int-) |  |
| [lastIndexOf(Object o)](#lastIndexOf-java.lang.Object-) |  |
| [listIterator()](#listIterator--) |  |
| [listIterator(int index)](#listIterator-int-) |  |
| [subList(int fromIndex, int toIndex)](#subList-int-int-) |  |
| [iterator()](#iterator--) | Bir koleksiyon içinde yineleme yapan bir enumeratörü döndürür. |
| [toArray(Object[] a)](#toArray-java.lang.Object---) |  |
### NonGenericList(List list) {#NonGenericList-java.util.List-}
```
public NonGenericList(List list)
```


`NonGenericList` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| liste | java.util.List | Liste - nesnelerin kapsayıcısı. |

### getList() {#getList--}
```
public List getList()
```




**Returns:**
java.util.List
### addItem(Object value) {#addItem-java.lang.Object-}
```
public int addItem(Object value)
```


`System.Collections.IList`'e bir öğe ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | `System.Collections.IList`'e eklenecek `System.Object`. |

**Returns:**
int - Yeni öğenin eklendiği konum.
### clear() {#clear--}
```
public void clear()
```


`System.Collections.IList`'den tüm öğeleri kaldırır.

### contains(Object value) {#contains-java.lang.Object-}
```
public boolean contains(Object value)
```


`System.Collections.IList`'in belirli bir değeri içerip içermediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | `System.Collections.IList` içinde bulunacak `System.Object`. |

**Returns:**
boolean - `System.Object` `System.Collections.IList` içinde bulunursa true; aksi takdirde false.
### indexOf(Object value) {#indexOf-java.lang.Object-}
```
public int indexOf(Object value)
```


`System.Collections.IList` içindeki belirli bir öğenin indeksini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | `System.Collections.IList` içinde bulunacak `System.Object`. |

**Returns:**
int - `value` listede bulunursa indeksi; aksi takdirde -1.
### insertItem(int index, Object value) {#insertItem-int-java.lang.Object-}
```
public void insertItem(int index, Object value)
```


Belirtilen indekste bir öğeyi `System.Collections.IList`'e ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | `value`'nin eklenmesi gereken sıfır tabanlı indeks. |
| değer | java.lang.Object | `System.Collections.IList` içine eklenecek `System.Object`. |

### get(int index) {#get-int-}
```
public Object get(int index)
```


Belirtilen indeksteki öğeyi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |

**Returns:**
java.lang.Object - belirtilen indeksteki öğe.
### set(int index, Object value) {#set-int-java.lang.Object-}
```
public Object set(int index, Object value)
```


Belirtilen indeksteki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |
| değer | java.lang.Object |  |

**Returns:**
java.lang.Object
### removeItem(Object value) {#removeItem-java.lang.Object-}
```
public void removeItem(Object value)
```


`System.Collections.IList`'ten belirli bir nesnenin ilk oluşumunu kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | `System.Collections.IList`'ten kaldırılacak `System.Object`. |

### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```


Belirtilen indeksteki `System.Collections.IList` öğesini kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### size() {#size--}
```
public int size()
```


`System.Collections.ICollection` içinde bulunan öğe sayısını alır.

**Returns:**
int
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```




**Returns:**
boolean
### toArray() {#toArray--}
```
public Object[] toArray()
```




**Returns:**
java.lang.Object[]
### add(Object o) {#add-java.lang.Object-}
```
public boolean add(Object o)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### remove(Object o) {#remove-java.lang.Object-}
```
public boolean remove(Object o)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### containsAll(Collection c) {#containsAll-java.util.Collection-}
```
public boolean containsAll(Collection c)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | java.util.Collection |  |

**Returns:**
boolean
### addAll(Collection c) {#addAll-java.util.Collection-}
```
public boolean addAll(Collection c)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | java.util.Collection |  |

**Returns:**
boolean
### addAll(int index, Collection c) {#addAll-int-java.util.Collection-}
```
public boolean addAll(int index, Collection c)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| c | java.util.Collection |  |

**Returns:**
boolean
### removeAll(Collection c) {#removeAll-java.util.Collection-}
```
public boolean removeAll(Collection c)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | java.util.Collection |  |

**Returns:**
boolean
### retainAll(Collection c) {#retainAll-java.util.Collection-}
```
public boolean retainAll(Collection c)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | java.util.Collection |  |

**Returns:**
boolean
### add(int index, Object element) {#add-int-java.lang.Object-}
```
public void add(int index, Object element)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| öğe | java.lang.Object |  |

### remove(int index) {#remove-int-}
```
public Object remove(int index)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Returns:**
java.lang.Object
### lastIndexOf(Object o) {#lastIndexOf-java.lang.Object-}
```
public int lastIndexOf(Object o)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
int
### listIterator() {#listIterator--}
```
public ListIterator<Object> listIterator()
```




**Returns:**
java.util.ListIterator<java.lang.Object>
### listIterator(int index) {#listIterator-int-}
```
public ListIterator<Object> listIterator(int index)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Returns:**
java.util.ListIterator<java.lang.Object>
### subList(int fromIndex, int toIndex) {#subList-int-int-}
```
public List<Object> subList(int fromIndex, int toIndex)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fromIndex | int |  |
| toIndex | int |  |

**Returns:**
java.util.List<java.lang.Object>
### iterator() {#iterator--}
```
public Iterator iterator()
```


Bir koleksiyon içinde yineleme yapan bir enumeratörü döndürür.

**Returns:**
java.util.Iterator - Bir `System.Collections.IEnumerator` nesnesi, koleksiyon içinde yineleme yapmak için kullanılabilir.
### toArray(Object[] a) {#toArray-java.lang.Object---}
```
public Object[] toArray(Object[] a)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bir | java.lang.Object[] |  |

**Returns:**
java.lang.Object[]
