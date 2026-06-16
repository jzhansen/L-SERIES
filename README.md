                        
				 JORGE ZUNIGA. (2026) L-SERIES WZ PROOFS
				   
    MAPLE 2026 FILES "L-SERIES-2026.TXT" AND/OR "L-SERIES-2026.MW".
	
    DIRECTIONS FOR BUILDING, LOADING & EXECUTING TO GET Wilf-Zeilberger PROOFS OF 
	L-SERIES IDENTITIES FROM ARTICLE "Fast Computing Formulas for some Dirichlet L-Series"
	ArXiv:2601.12495 [math.NT], Jorge Zuniga 2026:
	
 1.- DOWNLOAD MAPLE FILE "CreativeTelescoping.mla" from this link
 
    https://github.com/HBrochet/CreativeTelescoping/blob/main/CreativeTelescoping.mla
	
 2.- DOWNLOAD MAPLE FILE "Mgfun4.1.mla" from this link
 
    https://specfun.inria.fr/chyzak/Mgfun4.1.mla
	
 3.- Add both .mla files to the directory maple20XX/lib/
 
    You can either stop here and get all required files from this GitHub repository or 
	continue to get the necessary Maple script files from a large comment in the TeX 
	file downloaded from [ArXiv:2601.12495](https://arxiv.org/src/2601.12495) repository. 
	Follow these directions:	
 
 4.- CUT LAST COMMENT SECTION (FROM ArXiv TeX FILE) AND PASTE IT INTO ANY OF THESE TWO OPTIONS:
	
 5.- OPTION 1:
 
    A TEXT FILE "L-SERIES-2026.TXT" AND SAVE IT IN WORKING DIRECTORY, SAY \MyFile
	
 6.- EXECUTE THIS MAPLE WORKSHEET with the COMMANDS
 
    restart; read("\myFile\L-SERIES-2026.TXT");
	
 7.- OPTION 2 (TO TAKE MORE CONTROL):
 
    A WHITE MAPLE WORKSHEET, INSERTING MAPLE PROMPTS IF YOU WANT TO SPLIT PROOFS.
	
 8.- SAVE AS A MAPLE .MW FILE AS \myFile\L-SERIES-2026.MW AND EXECUTE IT.
 
    HAVE A NICE EXPLORATION !!
