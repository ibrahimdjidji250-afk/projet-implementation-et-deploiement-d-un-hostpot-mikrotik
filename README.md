# Implémentation et Déploiement d'un Hotspot MikroTik

## 📝 Présentation du Projet
Ce projet a été réalisé dans le cadre d'un stage pratique de 5 semaines au sein de **Pinto Company SARL** (Douala, Ndogpassi):L'objectif principal était de concevoir, configurer et déployer une solution de point d'accès Wi-Fi (Hotspot) baptisée **MBOGLEN UBNT 6** pour répondre à la saturation du réseau existant et optimiser la distribution de la bande passante

## 🛠️ Équipements et Outils Utilisés
Pour mener à bien ce déploiement réseau, les outils suivants ont été mobilisés :
**Matériel :** Routeur MikroTik, Câbles réseau à paires torsadées (connecteurs RJ45) et SWItch TPliink.
**Logiciels :** Winbox (administration MikroTik), Navigateur Web (Mozilla Firefox).

## ⚙️ Phases d'Ingénierie et Configuration
Le déploiement s'est articulé autour des configurations réseau clés suivantes sur RouterOS via l'interface Winbox :

1. **Interconnexion Physique :** Liaison entre le PC d'administration et le routeur MikroTik via câble RJ45
2. **Adressage IP :** Définition et attribution des adresses réseaux de la structure
3. **Gestion du Pool d'Adresses :** Création d'un `IP Pool` pour segmenter et réserver la plage d'adresses IP dynamiques
4. **Serveur DHCP :** Configuration du serveur DHCP pour automatiser l'affectation réseau aux équipements 
5. **Routage et Sécurité (NAT) :** Mise en place des règles de traduction d'adresses (NAT Rules / Masquerade) pour l'accès WAN 
6. **Configuration du Serveur Hotspot :** Initialisation du serveur Hotspot et gestion du portail captif d'authentification
7. **Gestion Radius (User Manager) :** Création des profils d'administration et des comptes d'accès pour sécuriser l'authentification des utilisateurs

## 📁 Autres tâches réalisées durant le stage
En parallèle du déploiement du Hotspot, plusieurs interventions techniques ont été effectuées :
**Maintenance matérielle :** Diagnostic de pannes, échange de composants (RAM, Disques durs) et réinstallation de systèmes d'exploitation (Windows 11).
**Téléphonie & Réseaux :** Câblage et raccordement de lignes de téléphones de bureau

## 📘 Documentation complète
Le rapport de stage détaillé comprenant toutes les captures d'écran, l'organigramme de l'entreprise et les conclusions techniques est disponible dans le dossier `/docs` de ce dépôt.
