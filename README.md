# Oryx Village — site web

Site statique (HTML/CSS/JS, aucune compilation nécessaire).

## Contenu

- `index.html` : le site complet (menu, panier WhatsApp, boutons d'appel, animations)
- `favicon.svg` : icône de l'onglet
- `vercel.json` : configuration Vercel

## Déployer sur Vercel

**Option 1 : depuis le site Vercel**
1. Mets ce dossier dans un dépôt GitHub (glisser-déposer les fichiers sur github.com > New repository > "uploading an existing file").
2. Sur vercel.com : **Add New… > Project**, importe le dépôt.
3. Framework Preset : **Other**. Laisse Build Command et Output Directory vides.
4. Clique **Deploy**.

**Option 2 : en ligne de commande**
```bash
npm i -g vercel
cd oryx-village
vercel --prod
```

## Modifier

- Numéro WhatsApp des commandes : constante `WA` dans le script de `index.html`.
- Plats et prix : tableau `MENU` dans le script de `index.html`.
