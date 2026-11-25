# TP01 - Mise en place du protocole SSH

## Informations générales

- Matière : Services Réseaux Avancés
- Niveau : L3 GLSI A
- Année universitaire : 2026-2027

## Membres du groupe

- Étudiant 1 :Abdoulaye SARR
- Étudiant 2 :

### Objectif : Comprendre comment utiliser SSH pour sécuriser l'accès à une machine distante.


## 1. Installation et configuration SSH
-  Installation

  ![](captures/install_opensshServer.png)
  ![](captures/installation_SSH.png)

-  Configuration
  
  ![](captures/configuration_SSH.png)

-  Vérification du port 22

  ![](captures/verification_port22.png)
  
## 2. Connexion distante

-  Connexion avec le client Windows au serveur ubuntu

  ![](captures/Wconnexion_UbuntuServer.png)

## 3. Connexion distante par clés SSH

-  Génération de la clé publioque

  ![](captures/generation_cjes_publique.png)

-  Vérification du fichier de la clé

  ![](captures/verification_de_la_clef.png)

-  Partage de la clé avec debian dans /home

  ![](captures/envoie_de_la_clef_publique.png)  
  
## 4.1 Tunnel ssh en ligne de commande

-  Connexion au serveur avec debian

  ![](captures/connexion_serveur_ubuntu.png)

-  Résultat du curl htp://127.0.0.1:1024

![](captures/resultat_de_la_connexion_avec_ubuntu.png)

### 4.2 MariaDB

-  Installation de Mariadb

  ![](captures/install_mariadb.png)

-  Configuration de Mariadb

  ![](captures/configuration_de_mariadb.png)

## Conclusion
Ce travail nous a permis de comprendre la connexion à distance avec SSH, avec ou sans clé, et avec tunnel SSH en ligne de  coimmande
