# wp-template-gallery-Rana

## Mise en place sur le serveur 

Ce WordPress a été fait en local donc lorsqu'il sera mis en ligne il faudra modifier quelques trucs :
1. Ouvrir le dossier dans votre éditeur de code.
2. Ouvrir le fichier wp-config.php. Vous y trouverez les données permettant de ce connecter à la base de donnée. Il faudra changer l'adresse de l’hébergement MySQL car le mien est 3008 ! A vérifier le vôtre.
3. Fermez.
4. N'oubliez pas de créer/importer la base de donnée (modifier dans wp-config.php si changement de nom/mot de passe etc).

5. Une fois dans le tableau de bord du WordPress(voir "Premier pas sur WordPress"), aller dans l'onglet Contact.
![Image description](.imageReadme/wp18.PNG)
6. Cliquer sur "Formulaire de contact 1".
7. Aller dans l'onglet E-mail et mettre votre adresse mail et enregistrer.
![Image description](.imageReadme/wp19.PNG)

8. Aller dans l'onglet Apparence -> Personnaliser -> Réglages de la page d'accueil -> Section de portfolio.
    * Sur la page d'accueil on peut afficher seulement 12 photos en tout.(voir "Arranger la page d'accueil").
    * Mais en cliquant sur "Voir plus", on est dirigé vars la page "portofolio" qui existe aussi dans le menu burger.
    * Il y a toutes les photos sur cette page "Portfolio".
    * Modifier le lien vers cette page une fois le site mis sur le serveur avec le nom de votre site.
    ![Image description](.imageReadme/wp20.PNG)



## Premier pas sur WordPress

1. Pour aller en mode "edition", il faudra taper dans votre url : /wp-admin pour aller sur le tableau de bord.
![Image description](.imageReadme/wp1.PNG)
2. Faire les mises à jour si besoin.
3. En cliquant sur le lien dans le cercle rouge, vous tomberez sur votre site.
![Image description](.imageReadme/wp3.PNG)
4. Pour revenir en arrière, on clique ici.
![Image description](.imageReadme/wp5.PNG)

## Ajouter photos

1. Allez dans Portfolios
![Image description](.imageReadme/wp4.PNG)
2. Vous avez 3 catégories: 
    * All Portfolios : ici s'affiche toutes les photos éditées sur le site ( le titre de la photo/ le nom de l'auteur/ le nom de la catégorie/ et la date de parution).
    * Add new : crée une nouvelle page pour ajouter une nouvelle photo.
    * Portfolios Categories : ici s'affiche et se crée toutes les catégories.( Catégorie : nom de onglet qui va s'afficher sur le site ex: "Photos de vacances").

3. Pour créer un nouvel onglet/categorie:
    * Allez dans Portfolios Categories.
    ![Image description](.imageReadme/wp6.PNG)
    * Remplir le nom et le slug(optionnel - en miniscule et avec des "-" à la place des espaces).
    * Puis "add new categories".

4. Allez ensuite dans "Add New"
![Image description](.imageReadme/wp7.PNG)

5. Si vous souhaiterez rajouter des photos dans une catégories déjà existante, faire "Add New".

6. * Mettre un titre à chaque fois.
   * Vous pourvez écrire un article mais ce n'est pas obligatoire.
   * Choisir une catégorie dans le menu de droite " Portfolio Categories" à chaque fois.
   * Cliquer dans "Set featured image" dans Featured Image dans le menu de droite à chaque fois.
   ![Image description](.imageReadme/wp8.PNG)

7. * Choisir une images déjà téléchargés dans la bibliothèque de médias.
   * Ou, Téléverser des fichiers.
   ![Image description](.imageReadme/wp9.PNG)

8. Séléctionner une image et remplir le "Texte Alternatif" pour le référencement.

9. Cliquer sur "Set featured image" pour valider.
![Image description](.imageReadme/wp10.PNG)

10. Titre : ok, catégorie: ok, photo: ok, faire "Publier" et encore "Publier" en haut à droite.
![Image description](.imageReadme/wp11.PNG)

11. Une fois le message de publication apparu, vous pouvez revenir sur le tableau de bord.
![Image description](.imageReadme/wp12.PNG)
![Image description](.imageReadme/wp13.PNG)

12. Il doit apparaitre dans "All Portfolios" et sur le site en cliquant sur le lien en haut à gauche.
![Image description](.imageReadme/wp14.PNG)


## Supprimer/modifier photos

1. Modifier:
    * Dans "All Portfolios", en passant la souris sur un titre, séléctionner "modifier" pour ouvrir la page ou "modification rapide".
    * Mettre à jour.
    ![Image description](.imageReadme/wp15.PNG)

2. Supprimer:
    * Cocher la case devant le titre à supprimer.
    * Aller dans "Actions groupées".
    ![Image description](.imageReadme/wp16.PNG)
    * Choisir "Mettre à la corbeille".
    * faire "Appliquer".
    ![Image description](.imageReadme/wp17.PNG)

## Arranger la page d'accueil

1. Vous avez créer plusieurs catégories, vous avez passer votre après-midi à ajouter une par une 300 photos, mais sur votre page d'accueil... seulement 12 photos et une seule catégorie !!!!
2. No panic ! Toutes vos photos et catégories sont bien crées et elle se trouvent toutes sur le page "Portfolio" dans le menu de votre site !
3. Mais alors pourquoi et comment faire pour en afficher plus !
4. L'accueil affichera que les 12 dernières photos publiés. Si les 12 viennent de la catégorie "A la montagne", les autres disparaîtront de l'accueil.
5. Il faut donc tricher !

6. Aller dans "All Portfolios".
7. Choisir les 12 photos que vous souhaitez faire apparaitre sur vois par d'accueil.
8. Pour chaque, faire "modification rapide".
9. Changer la date et l'heure !
![Image description](.imageReadme/wp15.PNG)
10. Mettre à jour.
