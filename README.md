# DAFLFQA
The repository of article “DAFLFQA：Dual Attention Fusion for Light Field Quality Assessment” 

Since the paper is currently in the review stage, only the code for reproducing the core data and the compiled binary files for direct execution are available in the repository.

The specific code details will not be disclosed for the time being, but this will not affect the reproduction of the paper's results.

All code details will be made public once the paper is published.

The code will be updated simultaneously with the publication of the paper.

This repository includes scripts, networks, and segmented datasets, which can be accessed via the following three links respectively:

- Network: Nets 
  Link: https://pan.baidu.com/s/1EGj44ylCqNWHqLiXj5_QsA?pwd=3yi2 
  Extraction code: 3yi2

- Dataset: Dataset 
  Link: https://pan.baidu.com/s/19ST7sunaqZDd1cEaik--pg?pwd=45ra 
  Extraction code: 45ra

- Script: Script 
  Link: https://pan.baidu.com/s/1tds_3v1zA3vvsHKBP9aJqQ?pwd=kezt 
  Extraction code: kezt

The script contains the necessary components to reproduce the results in Table 2 of the paper. Simply run it and you will obtain the same results as those in the paper.

As the binary executable files have been packaged, there is no need for additional environment configuration. You can directly download them and run the following commands:

The script includes both binary files and newly written scripts, and you can choose either one to run.

For example, to execute the binary executable file, use the following command:

```cpp
./core_tester your_weights_path your_dataset_path
```

Alternatively, you can run the written script.

```cpp
python run_test.py your_weights_path your_dataset_path
```
