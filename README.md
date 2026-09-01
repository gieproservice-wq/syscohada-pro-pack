# SYSCOHADA Pro Pack — Site web squelette

Site web statique (HTML + Bootstrap 5) réalisé pour la phase de laboratoire
« Site Web Squelette » : 3 pages liées par une navigation commune.

## Structure

```
syscohada-pro-pack/
├── index.html            Page d'accueil
├── fonctionnalites.html  Page des fonctionnalités
├── landing.html          Page de destination (offre + tarif)
├── css/
│   └── style.css         Feuille de style partagée
└── img/                  (dossier réservé aux visuels définitifs)
```

## Notes

- Produit : **SYSCOHADA Pro Pack** (15 000 FCFA), pack de formation/outils
  comptables OHADA avec annexe fiscale Sénégal, marché francophone
  d'Afrique de l'Ouest.
- Images de démonstration via Picsum Photos (libres de droit) — à
  remplacer par les visuels définitifs de la marque.
- Bibliothèques chargées en CDN : Bootstrap 5.3.3 et Bootstrap Icons
  (cdnjs.cloudflare.com).
- Témoignages de la page de destination = exemples illustratifs, à
  remplacer par de vrais retours clients.
- Le bouton « Commander le pack » est un espace réservé : à connecter à
  une solution de paiement (Wave, Orange Money, etc.) lors de la mise en
  production.

## Aperçu en local

Ouvrir `index.html` dans un navigateur, ou lancer un petit serveur local :

```
python3 -m http.server 8000
```

puis visiter `http://localhost:8000`.

## Déploiement

Prêt à être poussé sur GitHub et publié via GitHub Pages (dossier racine).
