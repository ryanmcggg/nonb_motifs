# nonb_motifs

McGinty and Sunyaev – Supplementary Code -  README



System Requirements:

Anaconda installation of Python 3.8	64bit          	- https://www.anaconda.com/products/individual#Downloads
Additional Python libraries:
	Biopython SeqIO                               		- https://biopython.org/wiki/SeqIO
	Plotly			                                    	- https://plotly.com/python/getting-started/
	PyLiftover	  	                                	- https://pypi.org/project/pyliftover/
	Regex			                                       	- https://pypi.org/project/regex/

Tested on the following system:
Windows 10
128 Gb RAM
AMD 5800X processor
Python 3.8.8.final.0; pandas 1.2.4; numpy 1.20.1; biopython 1.79;
plotly 5.1.0; pyliftover 0.4; regex 2021.4.4; statsmodels 0.12.2


Installation guide:

Follow above instructions to install Anaconda and additional dependencies.
Typical install time: ~15 minutes


Instructions for use:

Open Jupyter Notebook.
Open “McGinty and Sunyaev, Supplementary Code.ipynb”
Further instructions are included within the notebook, including instructions for downloading required public datasets and creating directories.
Run each notebook cell in order.

Note: Table of contents section 1,  “Process sample dataset or full dataset?” contains instructions for running a demo version using only chromosome 22, or a full version on all 22 autosomes.

	To run the demo version, run cell containing “Sample dataset”
	Approximate run time: 1-2 days

	For full dataset, run cell containing “Full dataset (all autosomes)”
	Approximate run time: 1-2 weeks

Table of contents section 6, “Prepare gnomAD SNV database” accounts for a substantial portion of the run time. Depending on CPU and RAM limitations, this section can be run in parallel, by manually copying the notebook cell into additional notebooks and specifying individual chromosomes to process.


Expected output:
	Figures 2, 3a, 4a, 5a
	Supplementary Figures S1a, S1b, S2a, S2b, S2c, S2d, S3, S4, S5a, S6a, S6c, S5b

Note: output figures for demo version will resemble the manuscript figures, though will be substantially lacking in power.
