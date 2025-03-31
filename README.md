README.md 

Hello! 
This GitHub repository contains my work for CM3070 Final Project (Fake News Detection). 

TO THE MARKER/GRADER, 

You are looking for:

product/main_pipeline_ver7.ipynb

That is the only file that relates to the final version of my codebase referenced in my report.
Please only launch that file. 

If you wish to run the codebase, please:
1. In cmd, run pip install -r product/requirements.txt
2. As WELFake_Dataset.csv file is excessively large, you may need to download WELFake_dataset.csv from this link: https://zenodo.org/records/4561253/files/WELFake_Dataset.csv?download=1
3. If you manually downloaded WELFake_Dataset.csv from the above link, move it to product/data/welfake_dataset
4. Run all cells in Jupyter Notebook. 

Other notable folders:

product/data - this directory contains the datasets used. 

product/data/isot_dataset - this directory contains ISOT dataset files (Fake.csv, True.csv)

product/data/liar_dataset - this directory contains LIAR dataset files (test.tsv, train.tsv, valid.tsv, README)

product/data/welfake_dataset - this directory contains WELFake dataset .csv, please note this file is quite large. 
