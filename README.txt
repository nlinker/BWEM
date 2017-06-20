This is a fork of BWEM. See src/examples.cpp for how to use.

See http://BWEM.sourceforge.net for original documentation.

API Changes from stock BWEM

OnDestroy for Minerals and Static Buildings has been combined.
Here is how to call it somewhere in your onUnitDestroy:
theMap.OnDestroy(unit);

All "ressources" spellings have been corrected to resources.
