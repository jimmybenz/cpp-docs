---
title: "Microsoft::WRL::Wrappers Namespace"
ms.date: "11/04/2016"
ms.topic: "reference"
f1_keywords: ["corewrappers/Microsoft::WRL::Wrappers"]
helpviewer_keywords: ["Wrappers namespace"]
ms.assetid: 36ac38c7-1fc3-42da-a879-5c68661dc9e1
---
# Microsoft::WRL::Wrappers Namespace

Defines Resource Acquisition Is Initialization (RAII) wrapper types that simplify the lifetime management of objects, strings, and handles.

## Syntax

```cpp
namespace Microsoft::WRL::Wrappers;
```

## Members

### Typedefs

|Name|Description|
|----------|-----------------|
|`FileHandle`|`HandleT<HandleTraits::FileHandleTraits>`|

### Classes

|Name|Description|
|----------|-----------------|
|[CriticalSection Class](../windows/criticalsection-class.md)|Represents a critical section object.|
|[Event Class (WRL)](../windows/event-class-wrl.md)|Represents an event.|
|[HandleT Class](../windows/handlet-class.md)|Represents a handle to an object.|
|[HString Class](../windows/hstring-class.md)|Provides support for manipulating HSTRING handles.|
|[HStringReference Class](../windows/hstringreference-class.md)|Represents an HSTRING that is created from an existing string.|
|[Mutex Class](../windows/mutex-class.md)|Represents a synchronization object that exclusively controls a shared resource.|
|[RoInitializeWrapper Class](../windows/roinitializewrapper-class.md)|Initializes the Windows Runtime.|
|[Semaphore Class](../windows/semaphore-class.md)|Represents a synchronization object that controls a shared resource that can support a limited number of users.|
|[SRWLock Class](../windows/srwlock-class.md)|Represents a slim reader/writer lock.|

## Requirements

**Header:** corewrappers.h

**Namespace:** Microsoft::WRL::Wrappers

## See Also

[Microsoft::WRL Namespace](../windows/microsoft-wrl-namespace.md)