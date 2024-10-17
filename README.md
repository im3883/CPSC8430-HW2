# Running Instruction

1. Download the github repository to the target machine
2. install the gdown module by running the command 'pip install gdown'. The main python file uses this module to download the trained model from google drive
3. Run the script like below command-
   ./hw2_seq2seq.sh your_test_data_path your_output_file_name.txt
4. If you get permission error when running hw2_seq2seq.sh, run 'chmod +x hw2_seq2seq.sh' command to set the execute privilege
5. Please make sure the your_test_data_path contains the feat, video, id and a testing_label.json file
