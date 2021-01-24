# References

You can create anchors and references to anchors inside of snekdown documents with the following syntax:



Anchor: `[?KEY]`


*renders as*


[?TestRef]



Reference: `[Description](#KEY)` (classic url syntax)


*renders as*


[Description](#TestRef)



Anchors don't render in the document but References to anchors do.
There's currently no validation if a reference is valid so make sure to use the correct keys.
