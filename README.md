# Devoir-le-Challenge-des-param-tres
Le but de ce devoir est de déterminer de manière pratique combien de paramètres une fonction en C++ peut accepter avant de provoquer une erreur ou un comportement inattendu.

# Test de Limite des Paramètres en C++

## Introduction
Ce projet a pour but de tester combien de paramètres une fonction peut accepter en C++ avant de provoquer une erreur.

## Résultats
Après avoir exécuté le programme, j'ai observé les résultats suivants :

- **Nombre de paramètres acceptés**: 10000
- **Erreur rencontrée**: 0
- **Moment de l'erreur**: 0.

## Observations

Le programme a été exécuté avec une fonction variadique qui accepte un nombre indéfini de paramètres. J'ai augmenté progressivement le nombre d'arguments passés à la fonction.

J'ai exécuté le programme avec des appels à fonctionTest en passant successivement de 1 à 10 000 arguments.
À chaque itération, le programme a exécuté avec succès l'appel de la fonction sans générer d'erreurs.

## Détails de l’Exécution :

Chaque appel à fonctionTest(i, i, i, i, i, i, i, i, i, i); (en passant 10 arguments identiques) a réussi sans interruption.
Des messages de suivi ont été imprimés sur la console à chaque 10 appels, confirmant que le programme fonctionnait correctement.

## Analyse :

L'absence d'erreurs peut être due à plusieurs facteurs :
Capacité de la Machine : Mon ordinateur dispose d'une quantité suffisante de mémoire vive (RAM) pour gérer les appels de fonction multiples.
Gestion de la Mémoire : Le compilateur C++ que j'utilise gère efficacement les arguments, ce qui permet d'éviter un dépassement de pile dans les limites testées.
Conception de la Fonction : La fonction est conçue pour accepter des arguments sans traitement spécifique, ce qui réduit la complexité et le risque d'erreurs.

## Conclusion :

Jusqu'à présent, le programme a montré une robustesse à des niveaux d'arguments élevés sans générer d'erreurs. Cela indique que, dans un environnement contrôlé et avec des ressources suffisantes, il est possible d'appeler une fonction avec un grand nombre d'arguments sans problèmes.
Il serait intéressant de continuer à augmenter le nombre d'arguments ou à modifier la fonction pour effectuer des opérations sur les paramètres, afin d'évaluer comment cela pourrait affecter la stabilité du programme.

### Captures d'Écran

![Capture d'écran 2024-10-17 093339](https://github.com/user-attachments/assets/7bc3fc31-298f-4768-8650-62544ab6087c)

![Capture d'écran 2024-10-17 093521](https://github.com/user-attachments/assets/f6767475-d4a8-4398-b2ea-19d343cc945b)

![Capture d'écran 2024-10-17 093617](https://github.com/user-attachments/assets/ae20eb80-6f73-44d2-a7b5-63c9de8c8326)

