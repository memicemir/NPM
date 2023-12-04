# NPM

Nitrogen Prescription Model (NPM) version 2 for DSSAT crop growth models.

NPM tool for DSSAT crop growth models.

1. The "NPM_v2.7z" file has to be unzipped (with 7-zip). 

2. Unzipped "NPM_v2" directory copied to the DSSAT Tools directory "C:\DSSAT48\Tools". 

3. In folder "NPM_v2" ("C:\DSSAT48\Tools\NPM_v2")  ->NPM_v2.exe<- executed as Administrator.

4. More detailed instructions can be found in user guidelines!


<pre>
├── C:/DSSAT48
│   ├── Genotype
│   ├── Pest
│   ├── Maize
│   ├── Wheat
│   ├── Soil
│   ├── ...	
│   └── Tools
│       ├── GBuild
│       ├── XBuild
│       ├── ...
│       └── NPM_v2
│           ├── ...
│           └── NPM_v2.exe	

After executing "NPM_v2.exe" a working directory "NitrogenPrescriptionWorkspace" is created in "Tools" directory where optimization is conducted and optimization output files saved:

├── C:/DSSAT48
│   ├── Genotype
│   ├── Pest
│   ├── Maize
│   ├── Wheat
│   ├── Soil
│   └── Tools	
│      ├── ...	
│      └── NitrogenPrescriptionWorkspace
│          ├── *.*X (File X used for N sensitivity analysis)
│          ├── N-reatesHarvestedYield-Optimums.txt
│          ├── ...
│          ├── *_boxPlot.png	
│          └── PlantGro.OUT
</pre>

NPM related publications:

Memic E., Trenz J., Heshmati S., Graeff S. Evaluation of crop model-based marginal net return maximising nitrogen application retes on site-specific level in maize. In Precision Agriculture '23 Proceedings of European Conference on Precision Agriculture, Bologna, Italy, 2 July 2023; John V. Stafford, Ed.; Wageningen Academics Publishers: Wageningen, The Netherlands, 2023. https://doi.org/10.3920/978-90-8686-947-3


NPM_v2 is a new version of the NPM model published in:

"Memic, E., Graeff, S., Claupein, W. et al. GIS-based spatial nitrogen management model for maize: short- and long-term marginal net return maximising nitrogen application rates. Precision Agric 20, 295–312 (2019). https://doi.org/10.1007/s11119-018-9603-4"


