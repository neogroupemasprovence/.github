# :bug: Bug fix

Supprimer la section si la PR ne fixe pas un problème, sinon ajouter le lien vers le ticket ou l'issue.

# :loudspeaker: Description

Veuillez inclure un résumé des modifications et du problème connexe. Veuillez également inclure la motivation et le contexte pertinents. Répertoriez toutes les dépendances requises pour ce changement.

# :clipboard: Type de changement

|     | Detail                                                                                                                                |
|-----|---------------------------------------------------------------------------------------------------------------------------------------|
| :x: | Correction de bogue (changement ininterrompu qui résout un problème)                                                                  |
| :x: | Nouvelle fonctionnalité (changement ininterrompu qui ajoute des fonctionnalités)                                                      |
| :x: | Modification avec rupture (correction ou fonctionnalité qui empêcherait la fonctionnalité existante de fonctionner comme prévu)       |
| :x: | Modification sans rupture (correction ou fonctionnalité qui n'empêcherait pas la fonctionnalité existante de fonctionner comme prévu) |
| :x: | Amélioration                                                                                                                          |
| :x: | Refactorisation                                                                                                                       |
| :x: | Cette modification nécessite une mise à jour de la documentation                                                                      |
| :x: | Cette modification nécessite une communication auprès de l'équipe                                                                     |

# :pencil: Comment cela a-t-il été testé ?

Veuillez décrire les tests que vous avez exécutés pour vérifier vos modifications. Fournissez des instructions afin que nous puissions reproduire. Veuillez également énumérer tous les détails pertinents pour votre configuration de test

:x: Non testé

# :white_check_mark: Liste de contrôle

|     | Detail                                                                                                |
|-----|-------------------------------------------------------------------------------------------------------|
| :x: | Mon code suit les conventions de ce projet                                                            |
| :x: | J'ai effectué une auto-révision de mon code                                                           |
| :x: | J'ai commenté mon code, notamment dans les zones difficiles à comprendre                              |
| :x: | J'ai apporté les modifications correspondantes à la documentation                                     |
| :x: | Mes modifications ne génèrent aucun nouvel avertissement                                              |
| :x: | J'ai ajouté des tests qui prouvent que mon correctif est efficace ou que ma fonctionnalité fonctionne |
| :x: | J'ai mis à jour l'exemple et les tests dans Postman                                                   |
| :x: | Les tests unitaires nouveaux et existants passent localement avec mes modifications                   |
| :x: | Toutes les modifications dépendantes ont été fusionnées et publiées dans les modules en aval          |
| :x: | La QA locale passe et aucune nouvelle anomalie n'a été introduite                                     |
| :x: | lint:container passe                                                                                  |
| :x: | lint:yaml config passe                                                                                |

# :question: Comment appliquer le changement ?

|     | Action                                | Commande                |
|-----|---------------------------------------|-------------------------|
| :x: | Build l'environnement                 | `make build`            |
| :x: | Configurer l'environnement            | `composer dump-env dev` |
| :x: | Supprimer les tables et les séquences |                         |
| :x: | Redémarrer Docker                     | `make restart`          |
| :x: | Recharger les fixtures                | `make fixt`             |

# :information_source: Informations additionnelles
Supprimer la section si elle n'est pas nécessaire.
