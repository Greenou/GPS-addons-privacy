# Politique de confidentialité — Addons GPS · Planisware

*Dernière mise à jour : 9 mars 2026*

## 1. Présentation

**Addons GPS · Planisware** est une extension Chrome développée par Yann Barthaux-Vallée à usage interne EDF. Elle opère exclusivement sur le domaine `https://prod-sdin.edf.fr` (application Planisware EDF).

## 2. Données collectées

**Cette extension ne collecte aucune donnée personnelle.**

Elle ne collecte pas, ne stocke pas et ne transmet pas :
- d'informations permettant d'identifier l'utilisateur (nom, e-mail, identifiant…)
- d'historique de navigation
- de contenu des pages visitées
- de données de localisation
- de communications personnelles
- de données financières ou de santé

## 3. Données stockées localement

L'extension stocke uniquement des **préférences d'interface** sur l'appareil de l'utilisateur :

| Mécanisme | Clé | Valeur | Rôle |
|---|---|---|---|
| `chrome.storage.sync` | `devMode` | booléen | Activer/désactiver le mode développeur |
| `chrome.storage.sync` | `checkTable` | booléen | Activer le contrôle du tableau Descriptif |
| `chrome.storage.sync` | `checkTP` | booléen | Activer le contrôle des inputs Descriptif |
| `localStorage` | `navig_help_hidden` | `'0'` ou `'1'` | Visibilité du bloc d'aide dans la popup |

Ces données **ne quittent jamais l'appareil** vers un serveur externe. `chrome.storage.sync` peut synchroniser les préférences entre les appareils Chrome connectés au même compte Google, conformément au fonctionnement standard de l'API Chrome.

## 4. Permissions utilisées

| Permission | Justification |
|---|---|
| `activeTab` | Interagir avec l'onglet Planisware actif lors d'une action utilisateur explicite |
| `scripting` | Exécuter des actions d'interface dans la page Planisware (mode développeur uniquement) |
| `storage` | Persister les préférences utilisateur entre les sessions |
| `https://prod-sdin.edf.fr/*` | Domaine unique sur lequel l'extension est active |

## 5. Code distant

L'extension n'utilise **aucun code distant**. L'intégralité du code JavaScript est incluse dans le package de l'extension. Aucune requête vers un CDN, serveur analytique ou service tiers n'est effectuée.

## 6. Partage des données

Aucune donnée n'est vendue, partagée ou transmise à des tiers, quelle qu'en soit la raison.

## 7. Contact

Pour toute question relative à cette politique : **yann.barthaux-vallee@edf.fr**
