# French-Wikipedia-Dataset

This dataset contains text extract from french Wikipedia articles.  
It has been created for the project Overton made by Naowak (Yannis Bendi-Ouis), you can find scrapping script in it.  

## Details about the size of the datasets

140317 articles are in that dump (last update 4th March 2023).  
It represents 935.832.354 characters encoding in utf-8.  
Which it's nearly 1GB large.  
(More or less 1000 books of 300 pages, each pages is 30 lines long and each line has 60 characters)  

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
