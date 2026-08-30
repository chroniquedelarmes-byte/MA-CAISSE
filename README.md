# Livre de caisse de l'église

Application de gestion des finances de l'église — le solde se calcule automatiquement dès qu'une entrée ou une sortie est saisie.

## Tester en local

```bash
npm install
npm run dev
```

Ouvre ensuite l'adresse affichée dans le terminal (ex : http://localhost:5173).

## Mettre le projet sur GitHub

1. Crée un nouveau dépôt sur https://github.com/new (nom suggéré : `finances-eglise`)
2. Dans ce dossier, exécute :

```bash J
git init
git add .
git commit -m "Première version : registre avec calcul automatique du solde"
git branch -M main
git remote add origin https://github.com/TON-NOM-UTILISATEUR/finances-eglise.git
git push -u origin main
```

## Tester en ligne avec GitHub Pages (gratuit, lien public)

```bash
npm install
npm run build
npm run deploy
```

Puis, dans les paramètres du dépôt GitHub (Settings → Pages), choisis la branche `gh-pages`.
Ton application sera accessible à une adresse du type :
`https://TON-NOM-UTILISATEUR.github.io/finances-eglise/`
