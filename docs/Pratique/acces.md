# 🚪 Accès

## Boîte mail ✉️

Votre boite mail est disponible par le web [ici](https://partage.univ-ubs.fr/). Et voici les configurations pour les clients lourds :

=== "IMAP"

    | Champs                         | Paramètres             |
    | ------------------------------ | ---------------------- |
    | **Serveur entrant (IMAP)**     | partage.univ-ubs.fr    |
    | **Port**                       | 993                    |
    | **Sécurité**                   | SSL/TLS                |
    | **Identifiant de connexion**   | Votre adresse mail UBS |
    | **Méthode d'authentification** | Votre mot de passe UBS | 

=== "SMTP"

    | Champs                         | Paramètres             |
    | ------------------------------ | ---------------------- |
    | **Serveur entrant (IMAP)**     | partage.univ-ubs.fr    |
    | **Port**                       | 587                    |
    | **Sécurité**                   | STARTTLS               |
    | **Identifiant de connexion**   | Votre adresse mail UBS |
    | **Méthode d'authentification** | Votre mot de passe UBS | 

## Emploi du temps 📅

La visualisation de l'emploi du temps via l'*ENT* de l'UBS étant peu pratique, des alternatives sont possibles. La première alternative est le site [CyberPlanning](https://cyberplanning.fr/). Compatible mobile et PWA, il vous permet de suivre rapidement par internet le suivi des cours. La deuxième est la synchronisation de l'EDT avec l'agenda de votre mobile en suivant ce [Guide](https://17017.univ-ubs.fr/documentation/pages/viewpage.action?pageId=622660).

## Wifi 📶

Voici les informations à utiliser pour accéder au réseau wifi **eduoroam**. Cette configuration est la même pour accéder à tous les points d'accès du réseau eduoroam présents dans les universités françaises.

| Champs                       | Paramètres                                        |
| ---------------------------- | ------------------------------------------------- |
| **SSID**                     | eduoroam                                          |
| **Identifiant de connexion** | eXXXXXXX@univ-ubs.fr (Votre identifiant étudiant) |
| **Mot de passe**             | Votre mot de passe UBS                            |
| **Domaine**                  | radius.univ-ubs.fr                                |
| **Sécurité**                 | WPA2 Entreprise (802.1x EAP)                      |
| **Méthode EAP**              | TTLS / PAP                                        |

!!! warning "Linux"
    Certains périphériques (notamment sous Linux) peuvent vous demander de valider le certificat de l'infrastructure d'authentification de l'université. Pour cela [télécharger](/assets/misc/palpimanidae-univ-ubs-fr.pem) et indiquer le certificat **GEANT OV RSA CA 4**.

## Impressions 🖨️

L'école possède plusieurs imprimantes formats A4/A3 accessibles aux étudiants via le portail [PaperCut](https://papercut.univ-ubs.fr/) web.

Tarification

| Format | Noir et Blanc | Couleur |
| ------ | ------------- | ------- |
| **A4** | 0,05€         | 0,50€   |
| **A3** | 0,25€         | 0,50€   |

Recto verso possible mais tarification doublée.

!!! question "Numéro de l'imprimante du hall de Vannes"
    L'imprimante du hall ensibs de Vannes porte le numéro **COP-0054**.

Toutes les informations complémentaires sont disponibles sur ce [guide](https://17017.univ-ubs.fr/documentation/display/DOC/Le+service+d%27impression).

## Outils web universitaires ℹ️

Voici les espaces universitaires proposés :

- [ENT Université](https://ent.univ-ubs.fr/uPortal/render.userLayoutRootNode.uP) c'est l'espace numérique de travail de l'université
- [Moodle](https://moodle.univ-ubs.fr/) est la plateforme sur laquelle vous trouverez tous vos cours et certaines de vos évaluations
- [Bibliothèque numérique universitaire](https://www.univ-ubs.fr/fr/l-universite-en-pratique/bibliotheque/bibliotheque-numerique.html) est la BU de l'UBS
- [ForgENS](https://forgens.univ-ubs.fr/) est la forge logicielle basée sur une instance gitlab de l'université
- [Documentation espaces numériques UBS](https://17017.univ-ubs.fr/documentation/index.action) est la documentation référente pour les problèmes informatiques
