# Mon Energie

Application mobile Flutter et web-app/PWA de suivi de consommation des compteurs électriques prépayés.

## Fonctions

- Tableau de bord énergétique
- Gestion de plusieurs compteurs
- Relevés manuels et par photo
- Calcul de consommation moyenne
- Estimation d'autonomie
- Historique des recharges
- Alertes de solde faible et critique
- Budget mensuel
- Version web responsive et installable comme PWA

> Le projet n'est pas connecté à l'API CIE et ne génère pas de token CIE.

## Site web

Le workflow `.github/workflows/deploy-web.yml` publie automatiquement la web-app avec GitHub Pages.

Activation initiale à faire une seule fois dans GitHub :

1. Ouvrir **Settings** du dépôt.
2. Aller dans **Pages**.
3. Dans **Build and deployment**, choisir **GitHub Actions** comme source.
4. Ouvrir **Actions > Deploy Mon Energie Web** et relancer le workflow.

URL prévue après activation : `https://ryko95.github.io/Mon-Energie/`

## APK

Le workflow `.github/workflows/build-apk.yml` compile l'APK Android et le publie comme artefact GitHub Actions.
