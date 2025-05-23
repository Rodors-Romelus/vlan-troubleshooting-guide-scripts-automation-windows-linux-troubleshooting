# 📘 VLAN Troubleshooting Guide - Cisco CLI

Bienvenue dans ce guide avancé de dépannage VLAN dédié aux professionnels du réseau.  
Ce dépôt contient une checklist structurée accompagnée de commandes pratiques pour diagnostiquer les problèmes de VLAN dans un environnement Cisco.

---

## 🧰 Objectifs

- Identifier rapidement les causes de dysfonctionnement VLAN
- Appliquer les bonnes commandes en CLI Cisco
- Vérifier la configuration des ports, trunks, VLANs natifs
- Sécuriser les VLANs en production

---

## 🗂️ Contenu du dépôt

| Nom du fichier | Description |
|----------------|-------------|
| `Checklist_VLAN_CLI_Pro.pdf` | Guide PDF avec 10 étapes de vérification VLAN |
| `README.md` | Présentation du projet |
| `vlan_troubleshooting.md` *(optionnel)* | Version Markdown de la checklist |

---

## 🔍 Aperçu de la checklist

1. Vérifier l'existence du VLAN (`show vlan brief`)
2. Vérifier le mode des ports (`show interfaces status`)
3. Vérifier l'appartenance des ports au VLAN (`switchport access vlan`)
4. Vérifier la configuration trunk (`show interfaces trunk`)
5. Vérifier les VLANs natifs
6. Vérifier le routage inter-VLAN (SVI / L3)
7. Vérifier la configuration du DHCP relay
8. Vérifier les IP clients, ARP, Ping
9. Vérification physique & logs
10. Prévention des tempêtes de broadcast

---

## 🛡️ Conseils de sécurité VLAN

- Ne jamais utiliser VLAN 1 en production
- Bloquer les VLANs non utilisés sur les trunks
- Isoler les VLANs sensibles (admin, serveurs, DMZ)

---

## 👨‍💻 Auteur

**Robinson Rodors S. Romelus**  
Administrateur Systèmes et Réseaux  
📍 Montréal, QC  
📧 rodors.romelus@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/rodors-romelus)

---

## 📢 Contribution

Tu veux contribuer ? Ouvre une issue ou propose un script d’audit VLAN ou de configuration automatisée !
