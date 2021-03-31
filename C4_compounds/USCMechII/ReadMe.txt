///////////////////////////////////////////////
The major issue when converting to cantera format is the encoding of the thermo data.

See. https://groups.google.com/forum/#!msg/cantera-users/ObncOfzPOFc/SEVFtwBOafwJ

This issue is caused by the fact that the thermdat.txt file begins with a UTF-8 BOM (byte order marker) even though it is just ASCII text. If you're using Windows, you can remove the BOM by opening the file in Notepad (which is probably the editor which introduced the unnecessary BOM in the first place), selecting "Save As", and setting the "Encoding" to "ANSI". The current development version of Cantera does not have this problem because ck2cti now automatically strips all non-ASCII values when reading the file.
///////////////////////////////////////////////


Downloaded from http://ignis.usc.edu/Mechanisms/USC-Mech%20II/USC_Mech%20II.htm


High-Temperature Combustion Reaction Model of H2/CO/C1-C4 Compounds

This  H2/CO/C1-C4 kinetic model (111 species and 784 reactions), applicable to a wide variety of combustion scenarios, incorporates the recent thermodynamic, kinetic, and species transport updates relevant to high-temperature oxidation of hydrogen, carbon monoxide, and C1-C4 hydrocarbons. This model was developed on the basis of


·        an optimized reaction model of H2/CO combustion

·        GRI-Mech1.2 and 3.0

·        a comprehensive reaction model of ethylene and acetylene combustion

·        reaction mechanism of C3 fuel combustion

·        1,3-Butadiene oxidation at high temperatures.

Also, the rate parameters of CO+OH, OH+HO2 and CO+HO2 were updated from more recent studies. Rate parameters of several C1 and C2 reactions were reevaluated.  The oxidation model of benzene and toluene is included.  

The reaction model was subject to validation tests against reliable H2/CO/C1-C4 combustion data.

How to cite

Hai Wang, Xiaoqing You, Ameya V. Joshi, Scott G. Davis, Alexander Laskin, Fokion Egolfopoulos & Chung K. Law,  USC Mech Version II. High-Temperature Combustion Reaction Model of H2/CO/C1-C4 Compounds. http://ignis.usc.edu/USC_Mech_II.htm, May 2007.