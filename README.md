<h1 align="center">Welcome to readme scraping 👋</h1>
<p align="center">
  <a href="https://twitter.com/LaurentJouron">
    <img alt="Twitter: LaurentJouron"
      src="https://img.shields.io/twitter/follow/LaurentJouron.svg?style=social" target="_blank" />
  </a>   
  <a href="https://github.com/LaurentJouron">
    <img alt="GitHub followers" 
      src="https://img.shields.io/github/followers/LaurentJouron?style=social" />
  </a>
</p>
<p align="center">
    <img align="left"
      width="60px" 
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX4PiKOshpQfsfBToRmImIP_XLnyDnKDOL5A&usqp=CAU" />
</p>

### ``--- Explanation in English ---``

___________

This was done as part of a training course on :

___

You are a marketing analyst at Books Online, a major online bookstore specializing in used books. As part of your job, 
you try to manually track the prices of used books on your competitors' websites, but that’s too much work, and you can’t
cope with it: there are too many books and too many online bookstores ! You and your team decided to automate this
laborious task via a program (a scraper) developed in Python, able to extract price information
from other online libraries.

___________

# Books Online

*In order to better manage the company in which I work, I created a scraping application on the website
Book-toScrape.com. Scraping is a method of extracting data to analyze information.*

https://books.toscrape.com/

___________

<h1 align="center">Purpose of the application</h1>

___

<p align="center">
    <img align="right"
      width="350px" 
      src="https://www.e-bdd.com/images/scraping-web.webp" />
</p>

* Initially this software will take:
  * the names of the categories
  * category links.
 
* Then according to the links of the Categories, it will load :
  * the titles of the books
  * the links of the books
  * the covers of books

<p align="center">
    <img align="right"
      width="350px"
      src="https://www.okvoyage.com/wp-content/uploads/2021/01/bibliotheque-nationale-finlande-1024x683.jpeg" />
</p>
      
* Finally, he will retrieve the information from the books :

  * UPC (universal_product_code)
  * product_type
  * price_excl_tax
  * price_incl_tax
  * tax
  * available_in_stock
  * number_of_review
  * synopsis
___________

<h1 align="center">Language</h1>

___

<p align="center">
    <img align="center"
      width="500px"
      src="https://static.lpnt.fr/images/2017/11/06/11154015lpw-11154254-article-jpg_4741099_660x281.jpg" />
</p>

<p align="center">The entire application was developed in Python .</p>
    
<table>
  <tr>
    <td align="center">
      <a href=https://www.python.org/">
        <img width="200px"
          src="https://www.python.org/static/img/python-logo.png" /><br />
        <sub><b>Download Python</b></sub></a><br />
      <a href=https://www.python.org/" title="Download Python" ></a> 
    </td>
  </tr>
</table>
 
___________

<h1 align="center">IDE</h1>

___

The IDE used for programming is Pycharm. 
    
<table>
  <tr>
    <td align="center">
      <a href=https://www.jetbrains.com/fr-fr/pycharm/download/#section=windows">
        <img width="130px"
          src="https://www.qbssoftware.fr/image/cache/catalog/Editeurs/Jetbrains/jetbrains-pycharm-164-1600x1600.jpg" /><br />
        <sub><b>Download Pycharm</b></sub></a><br />
      <a href=https://www.jetbrains.com/fr-fr/pycharm/download/#section=windows" title="Download Pycharm" ></a> 
    </td>
  </tr>
</table>

It has been tested with :

<table>
  <tr>
    <td align="center">
      <a href="https://www.sublimetext.com/3">
        <img width="110px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6Mg79M0jZejQAa6OE5Hh1td-RE6Cs7pQ6Og&usqp=CAU" /><br />
        <sub><b>Sublime text 3</b></sub></a><br />
      <a href="https://www.sublimetext.com/3" title="Sublime text 3" ></a>
    </td>
    <td align="center">
      <a href="https://visualstudio.microsoft.com/fr/">
        <img width="130px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-H3CcAG7w2nXSnlqldVWR-ER4mvFfLgqYxA&usqp=CAU" /><br />
        <sub><b>Visuable Studio Code</b></sub></a><br />
      <a href="https://visualstudio.microsoft.com/fr/" title="Visuable Studio Code" ></a>
    </td>
    <td align="center">
      <a href="https://jupyter.org/">
        <img width="150px"
          src="https://jupyter.org/assets/nav_logo.svg" /><br />
        <sub><b>Jupyter Notebook</b></sub></a><br />
      <a href="https://jupyter.org/" title="Jupyter Notebook" ></a> 
    </td>
  </tr>
</table>

___________

<h1 align="center">Library</h1>

___

We used 3 different libraries for this project, here are the explanatory documents:
  
<table>
  <tr>
    <td align="center">
      <a href="https://docs.python-requests.org/en/latest">
        <img width="130px"
          src="https://docs.python-requests.org/en/latest/_static/requests-sidebar.png" /><br />
        <sub><b>Requets</b></sub></a><br />
      <a href="https://docs.python-requests.org/en/latest" title="Documentation Requests" ></a>
    </td>
    <td align="center">
      <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/">
        <img width="130px"
          src="https://www.crummy.com/software/BeautifulSoup/bs4/doc/_images/6.1.jpg" /><br />
        <sub><b>BeautifulSoup</b></sub></a><br />
      <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/" title="Documentation BeautifulSoup" ></a>
    </td>
    <td align="center">
      <a href="https://docs.python.org/fr/3/library/csv.html">
        <img width="150px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTeFQCFFmRX7dsxcyLmKNYn9Umgdg71FDMsZQ&usqp=CAU" /><br />
        <sub><b>csv</b></sub></a><br />
      <a href="https://docs.python.org/fr/3/library/csv.html" title="Documentation csv" ></a> 
    </td>
    <td align="center">
      <a href="https://docs.python.org/3/library/os.html">
        <img width="150px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQGeVC6EubMa9PBsn1aoXsbCmGEVENRpb9wlg&usqp=CAU" /><br />
        <sub><b>os</b></sub></a><br />
      <a href="https://docs.python.org/3/library/os.html" title="Documentation csv" ></a> 
    </td>
  </tr>
</table>

___________

<h1 align="center">Software installation</h1>

___
<p align="left">For the terminal I used GIT.

<table>
  <tr>
    <td align="center">
      <a href=https://git-scm.com/downloads">
        <img width="130px"
          src="https://git-scm.com/images/logo@2x.png" /><br />
        <sub><b>Download GIT</b></sub></a><br />
      <a href=https://git-scm.com/downloads" title="Download GIT" ></a> 
    </td>
  </tr>
</table>


* To start you must clone the project with the following url :
  * ``git clone https://github.com/LaurentJouron/Books-online.git``
  

* There is no virtual environment, so you must create it with the command :
  * ``python -m venv env``


* Enable this environment, with the command : 
  * ``source/env/bin/activate``


* After installing the environment, you must set the libraries on which the software was developed, use the following command : 
  * ``pip install -r requirements.txt``


* To test if all packages have been configured correctly : 
  * ``pip freeze``


* Then all that remains is to run the script so that the software starts with the command : 
  * ``pip main.py``


* Click Run to activate the program :
  * ``Run``

___________

As the process progresses, we note the writing of .csv files that allow the analysis of the information of the books .

<p align="center">
    <img align="center" 
      width="350px" 
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTRCQnMkK3eTUga21tSq4dsh6xBfffxX5YWVg&usqp=CAU" />
</p>

___________

<h1 align="center">Author and collaborators</h1>

___

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/LaurentJouron">
        <img width="100px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRlW-w7O7g3hQTw8qcIAy3LCRhiHg5tUPfvVg&usqp=CAU" /><br />
        <sub><b>Laurent Jouron</b></sub></a><br />
      <a href="https://openclassrooms.com/fr/" title="student">🈸</a>
      <a href="https://github.com/LaurentJouron/Books-online" title="Application Coder">💻</a>
    </td>
    <td align="center">
      <a href="https://github.com/thierhost">
        <img width="100px"
          src="https://avatars.githubusercontent.com/u/7854284?s=100&v=4" /><br />
        <sub><b>Thierno Thiam</b></sub></a><br />
      <a href="https://github.com/thierhost" title="Mentor to Laurent">👨‍🏫</a> 
      <a href="https://www.python.org/dev/peps/pep-0008/" title="Doc PEP 8">📄</a>
    </td>
  </tr>
</table>

___________

#####################################################################################

___________

<h1 align="center">Bienvenue sur le readme de scraping 👋</h1>
<p align="center">
  <a href="https://twitter.com/LaurentJouron">
    <img alt="Twitter: LaurentJouron" 
      src="https://img.shields.io/twitter/follow/LaurentJouron.svg?style=social" target="_blank" />
  </a>
  <a href="https://github.com/LaurentJouron">
    <img alt="GitHub followers" 
      src="https://img.shields.io/github/followers/LaurentJouron?style=social" />
  </a>
</p>

<p align="center">
    <img align="left"
      width="50px" 
      src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToscdusMNjQbffwasgiLuCsbCNZisJRE95Fg&usqp=CAU" />
</p>

### ``--- Explication en français ---``
___________
Cet exercice a été réalisé dans le cadre d'une formation dont voici le sujet :
___


Vous êtes analyste marketing chez Books Online, une importante librairie en ligne spécialisée dans les livres d'occasion.
Dans le cadre de vos fonctions, vous essayez de suivre manuellement les prix des livres d'occasion sur les sites web de 
vos concurrents, mais cela représente trop de travail et vous n'arrivez pas à y faire face : il y a trop de livres
et trop de librairies en ligne ! Vous et votre équipe avez décidé d'automatiser cette tâche laborieuse via un programme
(un scraper) développé en Python, capable d'extraire les informations tarifaires d'autres librairies en ligne.
___________

# Books Online

*Afin de mieux gérer la société dans laquelle je travaille, j'ai créé une application de scraping sur le site Book-toScrape.com.
Le scraping est une méthode qui permet d'extraire des données pour analyser les informations.*

https://books.toscrape.com/
___________

<h1 align="center">But de l'application</h1>

___

<p align="center">
    <img align="right" 
      width="350px" 
      src="https://www.e-bdd.com/images/scraping-web.webp" />
</p>

* Dans un premier temps ce logiciel va prendre :
  * les noms des catégories
  * liens des catégories

* Ensuite, d'après les liens des Catégories, il va charger :
  * les titres des livres
  * les liens des livres
  * les couvertures des livres

<p align="center">
    <img align="right"
      width="350px" 
      src="https://www.okvoyage.com/wp-content/uploads/2021/01/bibliotheque-nationale-finlande-1024x683.jpeg" />
</p>

* Pour finir il va récupérer les informations des livres :
  * UPC (universal_product_code)
  * product_type
  * price_excl_tax
  * price_incl_tax
  * tax
  * available_in_stock
  * number_of_review
  * synopsis

___________

<h1 align="center">Langage</h1>

___

<p align="center">
    <img align="center"
      width="500px"
      src="https://static.lpnt.fr/images/2017/11/06/11154015lpw-11154254-article-jpg_4741099_660x281.jpg" />
</p>

<p align="left">L'intégralité de l'application a été développer en Python .

<table>
  <tr>
    <td align="center">
      <a href=https://www.python.org/">
        <img width="200px"
          src="https://www.python.org/static/img/python-logo.png" /><br />
        <sub><b>Téléchargez Python</b></sub></a><br />
      <a href=https://www.python.org/" title="Téléchargez Python" ></a> 
    </td>
  </tr>
</table>

___________

<h1 align="center">EDI</h1>

___

<p align="left">L'EDI utilisé pour la programmation est Pycharm .

<table>
  <tr>
    <td align="center">
      <a href=https://www.jetbrains.com/fr-fr/pycharm/download/#section=windows">
        <img width="130px"
          src="https://www.qbssoftware.fr/image/cache/catalog/Editeurs/Jetbrains/jetbrains-pycharm-164-1600x1600.jpg" /><br />
        <sub><b>Téléchargez Pycharm</b></sub></a><br />
      <a href=https://www.jetbrains.com/fr-fr/pycharm/download/#section=windows" title="Téléchargez Pycharm" ></a> 
    </td>
  </tr>
</table>

Il a été testé avec :

<table>
  <tr>
    <td align="center">
      <a href="https://www.sublimetext.com/3">
        <img width="110px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6Mg79M0jZejQAa6OE5Hh1td-RE6Cs7pQ6Og&usqp=CAU" /><br />
        <sub><b>Sublime text 3</b></sub></a><br />
      <a href="https://www.sublimetext.com/3" title="Sublime text 3" ></a>
    </td>
    <td align="center">
      <a href="https://visualstudio.microsoft.com/fr/">
        <img width="130px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-H3CcAG7w2nXSnlqldVWR-ER4mvFfLgqYxA&usqp=CAU" /><br />
        <sub><b>Visuable Studio Code</b></sub></a><br />
      <a href="https://visualstudio.microsoft.com/fr/" title="Visuable Studio Code" ></a>
    </td>
    <td align="center">
      <a href="https://jupyter.org/">
        <img width="150px"
          src="https://jupyter.org/assets/nav_logo.svg" /><br />
        <sub><b>Jupyter Notebook</b></sub></a><br />
      <a href="https://jupyter.org/" title="Jupyter Notebook" ></a> 
    </td>
  </tr>
</table>

___________

<h1 align="center">Librairies</h1>

___

Nous avons utilisé 3 librairies différentes pour ce projet, voici les documents explicatifs :

<table>
  <tr>
    <td align="center">
      <a href="https://docs.python-requests.org/en/latest">
        <img width="130px"
          src="https://docs.python-requests.org/en/latest/_static/requests-sidebar.png" /><br />
        <sub><b>Requets</b></sub></a><br />
      <a href="https://docs.python-requests.org/en/latest" title="Documentation Requests" ></a>
    </td>
    <td align="center">
      <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/">
        <img width="130px"
          src="https://www.crummy.com/software/BeautifulSoup/bs4/doc/_images/6.1.jpg" /><br />
        <sub><b>BeautifulSoup</b></sub></a><br />
      <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/" title="Documentation BeautifulSoup" ></a>
    </td>
    <td align="center">
      <a href="https://docs.python.org/fr/3/library/csv.html">
        <img width="150px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTeFQCFFmRX7dsxcyLmKNYn9Umgdg71FDMsZQ&usqp=CAU" /><br />
        <sub><b>csv</b></sub></a><br />
      <a href="https://docs.python.org/fr/3/library/csv.html" title="Documentation csv" ></a> 
    </td>
    <td align="center">
      <a href="https://docs.python.org/3/library/os.html">
        <img width="150px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQGeVC6EubMa9PBsn1aoXsbCmGEVENRpb9wlg&usqp=CAU" /><br />
        <sub><b>os</b></sub></a><br />
      <a href="https://docs.python.org/3/library/os.html" title="Documentation csv" ></a> 
    </td>
  </tr>
</table>

___________

<h1 align="center">L'installation du logiciel </h1>

___

<p align="left">Pour le terminal j'ai utilisé GIT .

<table>
  <tr>
    <td align="center">
      <a href=https://git-scm.com/downloads">
        <img width="130px"
          src="https://git-scm.com/images/logo@2x.png" /><br />
        <sub><b>Téléchargez GIT</b></sub></a><br />
      <a href=https://git-scm.com/downloads" title="Téléchargez GIT" ></a> 
    </td>
  </tr>
</table>

* Pour commencer il faut cloner le projet grâce à l'url suivante :
  * ``git clone https://github.com/LaurentJouron/Books-online.git``
  
  
* Il n'y a pas d'environnement virtuel, il faut donc le créer avec la commande :
  * ``python -m venv env``
  

* Activer cet environnement, avec la commande :
  * ``source/env/bin/activate``
  

* Après avoir installé l'environnement, il faut paramétrer les librairies sur lesquelles le logiciel a été développé, 
utilisez la commande suivante :
  * ``pip install -r requirements.txt``
  

* Pour tester si tous les packages ont bien été configurés :
  * ``pip freeze``
  

* Ensuite il ne reste qu'à lancer le script pour que le logiciel se lance avec la commande : 
  * ``pip main.py``
  

* Cliquez sur run qui permet activer le programme :
  * ``Run``
  

Au fur et à mesure du déroulement, on constate l'écriture de fichier .csv qui permettent l'analyse des informations des livres.

<p align="center">
    <img align="center" 
      width="350px" 
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTRCQnMkK3eTUga21tSq4dsh6xBfffxX5YWVg&usqp=CAU" />
</p>

___________

<h1 align="center">Auteur et collaborateurs</h1>

___

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/LaurentJouron">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRlW-w7O7g3hQTw8qcIAy3LCRhiHg5tUPfvVg&usqp=CAU"
          width="100px;"/><br />
        <sub><b>Laurent Jouron</b></sub></a><br />
      <a href="https://openclassrooms.com/fr/" title="Étudiant">🈸</a>
      <a href="https://github.com/LaurentJouron/Books-online" title="Codeur de l'application">💻</a>
    </td>
    <td align="center">
      <a href="https://github.com/thierhost">
        <img src="https://avatars.githubusercontent.com/u/7854284?s=100&v=4"
          width="100px;"/><br />
        <sub><b>Thierno Thiam</b></sub></a><br />
      <a href="https://github.com/thierhost" title="Mentor de Laurent">👨‍🏫</a> 
      <a href="https://www.python.org/dev/peps/pep-0008/" title="Doc PEP 8">📄</a>
    </td>
  </tr>
</table>
