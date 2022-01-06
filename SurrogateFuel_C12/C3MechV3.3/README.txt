C3MechV3.3 - Published by the Computational Chemistry Consortium (https://fuelmech.org/)

Citation:
Dong S, Wagnon SW, Pratali Maffei L, Kukkadapu G, Nobili A, Mao Q, Pelucchi M, Cai L, Zhang K, Raju M, Chatterjee T, Pitz WJ, Faravelli T, Pitsch H, Senecal PK, Curran HJ. A new detailed kinetic model for surrogate fuels: C3MechV3.3. Applications in Energy and Combustion Science 2022.

https://doi.org/10.1016/j.jaecs.2021.100043

N.B. This directory contains the published CHEMKIN-formatted files (C3MechV3.3.MECH-ORIGINAL, C3MechV3.3.THERM, C3MechV3.3.TRAN) and a Cantera 2.5+ YAML formatted version of the mechanism.
The mechanism was converted with the `--permissive` option, which resulted in duplicated thermodynamic entries defaulting to the first appearance (see `convert_log.txt`).
The `DUPLICATE` keyword was added to four reactions in the mechanism file, C3MechV3.3.MECH, to pass validation once converted to Cantera format (lines 63750, 63764, 63769, and 63789).
These modifications should have no effect on the CHEMKIN mechanism file, but an unaltered version is retained as C3MechV3.3.MECH-ORIGINAL.
