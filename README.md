# DocTag-Data-Preprocessing-LongEval
Jupyter notebook scripts to preprocess the LongEval challenge data and create the configuration files for user annotation in Doctag (https://github.com/DocTAG/doctag-core)

1) Data available at https://clef-longeval.github.io/ Download the data and place the "publish" folder in the same folder of the Jupyter scripts

2) Need to create a stratified-pool-train-1.txt file with the queries-ID / document-ID and locate in the LongEval\publish\English or LongEval\publish\French folder
q06221312 doc062200205703
q06221312 doc062200111415
q06221312 doc062200108501
q06221312 doc062200111301

3) Need the queries_description.txt file with the queries-ID / queries description in the LongEval\publish\English\Queries or LongEval\publish\French\Queries folder
q06223196	      Car shelter
q062228	        airport
q062287	        antivirus comparison
q06223261	      free antivirus
q062291	        orange antivirus

4) Launch the notebook. Location of the files can be changed in the notebook. You will have as result 3 outputs: collection, run, topics, to be uploaded in Doctag (see tutorials in the platform). Labels file must be created manually
