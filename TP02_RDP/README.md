# TP02 - Configuration et Utilisation de Remote Desktop Protocol (RDP)

## Informations générales

- Matière : Services Réseaux Avancés
- Niveau : L3 GLSI A
- Année universitaire : 2026-2027

## Membres du groupe

- Étudiant 1 :Abdoulaye SARR
- Étudiant 2 :

### Objectif : Configurer et utiliser RDP pour accéder à un ordinateur Windows à distance de
manière sécurisée.

##  Partie 1 : Activer le Bureau à Distance sur le Serveur Windows
### 1. Vérification de la Version de Windows
-  Vérification des informations du système
  Dans Windows > paramètre > Système > informations système

  ![information systems](captures/informations_systeme.png)

### 2. Activation du bureau à distance

  ![activation bureau à distance](captures/activation_bureau_à_distance.png)


### 3. Configurer l'Accès des Utilisateurs :
Ici mon utilisateur principal hp à déjà accès au bureau à distance

![accès des users au bureau à distance](captures/acces_des_user_au_bureau_à_distance.png)

### 4. Vérification des paramètre du Pare-Feu

![Vérifications des pare-feu](captures/vérification_des_pare_feu.png)

##  Partie 2 : Connexion au Serveur RDP depuis un Client Windows

##  Partie 3 : Connexion au Serveur RDP depuis un Client Linux

### 1. Installer un Client RDP (Remmina ou FreeRDP) 
-  Installation de remmina : moi vue que je l'avais déjà installé ça donne ça

  ![installation de remmina](captures/installation_remmina.png)

### 2. Lancer Remmina et Configurer la Connexion 

-  Lancement de rémmina

  ![lancement de remmina](captures/lancement_remmina.png)
  ![validation de la connexion](captures/validation_de_connexion.png)

### 3. test de la connexion
validation de la connexion

![test de la connexion](captures/test_connexion.png)

##  Partie 4 : Activation du service RDP sous virtualbox pour accès à une machine
-  VirtualBox peut être configuré pour offrir un accès distant aux machines virtuelles, via le
protocole RDP (Bureau à distance). Lancez votre VitualBox.

  ![virtualbox_activation bureau à_distance](captures/vbox_activation_b_d.png)

-  Test de bon fonctionnement Comme client, nous allons utiliser l’outil Bureau à distance de
Windows

![connexion par windows sur ubuntu](captures/ubuntu_connexion_par_window_rdp.png)
![validation, de la connexion par windows sur ubuntu](captures/validation_de_connexion.png)
![](captures/connexion_à_ubuntu.png)

### Conclusion
ce tp nous a donc permis comprendre l'accès bureau à distance et les aspects essentiels de RDP

