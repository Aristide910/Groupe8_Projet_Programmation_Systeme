# Groupe8_Projet_Programmation_Systeme
Ucac-Icam Projet Programmation Systeme

Un logiciel de jeu vidéo pour un restaurant gastronomique construit à l'aide de .NET Core et C#. 

**Observation** : Ce logiciel est en cours de développement.

## Mise en route
Ces instructions vous permettront de mettre en place une copie du projet sur votre machine locale à des fins de développement et de test.
Conditions préalables
Ce projet nécessite l'installation des logiciels suivants sur votre machine locale pour fonctionner :
*.NET Core 3.1 LTS*
*Microsoft SQL Server 2019*
Ce projet est basé sur Windows Forms, pour accéder à l'outil de conception vous aurez besoin d'un Visual Studio IDE, mais pour modifier le code seulement vous pouvez utiliser n'importe quel éditeur de texte comme vscode ou atom.
*Visual Studio IDE*

# Aperçu de la Conception du Système
Vous trouverez ci-dessous des détails techniques sur l'interface, l'architecture, la base de données et d'autres décisions prises au cours du développement du projet.

## Modèle d'architecture
MVC (Modèle - Vue - Contrôleur)
Ce projet est écrit en utilisant le modèle MVC pour la séparation des préoccupations en raison de la capacité de couplage lâche, les couches logicielles comme le modèle sont indépendantes de l'interface utilisateur (vues) accédant aux données pour la présentation par la classe des contrôleurs, cette approche permet une meilleure maintenabilité et cohérence pour le développement à long terme.

## Vue d'ensemble du schéma UML
Pour visualiser l'ensemble du diagramme de cas d'utilisation nous vous invitons à parcourir le dépôt git.

**Vous pouvez également voir d'autres diagrammes utilisés pour la conception de ce système orienté objet :**

Diagramme de classes - Un diagramme de structure statique qui décrit la structure du système en montrant les classes du système, leurs attributs, leurs opérations et les relations entre les objets.

Diagrammes de séquence - Un diagramme de séquence montre, sous forme de lignes verticales parallèles (lignes de vie), différents processus ou objets qui vivent simultanément, et, sous forme de flèches horizontales, les messages échangés entre eux, dans l'ordre où ils se produisent.

Diagrammes d'activité - Représentation graphique d'un flux de travail composé d'activités et d'actions par étapes, avec prise en charge du choix, de l'itération et de la concurrence.

# Conçu avec
**Front-end :**

Windows Forms Core - Cadre d'interface utilisateur permettant de créer des applications client riches pour Windows.

**Back-end :**

.NET Core avec C# - Cadre Microsoft open source et multiplateforme.

**Base de données :**

Microsoft SQL Server - Solution complète de Microsoft pour les bases de données relationnelles.

# Contributeurs
- Koloko Aristide
- Kuate Yves-Alexis
- Simou Uziel
- Sonkin Reine
