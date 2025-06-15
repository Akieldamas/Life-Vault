#school #projet-final

## Slide by Slide Breakdown (20 mins) and speech

### Slide 1: Titre + Introduction
* Title project
* Name, school, date
* Brief intro
Bonjour, je m'appele ... de l'école... je vais vous parler du projet de 6 mois, où nous avons été chargés par notre professeur de créer un robot controllé par IA capable de naviguer dans un labyrinthe. Mon rôle était le developpeur d'applications et de l'IA.

### Slide 2: Objectif du projet
L'objectif principal était de développer une intelligence artificielle capable de prendre des décisions dans un environnement, par exemple dans une situation d'urgence comme lors d'un tremblement de terre. Le robot serait capable de se déplacer où les secouristes n'arrivent pas pour chercher des personnes qui peuvent être coincé, ou voire analyser les zones dangereuses.

### Slide 3: Gestion de projet
- Montrer le trello
- github pour versioning
trello nous a permit d'organiser et de répartir les tâches. chaque membre avait ses tâches clairement définies et expliqués, avec les ressources disponibles bien attribué et séparés.
github pour le versioning du code, ça m'a pas été personnelemnt utile puisque m'a partie était unique, mais pour d'autres membres c'était utile, surtout dans la programmation du robot.
des problèmes imprévus qu'on a eu pendant le projet, était par la construction du robot qui avait pris du temps, jusqu'à ce qu'on puisse tester. donc voir si l'IA était crédible également. puis la caméra.

### Slide 4: Diagramme de gantt
* Montrer le planning
* Expliquer les tâches que j'ai eu
J'ai commencé par étudier le cours donné par notre professeur qui expliquait le perceptron, toute les démarches dans la création. Au fur et à mesure que j'apprenais, je créeait la première application en tant qu'étudiant 2, documenter, créer des diagrammes qui expliquait le code.

### Slide 5: Synoptique du projet
* Expliquer l'ensemble du projet avec l'image
* Expliquer les softwares, les sensors (API, Always data, etc too)

### Slide 6: Répartition des tâches
* Lister les teammates et ce qu'ils ont fait
* En parler plus sur le teammate qui a travaillé sur la BDD + API (et montrer la BDD)
* je vais maintenant parler de mon role qui était la création de l'IA et de la simulation

### Slide 7: Le perceptron
Le perceptron est un algorithme d'apprentissage supervisé, (donner des informations et qu'il s'entraine pour apprendre à avoir une sortie qu'on définie nous même)
données d'entrées associées à une sortie
exemple avec un tableau avec des apartements (surface m² et nb pieces = prix)

### Slide 8: fonctionnement
comme dans la R2 (inputs, hidden, output) layers

### Slide 9: Concepts
fonction activation ,etc

### Slide 10-11?: Dev techonlogie et architecture
Presenter C#.Net MVC

### Slide 12: Use case of both apps (explain)

### Slide 13: App entrainement model
talk about fonctionnalités (je montrerait dans la demo comment créer un modèle)
montrer les diagrammes dans les deux apps qui montre que j'ai reflechi avant de commencer à travailler qui explique la logique de l'app en elle meme

### Slide 14: App Simulator
Talk about fonctionnalités (explain how it works)

### Slide 15: Conclusion
Ce que j'ai appris (C#, recherche, IA)
ponts égatif: reinforcement learning was difficult alone, stress
amélioraition futures, impléméntation reinforcement dans le robot, plus d'automation (talk about 7 input)
année prochaine: BUT+3 (peut être master), game dev et d'autres projets

De m'avoir écouté!​



## Demo (20 mins)

Start by presenting MY part. (the training app, show how to create a model, the different parameters,   test a model, load a model etc.
then move on to the simulation, show the manual mode, show the random (and the fact that it's not 100% randomized, show the code as well), then AI (and show it), then finally reinforcement and explain it (the best way possible, show code as well)

Reinforcement Learning:
Q-Learning, une méthode de RL basé sur du test aleatoire, qui fait des actions et qui donnent une conséquence (bonne ou mauvaise)
Q-Table, "Mémoire" pour chaque situation avec les actions + recompense.

then show API test (the token, body thing)
then create a bad model for later.

present the robot, what's the ESP32 for, whats the arduino for, moves with the servomoteurs, the amplificateur at the back for the volts.
camera

talk about the orientation part (remember that it was mentioned briefly in the repartition taches), show it running.
explain the color sensor and the "suiveur de ligne" to show its actual AI

talk about the issues like if it starts walking backwards, mention the fact it's not perfect.

after you complete one section, show the website.