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
**Âge** : 31 ans (née en 1994)
**Métier principal** : Ingénieure
**Nationalité** : Française, d'origine arménienne — mais elle ne mentionne pas ses origines dans
sa biographie publique. Ne pas l'écrire dans les textes du site ou les bios.
**Blog littéraire** : https://memosemoi.wordpress.com (ancien, remplacé par marieminassian.fr)
**Site** : marieminassian.fr (site statique HTML/CSS sur GitHub Pages)
**Instagram** : @marie.minassian (compte principal, anciennement @marieminassiaan)
**Instagram littéraire** : @memosemoi (à fusionner progressivement avec le principal)
**TikTok** : @marie_minassian
**Identité** : publie et se présente sous "Marie Minassian" dans le monde littéraire. Sur LinkedIn,
elle apparaît sous Baghdassarian (vie pro d'ingénieure) — les deux identités coexistent délibérément.

**Description par sa mère** (utilisable pour la com) : "née sous le signe des gémeaux, souvent
la somme de deux contraires : artiste et scientifique, indécise et déterminée, campagne et ville,
hippie et tradition, orientale et occidentale, fragile et forte." (sa mère ne croit pas à l'astrologie)

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

**Git — ne jamais exécuter les commandes git directement**

Marie gère elle-même les commits et pushes depuis son terminal.
Ne jamais tenter de lancer `git commit`, `git push`, `git rm`, etc. via bash.
Se contenter de lui donner les commandes à copier-coller.

**Terminal utilisé : Git Bash (MINGW64)** — pas PowerShell, pas cmd.
Les commandes Windows comme `Remove-Item` ne fonctionnent pas.
Utiliser la syntaxe bash : `rm -f .git/index.lock`, etc.

Exemple de bloc à donner :
```bash
rm -f .git/index.lock
git add -A
git commit -m "message"
git push
```

**Comptes GitHub :**
- GitHub perso : https://github.com/mariebaghdassarian/
- Repo du site : https://github.com/mariebaghdassarian/marieminassian.fr
- Email perso : minassianmarie@gmail.com

**Autres outils :**
- WordPress.com est bloqué sur le réseau de l'entreprise — ne pas essayer d'y accéder via Claude in Chrome depuis cet ordinateur.
- VS Code est installé et fonctionnel pour le développement.
- Claude a accès au dossier projet : C:\Users\MarieBaghdassarian\projets\marieminassian
  (peut lire et écrire les fichiers directement sans que Marie ait à copier quoi que ce soit)

---

## Premier roman — *Presque Normale*

**Parution** : septembre 2026
**Maison d'édition** : Assyelle (petite maison, édition participative)
**Genre** : Autofiction contemporaine
**Synopsis (sans spoiler)** :
Lucie, étudiante en école d'ingénieurs, essaie de faire comme tout le monde : sortir, boire, aimer,
s'intégrer. Mais au fond d'elle, un mal-être persiste. Elle se sent en permanence en décalage,
soupçonne un problème, veut comprendre. Au fil des soirées, des relations bancales, des substances
et des séances de psy, entre errance et lucidité, elle construit peu à peu une vie qui lui ressemble.

**⚠️ Ne jamais révéler la fin dans les textes publics** — la quête et la résolution sont le cœur
du roman. Le synopsis ci-dessus est la version correcte pour le site et la com.

**Particularité éditoriale** : Le roman contient des fiches explicatives sur toutes les substances
(alcool, médicaments, drogues) — noms, effets positifs et négatifs.
**Thèmes principaux** : introversion, quête d'identité, psychiatrie, substances, jeunesse, normalité
**Contexte d'écriture** : envie de transformer des notes éparses en roman pendant le confinement.
A suivi 3 stages à l'École Les Mots + Objectif Manuscrit 2024 avec Charlotte Milandri.

---

## Projets de romans futurs

1. **Roman sur les origines arméniennes** — Quête identitaire sur ce que ça veut dire d'être
   d'origine arménienne, avec un voyage en Arménie avec son père. Dimension familiale et mémorielle forte.

2. **Roman sur les manipulateurs / pervers narcissiques** — Inspiré de deux expériences personnelles :
   un ami proche de 6 ans qui a manipulé son entourage, et un homme qu'elle a fréquenté 6 mois
   qui lui a caché être en couple depuis 3 ans. Les lettres d'excuses des deux hommes étaient
   structurées de façon quasi identique — ce détail est frappant et potentiellement central dans le roman.

3. **Roman sur la non-monogamie** — Relation de presque 3 ans avec un partenaire qui voulait
   explorer la non-monogamie. Conclusion personnelle : elle n'a pas réussi à déconstruire la jalousie.
   Roman sur le fait qu'on ne peut pas forcer les choses quand les valeurs fondamentales divergent.

---

## Identité éditoriale et ligne de communication

**Ce qui la définit comme autrice** : Elle vit pour documenter. Elle est à la fois très émotionnelle
dans le ressenti et analytique dans la restitution. Elle écrit sur des choses dont on ne parle pas.

**Sa ligne éditoriale** : *"Les choses dont on ne parle pas, moi je les vis et je les écris."*
(tagline du site : "parler des choses dont on ne parle pas")

**Ton** : Authentique, direct, sensible, sans tabou. Ni donneuse de leçons ni moralisatrice.

**Lectorat cible** : Sa génération (millennials / début Gen Z), personnes sensibles qui se sentent
parfois en décalage.

---

## Site marieminassian.fr — structure et état actuel

**Repo GitHub** : https://github.com/mariebaghdassarian/marieminassian.fr
**Dossier local** : C:\Users\MarieBaghdassarian\projets\marieminassian
**DNS** : configuré et validé (OVH → GitHub Pages, mai 2026)
**Design** : police Lora (Google Fonts, serif littéraire), fond crème chaud (#faf7f5), max-width 860px

**Navigation** : Accueil · Élucubrations · Citations · Opuscules · À propos
(Historiettes et Coups de cœur supprimés)

**Posts publiés :**
- posts/elucubration-autoportrait.html — Autoportrait (texte signature)
- posts/elucubration-10.html — Élucubration #10, La maîtresse trompée (16 mai 2026)
- posts/elucubration-porte-inconnue.html — J'ai ouvert la porte à un inconnu (2017)
- posts/opuscule-4-beigbeder.html — Opuscule #4, Beigbeder

**Texte À propos actuel :**
"Je m'appelle Marie Minassian. Ingénieure le jour, autrice le reste du temps.
Quand j'étais petite, je rêvais d'être écrivaine.
Ce site rassemble mes textes (élucubrations et citations) et des extraits de romans qui m'ont marquée."
+ carte roman Presque Normale + liens Instagram et TikTok

**Page Citations** : une seule page avec les phrases courtes (pas de posts individuels)

**Pour ajouter un post** : créer le fichier HTML dans posts/ en s'inspirant du template
_TEMPLATE-elucubration.html, puis mettre à jour index.html et la page de catégorie.
Claude peut écrire directement dans le dossier projet sans que Marie ait à copier.

---

## Stratégie de communication

- **TikTok** : priorité n°1 pour BookTok. Format storytelling (parcours auteur, contrat, etc.)
- **Instagram** : @marie.minassian (principal). Fusion progressive avec @memosemoi.
- **Babelio** : créer un profil auteure avant septembre 2026.
- **Substack** : après le lancement, une fois l'audience fidèle constituée.

---

## Comment aider Marie

### Pour les textes
- Préserve son style avant tout — voix forte et reconnaissable, ne pas aseptiser
- Ajustements de rythme, structure, clarté OK — pas de réécriture totale
- Son style le plus fort : les listes "Je… Je… Je…"

### Pour la communication
- Ton authentique, direct, jamais condescendant ni moralisateur
- Angle "ce dont on ne parle pas" — c'est là que son contenu est le plus fort
- Septembre 2026 approche : construire l'anticipation autour du roman

### Pour la stratégie
- Beaucoup de projets simultanés — aider à prioriser sans submerger
- Ingénieure : apprécie les raisonnements structurés
- Aussi très intuitive et émotionnelle : ne pas être trop froid ou analytique
