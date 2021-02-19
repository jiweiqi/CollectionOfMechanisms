# CollectionOfMechanisms

This repo is a collection of combustion reaction mechanisms. This repo also tries to include a converted Cantera `XML` and `YAML` based mechanism. Therefore, cantera users can import those mechanism out of the shelf.

Below are the proposed data organization structure. See the demo folder for DME_CH3OCH3.

```
Fuel Name
|
│   README.md: list of reaction mechanisms and brief introduction
│
└───Mechanism abbr. (e.g., GRI30 for methane)
│   │   chem.inp (chemkin format)
│   │   /thermo.dat
│   │   /tran.dat
│   │   /chem.xml (cantera format)
│   │   /chem.yaml (cantera format)
│   │   /chem.cti (cantera format, optionally)
│   │   /README.md: link to the origional paper/website
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

## Useful links

[Useful tips for converting chemkin mechanisms to cti mechanisms](https://chemicalkinetics.wordpress.com/2013/11/15/my-procedure-for-converting-chemkin-mechanisms-to-cantera-cti-mechanisms/)
