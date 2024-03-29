## Outline of the causeOfDeath_extension ##

Expected to be used with the core property `vitality`.

### causeOfDeath ###

|  |  |
| --- | --- |
| Definition | The primary or immediate disease or condition resulting in the death of the organism  | 
| Format 	| Text | 
| Constraints 	|  Controlled vocabulary, see https://docs.google.com/spreadsheets/d/14FWRqdUVZUcG-Uln8-PQ8VRkAnP5Vcka65gN-YWldBc/edit and https://docs.google.com/document/d/1Qf-RdsHtUaEb2g1ESBpa4g7vYCwxiovSkj6sUAF0CiM/edit | 
| Notes 	| Expected to be used with the `causeOfDeathClass` term | 

### causeOfDeathClass ###

|  |  |
| --- | --- |
| Definition | The classification of primary or immediate disease or condition resulting in the death of the organism  | 
| Format 	| Text | 
| Constraints 	|  Controlled vocabulary: Natural - abiotic, Natural - biotic, Anthropogenic or Unknown. See https://docs.google.com/spreadsheets/d/14FWRqdUVZUcG-Uln8-PQ8VRkAnP5Vcka65gN-YWldBc/edit and https://docs.google.com/document/d/1Qf-RdsHtUaEb2g1ESBpa4g7vYCwxiovSkj6sUAF0CiM/edit | 

### underlyingCausesOfDeath ### 

|  |  |
| --- | --- |
| Definition |  Any underlying or secondary diseases, conditions or circumstances leading directly to death of the organism | 
| Format 	| Text | 
| Constraints 	|  None |

### vitalityRemarks ### 

|  |  |
| --- | --- |
| Definition |  Comments or notes on the conditions contributing to the death | 
| Format 	| Text | 
| Constraints 	|  None | 

### deathDate ###

|  |  |
| --- | --- |
| Definition |  The date the organism died | 
| Format 	| Date | 
| Constraints 	|  ISO 8601 date format, resolved to day, month or year | 
| Notes |  Date ranges are allowed. |

 - use the `deathDateNotes` property when date is unknown
 - use the Geological context Darwin Core terms for date of death in the case of prehistoric records
 - use `preservationDate` for `MaterialSamples`

### deathDateNotes ### 

|  |  |
| --- | --- |
| Definition |  A comments or notes on the date of death | 
| Format 	| Text | 
| Constraints 	|  None | 

