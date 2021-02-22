11:21:58     From  3. William Ulate : "Was death recent?" seems subjective

11:25:04     From  1. Pieter Huybrechts (MeiseBG) : @William Ulate: I agree, I think a date range seems more suitable. "Was death recent" could be closer as " what death co-temporary with the observation", but that would still be subjective. 

The goal of the field would be to be able to filter out observations that are distent enough in time in that they wouldn't match environemental parameters anymore. This could still be useful if the time of death is not encoded, or encoded in a free text field. 

11:29:30     From  3. William Ulate : @Pieter Fully agree, very useful.  I'm just saying that the Boolean would be hard to interpret.  A range might work better: "it must've died in the last week"

11:31:54     From  Paula Zermoglio : From what I hear, it would seem that we are talking about several different terms, if so, would it be reasonable to think of a DwC extension? not sure how many extra fields would justify building an extension

11:32:56     From  1 TDWG Executive (Quentin Groom) : Indeed, though perhaps a mix of core terms and extension, but perhaps there is a geological extension already

11:32:58     From  2Mary kennedy : Perhaps 'Vitality' needs to have fields that address HOW, WHY, WHEN. how did it die? roadkill; Why? (underlying disease); when - date of death versus date of observations

11:35:03     From  3. William Ulate : I like the idea that the vitality (dead or alive) is an attribute of the organism, but the cause of death is not... 

11:35:22     From  1. Pieter Huybrechts (MeiseBG) : I would plead for a date of death that is an absolute point or range in time, rather than an integer unit of time passed before the observation. Rather 1st feb 2018 than 2 years ago. 


11:36:35     From  Arthur Chapman (Australia) : I would think the time of death is a difficult topic, and can range from short (minutes) to decades or eons (the latter overlapping geological/fossils etc.)  If one uses an ISO Date range - that could be massive (e.g. for a dead tree - which could have a very long date range).  Perhaps some of this is best to put in remarks (dwc:occurenceRemarks?

11:37:03     From  3. William Ulate : Real use cases tell us if we are overcomplicating the modeling or not

11:37:16     From  Paula Zermoglio : I like How did it die

11:37:17     From  1 TDWG Executive (Quentin Groom) : +1

11:37:21     From  1. Pieter Huybrechts (MeiseBG) : I would love to continue this discussion on GitHub, I feel the data in a remarks field would be hard to extract

11:37:21     From  Christian Köhler (ganzgraph, Bonn) : +1

11:37:28     From  Janeen Jones : There is nothing stopping us from having both an iso date and a range field of time span.

11:38:24     From  Arthur Chapman (Australia) : How Did it Die? or "How and When Did it Die"?

11:38:52     From  3. William Ulate : EoL: End of Life


11:40:32     From  3. William Ulate : I see we talk about Dead or Alive, do we have to consider registering "Dying"?

11:41:56     From  Arthur Chapman (Australia) : Following Paula's comment.  A mix of CORE and Extension.  Vitality could be core but much of the other could be better managed as an Extension for the much smaller group of observers that would want to use it.  You don't want to put something in CORE that only 1 case in thousands would need or use.

11:44:10     From  Nicolas Noé : Agree with this core/extension distinction also because vitality is really an attribute of the occurrence, while the rest (when / how / certainty / …) are attributes of a different entity (the death itself)

11:46:10     From  2Mary kennedy : 'dying' --> the indiv is alive at time of observation.
