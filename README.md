# Tunisie-lutte-contre-le-covid-19

Ce projet est un essaie de localiser les personne infectées par COVID-19

## les interfaces:
1. comment vous protéger de COVID-19
2. amis contactée
3. liste des contacts infectées
4. je suis infectée

### 1. comment vous protéger de COVID-19:
- conseils

### 2. amis contactée
- ajouter:
  - id de contact
  - date
  - heure
- afficher tout

### 3. liste des contacts infectées:
affiche la liste des amis qui ont l'état malade
(affiche si un contact de moi qui a contactée un personne malade)

### 4. je suis infectée
- Que faire ?
  - donner la liste des numéro a appeler
- demande a des contacts de confirmer votre état

## les données sauvegarder
chaque personne a :
````
-un identifiant composée de 6 caractère (lettres et chiffres) 
pour identifier plus que 2 milliard utilisateur

-les personne contactées:
list_contact[
  {
    date:27-03-2020,
    contacts:[
      {hour:16:30, user:aol35c},
      {hour:16:49, user:okntg6}
    ]
  },
  {
    date:26-03-2020,
    contacts:[
      {hour:10:30, user:aol35c},
      {hour:12:00, user:lk65kh}
    ]
  }
]

-état: sain / malade
-liste des personne qui vont confirmer votre état
list_confidential:[6sfv15, ffgh5d, 3fg1hd]
````
