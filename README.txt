**Hadoop and Spark need to be installed. 

For Hadoop:
The core-site.xml file 'value' needs to be set to: hdfs://localhost:9000


For preprocessing notebook:
- The correct folders need to be used for the dataset and the cropped dataset
- The path for the train and test files needs to be edited 


For BDP Final notebook:
The following libraries need to be installed to run the jupyter notebook:
- pyspark
- skimage
- sklearn
- tensorflow
- keras
- os
- math
- numpy
- pandas
- matplotlib
- pathlib
- PIL (Pillow)
 

Specify directory to os.chdir path in jupyter notebook:
os.chdir("Insert_path_here")


The following files/folders need to be placed in the above mentioned directory:
- models folder
- images_flatten.txt
- test_sequence_length_12_months_ahead_1.txt
- test_sequence_length_12_months_ahead_2.txt
- test_sequence_length_12_months_ahead_3.txt
- test_sequence_length_4_months_ahead_1.txt
- test_sequence_length_4_months_ahead_2.txt
- test_sequence_length_4_months_ahead_3.txt
- test_sequence_length_8_months_ahead_1.txt
- test_sequence_length_8_months_ahead_2.txt
- test_sequence_length_8_months_ahead_3.txt
- train_sequence_length_12_months_ahead_1.txt
- train_sequence_length_12_months_ahead_2.txt
- train_sequence_length_12_months_ahead_3.txt
- train_sequence_length_4_months_ahead_1.txt
- train_sequence_length_4_months_ahead_2.txt
- train_sequence_length_4_months_ahead_3.txt
- train_sequence_length_8_months_ahead_1.txt
- train_sequence_length_8_months_ahead_2.txt
- train_sequence_length_8_months_ahead_3.txt

