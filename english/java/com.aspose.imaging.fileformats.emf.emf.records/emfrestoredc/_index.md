---
title: EmfRestoreDc
second_title: Aspose.Imaging for Java API Reference
description: The EMR_RESTOREDC record restores the playback device context to the specified state.
type: docs
weight: 106
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfRestoreDc extends EmfStateRecordType
```

The EMR\_RESTOREDC record restores the playback device context to the specified state. The playback device context is restored by popping state information off a stack that was created by prior EMR\_SAVEDC records (section 2.3.11).

The stack can contain state information for multiple instances of the playback device context. When a state is restored, all state instances that were saved more recently MUST be discarded.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfRestoreDc(EmfRecord source)](#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfRestoreDc` class. |
| [EmfRestoreDc()](#EmfRestoreDc--) | Initializes a new instance of the `EmfRestoreDc` class. |
## Methods

| Method | Description |
| --- | --- |
| [getSavedDc()](#getSavedDc--) | Gets or sets a 32-bit signed integer that specifies the saved state to restore relative to the current state. |
| [setSavedDc(int value)](#setSavedDc-int-) | Gets or sets a 32-bit signed integer that specifies the saved state to restore relative to the current state. |
### EmfRestoreDc(EmfRecord source) {#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRestoreDc(EmfRecord source)
```


Initializes a new instance of the `EmfRestoreDc` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfRestoreDc() {#EmfRestoreDc--}
```
public EmfRestoreDc()
```


Initializes a new instance of the `EmfRestoreDc` class.

### getSavedDc() {#getSavedDc--}
```
public int getSavedDc()
```


Gets or sets a 32-bit signed integer that specifies the saved state to restore relative to the current state. This value MUST be negative; \\u20131 represents the state that was most recently saved on the stack, \\u20132 the one before that, etc.

**Returns:**
int
### setSavedDc(int value) {#setSavedDc-int-}
```
public void setSavedDc(int value)
```


Gets or sets a 32-bit signed integer that specifies the saved state to restore relative to the current state. This value MUST be negative; \\u20131 represents the state that was most recently saved on the stack, \\u20132 the one before that, etc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

