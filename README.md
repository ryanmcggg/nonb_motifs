# nonb_motifs

McGinty and Sunyaev – Supplementary Code -  README



System Requirements:

	Anaconda installation of Python 3.8	64bit   
					- https://www.anaconda.com/products/individual#Downloads  
	Additional Python libraries:  
		Biopython SeqIO			- https://biopython.org/wiki/SeqIO  
		Plotly				- https://plotly.com/python/getting-started/  
		PyLiftover			- https://pypi.org/project/pyliftover/  
		Regex				- https://pypi.org/project/regex/  
		Sty				- https://pypi.org/project/sty/  
	
	Tested on the following system:
		Windows 10  
		128 Gb RAM  
		AMD 5800X processor  
		Python 3.8.12.final.0; pandas 1.4.1; numpy 1.20.3; biopython 1.79;  
		plotly 5.6.0; pyliftover 0.4; regex 2021.8.3; statsmodels 0.12.2  


Installation guide:

Follow above instructions to install Anaconda and additional dependencies.  
Typical install time: ~15 minutes


Instructions for use:

Open Jupyter Notebook.  
Open “McGinty and Sunyaev, Supplementary Code – Revision 1.ipynb”  
Further instructions are included within the notebook, including instructions for downloading required public datasets and creating directories.  
Run each notebook cell in order.  

Note: Table of contents section 1,  “Process sample dataset or full dataset?” contains instructions for running a demo version using only chromosome 22, or a full version on all 22 autosomes.

	To run the demo version, run cell containing “Sample dataset”  
	Approximate run time: 1-2 days  

	For full dataset, run cell containing “Full dataset (all autosomes)”  
	Approximate run time: 1-2 weeks  

Table of contents section 6, “Prepare gnomAD SNV database” accounts for a substantial portion of the run time. Depending on CPU and RAM limitations, this section can be run in parallel, by manually copying the notebook cell into additional notebooks and specifying individual chromosomes to process.


Expected output:  
	All plots (.png images) included in the manuscript.  
	     (see: https://www.biorxiv.org/content/10.1101/2022.02.08.479604v1)  
	Various temporary or intermediate files and databases in compressed .csv or .pickle format.  

Note: output figures for demo version will resemble the manuscript figures, though will be substantially lacking in power.

Note: temporary files can be used to resume running from various points. (See: Table of contents sections marked as "save/load.")
