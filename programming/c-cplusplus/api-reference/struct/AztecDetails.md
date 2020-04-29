---
layout: default-layout
sideHeader: C and C++ Struct
sourceCodeUrl: /programming/c-cplusplus/api-reference/struct/AztecDetails.md
sidebarListFile: sidelist-c-cpp-structs
needCollapsedSideBar: false
needAutoGenerateSidebar: false
---


# AztecDetails
Stores the Aztec details.
  

## Typedefs

```cpp
typedef struct tagAztecDetails  AztecDetails
```  
---
## Attributes
  
| Attribute | Type |
|---------- | ----------- | 
| [`moduleSize`](#modulesize) | *int* |
| [`rows`](#rows) | *int* | 
| [`columns`](#columns) | *int* |
| [`layerNumber`](#layernumber) | *int* |
| [`reserved`](#reserved) | *char\[32\]* |
  
  
### moduleSize
The barcode module size (the minimum bar width in pixel).
```cpp
int tagAztecDetails::moduleSize
```  
   
### rows
The row count of the barcode.
```cpp
int tagAztecDetails::rows
```  

### columns
The column count of the barcode.
```cpp
int tagAztecDetails::columns
```  

### layerNumber
A negative number (-1, -2, -3, -4) specifies a compact Aztec code. A positive number (1, 2, .. 32) specifies a normal (full-rang) Aztec code.  
```cpp
int tagAztecDetails::layerNumber
```  

### reserved
Reserved memory for the struct. The length of this array indicates the size of the memory reserved for this struct.  
```cpp
char tagAztecDetails::reserved[32]
``` 