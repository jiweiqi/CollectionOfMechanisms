# CollectionOfMechanisms

This repo is a collection of existing combustion reaction mechanisms.

Below are the proposed data organization structure.

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
    

See the demo folder for DME_CH3OCH3.

If you have any questions regarding including new mechanisms into the repo, feel free to contact me at jwq14@mails.tsinghua.edu.cn.

If you don't want a mechanism to be shown in the repo, just send me an e-mail and I will remove it and record it at this page, so that other people won't put it here in the future. 

useful tips for converting chemkin mechanisms to cti mechanisms. https://chemicalkinetics.wordpress.com/2013/11/15/my-procedure-for-converting-chemkin-mechanisms-to-cantera-cti-mechanisms/
