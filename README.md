# UE Introduction à l’Intelligence Artificielle

## Informations générales
- Master 1, Semestre 1, 3 ECTS
- Code UE : MU4RBR08-IA
- Chargé de Cours et resp. UE : Prof. Daniel Racoceanu
- Chargé de TP : Gabriel Jimenez
- Version : oct. 2023

## Travaux Pratiques (TP) / *Laboratories (Labs)*
### TP1 - Processus markoviens et apprentissage par renforcement *(Markovian Decision Process and Reinforcement Learning)*

L’objectif de ce TP est de découvrir la manière de déclarer et résoudre les processus markoviens (Markov Decision Process = MDP) ainsi que les différents aspects de l’apprentissage par renforcement (Renforcement Learning = RL).

*The objective of this lab is to discover how to declare and solve the Markov Decision Process (MDP) as well as the different aspects of reinforcement learning (Reinforcement Learning = RL)*

### General instructions
1. Tous les codes sont écrits en Python et ont été testés sur Google Collab et [Noteable.io](https://app.noteable.io). Veuillez suivre les instructions sur les Notebooks Jupyter correspondants à chaque exercice afin d'installer les libraries nécessaires.

    *All codes are written in Python and were tested on Google Collab and [Noteable.io](https://app.noteable.io). Please follow the instructions on the corresponding Jupyter Notebooks from each exercise in order to install the necessary libraries.*

2. Les CRs du TP vont consister en les codes-source Python ou Jupyter des Exos 1 et 2 (avec vos propres modifications, rajouts et commentaires, intégrés). Les 2 CRs est à déposer sur Moodle (dossier CR_TP1_votre_option (ISI, SAR, IPS, app)). 

    *The reports of the Lab will consist of the Python or Jupyter source codes of Exo 1 and Exo 2 (with your own adds, modifications, and comments integrated). The 2 reports are to be placed on Moodle (CR_TP1_your_option (ISI, SAR, IPS, app) folder).*

### Exo. # 1 : Comprendre les processus de Markov / *Understanding Markov Processes*

L'objectif de l'exercice est de comprendre les processus de Markov en utilisant un exemple simple pour étudier le comportement d'un client. Les instructions se trouvent dans le dossier exo-01 et le fichier exo-01.ipynb. Toutes les sections où vous devez commenter et coder sont explicitement signalées. Vous pouvez modifier d'autres parties du code, mais assurez-vous de les commenter.

*The objective of the exercise is to understand Markov processes using a simple example to study the behavior of a customer. The instructions are in the folder exo-01 and file exo-01.ipynb. All the sections where you need to comment and code are explicitly remarked. You may modify other parts of the code, but make sure you comment about it.*

### Exo. # 2 : Détection des bords / *Edge detection*
L'objectif de l'exercice est d'étendre l'étude des processus de Markov au domaine du traitement des images en utilisant la théorie des Markov Random Field. L'application est un algorithme de détection des contours. Vous comparerez deux méthodes courantes dans le domaine du traitement d'images : le filtre laplacien et le détecteur de contours de canny. Les instructions se trouvent dans le dossier exo-02 et le fichier exo-02.ipynb. Toutes les sections où vous devez commenter et coder sont explicitement signalées. Vous pouvez modifier d'autres parties du code, mais assurez-vous de les commenter.

*The objective of the exercise is to extend the study of Markov processes into the image processing domain using Markov Random Field theory. The application is an edge detection algorithm. You will compare with two common methods in the image processing domain: laplacian filter and canny edge detector. The instructions are in the folder exo-02 and file exo-02.ipynb. All the sections where you need to comment and code are explicitly remarked. You may modify other parts of the code, but make sure you comment about it.*

### Exo. # 3 : Monde gelé / *Frozen world*
L'objectif de l'exercice est de mettre en œuvre l'algorithme Q-learning pour faire parcourir à un agent un chemin gelé en évitant les trous jusqu'à ce qu'il atteigne l'objectif. Les instructions se trouvent dans le dossier exo-03 et dans le fichier exo-03.ipynb. Toutes les sections où vous devez commenter et coder sont explicitement signalées. Vous pouvez modifier d'autres parties du code, mais assurez-vous de les commenter. 

*The objective of the exercise is to implement the Q-learning algorithm to make an agent walk through a frozen path avoiding the holes until it reaches the goal. The instructions are in the folder exo-03 and file exo-03.ipynb. All the sections where you need to comment and code are explicitly remarked. You may modify other parts of the code, but make sure you comment about it.*

### Exo. facultatif : Blackjack
L'objectif de l'exercice est de comparer deux algorithmes pour résoudre un problème d'apprentissage par renforcement. Les algorithmes sont : SARSA et Q-learning. Le problème d'apprentissage par renforcement est le jeu Blackjack. Suivez attentivement les instructions du fichier exo-optional.ipynb dans le dossier exo-optional. 

*The objective of the exercise is to compare two algorithms to solve a reinforcement learning problem. The algorithms are SARSA and Q-learning. The reinforcement learning problem is the game Blackjack. Follow carefully the instructions of the file exo-optional.ipynb inside the folder exo-optional.*
