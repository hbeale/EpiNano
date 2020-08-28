Raw data used to train the SVM models (i.e. m6A-modified and unmodified 'curlcakes') can be found at https://trace.ncbi.nlm.nih.gov/Traces/sra/?study=SRP174366

Reference sequences can be found in cc.fasta

We provide error and electric signal features extracted with Epinano_Variants and Epinano_Current_Intensity scripts.

We also provide **train_test.sh** with commands to train SVM models and test prediciton accuracies.

You can find in ../make_predicitons/run.sh how to prepare feature table for training and making predicitons. 


Have a look into **train_test.sh** and run it to get an idea of how to do training models. 

## files
*middleAs* means [GCT][GCT]A[GCT][GCT] kmers
All A-bases are modified from the mod samples.