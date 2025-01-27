# Changelog




## izneo_get.py
### Version 0.09.03 (2021-12-16)
- [BUGFIX] Gestion des espaces en fin de nom de fichier. 

### Version 0.09.02 (2021-11-26)
- [NEW] Vérification de la version. 
- [CHANGE] Suppression d'un paramètre inutile. 
- [BUGFIX] Ajout compatibilité avec les tomes empruntés par médiathèque. 

### Version 0.09.00 (2021-06-07)
- [NEW] Ajout compatibilité avec les tomes empruntés par médiathèque. 

### Version 0.08.02 (2021-03-01)
- [BUGFIX] Gestion du cas quand il y a plus de 99 tomes. 

### Version 0.08.01 (2020-11-08)
- [BUGFIX] Gestion du cas des tomes non renseignés. 

### Version 0.08.0 (2020-10-05)
- [CHANGE] Script is blacked.
- [CHANGE] Disparition de l'option "--no-tree" qui devient le comportement par défaut. 
- [CHANGE] Apparition de l'option "--tree" qui permet de forcer la création des sous-répertoires. 
- [CHANGE] Compatibilité "webtoons".
- [BUGFIX] Le script déchiffre les images. 


## izneo_list.py
### Version 0.07 (2022-09-17)
- [CHANGE] La récupération d'albums ne peut se faire qu'à partir de l'URL d'une série. 
- [CHANGE] La recherche textuelle retourne les URL des séries. 

### Version 0.06 (2021-03-15)
- [CHANGE] Modification de la façon de récupérer les listes (corrige le problème avec les séries de plus de 40 tomes).


## izneo_infos.py
### Version 0.01 (2022-11-26)
- [NEW] Version initiale.

## izneo_get_selenium.py
### Version 1.04.0 (2020-10-04)
- [CHANGE] Récupération des images depuis les blobs.
- [CHANGE] Compatibilité "webtoons".

### Version 1.03.0 (2020-09-14)
- [BUGFIX] Compatibilité PIL version 7.

### Version 1.02.0 (2020-09-13)
- [BUGFIX] Erreur lorsqu'on donne un fichier contenant une liste d'URLs.

### Version 1.01.0 (2020-09-13)
- [CHANGE] Le fichier de config n'est plus écrasé. 
- [CHANGE] La recherche du binaire "chromebrowser*.exe" est désormais récursive. 

### Version 1.00.0 (2020-09-08)
- [NEW] Nouvelle version basée sur Selenium. 
- [CHANGE] Disparition de l'option "--no-tree" qui devient le comportement par défaut. 
- [CHANGE] Apparition de l'option "--tree" qui permet de forcer la création des sous-répertoires. 