# DUNKELGANG MC — Archives

Site web de worldbuilding fictif pour le **Dunkelgang MC**, un club de bikers 1% ancré dans la région franco-allemande du Rhin supérieur, fondé en 1971.

> Projet de création fictive. Tous les personnages, événements et organisations décrits sont imaginaires.

---

## Structure du projet

```
dunkelgang_mc/
├── index.html          # Point d'entrée — layout principal + navigation
├── logo.png            # Patch du club
├── shared.css          # Styles partagés entre toutes les pages
│
├── synthese.html       # Fiche de synthèse du club
│
├── kaspar.html         # Kaiser — Pierre Kaspar
├── morel.html          # Pater — André Morel
├── wolff.html          # Klingen — Karl Wolff
├── perrin.html         # Grillon — Luc Perrin
├── stein.html          # Brume — Raymond Stein
├── aubry.html          # Chacal — Michel Aubry
├── keller.html         # Rabe — Ernst Keller
├── brandt.html         # Maulwurf — Hans Brandt
├── voss.html           # Nichts — Otto Voss
├── volkov.html         # Volk — Alexandre Volkov
│
├── territoire.html     # Chapters et axes territoriaux
├── carte.html          # Carte interactive SVG
│
├── activites.html      # Activités légales et illégales
├── sentinel.html       # Sentinel GmbH — façade légale
│
├── historique.html     # Fil historique 1946→1989
├── crises.html         # Grandes crises 1974→1989
│
├── relations.html      # Alliances, ennemis, autorités
│
├── grades.html         # Grades et fonctions du club
├── ecussons.html       # Écussons spéciaux
└── regles.html         # Règles internes
```

---

## Déploiement

### GitHub Pages

1. Fork ou clone ce dépôt
2. Dans **Settings → Pages**, sélectionne la branche `main` et le dossier `/root`
3. Le site est accessible à `https://[ton-username].github.io/[nom-du-repo]`

### Netlify

1. Drag & drop le dossier sur [netlify.com/drop](https://app.netlify.com/drop)
2. C'est en ligne immédiatement — gratuit

### Serveur local

```bash
# Python (Mac/Linux)
python3 -m http.server 8080

# Node.js
npx serve .
```

Puis ouvre `http://localhost:8080`

> ⚠️ Le site nécessite un serveur HTTP pour fonctionner — ouvrir `index.html` directement dans le navigateur (`file://`) ne fonctionne pas à cause des requêtes `fetch()`.

---

## Contenu

| Section | Description |
|---|---|
| **Club** | Synthèse — origines, territoire, activités, chapters |
| **Membres** | 10 fiches fondateurs avec profil, parcours, écussons |
| **Territoire** | 9 chapters (1971→1989), axes Nord/Sud/Est/Ouest, carte SVG interactive |
| **Activités** | Trafic d'armes, Sentinel GmbH, passage de clandestins, jeu illégal |
| **Histoire** | Fil chronologique 1946→1989, 15 grandes crises |
| **Relations** | Clubs MC, crime organisé, autorités des deux côtés du Rhin |
| **Code** | Grades nordiques, écussons spéciaux, règles internes |

---

## Contexte fictif

Le Dunkelgang MC naît en 1971 des cendres de la cellule clandestine **DACHS** — un réseau stay-behind OTAN opérant sur le Rhin supérieur pendant la Guerre froide. Après une trahison au sein de la hiérarchie OTAN, les 10 membres survivants fondent le club à **Breisach am Rhein**, là où ils ont été formés ensemble au CEC 4.

Le club est binational dès l'origine — français et allemands, deux rives, un seul patch.

---

*Projet de worldbuilding fictif — co-construit avec Claude (Anthropic)*
