name: Bug
description: Créer un rapport de bug
title: "[Bug]: "
labels: ["bug"]
assignees:
  - atournayre
body:
  - type: markdown
    attributes:
      value: |
        Merci de prendre le temps de remplir le formulaire.
        S'il s'agit d'un nouveau besoin, merci d'utiliser le formulaire dédié.
  
  - type: input
    id: user
    attributes:
      label: Utilisateur
      description: Quel est l'utilisateur utilisé ?
      placeholder: John Doe
    validations:
      required: true
  - type: url
    id: url
    attributes:
      label: URL
      description: Quelle est l'url de la page concernée ?
      placeholder: ex. https://neo.construction
    validations:
      required: true
  
  - type: textarea
    id: what-happened
    attributes:
      label: Que s'est il passé ?
      description: Dites nous également quel était le comportement attendu
      placeholder: Dites nous ce que vous voyez!
      value: "Un bug est survenu!"
    validations:
      required: true
  - type: dropdown
    id: environnement
    attributes:
      label: Environnement
      description: Dans quel environnement cela est il arrivé ?
      options:
        - Production
        - Recette
        - Saisie
        - Projet
        - Migration
      default: Production
    validations:
      required: true

  - type: checkboxes
    id: vérification
    attributes:
      label: Vérification
      description: En validant cette issue, je confirme avoir vérifié qu'un rapport identique n'existe pas déjà
      options:
        - label: J'ai vérifié qu'il n'existe pas déjà un rapport de bug identique
          required: true
