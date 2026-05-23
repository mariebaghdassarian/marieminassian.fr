---
name: projet-litteraire
description: >
  Skill dédié aux projets littéraires et à la communication d'autrice de Marie Minassian.
  Déclencher dès que Marie mentionne : son roman, ses textes (élucubrations, opuscules, histoires),
  ses réseaux sociaux en tant qu'autrice, sa stratégie de communication autour du livre, du contenu
  pour Instagram ou TikTok, son blog memosemoi.wordpress.com, un nouveau roman en projet, la relecture
  ou l'amélioration d'un de ses textes, BookTok, Babelio, Substack, ou la communication littéraire
  en général. Ce skill connaît le profil complet de Marie et doit être utilisé sans hésiter dès
  qu'il y a un projet d'écriture ou de communication auteur.
---

# Skill : Projets littéraires de Marie Minassian

Ce skill te donne le contexte complet sur Marie en tant qu'autrice. Utilise-le pour personnaliser
toutes tes réponses : tu n'as pas besoin de lui reposer des questions sur son profil, ses projets
ou ses réseaux — tu les connais déjà.

---

## Profil autrice

**Nom** : Marie Minassian (nom de plume — vrai nom : Baghdassarian)  
**Âge** : 31 ans  
**Métier principal** : Ingénieure  
**Origine** : Franco-arménienne (moitié arménienne, jamais allée en Arménie — sujet important pour elle)  
**Blog littéraire** : https://memosemoi.wordpress.com (en cours de réorganisation, futur site : marieminassian.fr)  
**Instagram** : @marie.minassian (compte principal, anciennement @marieminassiaan)  
**Instagram littéraire** : @memosemoi (à fusionner progressivement avec le principal)  
**TikTok** : @marie_minassian  
**Identité** : publie et se présente sous "Marie Minassian" dans le monde littéraire. Sur LinkedIn, elle apparaît sous Baghdassarian (vie pro d'ingénieure) — les deux identités coexistent délibérément.

---

## Configuration technique — ordinateur de travail

Marie travaille sur son **ordinateur professionnel** (Dental Monitoring) pour ses projets personnels.
Cela implique des précautions importantes quand on l'aide avec du code ou Git.

**Git — règle absolue : toujours `--local`, jamais `--global`**

Son ordinateur a une config Git globale configurée pour le travail :
- Email pro : m.baghdassarian@dental-monitoring.com
- Utilisée pour tous ses repos professionnels

Pour ses projets personnels, il faut systématiquement configurer **localement** (dans le repo uniquement) :
```bash
git config --local user.email "minassianmarie@gmail.com"
git config --local user.name "Marie Minassian"
```
Ne jamais suggérer `git config --global` — cela écraserait sa config pro et impacterait son travail.

**Comptes GitHub :**
- GitHub perso : https://github.com/mariebaghdassarian/
- Repo du site : https://github.com/mariebaghdassarian/marieminassian.fr
- Email perso : minassianmarie@gmail.com

**Autres outils :**
- WordPress.com est bloqué sur le réseau de l'entreprise — ne pas essayer d'y accéder via Claude in Chrome depuis cet ordinateur.
- VS Code est installé et fonctionnel pour le développement.

---

## Premier roman — *Presque Normale*

**Parution** : septembre 2026  
**Maison d'édition** : Assyelle (petite maison, édition participative)  
**Genre** : Autofiction  
**Résumé** : On suit une jeune femme de 20 à 25 ans dans une école d'ingénieurs. Elle se sent en décalage
avec l'image qu'elle a d'une personne "normale" — extravertie, sociable, souriante. Pour dépasser sa
timidité, elle boit beaucoup, prend des drogues, consulte une psychologue puis un psychiatre, cherche
un diagnostic (HPI ? autisme ?). La conclusion : elle n'a rien d'anormal, elle est juste introvertie.
C'est une quête de soi mêlée à la jeunesse et à des comportements extrêmes.  
**Particularité éditoriale** : Le roman contient des fiches explicatives sur toutes les substances
(alcool, médicaments, drogues) — noms, effets positifs et négatifs. C'est le côté analytique et
pédagogique de Marie qui se manifeste dans la fiction.  
**Thèmes principaux** : introversion, quête d'identité, psychiatrie, substances, jeunesse, normalité  

---

## Projets de romans futurs

1. **Roman sur les origines arméniennes** — Quête identitaire sur ce que ça veut dire d'être
   d'origine arménienne, avec un voyage en Arménie avec son père. Dimension familiale et mémorielle forte.

2. **Roman sur les manipulateurs / pervers narcissiques** — Inspiré de deux expériences personnelles :
   un ami proche de 6 ans qui a manipulé son entourage, et un homme qu'elle a fréquenté 6 mois
   qui lui a caché être en couple depuis 3 ans. Les lettres d'excuses des deux hommes étaient
   structurées de façon quasi identique — ce détail est frappant et potentiellement central dans le roman.
   Angle : dénoncer, libérer la parole des femmes, montrer que ces comportements ne doivent pas rester impunis.

3. **Roman sur la non-monogamie** — Relation de presque 3 ans avec un partenaire qui voulait
   explorer la non-monogamie. Marie a plongé dans ce monde (groupes polyamour, soirées, terminologie :
   polyamour hiérarchique/non hiérarchique, libertinage, échangisme...). Conclusion personnelle :
   elle n'a pas réussi à déconstruire la jalousie. Roman sur le fait qu'on ne peut pas forcer les choses
   quand les valeurs fondamentales divergent, et sur la souffrance que ça engendre même quand on aime fort.

---

## Identité éditoriale et ligne de communication

**Ce qui la définit comme autrice** : Elle vit pour documenter. Dès qu'elle commence une expérience,
elle se dit "ça fera un bon roman." Elle est à la fois très émotionnelle dans le ressenti et analytique
dans la restitution. Elle écrit sur des choses dont on ne parle pas.

**Sa ligne éditoriale naturelle** : *"Les choses dont on ne parle pas, moi je les vis et je les écris."*

**Sujets de prédilection** : introversion, psychiatrie, substances (elle met alcool et cocaïne sur le
même plan), non-monogamie, manipulation, identité, origines, amour, jeunesse.

**Ton** : Authentique, direct, sensible, sans tabou. Ni donneuse de leçons ni moralisatrice — elle
documente et partage, le lecteur fait sa propre réflexion.

**Lectorat cible** : Sa génération (millennials / début Gen Z), personnes sensibles qui se sentent
parfois en décalage, curieux qui aiment qu'on leur parle de sujets peu traités.

---

## Blog memosemoi.wordpress.com

Le blog contient plusieurs types de contenus. Voici la structure de catégories proposée (en cours d'implémentation) :

- **Élucubrations** — ses propres textes courts sur tous sujets (réflexions, émotions, observations)
- **Opuscules** — ses 3 passages préférés d'un roman, avec le titre et l'auteur
- **Historiettes** — ses petites histoires narratives autonomes (ex : *"J'ai ouvert la porte à un inconnu"*)
- **Coups de cœur** — bibliothèque de recommandations : livres, films, musiques
- **Destins** — portraits de personnes

---

## Site marieminassian.fr

Site statique HTML/CSS hébergé sur GitHub Pages, connecté au domaine OVH marieminassian.fr.
- **Repo GitHub** : https://github.com/mariebaghdassarian/marieminassian.fr
- **Dossier local** : C:\Users\MarieBaghdassarian\projets\marieminassian
- **DNS configuré** : A records (@ → GitHub IPs) + CNAME (www → mariebaghdassarian.github.io) — validé
- **Structure** : index.html, elucubrations.html, opuscules.html, historiettes.html, coups-de-coeur.html, a-propos.html, style.css, posts/

---

## Stratégie de communication — recommandations en place

- **Nom de domaine** : marieminassian.fr (acheté sur OVH, 20€/3 ans). Site codé de zéro en HTML/CSS,
  hébergé gratuitement sur GitHub Pages.
- **TikTok** : priorité n°1 pour toucher de nouveaux lecteurs via BookTok. Le format storytelling
  (parcours auteur, envoi aux éditeurs, réception du contrat) fonctionne très bien.
- **Instagram** : compte principal @marie.minassian (nom récupéré). Fusion progressive avec @memosemoi.
- **Blog** : vitrine professionnelle. Quand quelqu'un cherche son nom, c'est ici qu'il doit arriver.
- **Babelio** : créer un profil auteure avant septembre 2026.
- **Substack** : à envisager après le lancement du roman, une fois qu'il y a une audience fidèle.
- **LinkedIn** : pour la crédibilité professionnelle et la visibilité auprès des médias / industrie.

---

## Comment aider Marie avec ce skill

### Pour la communication sur les réseaux
- Propose des idées de contenu concrètes (scripts TikTok, idées de carousels Instagram, textes de légende)
- Respecte son ton : authentique, direct, jamais condescendant ni moralisateur
- Pense toujours à l'angle "ce dont on ne parle pas" — c'est là que son contenu est le plus fort
- Rappelle-toi qu'elle approche la sortie du roman en septembre 2026 : aide-la à construire l'anticipation

### Pour les textes
- Quand elle partage un texte à relire, préserve son style avant tout — n'aseptise pas
- Son écriture a une voix forte et reconnaissable, ne la "corrige" pas vers un style générique
- Tu peux proposer des ajustements de rythme, de structure, de clarté — pas de réécriture totale
- Si elle partage un début de roman ou une idée, aide-la à l'approfondir en posant des questions pertinentes

### Pour le site marieminassian.fr
- Pour ajouter un post : créer le fichier HTML dans posts/ en s'inspirant du template _TEMPLATE-elucubration.html
- Mettre à jour index.html (section "derniers textes") et la page de catégorie correspondante
- Commit et push avec les credentials locaux (minassianmarie@gmail.com)
- Claude a accès direct au dossier C:\Users\MarieBaghdassarian\projets\marieminassian — peut écrire les fichiers sans que Marie ait à copier

### Pour la stratégie
- Elle a beaucoup de projets simultanés (blog, deux Instagrams, TikTok, roman, maison à rénover...)
- Aide-la à prioriser sans la submerger
- Elle est ingénieure : elle apprécie les raisonnements structurés et les explications du "pourquoi"
- Elle est aussi très intuitive et émotionnelle : ne sois pas trop froid ou purement analytique
