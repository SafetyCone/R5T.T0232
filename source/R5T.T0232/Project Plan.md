# R5T.T0232
Framework-typed, catch-all, location-aware types for the netstandard2.1 platform, with no associated functionality or independent associated functionality not even dependent on R5T.L0066.


## Allowed Dependencies

The only allowed dependencies are:

	* netstandard2.1
	* R5T.T0142 - Type marker attributes.


## How this library works

If you have an idea for a type, put it in the specific project you are working on.
If you have an idea for a type, and you want to site it in a library to make it commonly accessible, follow the waterfall in the "How To" file for siting types.
If you have an idea for a type, you want it somewhere commonly accessible, and following the waterfall in the "How To" file for siting types doesn't yield an answer, create a new library for the type, and make a new entry for it in the right place in the types waterfall.
If you have an idea for a type, you want it somewhere commonly accessible, and you don't want to think through siting the type at *all* (either selecting the right library, creating a new library, or putting it one of the a target framework-specific catch-all type library, and it might be complicated with associated functionality)... but the type has dependencies other than on just the netstandard2.1 target framework, or it has associated functionality that is not independent (even if only dependent on R5T.L0066) put it in R5T.T0238.

Put differently, this library contains any type, that depends on any type, for any of its functionality, that has not been sited in any other library for any reason, as long as that type targets netstandard2.1 and has no associated functionality, or has independent associated functionality (independent even of R5T.L0066).


## Contents




## See Also

In reverse waterfall order:

* R5T.T0238: Catch-all types library at the bottom of the waterfall.
* R5T.T0237: Catch-all types library, for types limited to targeting netstandard2.1.
* R5T.T0221: Catch-all for types targeting netstandard2.1, but with associated functionality dependent on R5T.L0066.
=> R5T.T0232: Catch-all for types targeting netstandard2.1, but with no associated functionality or with independent associated functionality (independent even of R5T.L0066).
* R5T.T0236: catch-all for IHasX/IWithX strictly-framework (netstandard2.1) types with no associated functionality.