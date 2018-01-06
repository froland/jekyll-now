---
layout: post
title: Réflexion sur l'évaluation de l'exercice integré de RTC
---

Date de l'évaluation: 2018-01-05

# Grille d'évaluation utilisée

* Qualité du code - indentation
  * L'équipe n'a pas remis de code (*0 points*) 
  * L'équipe a remis un code dont l'indentation n'est pas consistente (*0.5 points*) 
  * L'équipe a remis un code correctement indenté (*1 points*)
* Qualité du code - nommage
  * L'équipe a choisi des noms de variables de manière aléatoire (*0 points*)
  * L'équipe a choisi des noms de variable et de fonction qui n'apportent qu'une indication technique (ex: int counter) (*0.5 points*)
  * L'équipe a choisi des noms de variable et de fonction qui rappellent les notions du problème à résoudre (ex: int bookCounter) (*1 points*)
* Qualité du code - structure	
  * L'équipe a écrit un programme sans structure (*0 points*)
  * L'équipe a découpé son programme en plusieurs fonctions (*1 points*)
* Contrôle des retours de fonction	
  * L'équipe n'a vérifié aucun retour de fonction (*0 points*)
  * L'équipe a vérifié quelques retours de fonction mais a oublié des retours essentiels (*1 points*)
  * L'équipe a vérifié tous les retours de fonctions essentielles mais sans les gérer (*2 points*)
  * L'équipe a vérifié et géré tous les retours de fonctions essentielles (*3 points*)
* Nombre des threads
  * L'équipe n'a pas utilisé de threads (*0 points*)
  * L'équipe a utilisé un nombre de threads inopportun (*1 points*)
  * L'équipe a utilisé un nombre de threads opportun (*2 points*)
* Gestion des threads	
  * L'équipe n'a pas utilisé de threads (*0 points*)
  * L'équipe a créé ses threads correctement (*1 points*)
  * L'équipe a créé et synchronisé ses threads correctement (*2 points*)
  * L'équipe a créé, synchronisé et disposé de ses threads correctement (*3 points*)
* Gestion des ressources IPC	
  * L'équipe n'a pas utilisé de ressources IPC (*0 points*)
  * L'équipe a utilisé des ressources IPC mais de manière inappropriée (*1 points*)
  * L'équipe a utilisé des ressources IPC de manière appropriée mais sans les libérer (*2 points*)
  * L'équipe a utilisé des ressources IPC et les a libérées correctement (*3 points*)
* Gestion des signaux	
  * L'équipe n'a pas utilisé de signaux (*0 points*)
  * L'équipe a utilisé des signaux mais de manière inappropriée (*1 points*)
  * L'équipe a intercepté correctement certains signaux mais pas d'autres (*2 points*)
  * L'équipe a intercepté correctement tous les signaux nécessaires (*3 points*)
* Gestion des mutex/sémaphores	
  * L'équipe n'a pas utilisé de mutex ou de sémaphores (*0 points*)
  * L'équipe a utilisé des mutex ou sémaphores mais pas de manière appropriée (*1 points*)
  * L'équipe a utilisé des mutex ou sémaphores de manière appropriée mais également là où ce n'était pas nécessaire (*2 points*)
  * L'équipe a utilisé des mutex ou sémaphores partout où c'était nécessaire et pas ailleurs (*3 points*)
* Qualité rédactionelle du rapport de labo	
  * L'équipe n'a pas remis de rapport (*0 points*)
  * L'équipe a rédigé un rapport avec beaucoup de fautes ou sans structure ou sans rapport avec le code (*1 points*)
  * L'équipe a rédigé un rapport sans faute et bien structuré (*3 points*)
* Respect des consignes du rapport	
  * Le binôme n'a pas remis de rapport (*0 points*)
  * Le binôme a rédigé un rapport qui ne répond pas aux consignes (*1 points*)
  * Le binôme a rédigé un rapport présentant ce qui fonctionne, ce qui ne fonctionne pas et des pistes d'explications (*3 points*)

# Réfexions

* Hormis les quelques suggestions que je détaillerai après, la grille était assez complète.
  Je n'ai pas eu de réelle surprise entre mon sentiment général et la note finale.
* Il serait opportun d'ajouter un critère sur la compilation du code.
  Il est dommage de recevoir du code qui ne passe même pas le stade de la compilation.
* Les consignes ne détaillaient pas le format du rapport à fournir.
  J'ai reçu des fichiers `.pdf`, `.docx` et `.odw`, ce qui passe très bien dans le logiciel anti-plagiat.
  Par contre, j'ai reçu un fichier `.rar` contenant l'ensemble du dépôt ainsi qu'un fichier `.pdf`.
  Euphorus n'a rien su faire de ce document-là.
* Je m'interroge sur l'opportunité de vérifier si le programme fonctionne ou pas.
  D'une part, l'objectif à atteindre était vraiment challenging et les conditions de l'expérience, instables.
  D'autre part, j'ai le sentiment qu'il est important que les étudiants ressentent la nécessité de délivrer quelque chose qui fonctionne.
  Le banc d'essai physique n'est sans doute pas la meilleure plateforme pour l'évaluation.
  Peut-être pourrais-je m'en sortir en créant une librairie `mock` pour tester le programme.
  Ceci doit certainement être pris en compte dès le départ.
* Lié au point précédent, il peut être intéressant de parler aux étudiants des techniques de simulation et des "mocks". 