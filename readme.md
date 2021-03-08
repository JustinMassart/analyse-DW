# Analyse - Design Web

### La tête de l'emploi :

http://latetedelemploi.be/fr/

## Test d'utilisabilité d'Amélie Boucher

### Architecture : Le site est bien rangé.

#### Les regroupements sont logiques.

- L'architecture est plutôt bien rangée, avec des exceptions comme l'onglet Liens par exemple. On arrive bien a trouver
  ce que l'on cherche. Chaque rubriques contient bien des infos sur le titre de la rubrique.

#### La structuration met en avant les contenus clés.

- La structuration ne met pas en avant les contenus clés, certains liens et infos pourraient être dans d'autres
  sections.

#### Les menus aident l'internaute à naviguer dans les contenus.

- Certains menus ne sont pas expressifs, une fonctionnalité comme l'explication du mot au survol ou autre aurait été
  sympa.

### Organisation visuelle : la page est bien rangée.

#### Eviter le trop-plein d'information.

- Sur une majorité de page il n'y a pas trop d'infos inutiles, mais certaines pages n'ont même pas de contenu.

#### Réduire la quantioté de mots sur les pages navigantes.

- Certains pages (news, accueil) peuvent avoir des quantités de texte réduites, on comprend déjà où on va sans la
  deuxième moitié de phrase.

#### N'afficher que les principaux éléments de navigation et d'interaction.

- Il n'y a pas de surplus d'éléments de navigation et d'interaction. Sauf pour le cv vidéo qui n'est pas dans sa section
  et peut-être séparer les deux en cv écrit et vidéo.

#### Différencier les quantités d'informations réelles et perçues.

- La quantité d'information réelle et perçue n'est pas gênante lors de la navigation.

#### Les animations augmentent la charge informationnelle.

- Les animations des slider ne fonctionnent pas en même temps donc pas de gêne. Celui du dessus est en boucle par
  contre. Celui du bas fonctionne si la souris est dessus.

#### Démultiplier la valeur du pixel carré.

- Il y a de l'additionnement d'information lors du survol et les boutons des sliders pour changer d'info. (Suivant les
  machines ils fonctionnent différemment).

### Cohérence : le site capitalise sur l'apprentissage interne.

#### Les localisations sont cohérentes.

- La localisation est cohérente, les objets ne changent pas de place.

#### Les appellations sont cohérentes.

- Les appellations sont cohérentes sauf pour l'onglet Lien>>

#### Les formats de présentation sont cohérents.

- Les style sont les mêmes sauf pour les pages employeurs et espace jeune.

#### Les interactions sont cohérentes.

- Idem pour les interractions, dans les formations les boîtes qui apparaissent n'ont pas toutes le même style.

### Conventions : le site capitalise sur l'apprentissage externe.

#### Respecter les conventions de localisations.

- Conventions respectées sauf pour la barre de recherche.

#### Respecter les conventions de vocabulaire.

- Le vocabulaire est +/-.

### Information : le site informe internaute et lui répond.

#### Ne soyez pas avare d'informations.

- Suivant les pages, soit il n'y a pas contenu soit il y en a et il est correct.

#### Donner de l'information générale.

- Beaucoup trop de pages sont sans contenu.

#### Donner de l'information pour faciliter la navigation.

- Navigation moyenne, plusieurs liens inutiles.

#### Donner de l'information ponctuelle.

- Le site informe bien quand on envoie un mail.

#### Informez, mais au bon moment.

- Ne s'applique pas.

#### L'ordinateur répond aux actions de l'interaute.

- Feedback lors des formulaires si on ne complète pas tous les champs.

#### Visibilité du feedback.

- Il s'affiche en message d'erreur.

### Compréhension : les mots et symboles sont choisis minutieusement.

#### Le vocabulaire doit être compréhensible.

- Mots, titre, mal choisis (abbr auraient été sympa).

#### Les symboles de codes doivent être compréhensibles.

- Les moins : symbole de l'onglet lien est mal choisi, celui du slider avec les flèches.

- Les plus : recherche loupe, vidéo play, pagination.

### Assistance : le site aide et dirige l'internaute.

- Il ne dirige pas l'utilisateur

#### Call-To-Action.

- Pas bcp de CTA

### Gestion des erreurs : Le site prévoit que l'internaute se trompe.

#### Éviter les erreurs grâce à l'indication des champs obligatoires.

- Formulaire, champs essentiels pas olbigatoires.
- Gestion php mais champs obligatoire pas mis en html.

#### Éviter les erreurs grâce aux libellés et légendes des champs.

- Les champs sont légendés.

#### Éviter les erreurs grâce à la taille des champs.

- La taille est correcte. Text-area pété.

#### Faciliter le repérage des erreurs.

- texte rouge, erreur bien expliquée. Champs rouge aurait été sympa.
- (On peut mettre n'importe quoi dans le champ 'nom'.)

#### Faire preuve de courtoisie dans les messages d'erreurs.

- C'est courtois.

#### L'internaute doit facilement pouvoir corriger ses erreurs.

- Corrige simplement.

#### Faciliter la correction grâce aux mécanismes de gestion des erreurs.

- Pas de mécanisme sauf pour le champ obligatoire.

### Rapidité : l'internaute ne perd pas son temps.

#### Faciliter les interractions.

- Suffisament grand, padding appliqué, effet de hover, opacité de texte, background devient plus foncé.

### Liberté : c'est l'internaute qui commande.

#### Respectez les contrôles utilisateur conventionnels.

- Fonctionnalités du navigateur fonctionnelles.

#### Fuyez les actions au rollover.

- Il y a du rollover avec effet hover

#### Flexibilité des actions utilisateur.

- Pas de flexibilité

### Accessibilité : un site facile d'accès pour tous.

- pas pour mal-voyant.
- TAB fonctionne à moitié.
- pas responsive.
- script en masse, iframe, pdf reader, Vidéo sans sous-titres.

### Satisfaction de votre internaute

- Satisfaction moyenne (Impression de perdre un peu son temps car le site redirige beaucoup vers d'autres sites et que
  beaucoup trop de pages sont inutiles).

---

### Test d'Anysurfer.

| Numéro      |     Description                                                                                        |   Poids | Résultat |
| ------------|: ------------------------------------------------------------------------------------------------------|: ------:| --------:|
| 1           |        Les titres de pages sont-ils significatifs ?                                                    |       1 |      1   |
| 2           |        La langue des pages est-elle correctement indiquée ?                                            |       2 |      0   |
| 3           |        Le focus est-il visible lors de la tabulation ?                                                 |       2 |      0   |
| 4           |        Le site est-il entièrement utilisable au clavier ?                                              |       3 |      3   |
| 5           |        Est-il possible d'arrêter les animations ?                                                      |       2 |      0   |
| 6           |        La différence entre les liens et le simple texte est-elle visuellement claire ?                 |       1 |      1   |
| 7           |        Les intitulés des liens sont-ils significatifs ?                                                |       2 |      2   |
| 8           |        Toutes les imahges ont-elle une alternative textuelle ?                                         |       2 |      0   | 
| 9           |        Les vidéos sont-elles sous-titrées ?                                                            |       3 |      0   |
| 10          |        Le contarste entre le texte et l'arrière-plan est-il suffisant ?                                |       3 |      0   |
| 11          |        Les titres sont-ils codés au moyen des balises HTML adéquates ?                                 |       2 |      0   |
| 12          |        Les listes sont-elles codées au moyen des balises HTML adéquates ?                              |       1 |      0   |
| 13          |        Les champs de formulaire sont-ils reliés à leur label ?                                         |       2 |      0   | 
| 14          |        Une aide textuelle est-elle présente lorsque la validation d'un formulaire détecte des erreurs ?|       2 |      2   |
| 15          |        Le code soure est-il valdie ?                                                                   |       1 |      0   |

#### Résultat

1 + 3 + 1 + 2 + 2 = 9 sur 29

Donc 31 %, test raté. 

---  

### Test sur le site de GTMetrix

### Accueil

- Performance de 51%.
- Chargement du contenu le plus long est de 6.4s.
- Trop de script.

### Employeurs

- Performance de 50%.
- Chargement du contenu le plus long de 8s.
- Trop de script.

### Listes des Entreprises

- Performance de 5%.
- Chargement du contenu le plus long de 7.6s.
- Trop de script.
- Les images occupent 92.7% de la taille du site (7.85mb sur 8.56mb).

### Espace Jeunes

- Perf de 97%.
- Chargement de 1s.

### Formation

- Perf de 76%.
- Chargement de 2s.

### CV Vidéo

- Perf de 71%
- Chargement 2.1s
- Trop de script.

---

