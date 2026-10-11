# Matmata Moto Store — Gestion de vente et de stock

Application web (HTML/CSS/JS, sans serveur) : tableau de bord, produits, ventes (panier), rapports, alertes, commandes, comparaison de prix, fournisseurs, clients.

## Mise en ligne sur GitHub Pages
1. Créez un dépôt GitHub (ex. `matmata-moto-store`) et déposez `index.html`, `data.json`, `README.md`.
2. Dépôt → **Settings → Pages** → Source : *Deploy from a branch* → branche `main`, dossier `/ (root)` → Save.
3. L'application sera disponible sur `https://<votre-compte>.github.io/matmata-moto-store/`.

## Données
- `data.json` contient les ventes, fournisseurs et clients du fichier Excel, chargés au premier lancement. **Le tableau des produits démarre vide.**
- `produits-initiaux.xlsx` contient la liste des 832 produits : téléchargez-la depuis la page Produits, puis cliquez sur « Remplir le tableau (Excel) ».
- Ensuite tout est enregistré dans le navigateur (localStorage). Utilisez la page **Données** pour exporter/importer une sauvegarde JSON.
- Les données étant locales à chaque navigateur, exportez-les pour passer d'un appareil à un autre.
