---
layout: default-layout
sideHeader: C Methods
sourceCodeUrl: /programming/c-cplusplus/api-reference/c-api/initialize-and-destroy.md
sidebarListFile: sidelist-c-methods
needCollapsedSideBar: true
needAutoGenerateSidebar: false
---


# C API Reference - Initialize and Destroy Methods

  | Method               | Description |
  |----------------------|-------------|
  | [`DBR_CreateInstance`](#dbr_createinstance) | Create an instance of Dynamsoft Barcode Reader. |
  | [`DBR_DestroyInstance`](#dbr_destroyinstance) | Destroy the instance of Dynamsoft Barcode Reader. |
  
  ---
  
   




## DBR_CreateInstance
Create an instance of Dynamsoft Barcode Reader.


```c
DBR_API void* DBR_CreateInstance ()	
```   

#### Return value
Returns an instance of Dynamsoft Barcode Reader. If failed, returns NULL.


#### Remark
Partial of the decoding result will be masked with "\*" without a valid license key.

#### Code Snippet
```c
void* barcodeReader = DBR_CreateInstance();
DBR_InitLicense(barcodeReader, "t0260NwAAAHV***************");
DBR_DestroyInstance(barcodeReader);
```


&nbsp;





## DBR_DestroyInstance
Destroy the instance of Dynamsoft Barcode Reader.

```c
DBR_API void DBR_DestroyInstance (void* barcodeReader)	
```   
   
#### Parameters
`[in]	barcodeReader` Handle of the barcode reader instance.

#### Code Snippet
```c
void* barcodeReader = DBR_CreateInstance();
DBR_InitLicense(barcodeReader, "t0260NwAAAHV***************");
DBR_DestroyInstance(barcodeReader);
```

