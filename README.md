# Differential Gene Expression Analyses using Raw Read Counts obtained from Bulk RNA Sequencing Methods of the Starlet Sea Anemone (Nemtostella vectensis) 

## This pipeline uses the PyDeSeq2 implementation to obtain meaningful data from raw read counts of RNA sequencing. The analysed data was then visualised using common bioinformatic visualisation tools like scanpy and bioinfokit. After visualising the data, a gene of interest was chosen and ran through a BLAST search via Python. The details of the highlighted gene were shown. 

### To execute the script; 
1. Download the Assignment.ipynb file and run it on Jupyterlab via Anaconda Navigator
2. Download and run all the necessary packages as per the script
3. Download the dataset attached herein (Raw_read_counts_NVe.csv)
4. The dataset has been published. Therefore, there are no issues with privacy.
5. Use the dataset to run the script
6. The dataset is in a comma-separated value format (csv: Microsoft Excel). So, loading the dataset should be done using a 'read csv' command (as per the script).
7. Several amendments can be made to the script for more filtering
   i. Cell 19: You can change the baseMean value.
   ii. Cell 21: You can change the padj value for a lower significance value and to a larger log2FoldChange to see which genes have a higher expression magnitude
8. Any other highly expressed gene can be selected for the BLAST search (Step 7).
9. Be sure to read in the proteome file (nve.fa) for the BLAST search step
10. This is to let you grab the full sequence of the gene of interest for the BLAST search 
  
