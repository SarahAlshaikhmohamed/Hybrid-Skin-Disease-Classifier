# HAM10000 Dataset Setup

This folder is used to store the HAM10000 dataset files required to run the notebooks in this project.

Download dataset from Kaggle and organize it as follows:

1. Go to the Kaggle dataset page:
   https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000

2. Download the following files:
   - `HAM10000_metadata.csv`
   - `HAM10000_images_part_1.zip`
   - `HAM10000_images_part_2.zip`

3. Unzip the image files and organize them like this:
data/
├── HAM10000_metadata.csv
├── HAM10000_images_part_1/
│ ├── ISIC_0024306.jpg
│ └── ...
├── HAM10000_images_part_2/
│ ├── ISIC_0033537.jpg
│ └── ...