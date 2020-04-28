---
layout: default-layout
sideHeader: Enumerations
sourceCodeUrl: /parameters/reference/enums/frame-decoding-enums.md
sidebarListFile: sidelist-enums
needCollapsedSideBar: true
needAutoGenerateSidebar: false
---


# Dynamsoft Barcode Reader Enumeration - Frame Decoding Enumeration

  | Enumeration | Description |
  |-------------|-------------|
  | [`ClarityCalculationMethod`](#claritycalculationmethod) | Describes the clarity calculation method. |
  | [`ClarityFilterMode`](#clarityfiltermode) | Describes the clarity filter mode. |
  
---

## ClarityCalculationMethod
Describes the clarity calculation method.

### Declarations
   
| Language | Declaration |
| -------- | ----------- |
| C / C++ | `enum ClarityCalculationMethod` |
| .Net | `enum Dynamsoft.Barcode.EnumClarityCalculationMethod` |


### Members
   
| Member | Value | Description |
| ------ | ----- | ----------- |
| ECCM_CONTRAST | 0x01 | Calculates clarity using the contrast method. |


&nbsp;



## ClarityFilterMode
Describes the clarity filter mode 

### Declarations
   
| Language | Declaration |
| -------- | ----------- |
| C / C++ | `enum ClarityFilterMode` |
| .Net | `enum Dynamsoft.Barcode.EnumClarityFilterMode ` |


### Members
   
| Member | Value | Description |
| ------ | ----- | ----------- |
| CFM_GENERAL | 0x01 | Filters the frames using the general algorithm based on calculated clarity. |
