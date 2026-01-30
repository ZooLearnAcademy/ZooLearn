# 📁 ZooLearn - Complete File Structure

> A comprehensive Zoology learning platform built with React + Vite

---

## 📦 Root Directory

```
d:\hackthon\zoo\
├── 📄 index.html
├── 📄 package.json
├── 📄 vite.config.js
├── 📄 eslint.config.js
├── 📁 public/
└── 📁 src/                          # Main source code
```

---

## 📁 src/ - Source Code

```
src/
├── 📄 App.jsx                       # Main routing & layout
├── 📄 App.css                       # App-level styles
├── 📄 index.css                     # Global CSS reset & variables
├── 📄 main.jsx                      # React entry point
│
├── 📁 context/
│   └── 📄 AuthContext.jsx           # Authentication context
│
└── 📁 Components/                   # All UI components
```

---

## 📁 Components/ - UI Components

```
Components/
├── 📄 ProtectedRoute.jsx            # Auth route wrapper
├── 📄 ScrollToHash.jsx              # Hash scroll utility
├── 📄 ScrollToTop.jsx               # Scroll restoration
│
├── 📁 About/                        # About page
│   ├── 📄 About.jsx
│   ├── 📄 About.css
│   ├── 📄 HomePage.css
│   └── 📁 Footer/
│       ├── 📄 Footer.jsx
│       └── 📄 Footer.css
│
├── 📁 Banner/                       # Hero banner
│   ├── 📄 Banner.jsx
│   └── 📄 Banner.css
│
├── 📁 Footer/                       # Global footer
│   ├── 📄 Footer.jsx
│   └── 📄 Footer.css
│
├── 📁 Header/                       # Navigation header
│   ├── 📄 Header.jsx
│   ├── 📄 Header.css
│   ├── 📄 ProfileCard.jsx
│   └── 📄 ProfileCard.css
│
├── 📁 Legal/                        # Legal pages
│   ├── 📄 Legal.jsx
│   └── 📄 Legal.css
│
├── 📁 login/                        # Authentication
│   ├── 📄 SignIn.jsx
│   ├── 📄 SignIn.css
│   └── ... (other auth files)
│
├── 📁 Home/                         # Home page
│   ├── 📁 Learning/
│   │   ├── 📄 Learning.jsx
│   │   └── 📄 Learning.css
│   ├── 📁 scientist/
│   │   ├── 📄 ScientistCarousel.jsx
│   │   └── 📄 ScientistCarousel.css
│   ├── 📁 Footer/
│   │   ├── 📄 Footer.jsx
│   │   └── 📄 Footer.css
│   └── 📁 Organisms/
│       └── 📁 leech/
│           ├── 📄 LeechLayout.jsx
│           ├── 📄 leech.css
│           ├── 📁 banner/
│           │   ├── 📄 Intro.jsx
│           │   └── 📄 Intro.css
│           └── 📁 sections/
│               ├── 📄 BodyWall.jsx
│               ├── 📄 BodyWall.css
│               ├── 📄 bodyDivisions.jsx
│               ├── 📄 circulatorySystem.jsx
│               ├── 📄 digestivesystem.jsx
│               ├── 📄 excretorySystem.jsx
│               ├── 📄 externalMorphology.jsx
│               ├── 📄 locomotion.jsx
│               ├── 📄 nervousSystem.jsx
│               ├── 📄 parasiticAdaptations.jsx
│               ├── 📄 reproductiveSystem.jsx
│               ├── 📄 respiratorySystem.jsx
│               ├── 📄 revision.jsx
│               ├── 📄 taxonomy.jsx
│               └── ... (corresponding .css files)
│
├── 📁 livingworld/                  # Living World page
│   ├── 📄 TheLivingWorld.jsx
│   ├── 📄 TheLivingWorld.css
│   ├── 📁 Binomial/
│   │   ├── 📄 Binomial.jsx
│   │   └── 📄 Binomial.css
│   ├── 📁 LivingWorldIntro/
│   │   ├── 📄 LivingWorldIntro.jsx
│   │   └── 📄 LivingWorldIntro.css
│   ├── 📁 TaxonomySystematics/
│   │   ├── 📄 TaxonomySystematics.jsx
│   │   └── 📄 TaxonomySystematics.css
│   ├── 📁 circle/
│   │   ├── 📄 KingdomChart.jsx
│   │   └── 📄 KingdomChart.css
│   ├── 📁 pramid/
│   │   ├── 📄 TaxonomyPage.jsx
│   │   └── 📄 TaxonomyPage.css
│   ├── 📁 rulecard/
│   │   ├── 📄 BinomialRules.jsx
│   │   └── 📄 BinomialRules.css
│   └── 📁 Footer/
│       ├── 📄 Footer.jsx
│       └── 📄 Footer.css
│
├── 📁 tree/                         # Taxonomy Tree
│   ├── 📄 tree.jsx
│   ├── 📄 tree.css
│   └── ... (tree utilities)
│
├── 📁 BasicFeaturesOfClassification/
│   ├── 📄 BasicFeatures.jsx
│   ├── 📄 BasicFeatures.css
│   ├── 📁 BodyPlans/
│   │   ├── 📄 BodyPlans.jsx
│   │   ├── 📄 BodyPlans.css
│   │   ├── 📄 ProtostomeComparison.jsx
│   │   └── 📄 ProtostomeComparison.css
│   ├── 📁 BodySymmetry/
│   │   ├── 📄 BodySymmetry.jsx
│   │   └── 📄 BodySymmetry.css
│   ├── 📁 Coelom/
│   │   ├── 📄 Coelom.jsx
│   │   └── 📄 Coelom.css
│   ├── 📁 Development/
│   │   ├── 📄 Development.jsx
│   │   └── 📄 Development.css
│   ├── 📁 GermLayers/
│   │   ├── 📄 GermLayers.jsx
│   │   └── 📄 GermLayers.css
│   ├── 📁 Intro/
│   │   ├── 📄 Intro.jsx
│   │   └── 📄 Intro.css
│   ├── 📁 LevelsOfOrganisation/
│   │   ├── 📄 LevelsOfOrganisation.jsx
│   │   └── 📄 LevelsOfOrganisation.css
│   ├── 📁 Metazoa/
│   │   ├── 📄 Metazoa.jsx
│   │   └── 📄 Metazoa.css
│   ├── 📁 Nutrition/
│   │   ├── 📄 Nutrition.jsx
│   │   └── 📄 Nutrition.css
│   └── 📁 TaxonomySession/
│       ├── 📄 TaxonomySession.jsx
│       └── 📄 TaxonomySession.css
│
└── 📁 zoohub/                       # 🦎 ZooHub - Animal Kingdom
```

---

## 📁 zoohub/ - Animal Kingdom Explorer (546 files)

```
zoohub/
├── 📄 ZooHub.jsx                    # Main ZooHub page
├── 📄 ZooHub.css                    # ZooHub styles
│
├── 📁 porifera/                     # Phylum: Porifera (Sponges)
│   ├── 📄 Porifera.jsx
│   ├── 📄 Porifera.css
│   ├── 📄 PoriferaHub.jsx
│   ├── 📄 poriferaData.json
│   │
│   ├── 📁 calcarea/                 # Class: Calcarea
│   │   ├── 📁 sycon/
│   │   │   ├── 📄 GenusSycon.jsx
│   │   │   └── 📄 GenusSycon.css
│   │   ├── 📁 leucosolenia/
│   │   │   ├── 📄 Leucosolenia.jsx
│   │   │   └── 📄 Leucosolenia.css
│   │   └── 📁 grantia/
│   │       ├── 📄 Grantia.jsx
│   │       └── 📄 Grantia.css
│   │
│   ├── 📁 hexactinellida/           # Class: Hexactinellida
│   │   ├── 📁 euplectella/
│   │   │   ├── 📄 Euplectella.jsx
│   │   │   └── 📄 Euplectella.css
│   │   └── 📁 hyalonema/
│   │       ├── 📄 Hyalonema.jsx
│   │       └── 📄 Hyalonema.css
│   │
│   └── 📁 demospongiae/             # Class: Demospongiae
│       ├── 📁 spongilla/
│       │   ├── 📄 Spongilla.jsx
│       │   └── 📄 Spongilla.css
│       ├── 📁 euspongia/
│       │   ├── 📄 Euspongia.jsx
│       │   └── 📄 Euspongia.css
│       ├── 📁 cliona/
│       │   ├── 📄 Cliona.jsx
│       │   └── 📄 Cliona.css
│       ├── 📁 chalina/
│       │   ├── 📄 Chalina.jsx
│       │   └── 📄 Chalina.css
│       └── 📁 xestospongia/
│           ├── 📄 Xestospongia.jsx
│           └── 📄 Xestospongia.css
│
├── 📁 coelenterata/                 # Phylum: Coelenterata (Cnidaria)
│   ├── 📄 Coelenterata.jsx
│   ├── 📄 Coelenterata.css
│   ├── 📄 CoelenterataData.json
│   │
│   ├── 📁 hydrozoa/                 # Class: Hydrozoa
│   │   ├── 📁 hydra/
│   │   │   ├── 📄 Hydra.jsx
│   │   │   └── 📄 Hydra.css
│   │   └── 📁 obelia/
│   │       ├── 📄 Obelia.jsx
│   │       └── 📄 Obelia.css
│   │
│   ├── 📁 scyphozoa/                # Class: Scyphozoa
│   │   └── 📁 aurelia/
│   │       ├── 📄 Aurelia.jsx
│   │       └── 📄 Aurelia.css
│   │
│   └── 📁 anthozoa/                 # Class: Anthozoa
│       ├── 📁 adamsia/
│       │   ├── 📄 Adamsia.jsx
│       │   └── 📄 Adamsia.css
│       └── ... (more species)
│
├── 📁 ctenophora/                   # Phylum: Ctenophora (Comb Jellies)
│   ├── 📄 Ctenophora.jsx
│   ├── 📄 Ctenophora.css
│   └── 📁 species/
│       ├── 📁 pleurobrachia/
│       ├── 📁 ctenoplana/
│       └── 📁 hormiphora/
│
├── 📁 platyhelminthes/              # Phylum: Platyhelminthes (Flatworms)
│   ├── 📄 Platyhelminthes.jsx
│   ├── 📄 Platyhelminthes.css
│   └── 📁 species/
│       ├── 📁 dugesia/
│       ├── 📁 fasciola/
│       ├── 📁 schistosoma/
│       └── 📁 taenia/
│
├── 📁 aschelminthes/                # Phylum: Aschelminthes (Roundworms)
│   ├── 📄 Aschelminthes.jsx
│   ├── 📄 Aschelminthes.css
│   └── 📁 species/
│       ├── 📁 ascaris/
│       └── 📁 wuchereria/
│
├── 📁 annelida/                     # Phylum: Annelida (Segmented Worms)
│   ├── 📄 Annelida.jsx
│   ├── 📄 Annelida.css
│   └── 📁 species/
│       ├── 📁 lumbricus/            # Earthworm
│       │   ├── 📄 Lumbricus.jsx
│       │   └── 📄 Lumbricus.css
│       └── 📁 hirudinaria/          # Leech
│           ├── 📄 Hirudinaria.jsx
│           └── 📄 Hirudinaria.css
│
├── 📁 arthropoda/                   # Phylum: Arthropoda (66 files)
│   ├── 📄 Arthropoda.jsx
│   ├── 📄 Arthropoda.css
│   ├── 📁 insecta/                  # Class: Insecta
│   │   ├── 📁 periplaneta/          # Cockroach
│   │   ├── 📁 musca/                # Housefly
│   │   └── ... (more insects)
│   ├── 📁 crustacea/                # Class: Crustacea
│   ├── 📁 arachnida/                # Class: Arachnida
│   └── 📁 myriapoda/                # Class: Myriapoda
│
├── 📁 mollusca/                     # Phylum: Mollusca (36 files)
│   ├── 📄 Mollusca.jsx
│   ├── 📄 Mollusca.css
│   ├── 📁 gastropoda/               # Class: Gastropoda
│   │   └── 📁 pila/                 # Apple Snail
│   │       ├── 📄 Pila.jsx
│   │       └── 📄 Pila.css
│   ├── 📁 cephalopoda/              # Class: Cephalopoda
│   │   └── 📁 octopus/
│   │       ├── 📄 Octopus.jsx
│   │       └── 📄 Octopus.css
│   └── 📁 bivalvia/                 # Class: Bivalvia
│
├── 📁 echinodermata/                # Phylum: Echinodermata (22 files)
│   ├── 📄 Echinodermata.jsx
│   ├── 📄 Echinodermata.css
│   └── 📁 species/
│       ├── 📁 asterias/             # Starfish
│       ├── 📁 echinus/              # Sea Urchin
│       └── 📁 holothuria/           # Sea Cucumber
│
├── 📁 hemichordata/                 # Phylum: Hemichordata (8 files)
│   ├── 📄 Hemichordata.jsx
│   ├── 📄 Hemichordata.css
│   └── 📁 species/
│       └── 📁 balanoglossus/
│           ├── 📄 Balanoglossus.jsx
│           └── 📄 Balanoglossus.css
│
└── 📁 chordata/                     # Phylum: Chordata (254 files)
    ├── 📄 Chordata.jsx
    ├── 📄 Chordata.css
    ├── 📁 protochordata/            # Subphylum: Protochordata
    │   └── 📁 branchiostoma/
    │       ├── 📄 Branchiostoma.jsx
    │       └── 📄 Branchiostoma.css
    ├── 📁 pisces/                   # Class: Pisces (Fish)
    ├── 📁 amphibia/                 # Class: Amphibia
    ├── 📁 reptilia/                 # Class: Reptilia
    ├── 📁 aves/                     # Class: Aves (Birds)
    └── 📁 mammalia/                 # Class: Mammalia
```

---

## 🔗 Route Structure

| Route | Component | Description |
|-------|-----------|-------------|
| `/` | `Home` | Home page |
| `/living-world` | `TheLivingWorld` | Living World learning page |
| `/taxonomy-tree` | `Tree` | Interactive taxonomy tree |
| `/basic-features-of-classification` | `BasicFeatures` | Classification concepts |
| `/zoohub` | `ZooHub` | Animal Kingdom explorer |
| `/zoohub/porifera` | `ZooHub` | Porifera phylum section |
| `/zoohub/porifera/sycon` | `GenusSycon` | Sycon species page |
| `/zoohub/porifera/leucosolenia` | `Leucosolenia` | Leucosolenia species page |
| `/zoohub/porifera/grantia` | `Grantia` | Grantia species page |
| `/about` | `About` | About page |
| `/profile` | `Profile` | User profile |
| `/legal` | `Legal` | Legal information |
| `/leech` | `LeechLayout` | Leech organism study |

---

## 📊 File Count Summary

| Directory | Files | Description |
|-----------|-------|-------------|
| `src/` | 4 | Core app files |
| `Components/` | 667 | All UI components |
| `zoohub/` | 546 | Animal species pages |
| `Home/` | 41 | Home page sections |
| `BasicFeatures/` | 29 | Classification features |
| `livingworld/` | 19 | Living World content |

---

## 🛠️ Technology Stack

- **Framework**: React 18 + Vite
- **Routing**: React Router DOM
- **Styling**: CSS (component-scoped)
- **Icons**: Lucide React
- **Auth**: Custom AuthContext
- **Notifications**: React Toastify

---

## 📝 File Naming Convention

- **Components**: `PascalCase.jsx` (e.g., `GenusSycon.jsx`)
- **Styles**: `PascalCase.css` (matching component name)
- **Data**: `camelCase.json` (e.g., `poriferaData.json`)
- **Folders**: `lowercase` (e.g., `calcarea/`, `hydrozoa/`)

---

*Generated for ZooLearn Project - January 2026*
