
# 🛡️ **pfSense Network Configuration and Security Guide**

[![pfSense](https://img.shields.io/badge/pfSense-003366?style=flat-square&logo=pfsense&logoColor=white)](https://www.pfsense.org/)
[![ClamAV](https://img.shields.io/badge/ClamAV-FF0000?style=flat-square&logo=clamav&logoColor=white)](https://www.clamav.net/)
[![Snort](https://img.shields.io/badge/Snort-FF69B4?style=flat-square&logo=snort&logoColor=white)](https://www.snort.org/)
[![Squid](https://img.shields.io/badge/Squid-004B87?style=flat-square&logo=squid&logoColor=white)](http://www.squid-cache.org/)
[![Nmap](https://img.shields.io/badge/Nmap-0078D7?style=flat-square&logo=nmap&logoColor=white)](https://nmap.org/)

![pfSense Logo](img/pfsense-logo1.png)

---

### 📄 **Description**

Ce repository contient des guides détaillés pour l'installation, la configuration et la sécurisation d'une infrastructure réseau avec **pfSense**. Il couvre diverses configurations réseau et de sécurité, des outils d'analyse des logs, ainsi que des fonctionnalités avancées comme le VPN, le proxy et les règles de pare-feu.

Les étapes sont conçues pour aider à mettre en place une solution de sécurité réseau robuste et conforme aux meilleures pratiques.

---

### 📂 **Repository Content**

- **cert-https/** : Contient les certificats pour sécuriser les communications HTTPS.
- **data/** : Fichiers de configuration et de données pour les tests et les déploiements.
- **doc/** : Documentation complète des configurations et explications des choix techniques.
- **img/** : Images et captures d’écran pour illustrer les configurations et l’analyse des logs.
- **README.md** : Guide détaillé du projet.

---

### ⚙️ **Table des Matières**

1. **Introduction**
   - Adresse réseaux

2. **Installation**
   - Configuration des interfaces réseau

3. **Configuration Initiale du Système**
   - Modification du nom d’hôte et du domaine
   - Paramètres DNS

4. **NTP et Journaux**
   - Configuration de NTP
   - Analyse des logs système et pare-feu

5. **DHCP et Alias**
   - Configuration du service DHCP
   - Création et gestion des alias

6. **Sécurisation de l’Accès**
   - Configuration SSH sécurisée
   - Règles de pare-feu pour SSH

7. **Pare-feu et DMZ**
   - Configuration des règles WAN, LAN, DMZ

8. **Proxy Squid et SquidGuard**
   - Filtrage des contenus et blocage des sites inappropriés

9. **VPN OpenVPN**
   - Mise en place d’un VPN sécurisé

10. **Snort IDS**
    - Détection et prévention des intrusions

11. **Sauvegarde Automatique**
    - Planification avec Cron

12. **Analyse des Logs**
    - Analyse textuelle et graphique des logs

---

### 🛠️ **Setup and Usage**

1. **Cloner le repository :**

   ```bash
   git clone https://github.com/caroneloham/pfSense.git
   cd pfSense
   ```

2. **Consulter la documentation :**

   La documentation détaillée est disponible dans le dossier `doc/` :

   ```bash
   cd doc
   ```

3. **Ajouter des contributions :**

   ```bash
   git add .
   git commit -m "Ajout de nouvelles configurations"
   git push origin main
   ```

---

### 📦 **Technologies Utilisées**

- **pfSense** : Pare-feu et routeur open-source
- **ClamAV** : Antivirus open-source
- **Snort** : Système de détection d’intrusion (IDS)
- **Squid** : Serveur proxy
- **Nmap** : Outil de scan réseau
- **SquidGuard** : Filtrage de contenu pour Squid

---

### 📧 **Contact**

Pour toute question ou contribution, contactez **caroneloham** via GitHub.
