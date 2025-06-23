# French-Wikipedia-Dataset

This dataset contains text extract from french Wikipedia articles.  
It has been created for the project Overton made by Naowak (Yannis Bendi-Ouis), you can find scrapping script in it.  

## Download

Git LFS restricts the download of large files, so the dataset has been moved to a Google Drive:  
https://drive.google.com/file/d/1J5BsFB2ST6KQzf3Kq8Nj_kSTcIOA4rUe/view?usp=sharing

## Details about the size of the datasets

98716 articles encoding in utf-8 are in that dump (last update 7th March 2023).
This dataset is 783.7Mo large.  
(More or less 800 books of 300 pages, each pages is 30 lines long and each line has 60 characters)  

## How was the scrapping made ?

The script start from a link that refer to a category.  
The script retrieve all articles in that category (N=0), then it retrieves all articles in children categories (N=1), ...  
You can find all categories for french Wikipédia here : https://fr.wikipedia.org/wiki/Catégorie:Accueil

## Selected categories

| Name | N | Link |
|:-------------|:-------------:|:-----|
| Science Politique | 3 | https://fr.wikipedia.org/wiki/Catégorie:Science_politique |
| Idéologie Politique | 3 | https://fr.wikipedia.org/wiki/Catégorie:Idéologie_politique |
| Politique en France | 3 | https://fr.wikipedia.org/wiki/Catégorie:Politique_en_France |
| Politique | 2 | https://fr.wikipedia.org/wiki/Catégorie:Politique |
| Société | 2 | https://fr.wikipedia.org/wiki/Catégorie:Société |
| Sciences | 2 | https://fr.wikipedia.org/wiki/Catégorie:Science |
| Technologies | 2 | https://fr.wikipedia.org/wiki/Catégorie:Techniques_et_sciences_appliquées |
| Arts | 2 | https://fr.wikipedia.org/wiki/Catégorie:Art |


## License
This project is licensed under the MIT License with an Acknowledgment Clause. See LICENSE for more information.

Scraped by Yannis Bendi-Ouis.
Website: https://www.naowak.fr/
