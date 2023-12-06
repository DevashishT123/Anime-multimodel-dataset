# Anime-multimodel-dataset
### Dataset link - https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020

## Extracting Data from Datasets

The extraction process utilizes Beautiful Soup. Additional details on data extraction are outlined within this notebook.

## Context
This dataset encompasses information regarding anime characters, including their names, images, and associated links.

## Content
The data is structured into three components:

1. `animelinks.csv`: This file comprises approximately 73,000 links directing to pages featuring various anime characters.
2. `animenames.csv`: This file contains around 71,000 names of anime characters, excluding those with non-ASCII characters.
3. `finalnames.csv`: This file consists of names of anime characters, ensuring they contain only ASCII characters. (For instance, names like RaoulMathiasJeanAimÃ©e are excluded.)

Moreover, the dataset folder encompasses over 58,000 images of anime characters, with filenames corresponding to their character names.

## Usage
The dataset serves various purposes, such as:

- **For Anime Enthusiasts**: Utilize images from the dataset folder as desktop wallpapers.
- **Web Scraping**: Employ `animelinks.csv` for web scraping to extract further features of anime characters (a favorite activity for true anime enthusiasts).
- **Generating New Content**: Utilize `animenames.csv` to create new names for anime characters or use dataset images to generate new anime character visuals.
- **Creating New Characters**: The goal is to combine information from `animenames.csv` and `finalnames.csv` to craft a brand-new anime character with a unique name—a thrilling prospect!
  


