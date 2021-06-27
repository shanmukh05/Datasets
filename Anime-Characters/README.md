# [Go to Dataset](https://www.kaggle.com/shanmukh05/anime-names-and-image-generation)

## Dataset Extraction
- `Beautiful Soup` is used.

More details of Data Extraction can be found in [this notebook](https://github.com/shanmukh05/Datasets/blob/main/Anime-Characters/extract-anime-images.ipynb)

## Context
Following dataset contains the names, images and links of anime characters.

## Content
Data contains 3 parts.
- `animelinks.csv` file contains the links to all anime characters pages present in above mentioned site. There are around `73000 links`. (That's a huge family xd😅 ).
- `animenames.csv` file contains the names of all anime characters excluding the one's with characters other than ascii in them (You can include them by editing `anime-links.csv`.). There are around `71000 names`. (Those 2000 characters have a very complex names lol👀 , sorry if you are a fan of one of them🙁)
- `finalnames.csv` file contains the names of anime characters but not with names having the characters other than ASCII (eg: `RaoulMathiasJeanAimÃ©e` )
- dataset folder contains all the images of anime characters(over `58000 images` are present) with name of file as it's character name.

## Usage
Well the data can be used in many ways, Some of the ways are
- If you are an anime fan, you can use images in dataset folder as desktop wallpaper😄.
- `animelinks.csv` can be used for web scraping to extract other features of anime characters (True anime lover will do this😄)
- `animenames.csv` can be used to generate new anime character names.
- dataset images can be used to generate new anime images.
- My target is to combine 2,3 and create a new anime character with a new name. (Very exciting right💥)

If you find any other usage, kindly inform me , we can work on that together🙏

## Acknowledgements
All the data is extracted from [Anime and Manga](https://myanimelist.net/character.php)
