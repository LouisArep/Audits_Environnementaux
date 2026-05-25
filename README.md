# Audit Environnemental Chantier

Application mobile de suivi environnemental de chantier, conçue pour les visites terrain. Elle permet de renseigner des points de contrôle par catégorie, d'associer des photos à chaque item et de générer un rapport exportable.

---

## Fonctionnalités

- Checklist structurée en 7 catégories : Installation de chantier, Affichages, Déchets, Pollution, Gestion de l'eau, Nuisances, Biodiversité
- 5 statuts par item : Conforme, À améliorer, Non conforme, Non vérifié, Non concerné
- Prise de photos depuis l'appareil photo ou la galerie, associées directement à chaque item
- Champ de remarques par item
- Récapitulatif de visite avec avancement par catégorie
- Export d'un rapport complet en **HTML** (avec photos intégrées) et en **Word (.docx)** directement depuis l'application
- Compression automatique des photos à l'export pour alléger les fichiers
- Données stockées localement sur l'appareil — aucun envoi sur internet
- Écran Paramètres pour changer le dossier de travail en cours d'utilisation

---

## Compatibilité

L'application fonctionne sur **Android** et **PC/Mac**, avec **Chrome ou Edge**. Elle n'est pas compatible avec Firefox, Samsung Internet ou Safari iOS.

> Sur PC, l'application peut être ouverte directement depuis le fichier `.html` dans Edge ou Chrome, sans installation. Elle est principalement conçue pour une utilisation mobile sur le terrain.

---

## Installation sur Android

1. Ouvrir Chrome sur votre téléphone
2. Accéder à l'adresse : `https://louisarep.github.io/Audits_Environnementaux/`
3. Ouvrir le menu (trois points en haut à droite)
4. Sélectionner "Installer l'application" ou "Ajouter à l'écran d'accueil"
5. L'application est accessible depuis l'écran d'accueil du téléphone

---

## Première utilisation

Au premier lancement, l'application demande de choisir un dossier sur l'appareil pour stocker les audits et les photos. Créer un dossier dédié est recommandé, par exemple `Documents/Audits_Environnement`.

Le nom du dossier est mémorisé entre les sessions. À chaque réouverture, le navigateur demande de confirmer l'accès au dossier — il suffit de sélectionner le même dossier dans la fenêtre qui s'ouvre. Sur Android/Chrome, le navigateur s'ouvre directement au bon endroit.

Une fois le dossier configuré, créer un nouvel audit via le bouton correspondant, renseigner les informations du chantier, puis naviguer dans les catégories pour compléter la visite.

Le dossier de travail peut être modifié à tout moment depuis l'écran **Paramètres** (icône en haut à droite de l'accueil).

---

## Export du rapport

Deux formats sont disponibles depuis l'écran de récapitulatif :

### Export HTML (avec photos)
Le rapport est généré et sauvegardé dans le dossier de travail. Pour l'ouvrir dans Word sur PC :
1. Transférer le fichier `.html` sur l'ordinateur (OneDrive, Teams, email…)
2. Dans Word : Fichier > Ouvrir > sélectionner le fichier
3. Le rapport s'affiche avec les photos intégrées
4. Il peut ensuite être enregistré en `.docx` ou exporté en PDF

### Export Word (.docx)
Le fichier `.docx` est généré directement et téléchargé sur l'appareil. Il peut être ouvert dans Microsoft Word sans manipulation supplémentaire. Les photos sont compressées automatiquement pour alléger le fichier.

> L'export Word nécessite une connexion internet au premier usage (chargement de la librairie docx.js). Les exports suivants dans la même session n'en ont pas besoin.

---

## Points d'attention

- En cas de changement de téléphone, sauvegarder le dossier de travail sur OneDrive avant la migration
- Le rapport doit être exporté à la fin de chaque visite — c'est la sauvegarde principale des données structurées
- Les mises à jour de l'application sont automatiques au prochain lancement, si l'appareil est connecté à internet
