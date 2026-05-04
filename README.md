# PromoInvest une appli pour faire un tirage aléatoire dans une tontine entre amis 

Une solution simple, transparente et automatisée pour gérer une tontine de groupe (conçue pour 20 participants). Ce projet se compose d'une interface web de tirage au sort et d'un outil de suivi financier.

## Fonctionnalités

* **Tirage au sort équitable** : Algorithme de mélange aléatoire (Fisher-Yates) pour définir l'ordre de passage des membres, avec un affichage progressif pour le suspense.
* **Compte à rebours intégré** : Visualisation en temps réel du temps restant avant la prochaine levée de fonds.
* **Interface Web Responsive** : Accessible sur mobile ou PC, parfaite pour être partagée lors d'un appel vidéo de groupe.
* **Suivi Financier Premium** : Un fichier Excel (fourni séparément) avec tableau de bord dynamique, suivi des cotisations hebdomadaires, mise en évidence des statuts de paiement et génération de relevés PDF.

## Technologies Utilisées

* **Interface Web** : HTML5, CSS3, Vanilla JavaScript.
* **Gestion Financière** : Microsoft Excel (.xlsx avec formules avancées et mise en forme conditionnelle).

## Déploiement

L'application web est conçue pour être déployée instantanément sur des plateformes d'hébergement statique.

**Via Vercel (Recommandé) :**
1. Forkez ou clonez ce dépôt GitHub.
2. Connectez-vous sur [Vercel](https://vercel.com) et importez le dépôt.
3. Le déploiement se fait automatiquement sans configuration supplémentaire.

## Utilisation

1. **Le tirage** : Le jour J, lancez l'application web. Saisissez les 20 noms séparés par des virgules et cliquez sur le bouton de tirage pour générer l'ordre officiel.
2. **Le suivi** : Reportez cet ordre dans le fichier `Tontine_Premium_Design.xlsx`.
3. **Les relances** : Utilisez l'onglet "Relevé de la Semaine" de l'Excel pour exporter la situation à jour en PDF et la partager au groupe.

## Auteur

**Bruno Bengono Bekolo**
