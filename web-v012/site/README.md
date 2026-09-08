# Mon Énergie — Web v0.1.2

Web-app/PWA responsive pour le suivi de compteurs électriques prépayés.

Fonctions : tableau de bord, multi-compteurs, relevés, recharges, consommation moyenne, autonomie estimée, alertes, budget, stockage local et mode installable PWA.

La version v0.1.2 démarre sans chiffres fictifs : aucun relevé ni recharge de démonstration n'est préchargé. Les anciennes données de démonstration connues sont retirées lors de la migration, tout en conservant les saisies personnelles quand elles existent.

Dans la page Relevés :
- saisie d'un relevé réel ;
- mise à zéro du compteur par un relevé à 0 kWh ;
- suppression individuelle d'un ancien relevé avec confirmation ;
- recalcul automatique des statistiques après suppression.

Le site n'est pas connecté à l'API CIE et ne génère aucun token de recharge.
