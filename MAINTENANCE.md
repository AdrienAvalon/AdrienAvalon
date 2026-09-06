# Maintenir ce profil

Ce dépôt public `AdrienAvalon/AdrienAvalon` fournit le README affiché sur le profil GitHub.
Le texte principal est en français ; les noms et liens des projets restent ceux de leurs dépôts.

## Sources de vérité

- Bio et identité : champs publics existants du compte et choix du propriétaire.
- Avash : [README](https://github.com/AdrienAvalon/avash), documentation et releases du projet.
- Outils Linux : [SysAdmin-Tools](https://github.com/AdrienAvalon/SysAdmin-Tools).
- FPS : [guide de reprise](https://github.com/AdrienAvalon/destructible-fps/blob/main/REPRISE.md) ; ne pas présenter l'objectif photoréaliste comme atteint.
- Recherche : [avalon-research](https://github.com/AdrienAvalon/avalon-research) ; travaux exploratoires indépendants, pas de validation scientifique ou d'évaluation par les pairs supposée.
- Activité et contact : [site public](https://avalon-network.com).

Les contenus publics de ces sources ont été consultés le 6 septembre 2026. Les descriptions sont
volontairement courtes et sans compteurs de stars, téléchargements, tests ou performances qui
vieilliraient. Ne pas inventer diplôme, certification, employeur, clientèle ou niveau d'expertise.
Ne pas publier d'inventaire privé, endpoint interne, adresse de messagerie non publique ou secret.

## Identité visuelle

`assets/banner.svg` est un dessin vectoriel original du dépôt : pas d'image générée prétendant
montrer un produit réel, pas de ressource externe, script, animation, police téléchargée ou tracker.
Les informations restent lisibles dans le README sans l'image. La bannière est identique en thème
clair/sombre et s'adapte à la largeur disponible. Garder l'image légère et un texte alternatif.

Prévisualisation optionnelle, avec librsvg déjà installé :

```bash
mkdir -p .preview
rsvg-convert assets/banner.svg -o .preview/banner.png
```

À la demande du propriétaire, six badges de technologies et un badge de release Avash utilisent
[Shields.io](https://shields.io/). Les six badges sont descriptifs et statiques, pas des certifications
ou des scores de maîtrise. Le badge de version interroge la dernière release publique d'Avash ;
aucun numéro n'est recopié à la main. Si Shields.io est indisponible, le texte et les liens ordinaires
restent utilisables. Aucun compte, jeton ou générateur de statistiques n'est nécessaire.

Les images de badges impliquent une ressource externe ; ne pas prétendre que toute la page est
autonome. La bannière reste locale au dépôt. Pas de compteur de visiteurs, trophées, streaks,
workflow planifié ou serveur tiers nécessitant un jeton d'accès aux dépôts.

## Références de présentation

Profils consultés le 6 septembre 2026, à titre d'inspiration de structure, sans copie de leur
biographie, de leurs images ou de leurs réalisations :

- [Jeff Geerling](https://github.com/geerlingguy) : présentation courte, site personnel comme point
  de contact, projets d'infrastructure visibles dans les épingles.
- [Sindre Sorhus](https://github.com/sindresorhus) : proposition claire et lien direct vers un
  produit ; le travail mis en avant prime sur une longue liste de technologies.
- [Abhishek Naidu](https://github.com/abhisheknaiidu) et sa
  [galerie de profils](https://github.com/abhisheknaiidu/awesome-github-profile-readme) : exemples de
  personnalisation et de modules dynamiques. Ici, ne retenir que les modules utiles au lecteur,
  sans reprendre les statistiques de productivité, les dons ou les compteurs personnels.
- Documentation [badges statiques](https://shields.io/badges/static-badge) et
  [release GitHub](https://shields.io/badges/git-hub-release) de Shields.io.

Le choix final garde une bannière originale, une palette sombre/menthe, des sections courtes et des
liens directs. Pas de classement prétendant désigner objectivement les « meilleurs profils ».

## Bio proposée

```text
Administrateur systèmes Linux | Automatisation, outils Rust & self-hosting | Avash · SysAdmin-Tools · Recherche IA | Avalon Network
```

La bio du compte n'est pas synchronisée automatiquement depuis Git. La modification de README ne
change pas la bio latérale. Pour la mettre à jour, utiliser « Edit profile » ou l'API avec le droit
de modification de profil ; ne pas élargir silencieusement les permissions d'un jeton. La bio
précédente lors de cette intervention était `SysAdmin Linux`.

Les quatre épingles existantes sont conservées : Avash, SysAdmin-Tools, Avalon Research et
Destructible FPS. Le nom, la société, la localisation, l'avatar, les liens sociaux, les réglages de
confidentialité et la disponibilité professionnelle du compte ne sont pas modifiés par le README.

## Validation et retour arrière

Vérifier liens publics, Markdown rendu, banner SVG et lisibilité sur une largeur mobile avant push.
Après push, vérifier le SHA distant et l'apparition du README sur la page du profil. Préserver les
modifications du propriétaire ; le rollback du contenu passe par un nouveau commit qui restaure
la version voulue, jamais une réécriture forcée de l'historique.

Retirer ou vider le README désactive son affichage sur le profil ; ne pas supprimer le dépôt ou
changer sa visibilité sans demande du propriétaire. Les [conditions du README de profil](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)
et les [réglages d'épingles](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/pinning-items-to-your-profile)
restent documentés par GitHub.
