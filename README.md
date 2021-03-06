# Scraper books to scrape 


- Projet permettant de scraper de 3 manières différentes le contenu du site [https://books.toscrape.com](https://books.toscrape.com/).<br/>
- On récupère les données scrapées sous forme de fichiers **.csv**, et **.jpg**
<br/>



## Téléchargement et installation 


- copiez le dépôt distant, dans votre terminal/interpréteur. <br/>
	Vous allez dans le dossier ou vous souhaitez placer le projet.<br/> 
Exemple : ``cd C:\Users\damie\Documents\Python_Project``
- Puis ``git clone https://github.com/DamienZeh/scraper_le_site_books_to_scrape.git``
- Puis, allez dans ce projet : ``cd scraper_le_site_books_to_scrape\``
- On crée l’environnement virtuel avec  ``python -m venv env``<br/>
	_(‘env’ est le nom que j’ai sur mon environnement virtuel, il est aussi noté dans le gitignore.)_
- Puis activez le : ``.\env\Scripts\activate.bat`` (pour windows)<br/>
	_(Vous avez maintenant un ‘(env)’ d’affiché, l'environnement est activé)_
- Puis, l’installation  des packages (présent dans le requirements.txt): ``pip install -r requirements.txt``

<br/>


## Démarrage


### Basique

Lancez l’un des 3 fichiers python que vous souhaitez, avec la commande « **python fichier.py** ».<br/>
exemple : ``python Analyze_A_Product.py``

- **Analyze_A_Product.py** va donner toutes les informations d’un livre du site [https://books.toscrape.com](https://books.toscrape.com/).<br/> 
De base il donne des infos sur le livre [‘Sharp Objects’](https://books.toscrape.com/catalogue/sharp-objects_997/index.html).

- **Analyze_Products_From_Category.py** va donner toutes les infos de tous les livres d’une catégorie du site.<br/>
De base, il affiche les données de la catéorie [‘fantasy’](https://books.toscrape.com/catalogue/category/books/fantasy_19/index.html).

- **Analyze_All_Categories.py** va donner tous les livres et leurs informations de tout le site [https://books.toscrape.com](https://books.toscrape.com/)



### Avancé

Si vous souhaitez scraper d’autres liens dans le site, vous pouvez passer par un IDE, comme [**Pycharm**](https://www.jetbrains.com/fr-fr/pycharm/) :

- Lancez **Pycharm**
- Ouvrez le dossier **scraper_le_site_books_to_scrape**.<br/>
Puis pour activer l’environnement virtuel déjà présent dans le projet :<br/>
 ``File`` → ``Settings`` → ``Project : scraper_le_site_books_to_scrape`` → ``Python Interpreter`` → cliquez sur le lien -> ``Show All``, <br/>
``+``, et vérifier que ``Existing environnment`` est coché, et que le chemin va bien jusqu'au **python.exe** du projet,<br/>
 puis faire ``OK`` -> ``Apply`` -> ``OK``.

 



Puis ouvrez le fichier qui vous intéresse. Chaque fichier python, une fois exécuté vous donnera un dossier de sortie avec ses fichiers csv, et un dossier avec ses fichiers images de livres.<br/>
 _(les dossiers porteront le même nom que leur fichier python, plus '**__Csv**' ou '**__Images**' à la fin.)_ <br/>
Les 3 fichiers fonctionnent de la même manière. Le lien que vous voulez taper est à mettre  tout en bas du code dans le **main**, entre ses guillemets.

- Pour **Analyze_A_Product.py**, vous tapez le lien d’un des livres, et vous aurez son contenu.

- Pour **Analyze_Products_From_Category.py**, vous tapez le lien de la première page d’une catégorie, pour avoir tout le contenu de cette catégorie.

- Et enfin pour **Analyze_All_Categories.py**, vous aurez tout le contenu du site book.toscrape.com.



<br/><br/><br/>





## Auteur

* **Damien Hernandez** _alias_ [DamienZeh](https://damienhernandez.fr/)


