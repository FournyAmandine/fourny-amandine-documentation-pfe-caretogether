# Qualité du code HTML

Voici les différents rapport qui attestent de la qualité du code HTML:

---

## Headings Map

### Accueil
![Headings Map - HTML4 - Accueil](images/heading/HTML4 - Accueil.png)
![Headings Map - HTML5 - Accueil](images/heading/HTML5 - Accueil.png)


### A propos
![Headings Map - HTML4 - A propos](images/heading/HTML4 - A propos.png)
![Headings Map - HTML5 - A propos](images/heading/HTML5 - A propos.png)


### Contact
![Headings Map - HTML4 - Contact](images/heading/HTML4 - Contact.png)
![Headings Map - HTML5 - Contact](images/heading/HTML5 - Contact.png)


### Annonces
![Headings Map - HTML4 - Annonces](images/heading/HTML4 - Annonces.png)
![Headings Map - HTML5 - Annonces](images/heading/HTML5 - Annonces.png)


### Détail
![Headings Map - HTML4 - Detail](images/heading/HTML4 - Detail.png)
![Headings Map - HTML5 - Detail](images/heading/HTML5 - Detail.png)


### Mentions légales
![Headings Map - HTML4 - Mentions](images/heading/HTML4 - Mentions.png)
![Headings Map - HTML5 - Mentions](images/heading/HTML5 - Mentions.png)


### Politique de confidentialité
![Headings Map - HTML4 - Politique](images/heading/HTML4 - Politique.png)
![Headings Map - HTML5 - Politique](images/heading/HTML5 - Politique.png)


### Conditions d'utilisation
![Headings Map - HTML4 - Conditions](images/heading/HTML4 - Conditions.png)
![Headings Map - HTML5 - Conditions](images/heading/HTML5 - Conditions.png)

---

## Validation HTML

### Accueil
![Validation HTML - Accueil](images/html/HTML - Accueil.png)


### A propos
![Validation HTML - A propos](images/html/HTML - A propos.png)


### Contact
![Validation HTML - Contact](images/html/HTML - Contact.png)


### Annonces
![Validation HTML - Annonces](images/html/HTML - Annonces.png)


### Détail
![Validation HTML - Détail](images/html/HTML - Detail.png)

---

## Efforts pour la sémantique
Tout d'abord chaque page du site public est validée niveau sémantique.  

Ensuite pour les pages publiques, un composant est utilisé pour avoir une cohérence. Dans ce composant, il y a le head, header, main et footer. 
![Composant app](images/semantique/HTML-App.png)

Chaque input des formulaires de connexion, inscription, contact est accompagné de son label et connecté à celui-ci. Un composant est utilisé pour garder la même structure.  
![Composant input](images/semantique/HTML-Input.png)

Chaque call to actions a la balise adéquate :  
- Quand il y a une redirection, la balise 'a' est utilisée avec l'href correspondant
- Quand il n'y a pas de redirection, juste une action, c'est un bouton de type button qui est utilisé
- Pour les formulaires, c'est un bouton de type submit
![Composant bouton](images/semantique/HTML-Button.png)
![Composant lien](images/semantique/HTML-Link.png)

Les annonces qui sont dans les pages d'index (achats, locations, annonces, accueil...) sont des articles avec un titre, en général h3, qui correspond.   
![Composant lien](images/semantique/HTML-Article.png)  

J'ai une liste de composants séparée en fonction des différentes parties du site que j'utilise pour construire le site. Ça me permet d'avoir une cohérence pour la sémantique. 
![Liste des composants](images/semantique/HTML-Components.png)  

Chaque formulaire est dans une balise form avec un csrf. 
![Formulaire](images/semantique/HTML-Form.png)  

---

## Micro-datas

### Détail d'une annonce
![Micro-datas de la page détail](images/micro-datas/DATA - Detail.png)

### Liste des annonces
![Micro-datas de la page détail](images/micro-datas/DATA - Liste.png)

### Carte d'une annonce
![Micro-datas de la page détail](images/micro-datas/DATA - Annonce.png)

---

## Retour

[← Retour à l’accueil](index.md)
