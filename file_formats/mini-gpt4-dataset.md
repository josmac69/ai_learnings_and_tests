# Mini GPT4 Dataset

The Mini-GPT4 dataset involves a two-stage preparation process, each having different file formats:

1. **First stage dataset:** The first stage dataset comes from filtered Conceptual Captions, SBU, and LAION datasets. These datasets are downloaded as `.json` files, namely `ccs_synthetic_filtered_large.json` and `laion_synthetic_filtered_large.json`. They are then moved to designated dataset folders, namely `cc_sbu` and `laion` within your specified `MINIGPT4_DATASET` directory.

   Scripts for conversion and downloading, `convert_cc_sbu.py`, `download_cc_sbu.sh`, `convert_laion.py`, and `download_laion.sh`, are also copied to their respective dataset folders. These scripts are used to convert the `.json` annotation files to `img2dataset` format and download the datasets. This results in `.tsv` files (`ccs_synthetic_filtered_large.tsv` and `laion_synthetic_filtered_large.tsv`) and dataset folders (`cc_sbu_dataset` and `laion_dataset`) containing `.tar` and `.parquet` files【15†source】【16†source】【17†source】【18†source】【19†source】【20†source】.

2. **Second stage dataset:** The second stage dataset is a collection of images arranged in a specific directory structure. Upon extraction, the dataset is organized in a `cc_sbu_align` folder, which contains a `filter_cap.json` file and an `image` directory. The `image` directory then contains numerous image files, such as `2.jpg`, `3.jpg`, and so forth. This folder can be placed in any path you prefer, and the path must be specified in the dataset configuration file【9†source】.

Therefore, the Mini-GPT4 dataset consists of a variety of file formats, including `.json`, `.jpg`, `.tsv`, `.tar`, and `.parquet` files, all organized in specific directory structures. The scripts provided help convert and prepare these files for training the model.
