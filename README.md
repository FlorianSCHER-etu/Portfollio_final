# 🛡️ Project Energy-OS : Portfolio d'alternant SI & TELECOM de SCHER Florian

Ce projet est un portfolio interactif simulant un environnement multi-systèmes (**Multi-boot**). Il retrace mon parcours au sein du **BUT Réseaux & Télécommunications** et mon immersion opérationnelle à la **Direction de Crise (DC/FARN) d'EDF**.

https://florianscher-etu.github.io/Portfollio_final/ 
---

## 🧬 Architecture du Projet
Le code est structuré comme un moteur d'états gérant trois "partitions" logicielles isolées :

* **Node-EDF (Energy OS) :** Interface SCADA/Supervision tactique simulant le Local Technique de Crise National (LTCN).
* **Node-Kali (Cyber Security Audit) :** Station de travail orientée pentest pour l'audit des compétences techniques.
---

## 🛰️ Spécifications Techniques & Sources

### 1. Télécommunications Critiques (Source : EDF / FARN)
Le contenu technique relatif à l'alternance repose sur les standards de haute disponibilité d'EDF :
* **Protocole TETRA :** Standard ETSI pour la radio numérique. Étude de la gestion des itérances, du mode **TMO/DMO** et du partage de ressources **TDMA**.
* **Segment Satellitaire :**
    * **VSAT :** Liaisons haut débit en bande **Ka**.
    * **BGAN :** Terminaux mobiles via le réseau Inmarsat (bande L).
    * **Iridium :** Constellation en orbite basse (LEO) pour la couverture mondiale résiliente.
* **MCO (Maintien en Condition Opérationnelle) :** Méthodologie d'audit de pannes sur multiplexeurs et relais tactiques.



### 2. Cursus Académique (Source : IUT - Programme National R&T)
Le développement des compétences est segmenté selon le référentiel national du BUT :

#### **Semestre 1 : Initialisation & Physique**
* **Stack TCP/IP :** Maîtrise de l'adressage IPv4/v6 et des masques de sous-réseau.
* **Propagation RF :** Étude des ondes et du phénomène de **Cage de Faraday** appliqué aux bâtiments réacteurs (Peau d'étanchéité métallique).



#### **Semestre 2 : Routage & Services**
* **Routage Dynamique :** Implémentation du protocole **OSPFv2** (états de liens, aires).
* **ToIP :** Architecture de services SIP, Trunking et gestion de la **QoS** (Qualité de Service).

#### **Semestre 3 : WAN & Sécurité**
* **Routage Inter-Domaine :** Configuration de **BGP** (AS, politiques d'annonces).
* **Filtrage :** Stack **Netfilter** (iptables/nftables) et VPN **IPSec** (IKEv2).

### 3. Projet Maquette Cyber (TOTR)
* **Moteur Crypto :** Basé sur l'algorithme **AES-256** et le hachage **SHA-512**.
* **Conteneurisation amovible :** Utilisation de protocoles de disques virtuels via **VeraCrypt** et **EDS Lite**.
* **Automatisation :** Scripting via **MacroDroid** pour le déclenchement de scripts de sécurisation post-connexion.

---

## 🛠️ Stack Technologique du Portfolio
* **Langages :** HTML5 pur, CSS3 (Grid & Flexbox), JavaScript (Vanilla ES6).
* **Frameworks Design :** FontAwesome 6.4 (Icônes), Chart.js (Visualisation des données).
* **Typographie :** * *Orbitron / Share Tech Mono :* Immersion technique.
    * *Rajdhani / Inter / Ubuntu :* Lisibilité documentaire et système.

> [!IMPORTANT]
> **Utilisation de l'Intelligence Artificielle :**
> L'intelligence artificielle a été utilisée comme partenaire de réflexion pour :
> 1. La conception et l'optimisation du **visu** et du **style CSS** (UI/UX).
> 2. La structuration algorithmique du code **JavaScript** (moteur de gestion des fenêtres et du boot).
> 3. L'aide à la mise en page de la structure globale pour garantir un code propre et maintenable.

---

## ⚖️ Mentions de Confidentialité & Sécurité
**AVERTISSEMENT :** Ce projet est une simulation pédagogique.
* Les schémas de principe (ex: REP) sont des modèles simplifiés issus de sources publiques (**ASNR**).
* Toutes les données techniques EDF (IP, logs, noms de serveurs) sont **fictives** et ne révèlent aucun secret industriel.
* **Logos EDF et FARN :** Propriété exclusive du groupe EDF.
* **Logo Dragon Kali :** Propriété de Offensive Security.

---

## 👤 Contact
**Florian SCHER** *Alternant SI & Télécoms - Direction de Crise EDF* 📧 [florian.scher.pro@gmail.com](mailto:florian.scher.pro@gmail.com)  
📍 Cap Ampère, Saint-Denis
