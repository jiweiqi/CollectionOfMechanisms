# CollectionOfMechanisms
This repo is a collection of existing combustion reaction mechanisms. This repo also tries to include a converted Cantera .xml based mechanism. Therefore, cantera users can import those mechanism out of the shelf.

Below are the proposed data organization structure. See the demo folder for DME_CH3OCH3.

    /fuel name
    	/readme.md (List of avaliable mechanisms)
    	/Mechanism abbr. (e.g., GRI30 for methane)
    		/chem.inp (chemkin format)	
    		/thermo.dat
    		/tran.dat
    		/chem.xml (cantera format)
			/chem.cti (cantera format, optionally)
    		/readme.md
    			+ how to cite?
    			+ link to the origional papers
    			+ original link for downloading the mechanisms
    

## Useful links

[Useful tips for converting chemkin mechanisms to cti mechanisms](https://chemicalkinetics.wordpress.com/2013/11/15/my-procedure-for-converting-chemkin-mechanisms-to-cantera-cti-mechanisms/)

[Mechanisms from Lawrence Livermore National Laboratory (LLNL)](https://combustion.llnl.gov/mechanisms)

[Mechanisms Collected on Cefac Cantera Manual](https://www.cerfacs.fr/cantera/mechanisms/meth.php#)

[Mechanisms collected on Explosion Dynamics Laboratory of CalTech](https://shepherd.caltech.edu/EDL/PublicResources/sdt/cti_mech.html)
