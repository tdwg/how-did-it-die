### Proposal for vitality as a new term, using the required template ###

* Submitter:
Sophia Ratcliffe

* Efficacy Justification (why is this term necessary?):
There is a requirement that species records express whether the organism was dead or alive at the time of the observation or collection. Currently no such explicit term exist in Darwin Core.

* Demand Justification (name at least two organizations that independently need this term):
  - NBN Trust
  - Ocean Biodiversity Information System (OBIS)
  - The Field Museum
  
* Stability Justification (what concerns are there that this might affect existing implementations?):
  None
  
* Implications for dwciri: namespace (does this change affect a dwciri term version)?:


Proposed attributes of the new term:

[Details here: https://github.com/tdwg/how-did-it-die/issues/1]

* Term name (in lowerCamelCase for properties, UpperCamelCase for classes): 
  `vitality`
  
* Organized in Class (e.g., Occurrence, Event, Location, Taxon): 
  `Occurrence`
  
* Definition of the term (normative): 
  An indication of whether the organism was alive or dead at the time of collection or observation

* Usage comments (recommendations regarding content, etc., not normative): 
  Generally intended to be used with a `dwc:basisOfRecord` of `PreservedSpecimen`, `MaterialSample`, or `HumanObservation`.

* Examples (not normative): 
  alive, dead, unable to determine. [Definitions can be found here: https://github.com/tdwg/how-did-it-die/issues/6]

* Refines (identifier of the broader term this term refines; normative): 
  None
  
* Replaces (identifier of the existing term that would be deprecated and replaced by this term; normative): 
  None
  
* ABCD 2.06 (XPATH of the equivalent term in ABCD or EFG; not normative):
