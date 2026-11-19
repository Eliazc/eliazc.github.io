# Portfolio BTS SIO SISR — Eliaz (épreuve E5)

Site statique (HTML/CSS, aucune dépendance), habillé avec le design system « Tuturu OS » (`assets/css/os.css`, copie identique de celle du site principal) + `assets/css/portfolio.css` pour les écrans des chaînes du portfolio.

## Arborescence

```
index.html              Menu (grille de chaînes)
├── parcours.html        Présentation du parcours
├── competences.html     Les 6 compétences du bloc 1 + liens vers les réalisations
├── projets.html         Réalisations en classe (R1 à R4)
├── stage.html           Stages de 1re et 2e année
├── realisations-pro.html Réalisations professionnelles en stage (P1 à P4)
├── synthese.html        Tableau de synthèse réalisations × compétences
├── veille.html          Veille technologique
├── documentation.html   Procédures, tutoriels, projets perso
├── certifications.html  PIX, ANSSI, CNIL…
├── cv.html              CV à télécharger
├── contact.html         Contacts pro, LinkedIn, GitHub
└── mentions-legales.html
assets/
├── css/   os.css, portfolio.css
├── fonts/ ← copier ici les 3 .woff2 M PLUS Rounded 1c du site principal
└── docs/  ← CV, tableau de synthèse officiel, attestation de stage, tutos (PDF)
```

## À compléter

Tout ce qui est encadré en jaune (`<span class="todo">`) dans les pages. Pour retrouver les trous :

```
grep -c 'class="todo"' *.html
```

Fichiers PDF attendus dans `assets/docs/` : `cv-eliaz.pdf`, `tableau-de-synthese.pdf`, `attestation-stage-1.pdf`, `attestation-stage-2.pdf`, `tuto-scribe.pdf`, `flatpak-proxy-amon.pdf`, `ostree-reset.pdf`.

## Hébergement envisagé

**GitHub Pages** (dépôt `elimanee.github.io` ou `portfolio`) : gratuit, HTTPS, toujours accessible le jour de l'épreuve, et l'historique Git sert de sauvegarde. Les chemins sont tous relatifs, donc le site marche aussi tel quel dans un sous-dossier, sur une VM du lycée (Apache/Nginx) ou sur Neocities.

Dans tous les cas : garder une copie en local (clé USB) au cas où le réseau tombe pendant l'oral.
