# Réseau d’entreprise – Journal Libération

##  Description
Projet de conception et configuration d’un réseau d’entreprise sécurisé pour le journal **Libération**, réalisé avec **Cisco Packet Tracer**.

##  Architecture
- **3 VLANs** : Rédaction (10), IT (20), Serveurs (30)
- **Routage inter-VLAN** sur SW-HQ-L3
- **Trunks** entre les switches
- **SSH** pour l’administration sécurisée
- **NAT Overload** sur routeur 2911 pour l’accès Internet
- **Serveurs** : Web, DNS, Base de données

##  Tests effectués
-  Ping entre VLANs
-  Accès au site web via DNS (`www.liberation.fr`)
-  Connexion SSH depuis PC IT
-  Accès Internet simulé vers FAI et PC-Internet

## Contenu du dépôt
- `liberation.pkt` : topologie Packet Tracer
- `presentation.pdf` : slides de soutenance
- `screenshots/` : captures d’écran des configurations et tests
- `rapport.pdf` : documentation complète

## Technologies utilisées
- Cisco Packet Tracer
- LaTeX (présentation)
- VLAN, Trunk, SSH, NAT, DNS, HTTP

##  Auteur
Zineb ELAMRANI
