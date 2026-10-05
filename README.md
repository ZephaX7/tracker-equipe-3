# Trackr 
Suivre tous ses colis au même endroit : recherche par numéro de suivi, statut et date de livraison estimée. Application fictive réalisée par l'équipe N (Ynov Val d'Europe, Bachelor 2, 2026-2027).  /Utilisateur ou évaluateur
 ## Installation 
Prérequis : Node.js 22 ou plus (`node -v`), Git.
 ```bash 
git clone https://github.com//trackr-equipe-N.git
 cd trackr-equipe-N
 npm install
 npm run dev 
``` L'application s'ouvre sur http://localhost:5173 avec 6 colis. /Nouveau développeur
 ## Utilisation
 | Commande | Effet | 
	
 | `npm run dev` | Serveur de développement avec rechargement |
 | `npm run build` | Vérifie les types, construit la version dans dist/ | 
| `npm run preview` | Sert la version construite | 
| `npm run lint` | Analyse le code (oxlint) | 
Les données sont fictives : `src/data/colis.ts` (6 colis de démonstration). 
/Utilisateur ou évaluateur
## Architecture 
``` 
src/ ├── App.tsx état de la page (recherche, filtre) et assemblage 
├── components/ composants d'affichage (CarteColis, ListeColis…) 
├── data/colis.ts colis de démonstration 
├── utils/ fonctions sans effet de bord (recherche, dates, tri) 
└── types.ts types Colis et Statut 
``` 
Les décisions techniques sont expliquées dans [docs/adr/](docs/adr/).
/Nouveau développeur
 ## Contribuer 
Une issue, une branche `type/numéro-sujet`, une Pull Request relue (1 Approve obligatoire). Détails : [CONTRIBUTING.md](CONTRIBUTING.md).
/Contributeur

## Equipe
Nom	Pseudo GitHub	Rôle
Romain Voynier	@RomainVoynier	Développeur
Theo Delourneau-Maussant	@ZephaX7	Chef de projet
Augustin Benoit	@Augustin-Benoit	Développeur
Preston Walter-Bassette	@Prestonwalterbassette	Développeur


Application (fictive) de suivi de colis, en React + TypeScript.

