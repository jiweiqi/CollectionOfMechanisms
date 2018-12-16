# CollectionOfMechanisms
This repo is a collection of existing combustion reaction mechanisms.

Below are the proposed data orgnization structure.

/fuel name
	/readme.md (List of avaliable mechanisms)
	/Mechanism abbr. (e.g., GRI30 for methane)
		/chem.inp (chemkin format)
		/thermo.dat
		/tran.dat
		/chem.xml (centera format)
		/readme.md
			+ how to cite?
			+ link to the origional papers
			+ original link for downloading the mechanisms

/mechanism for mixture (e.g., Aramoco mechanism)
