# Maintenir ce profil

Ce dépôt public `AdrienAvalon/AdrienAvalon` fournit le README affiché sur le profil GitHub.
Le texte principal est en français. `README.en.md` est sa version anglaise, accessible par un lien
réciproque ; modifier les deux ensemble, y compris les limites des projets et les textes alternatifs.
Les noms et liens des projets restent ceux de leurs dépôts.

## Parcours de lecture

La version portfolio met en avant Avash, puis l'outillage Linux, puis les explorations FPS et IA.
Conserver une introduction courte, les badges après les projets et un lien vers les preuves de
qualité plutôt que des chiffres recopiés. Ne pas remettre les quatre projets au même niveau de
maturité : le FPS reste un prototype et la recherche reste exploratoire.

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
Elle ne contient que deux grands titres et le motif Avalon : les informations personnelles et
professionnelles restent dans le texte Markdown, lisible sur téléphone et sans l'image.
Le paramètre `v` de son URL est le préfixe de son SHA-256 : le mettre à jour dans les deux README
après chaque modification du SVG. GitHub peut sinon afficher la nouvelle page avec une ancienne
image encore en cache. Ce paramètre ne change pas le chemin du fichier local.

### Capture Avash

`assets/avash-terminal.png` est une copie **sans retouche** de la capture déjà publiée par le
propriétaire dans son dépôt Avash :

- Source : [`docs/captures/terminal-ssh.png`](https://github.com/AdrienAvalon/avash/blob/09297fdec3112a2b17b1218bf09575fda8322354/docs/captures/terminal-ssh.png).
- Commit source : `09297fdec3112a2b17b1218bf09575fda8322354`.
- Dimensions : 1280 × 800 ; taille : 112 361 octets.
- SHA-256 : `b776797abd6d4d9033d4fd6e91b08d7ebe73b5ae7297cc90c9b06c8d605f83b8`.
- Lien de démonstration : le README Avash, qui contient déjà son animation SSH/RDP.

Le profil affiche une image statique pour éviter une animation automatique sans contrôle de pause.
Il renvoie vers le projet pour voir la démo. La capture illustre une version de l'interface, pas une
preuve de performances ou de compatibilité sur tous les OS. Le badge reste la source de version
courante ; une capture historique peut afficher un numéro plus ancien.

Avant remplacement, inspecter le visuel entier et les métadonnées, vérifier sa provenance publique,
refuser les secrets et les données d'infrastructure privée. Conserver le fichier original, sa source
épinglée et la même capture dans les deux langues. Cette réutilisation ne change pas la licence du
projet Avash, [AGPL-3.0-or-later](https://github.com/AdrienAvalon/avash/blob/09297fdec3112a2b17b1218bf09575fda8322354/LICENSE).

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
autonome. La bannière et la capture restent locales au dépôt. Pas de compteur de visiteurs, trophées, streaks,
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

## Bio du profil

```text
Administrateur systèmes Linux | Automatisation, outils Rust & self-hosting | Avash · SysAdmin-Tools · Recherche IA | Avalon Network
```

La bio du compte n'est pas synchronisée automatiquement depuis Git. La modification de README ne
change pas la bio latérale. Pour la mettre à jour, utiliser « Edit profile » ou l'API avec le droit
de modification de profil ; ne pas élargir silencieusement les permissions d'un jeton. La bio
précédente lors de cette intervention était `SysAdmin Linux`.

Cette bio a été appliquée le 6 septembre 2026, après validation explicite du propriétaire de
l'autorisation GitHub, puis relue via l'API du profil public. Seul le champ `bio` a été écrit ; les
autres champs de présentation ont été recoupés avant/après et conservés.

Les quatre épingles existantes sont conservées : Avash, SysAdmin-Tools, Avalon Research et
Destructible FPS. Le nom, la société, la localisation, l'avatar, les liens sociaux, les réglages de
confidentialité et la disponibilité professionnelle du compte ne sont pas modifiés par le README.

## Validation et retour arrière

Vérifier liens publics, Markdown rendu, banner SVG et lisibilité sur une largeur mobile avant push.
Après push, vérifier le SHA distant et l'apparition du README sur la page du profil. Préserver les
modifications du propriétaire ; le rollback du contenu passe par un nouveau commit qui restaure
la version voulue, jamais une réécriture forcée de l'historique.

Validation initiale : les dix liens publics et les sept images Shields répondaient en HTTP 200 ;
le badge Avash correspondait à sa release publique. Le Markdown a été rendu par l'API GitHub,
le SVG inspecté et rasterisé à deux largeurs. Après publication, la page réelle du profil a été
inspectée dans un navigateur isolé du profil personnel, en thème clair à 1440 px et à 390 px :
bannière chargée, badges visibles avec retour à la ligne mobile, contenu correctement affiché.
Le SHA du README relu via l'API correspond au blob local. Ces observations sont ponctuelles, pas
une garantie permanente de disponibilité des liens ou des services de badges.

### Version portfolio — 6 septembre 2026

Avant publication : les 29 URL distinctes des trois documents répondaient HTTP 200, dont les
sept badges. Les versions FR/EN partagent les mêmes 18 URL publiques et les chemins relatifs
existent. L'ancre de démonstration et la présence du WebP animé ont été recoupées dans Avash.
La capture est identique à sa source épinglée ; le PNG ne contient que les chunks IHDR, IDAT et
IEND. Les quatre sources textuelles ont été relues et contrôlées contre des motifs de secrets.

Les deux README ont été rendus avec l'API Markdown GitHub puis prévisualisés dans le cadre et les
styles natifs du profil, avec Firefox isolé piloté par Playwright : thèmes clair/sombre, largeurs
1440, 390 et 320 px, soit 12 cas. Les neuf images chargent et le README ne déborde pas
horizontalement. Les thèmes sont sélectionnés uniquement dans le navigateur de test, sans
écriture de réglage de compte. Les prévisualisations locales substituent les fichiers candidats ;
elles ne constituent pas à elles seules une preuve de publication.

Outils de cette vérification : Git/GitHub CLI, librsvg, contrôle de chunks PNG, Playwright 1.58.0
dans un environnement Python isolé via uv et son Firefox dédié. Aucun outil de statistiques,
workflow, jeton supplémentaire ni modification du navigateur personnel. Les artefacts de test
restent sous `.preview/`, ignoré par Git.

Une relecture indépendante a confirmé les liens, la parité FR/EN, la provenance et les descriptions.
La revue complémentaire `claude-pair`, limitée à un résumé anonymisé, a échoué avant de produire un
avis exploitable : aucune approbation Claude n'est revendiquée.

Retirer ou vider le README désactive son affichage sur le profil ; ne pas supprimer le dépôt ou
changer sa visibilité sans demande du propriétaire. Les [conditions du README de profil](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)
et les [réglages d'épingles](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/pinning-items-to-your-profile)
restent documentés par GitHub.
