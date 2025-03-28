# Reinforcement-Learning-TPs

## Machine-Learning-2

Ce repository regroupe des ressources, du code et des exemples pratiques sur l'Apprentissage par Renforcement (Reinforcement Learning, RL). Il est conçu pour aider à comprendre et implémenter des algorithmes RL grâce à Python et des bibliothèques spécialisées comme OpenAI Gym.

 
---

## MACHINE LEARNING II – Travaux Pratiques (TP)


### **TP 1 : Introduction au Reinforcement Learning et OpenAI Gym**

#### **Objectif**
- Comprendre les bases du Reinforcement Learning et ses concepts clés : agent, environnement, états, actions, récompenses.
- Explorer OpenAI Gym, un cadre standardisé pour tester des algorithmes d’apprentissage par renforcement.
- Expérimenter l’interaction entre un agent et un environnement RL avant de coder des algorithmes plus avancés.

#### **Contenu**
- Présentation des bibliothèques RL : OpenAI Gym, NumPy, Matplotlib.
- Mise en place d’un environnement RL : installation et configuration.
- Premiers pas avec OpenAI Gym : exploration et manipulation d’un environnement simple.
- Exécution et observation d’actions : comprendre comment l’agent interagit avec l’environnement.

#### **Exercices**
1. Découverte et exploration d’un environnement Gym.
2. Manipulation des observations et des récompenses.
3. Contrôle manuel de l’agent dans l’environnement.
4. Évaluation des performances d’une politique aléatoire.

---

### **TP 2 : Implémentation de l’Algorithme Q-Learning**

#### **Objectif**
- Implémenter l'algorithme Q-Learning, un des algorithmes les plus fondamentaux du RL.
- Utiliser une Q-table pour estimer la meilleure action à chaque état.
- Comprendre et tester différentes stratégies d'exploration (ex : ε-greedy).
- Observer la convergence des valeurs Q dans l’environnement **FrozenLake-v1** d’OpenAI Gym.

#### **Contenu**
- Présentation du Q-Learning : principe de mise à jour des valeurs Q.
- Exploration vs Exploitation : définition et impact du paramètre ε.
- Implémentation d’une Q-table : stockage et mise à jour des valeurs Q.
- Entraînement et convergence : ajustement des hyperparamètres et analyse des résultats.

#### **Exercices**
1. Exploration de l’environnement **FrozenLake** .
2. Implémentation et initialisation d’une Q-table.
3. Implémentation de l’algorithme Q-Learning et mise à jour des valeurs Q.
4. Évaluation des performances de l’agent sur plusieurs épisodes.

---

### **TP 3 : Optimisation des Feux de Circulation avec RL**

#### **Objectif**
- Appliquer le RL à un problème du monde réel : la gestion intelligente des feux de circulation.
- Comparer deux algorithmes d’apprentissage : **Q-Learning** et **SARSA**.
- Analyser l’impact des décisions de l’agent sur l’efficacité du trafic.

#### **Contenu**
- Présentation du problème : réduction des embouteillages par optimisation des signaux de feux.
- Modélisation d’un environnement simulé : structure des états, actions et récompenses.
- Implémentation de **Q-Learning** et **SARSA** : entraînement et convergence.
- Comparaison des performances : analyse des temps d’attente, fluidité du trafic et visualisation graphique.

#### **Exercices**
1. Exploration et compréhension de l’environnement simulé.
2. Implémentation de **Q-Learning** pour apprendre une politique optimale.
3. Implémentation de **SARSA** et comparaison avec **Q-Learning**.
4. Analyse et visualisation des performances avec **Matplotlib**.

---

### **TP 4 : Apprentissage Profond pour les Jeux – PPO**

#### **Objectif**
- Approfondir l’apprentissage par renforcement en utilisant un modèle basé sur des réseaux de neurones.
- Implémenter **Proximal Policy Optimization (PPO)**, un algorithme avancé de RL utilisé dans des applications réelles (**jeux vidéo, robotique**).
- Entraîner un agent pour résoudre l’environnement **Taxi-v3** (optimisation du transport de passagers).

#### **Contenu**
- Introduction au **RL basé sur les politiques** : différences entre **Q-Learning** et **PPO**.
- Architecture de **PPO** : principe de mise à jour de la politique avec clipping.
- Collecte et stockage des épisodes : importance de l’exploration.
- Entraînement et évaluation : convergence et analyse des résultats.

#### **Exercices**
1. Initialisation de l’environnement **Taxi-v3** et exploration des actions possibles.
2. Collecte d’épisodes et stockage des expériences.
3. Implémentation de l’algorithme **PPO** et mise à jour des paramètres.
4. Évaluation des performances de l’agent et ajustement des hyperparamètres.

---

## **Réalisé par** :
**AJI Othmane**

## **Supervisé par** :
**Professeur Mohemed Khalifa Boutahir**
