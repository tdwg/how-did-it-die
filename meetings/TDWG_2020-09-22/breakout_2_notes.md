# Notes from Breakout 2 #

## Issues and discussion points ##
Footprints, scat etc → evidence that an animal was alive at some point but not at the observation TIME
Roadkill/windowkill → example of animal dead at location and time of observation
Shell on a beach → evidence that an individual was alive somewhere in the vicinity…
Dying → this is related to ‘health’. It is still ALIVE at the time of observation. Can add another observation when the animal is dead.


## Use Cases: What are they? ##
Uses cases: Examples: iNat has many examples of not just alive/dead but also ‘evidence’ (scat, feathers, shells, molt skin, etc); marine datasets - dead and dying whales on beaches; Meise Botanic Garden: the living collections follow the status of the plants in the collection (dead / alive / condition) as well as the cause of death when the plant dies);

## Vitality: Is this a good name? ##
Darwin core already have dwc:reproductiveCondition The ability to reproduce is effectively showing its alive.
What is the definition?
Definition:
Refers to status of the specimen when it was originally observed/collected NOT its status as it sits in a jar or on a museum shelf(MK)
An organism that has a functional metabolism at the time of observation.
Need to separate how an animal was collected - need to separate sampling protocol - hunter/fisherman observed live animal before ‘death’
What should the controlled vocabulary be?
Alive, dead, unknown (this includes evidence of life); (MK - do we need an additional term for ‘evidence’)
“Unable to determine” - eg. seeds (CIH)
“Not applicable” - for things like footprints (CIH) |footprints provide ‘evidence’ of life at some point in time at that location.
Unknown is not the same as null (MK)
no recognizable vitality - for the edge cases?
What if an individual is dying - example whale on a beach (MK). It is ALIVE until DEAD 
Not related to dwc:samplingProtocol when an organism may have been killed during sampling

## Cause of death ##
What is the definition?
Description of how the individual died.
Death: An organism that does not has a functional metabolism at time of observation; not living
What should the controlled vocabulary be?
Natural, unnatural, unknown
Natural: old age, disease
Unnatural: roadkill, cat kill, window kill, hunting /trapping
Special cases: What are they?
Do we need date of death? 
Difficult to provide an exact date in a lot of cases
Fossils?
Restrictions on usage with other terms in Darwin Core
Basis of record
Lifestage (spores)
occurrenceStatus (present/absent/???)
Circumstantial evidence of presence
