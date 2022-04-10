# Liquid-Biopsies-Project---KCL

File #1: Load and Combine VCF files (R script):

      a)Load each individual VCF file and convert it to a dataframe

      b)Load and combine each individual VCF

File #2: Install Annovar and Download Databases (Terminal script):

      a) Download Annovar and setup databases
      
      b) Download COSMIC 95 and prepare database from COSMIC files

File #3: Annotate Combined VCF from Step 1 using Annovar (Terminal script):
      
      a) Run Annovar on combined VCF files

File #4: Filter Variants in the Annotated VCF (R script):
      
      a) Load Annovar Annotated Combined VCF files 
      
      b) Generate MAF input for the somatic and germline variants

File #5: Convert VCF Files to MAF Files (Terminal script):
      
      a) Install Anaconda and VEP
      
      b) Run MAF to VCF file conversion for the somatic and germiline variants seperately 

File #6: Analyze Combined VCF & MAF Files and Plot Graphs (R script):
      
      a) Analyze MAF and VCF files
      
      b) Print statistics and plot graphs for each potential biomarker data
