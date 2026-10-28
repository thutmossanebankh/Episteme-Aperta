<div align="center">

# Épistémè Aperta

### La R&D, l'Open Source, l'Open Science et l'IA Agentique

**Pour une refondation de la philosophie africaine
et de la recherche scientifique et technologique en Afrique**

*par Salvador-José Mountanta Famorosa*

![Langue](https://img.shields.io/badge/langue-français-1f3a5f)
![Format](https://img.shields.io/badge/format-LaTeX-b06020)
![Statut](https://img.shields.io/badge/statut-en%20rédaction-6e3c8c)
![Licence](https://img.shields.io/badge/licence-tous%20droits%20réservés-8b0000)

</div>

---

> *L'Afrique est absente de la carte mondiale de la source ouverte.
> Ce qui est absent du code est absent du monde à venir.*

## Le propos

Le monde a déjà changé de civilisation. L'intelligence artificielle découvre des théorèmes, conçoit des molécules et, avec la robotique, a maintenant un corps. Les États qui maîtrisent le calcul, les semi-conducteurs et les standards ouverts dictent les règles. Les autres les subissent.

**Épistémè Aperta** part d'un constat : la philosophie et la recherche africaines tournent encore dans des **épistémès fermées**. Ce sont la colonialité du savoir, le mimétisme stérile et la réinvention perpétuelle de la roue.

L'ouvrage propose une sortie en trois temps :

1. **Une rupture** : la *catharsis* épistémologique, au sens de Bachelard.
2. **Une raison ouverte** : le *Logos Apertus*. Ses normes sont la publicité des méthodes, la reproductibilité et la réfutabilité. L'Open Science et l'Open Source en sont la forme concrète.
3. **Une stratégie** : la *Mimésis stratégique*. Il s'agit de copier, assimiler, innover, puis devenir indépendant et puissant. C'est l'*Aufhebung* hégélienne appliquée à la technologie.

Ce n'est pas seulement un livre de philosophie. C'est aussi un **protocole de formation** et un **manuel de souveraineté**.

## Architecture de l'ouvrage

| Partie | Titre | Ce qu'elle apporte |
|:---:|---|---|
| **I** | **Théorie** : fondations épistémiques et ontologiques | Catharsis, *Logos Apertus*, critique de l'ethnophilosophie, *Techné* et *Dunamis*, *Aufhebung* technologique, lexique propédeutique |
| **II** | **Pratique** : le protocole RPA | 15 modules : GNU/Linux, LaTeX, programmation (C, C++, Python, Rust…), science ouverte, IA agentique, matériel ouvert (ESP32, Arduino, Raspberry Pi, LoRa), IoT, robotique, R&D par discipline |
| **III** | **Gouvernance technique** | ITIL v4, Agile, gestion de projet, standards ouverts et normes ISO, gouvernance des données de recherche |
| **IV** | **Pour le décideur politique** | OSINT/GEOSINT, technologies critiques (ASML, TSMC, Nvidia, SWIFT, GPS), guerre économique, dépendances, modèles de pouvoir à l'ère de l'IA, intégration africaine |

### Le protocole RPA

Chaque module de formation porte l'un de ces deux niveaux :

- 🟩 **Incontournable** : pour tout chercheur, étudiant ou citoyen.
- 🟪 **Spécialité** : selon la discipline, le projet ou le niveau d'expertise.

Pour commencer : **tout chercheur doit devenir un GLDPU**, c'est-à-dire un utilisateur de distribution GNU/Linux de bureau.

## À qui s'adresse ce livre

- **Aux chercheurs et enseignants-chercheurs** : avoir quatre doctorants et trois masters ne suffit plus. L'IA est le nouveau laboratoire.
- **Aux étudiants**, du lycée à l'université : Linux, LaTeX, programmation et IA, pas à pas.
- **Aux philosophes** qui veulent dépasser le débat Hountondji–ethnophilosophie.
- **Aux décideurs politiques** : aucun État ne devient autonome sans connaître les technologies qui gouvernent le monde.

## Compiler le document

Le source est en LaTeX. Il est prévu pour **TeXstudio** sous **Ubuntu**.

```bash
# Dépendances (Ubuntu / Debian)
sudo apt install texlive-latex-extra texlive-lang-french texlive-fonts-recommended

# Compilation (deux passes pour la table des matières)
pdflatex plan_episteme_aperta.tex
pdflatex plan_episteme_aperta.tex

# ou, plus simplement
latexmk -pdf plan_episteme_aperta.tex
```

## Contenu du dépôt

```
.
├── plan_episteme_aperta.tex   # Plan complet de l'ouvrage (LaTeX)
├── README.md                  # Ce fichier
└── LICENSE                    # Licence propriétaire — tous droits réservés
```

## Statut

📝 **En cours de rédaction.** Le plan est arrêté. La rédaction des chapitres est en cours.

## Licence

**© 2026 Salvador-José Mountanta Famorosa. Tous droits réservés.**

Cette œuvre **n'est pas** sous licence libre. Vous pouvez la lire sur GitHub. Toute reproduction, diffusion, adaptation, traduction ou utilisation commerciale exige l'**autorisation écrite préalable de l'auteur**. L'usage pour entraîner des modèles d'IA l'exige aussi.
Les conditions complètes figurent dans le fichier [`LICENSE`](./LICENSE).

> Un livre qui défend l'ouverture peut-il être protégé ? Oui. Ouvrir une méthode n'oblige pas à renoncer à son œuvre.
> Les idées circulent. Le texte reste à son auteur.

## Citer cet ouvrage

```bibtex
@book{famorosa_episteme_aperta,
  author    = {Mountanta Famorosa, Salvador-José},
  title     = {Épistémè Aperta : la R\&D, l'Open Source, l'Open Science et l'IA agentique.
               Pour une refondation de la philosophie africaine et de la recherche
               scientifique et technologique en Afrique},
  year      = {2026},
  note      = {Manuscrit en cours de rédaction}
}
```

## Contact

Pour toute demande d'autorisation, de collaboration, d'édition ou de traduction, contactez l'auteur :
**Salvador-José Mountanta Famorosa** · [salvador.jose@opensource-university.org](mailto:salvador.jose@opensource-university.org)

---

<div align="center">
<i>Copier d'abord. Innover ensuite. Devenir indépendant et puissant.</i>
</div>
