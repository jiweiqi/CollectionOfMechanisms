# CollectionOfMechanisms

This repo is a collection of combustion reaction mechanisms.
This repo also tries to include a converted Cantera `YAML` format mechanism to
allow Cantera users to avoid the effort of repeatedly converting mechanisms.

Below is the proposed data organization structure.

```
Fuel Name
|
│   README.md: list of reaction mechanisms and brief introduction
│
└───Mechanism abbr. (e.g., GRI30 for methane)
│   │   chem.inp (chemkin format)
│   │   /thermo.dat
│   │   /tran.dat
│   │   /chem.yaml (cantera format)
│   │   /README.md: link to the original paper/website and any relevant comments (e.g. on mechanism conversion)
|
```

## Chemical Mechanism Resources

Resources published by kinetics groups (incomplete alphabetic list):

* [CaltechMech](https://www.theforce.caltech.edu/CaltechMech/)
* [CRECK Mechanisms](http://creckmodeling.chem.polimi.it/menu-kinetics/menu-kinetics-detailed-mechanisms)
* [Lawrence Livermore National Laboratory (LLNL) Mechanisms](https://combustion.llnl.gov/mechanisms)
* [NUI Galway Mechanisms](http://c3.nuigalway.ie/combustionchemistrycentre/mechanismdownloads/)
* [San Diego Mechanisms](http://web.eng.ucsd.edu/mae/groups/combustion/mechanism.html)
* [Stanford Mechanisms](https://web.stanford.edu/group/haiwanglab/)
* [UConn Mechanisms](http://spark.engr.uconn.edu/mechs/mechs.htm)

Other collections:

* [Cefac Cantera Manual](https://www.cerfacs.fr/cantera/mechanisms/meth.php#)
* [Explosion Dynamics Laboratory of CalTech](https://shepherd.caltech.edu/EDL/PublicResources/sdt/cti_mech.html)
* [ZhangYanTJU/chemicalMechanisms](https://github.com/ZhangYanTJU/chemicalMechanisms)

## Useful links

* [Converting Chemkin-format files](https://cantera.org/tutorials/ck2yaml-tutorial.html)
* [fitData_Cantera: fit thermo file to a uniform common T](https://github.com/ZhangYanTJU/fitData_Cantera)
