# Formation IA creative

Un guide d'apprentissage sous forme de prompts a coller dans ChatGPT, Claude, Codex ou un autre assistant IA.

Ce n'est pas une banque de prompts pour "faire a sa place". C'est une formation guidee : a chaque chapitre, tu colles un prompt pour que l'IA t'enseigne une competence, te fasse pratiquer, verifie ta comprehension et t'aide a passer a l'etape suivante.

Le but final : savoir creer avec l'IA de facon autonome sur Mac, comprendre le terminal, installer les bons outils, utiliser des assistants comme Codex, Claude Code ou Cursor, puis construire et publier un petit portfolio.

---

## Comment utiliser cette formation

Pour chaque chapitre :

1. Lire l'introduction.
2. Copier le prompt "Lecon guidee".
3. Repondre a l'IA et faire les actions demandees.
4. Copier ensuite le prompt "Exercice".
5. Finir par le prompt "Verification".
6. Ne passer au chapitre suivant que si le resultat attendu est obtenu.

Chaque prompt est ecrit pour obliger l'IA a enseigner lentement, expliquer les mots techniques, attendre les reponses et corriger sans aller trop vite.

---

# Chapitre 1 - Comprendre ce qu'on peut creer avec l'IA

## Ce chapitre sert a quoi

Tu sais deja discuter avec ChatGPT. Ici, tu apprends la vraie carte du territoire : quoi demander a ChatGPT, quoi demander a Claude, quoi demander a Codex, quoi faire dans Cursor ou VS Code, et pourquoi le terminal devient utile.

## Ce que tu vas apprendre

- La difference entre assistant de discussion, assistant de code et editeur IA.
- Ce que l'IA peut aider a creer : textes, images de reference, sites, automatisations, organisation.
- Ce que l'IA ne doit pas decider seule : gout, intention, validation finale.
- Le parcours complet : idee -> brief -> fichiers -> code -> test -> publication.

## Prompt 1A - Lecon guidee

```text
Tu es ma prof d'IA creative.

Je sais deja utiliser ChatGPT pour discuter, mais je veux comprendre comment CREER avec l'IA.

Explique-moi simplement :
- ce que je peux creer avec ChatGPT,
- ce que je peux creer avec Claude,
- ce que je peux faire avec Codex ou Claude Code,
- ce que Cursor ou VS Code apportent,
- pourquoi le terminal devient utile,
- comment tout cela peut servir a creer un portfolio.

Je veux une explication concrete, avec des exemples dans mes domaines :
- graphisme,
- photo,
- edition,
- artisanat,
- portfolio.

Ta methode :
- avance lentement,
- donne des exemples concrets,
- ne me donne pas encore de commandes,
- termine par une carte simple : outil -> a quoi il sert -> exemple d'usage.
```

## Prompt 1B - Exercice

```text
Fais-moi pratiquer.

Donne-moi 8 situations concretes, par exemple :
- ecrire une bio,
- organiser des photos,
- corriger un site,
- creer une page portfolio,
- generer une idee de direction artistique.

Pour chaque situation, je dois choisir l'outil le plus adapte :
- ChatGPT,
- Claude,
- Codex,
- Claude Code,
- Cursor ou VS Code,
- moi-meme sans IA.

Corrige mes choix et explique simplement.
```

## Prompt 1C - Verification

```text
Verifie si j'ai compris le paysage des outils IA.

Pose-moi 6 questions courtes :
- 2 sur ChatGPT/Claude,
- 2 sur Codex/Claude Code/Cursor,
- 2 sur ce que je dois garder sous mon controle.

Apres mes reponses, donne-moi :
- ce qui est compris,
- ce qui reste flou,
- le chapitre suivant a faire.
```

## Resultat attendu

Tu sais expliquer quel outil utiliser selon la situation.

---

# Chapitre 2 - Preparer son Mac pour apprendre sans stress

## Ce chapitre sert a quoi

Avant le terminal et le code, tu dois savoir ou tu travailles : dossiers, navigateur, comptes, applications, fichiers. Le but est de creer un espace propre pour apprendre.

## Ce que tu vas apprendre

- Creer un dossier de formation.
- Organiser les fichiers de travail.
- Verifier les applications utiles.
- Comprendre les comptes necessaires : ChatGPT, Claude, GitHub.

## Prompt 2A - Lecon guidee

```text
Tu es ma prof pour preparer mon Mac avant d'apprendre a creer avec l'IA.

Objectif :
creer un espace de travail simple et propre pour ma formation.

Explique-moi :
- quels dossiers creer sur mon Mac,
- quelles applications je vais utiliser,
- quels comptes je dois avoir,
- comment eviter de melanger mes fichiers personnels et mes fichiers d'apprentissage.

Applications possibles :
- navigateur web,
- ChatGPT,
- Claude,
- VS Code ou Cursor,
- Terminal,
- GitHub plus tard.

Ta methode :
- donne-moi une checklist courte,
- fais-moi faire une seule action a la fois,
- attends ma confirmation avant de continuer.
```

## Prompt 2B - Exercice

```text
Guide-moi pour creer mon dossier de formation sur Mac.

Je veux une organisation simple :
- un dossier principal,
- un dossier pour le portfolio,
- un dossier pour les images,
- un dossier pour les notes,
- un dossier pour les tests.

Donne-moi les etapes dans Finder d'abord, sans terminal.
Ensuite seulement, montre-moi comment retrouver ce dossier dans le terminal.
```

## Prompt 2C - Verification

```text
Verifie mon organisation.

Je vais te decrire mes dossiers.
Dis-moi :
- si c'est assez simple,
- si quelque chose manque,
- si quelque chose est trop complique,
- quelle est la prochaine etape.

Voici mon organisation :
[COLLER ICI]
```

## Resultat attendu

Tu as un dossier de formation clair sur son Mac.

---

# Chapitre 3 - Comprendre le terminal sans panique

## Ce chapitre sert a quoi

Le terminal n'est pas le but. C'est un outil pour ouvrir des projets, verifier des installations, lancer Codex/Claude Code, et comprendre ce qui se passe.

## Ce que tu vas apprendre

- Ce qu'est Terminal.
- Ce qu'est une commande.
- Naviguer dans les dossiers.
- Lire une erreur sans paniquer.
- Faire les commandes de base : `pwd`, `ls`, `cd`, `mkdir`, `touch`, `open`.

## Prompt 3A - Lecon guidee

```text
Tu es ma prof de terminal Mac.

Je suis creative, pas developpeuse, et je veux comprendre le terminal uniquement pour pouvoir travailler avec l'IA et mes projets.

Explique-moi simplement :
- ce qu'est Terminal,
- ce qu'est une commande,
- ce qu'est le dossier courant,
- ce que veut dire chemin,
- pourquoi Codex ou Claude Code utilisent le terminal,
- ce que je peux faire sans danger avec des commandes simples.

Regles :
- pas de jargon non explique,
- une commande a la fois,
- explique avant que je tape,
- attends que je colle le resultat,
- corrige-moi doucement.

Commence par la commande `pwd`.
```

## Prompt 3B - Exercice

```text
Fais-moi un exercice guide de terminal.

Objectif :
creer un petit dossier test, entrer dedans, creer un fichier, l'ouvrir dans le Finder, puis revenir en arriere.

Commandes a apprendre :
- pwd
- ls
- cd
- mkdir
- touch
- open .

Donne-moi une commande a la fois.
Avant chaque commande :
- explique ce que la commande fait,
- dis-moi ce que je dois voir.
Apres chaque resultat :
- dis-moi si c'est bon,
- puis passe a l'etape suivante.
```

## Prompt 3C - Depannage

```text
Je vais te coller un message de mon terminal.

Ta mission :
- traduire le message en francais simple,
- me dire si c'est grave ou normal,
- me dire ce qui a probablement cause le probleme,
- me donner UNE seule action suivante,
- ne pas me donner 10 solutions.

Message :
[COLLER ICI]
```

## Resultat attendu

Tu sais se deplacer dans les dossiers et comprendre une sortie simple du terminal.

---

# Chapitre 4 - Installer les outils de base

## Ce chapitre sert a quoi

Pour creer avec l'IA en local, il faut quelques outils : VS Code ou Cursor, Git, Node.js/npm, puis Codex ou Claude Code. Ce chapitre sert a installer et verifier proprement.

## Ce que tu vas apprendre

- Verifier si Git est installe.
- Installer Node.js LTS.
- Installer VS Code ou Cursor.
- Comprendre `node`, `npm`, `git`, `code`, `cursor`.
- Ne jamais coller une commande d'installation sans comprendre.

## Prompt 4A - Lecon guidee

```text
Tu es ma prof de setup Mac pour creation avec l'IA.

Je veux preparer mon Mac pour utiliser :
- VS Code ou Cursor,
- Git,
- Node.js et npm,
- plus tard Codex ou Claude Code.

Ta mission :
1. m'expliquer a quoi sert chaque outil,
2. me dire dans quel ordre les installer,
3. me guider une etape a la fois,
4. me faire verifier chaque installation,
5. m'expliquer chaque commande avant que je la lance.

Important :
- utilise uniquement des sources officielles,
- si une commande peut changer, dis-moi de verifier la page officielle,
- ne me fais pas installer Codex ou Claude Code avant que Git et Node soient verifies.

Commence par me demander ce que j'ai deja installe.
```

## Prompt 4B - Verification des outils

```text
Guide-moi pour verifier mes outils dans le terminal.

Je veux verifier :
- git --version
- node --version
- npm --version
- code --version si j'utilise VS Code
- cursor --version si j'utilise Cursor

Donne-moi une commande a la fois.
Pour chaque commande :
- explique ce que la commande verifie,
- attends que je colle le resultat,
- dis-moi si c'est OK,
- dis-moi quoi faire si ce n'est pas OK.
```

## Prompt 4C - Depannage installation

```text
Je suis bloquee pendant une installation.

Outil concerne :
[GIT / NODE / NPM / VS CODE / CURSOR / AUTRE]

Ce que j'ai fait :
[DECRIRE]

Message obtenu :
[COLLER LE MESSAGE]

Ta mission :
- identifier l'etape qui bloque,
- m'expliquer le message simplement,
- me dire si je dois fermer et rouvrir le terminal,
- me donner l'action la plus sure,
- attendre mon retour.
```

## Resultat attendu

Tu peux taper `git --version`, `node --version` et `npm --version` et comprendre le resultat.

---

# Chapitre 5 - Comprendre Git et GitHub

## Ce chapitre sert a quoi

Git sert a garder l'historique d'un projet. GitHub sert a sauvegarder et publier. Tu n'as pas besoin de tout maitriser, mais tu dois comprendre les gestes de base.

## Ce que tu vas apprendre

- Depot, commit, historique.
- `git status`.
- Pourquoi faire un commit avant une grosse modification IA.
- Difference entre Git et GitHub.

## Prompt 5A - Lecon guidee

```text
Tu es ma prof de Git pour debutante creative.

Explique-moi Git avec une metaphore simple.

Je veux comprendre :
- ce qu'est un depot,
- ce qu'est un commit,
- ce qu'est l'historique,
- pourquoi Git me protege quand je travaille avec l'IA,
- la difference entre Git et GitHub.

Ensuite, guide-moi pour :
- initialiser Git dans un dossier test,
- creer un README,
- faire un premier commit,
- lire `git status`.

Une etape a la fois.
Explique chaque commande avant que je la lance.
```

## Prompt 5B - Exercice Git status

```text
Je veux apprendre a lire `git status`.

Donne-moi d'abord une explication simple.
Puis donne-moi 3 exemples fictifs de sorties `git status`.

Pour chaque exemple, demande-moi :
- ce qui a change,
- ce qui est pret a etre enregistre,
- ce qui ne l'est pas,
- quelle action faire ensuite.

Corrige mes reponses.
```

## Prompt 5C - Verification

```text
Verifie si j'ai compris Git.

Pose-moi 5 questions courtes.
Puis donne-moi un mini-scenario :
"J'ai demande a l'IA de modifier mon site et plusieurs fichiers ont change."

Je dois expliquer :
- ce que je regarde,
- ce que je teste,
- quand je fais un commit,
- quand je refuse une modification.
```

## Resultat attendu

Tu sais pourquoi et quand faire un commit.

---

# Chapitre 6 - Comprendre les assistants de code IA

## Ce chapitre sert a quoi

Tu apprends la difference entre ChatGPT, Claude, Codex, Claude Code, Cursor et VS Code. Le but est de savoir quel outil choisir selon le travail.

## Ce que tu vas apprendre

- ChatGPT/Claude : expliquer, cadrer, reflechir, corriger.
- Codex/Claude Code : travailler dans un dossier de code.
- Cursor : editeur avec IA integree.
- VS Code : editeur simple et fiable.
- La notion de "contexte du projet".

## Prompt 6A - Lecon guidee

```text
Tu es ma prof d'assistants IA pour le code.

Je veux comprendre la difference entre :
- ChatGPT,
- Claude,
- Codex,
- Claude Code,
- Cursor,
- VS Code.

Explique-moi :
- ce que chaque outil fait bien,
- ce qu'il ne faut pas lui demander,
- dans quel cas je l'utilise pour mon portfolio,
- ce que veut dire "donner le contexte du projet",
- pourquoi il faut verifier les modifications.

Fais-moi un tableau simple :
outil / role / exemple / risque / bon reflexe.
```

## Prompt 6B - Choisir le bon outil

```text
Fais-moi un entrainement.

Donne-moi 10 situations de creation avec l'IA.
Pour chaque situation, je dois choisir :
- ChatGPT ou Claude,
- Codex,
- Claude Code,
- Cursor,
- VS Code sans IA,
- moi-meme.

Exemples de situations :
- comprendre une erreur,
- modifier une couleur,
- reorganiser un fichier,
- ecrire une bio,
- publier un site,
- refactorer du code.

Corrige mes choix et explique.
```

## Prompt 6C - Regles de securite

```text
Apprends-moi les regles de securite quand un assistant IA peut modifier des fichiers.

Je veux comprendre :
- pourquoi il faut limiter la demande,
- pourquoi il faut lire les fichiers modifies,
- pourquoi il faut tester,
- pourquoi il faut faire un commit avant les grosses modifications,
- ce que je ne dois jamais confier a l'IA.

Termine par une checklist "avant d'accepter une modification IA".
```

## Resultat attendu

Tu sais choisir entre discussion, editeur, agent de code et travail manuel.

---

# Chapitre 7 - Installer Codex ou Claude Code

## Ce chapitre sert a quoi

Ce chapitre ne force pas a tout installer. Il apprend a installer proprement un assistant de code quand le Mac est pret.

## Ce que tu vas apprendre

- Verifier Node/npm avant installation.
- Installer Codex CLI ou Claude Code avec les commandes officielles.
- Lancer l'outil dans un dossier de projet.
- Comprendre qu'un agent peut lire/modifier des fichiers.

## Prompt 7A - Lecon guidee avant installation

```text
Tu es ma prof pour installer un assistant de code IA sur Mac.

Je veux peut-etre installer Codex ou Claude Code.

Avant toute commande, explique-moi :
- ce qu'est un CLI,
- pourquoi ces outils s'installent souvent avec npm,
- pourquoi Node.js doit etre pret,
- dans quel dossier il faut lancer ces outils,
- quels risques existent quand un outil peut modifier des fichiers.

Puis guide-moi pour verifier :
- node --version
- npm --version
- git --version

Ne me donne pas encore la commande d'installation tant que les verifications ne sont pas OK.
```

## Prompt 7B - Installation accompagnee

```text
Guide-moi pour installer un assistant de code IA.

Outil choisi :
[CODEX / CLAUDE CODE]

Regles :
- utilise les instructions officielles les plus recentes,
- explique chaque commande avant que je la lance,
- donne une seule commande a la fois,
- attends mon resultat,
- verifie que l'installation fonctionne,
- ne me fais pas lancer l'outil dans un dossier important avant un test.

Si l'outil choisi est Codex, aide-moi a verifier l'installation avec la commande officielle actuelle.
Si l'outil choisi est Claude Code, aide-moi a verifier l'installation avec la commande officielle actuelle.
```

## Prompt 7C - Premier test sans risque

```text
Guide-moi pour faire un premier test sans risque avec mon assistant de code IA.

Je veux :
- creer un dossier test,
- lancer l'assistant dans ce dossier,
- lui demander seulement de lire ou creer un petit fichier,
- verifier ce qu'il a fait,
- supprimer le dossier test si tout est fini.

Ne touche pas a mon vrai portfolio pour l'instant.
Explique chaque etape.
```

## Note pratique

Au moment de cette formation, les installations officielles indiquent notamment :

- Codex CLI : `npm install -g @openai/codex`
- Claude Code : `npm install -g @anthropic-ai/claude-code`

Comme ces outils evoluent, il faut toujours demander a l'IA de verifier les instructions officielles recentes avant installation.

## Resultat attendu

Tu sais installer ou reporter l'installation, et comprend pourquoi il faut tester dans un dossier sans risque.

---

# Chapitre 8 - Creer le projet portfolio d'apprentissage

## Ce chapitre sert a quoi

Le portfolio devient le fil rouge. Chaque competence IA sert a fabriquer quelque chose de visible.

## Ce que tu vas apprendre

- Transformer son univers en structure de site.
- Preparer les sections.
- Creer les fichiers HTML/CSS/JS.
- Comprendre ce que chaque fichier fait.

## Prompt 8A - Lecon guidee

```text
Tu es ma prof pour creer un portfolio avec l'IA.

Je veux creer un portfolio simple pour apprendre.

Mon univers :
- graphisme,
- photo,
- edition litteraire,
- artisanat.

Explique-moi :
- ce qu'est un site statique,
- a quoi servent HTML, CSS et JavaScript,
- pourquoi un portfolio simple est un bon projet d'apprentissage,
- quelles sections je peux creer,
- quels contenus je dois preparer avant de coder.

Puis aide-moi a definir la structure du site.
Ne genere pas encore le code.
```

## Prompt 8B - Exercice de structure

```text
Aide-moi a construire le plan de mon portfolio.

Je veux definir :
- page ou section d'accueil,
- a propos,
- travaux,
- fiche projet,
- contact,
- images a preparer,
- textes a ecrire.

Pose-moi les questions necessaires.
Ensuite, propose une structure simple et explique pourquoi elle est adaptee a mon projet.
```

## Prompt 8C - Verification

```text
Verifie si mon plan de portfolio est pret pour passer au code.

Voici mon plan :
[COLLER ICI]

Dis-moi :
- ce qui est clair,
- ce qui manque,
- ce qui est trop ambitieux,
- la version la plus simple a creer en premier.
```

## Resultat attendu

Tu as un plan de portfolio simple avant de generer du code.

---

# Chapitre 9 - Apprendre HTML, CSS et JavaScript en construisant

## Ce chapitre sert a quoi

Tu ne suis pas un cours abstrait. Tu apprends les bases du web en fabriquant ton portfolio.

## Ce que tu vas apprendre

- HTML = structure.
- CSS = apparence.
- JavaScript = interaction.
- Modifier un texte, une couleur, une section.
- Tester dans le navigateur.

## Prompt 9A - Lecon guidee

```text
Tu es ma prof de web.

Je veux apprendre HTML, CSS et JavaScript en construisant mon portfolio.

Explique-moi tres simplement :
- HTML,
- CSS,
- JavaScript,
- navigateur,
- fichier local.

Puis guide-moi pour creer une premiere version ultra simple.

Regles :
- genere un seul fichier a la fois,
- commence par index.html,
- explique les grandes zones,
- attends que je teste dans le navigateur,
- ensuite seulement passe a style.css,
- garde JavaScript pour plus tard si ce n'est pas necessaire.
```

## Prompt 9B - Exercice de modification

```text
Fais-moi pratiquer sur mon site.

Donne-moi 5 petites modifications a faire moi-meme :
- changer un titre,
- modifier un texte,
- changer une couleur,
- ajouter une carte projet,
- changer un espacement.

Pour chaque exercice :
- dis-moi dans quel fichier aller,
- donne-moi un indice,
- attends que je tente,
- corrige-moi ensuite.
```

## Prompt 9C - Verification

```text
Verifie si je comprends mon site.

Pose-moi des questions pratiques :
- ou changer le titre principal ?
- ou changer une couleur ?
- ou ajouter une nouvelle image ?
- ou ajouter un projet ?
- que fait le fichier CSS ?

Corrige mes reponses avec des explications simples.
```

## Resultat attendu

Tu sais modifier des petites parties du site sans demander a l'IA de tout refaire.

---

# Chapitre 10 - Travailler avec Codex ou Claude Code comme coworker

## Ce chapitre sert a quoi

Tu apprends a utiliser un agent de code comme un collaborateur borne : une demande precise, peu de fichiers, un test clair.

## Ce que tu vas apprendre

- Ecrire un brief de modification.
- Limiter le perimetre.
- Lire un resume de changements.
- Tester avant d'accepter.

## Prompt 10A - Lecon guidee

```text
Tu es ma prof pour travailler avec Codex ou Claude Code comme coworker.

Je veux apprendre a demander une modification de code sans perdre le controle.

Explique-moi :
- ce qu'est un bon brief pour un assistant de code,
- pourquoi il faut limiter les fichiers,
- pourquoi il faut definir le "fini",
- pourquoi il faut demander un test de validation,
- comment relire le resume des changements.

Ensuite, donne-moi un modele de demande pour mon portfolio.
```

## Prompt 10B - Creer une demande agent

```text
Aide-moi a transformer ma demande en prompt pour Codex ou Claude Code.

Ma demande :
[COLLER LA DEMANDE]

Contexte :
- portfolio statique simple,
- fichiers possibles : index.html, style.css, script.js,
- je suis debutante,
- je veux comprendre les changements.

Le prompt final doit contenir :
- contexte,
- objectif,
- fichiers concernes,
- contraintes,
- definition du fini,
- test de validation,
- demande de resume des fichiers modifies.

Garde le perimetre petit.
```

## Prompt 10C - Relire les changements

```text
J'ai recu une modification de mon assistant de code.

Ma demande initiale :
[COLLER ICI]

Resume ou diff :
[COLLER ICI]

Agis comme ma prof de relecture.
Dis-moi :
- ce qui a change,
- si cela respecte ma demande,
- si le changement est trop large,
- quoi tester dans le navigateur,
- si je dois accepter, corriger ou refuser.
```

## Resultat attendu

Tu sais piloter un agent de code sans lui laisser tout refaire.

---

# Chapitre 11 - Publier le portfolio

## Ce chapitre sert a quoi

Publier donne un vrai resultat : un lien partageable. Le but est de comprendre les etapes, pas seulement cliquer partout.

## Ce que tu vas apprendre

- Ce qu'est GitHub Pages ou une solution de publication simple.
- Envoyer un projet sur GitHub.
- Verifier le site en ligne.
- Mettre a jour apres une modification.

## Prompt 11A - Lecon guidee

```text
Tu es ma prof pour publier un site portfolio.

Je veux comprendre simplement :
- ce que veut dire publier un site,
- ce qu'est GitHub,
- ce qu'est GitHub Pages,
- ce qu'est un depot distant,
- comment une modification locale arrive en ligne.

Ensuite, guide-moi pour choisir la solution de publication la plus simple.
Ne me donne pas toutes les options, recommande une voie debutante.
```

## Prompt 11B - Publication pas a pas

```text
Guide-moi pas a pas pour publier mon portfolio.

Contexte :
- site statique simple,
- fichiers HTML, CSS, JavaScript et images,
- Git est deja installe ou en cours d'installation,
- je veux comprendre chaque etape.

Regles :
- une action a la fois,
- explique pourquoi on la fait,
- attends mon retour,
- si une erreur apparait, donne une seule action suivante,
- a la fin, donne-moi une checklist pour mettre a jour le site.
```

## Prompt 11C - Verification publication

```text
Verifie avec moi que mon site est bien publie.

Je vais te donner :
- le lien du site,
- ce que je vois,
- ce qui ne marche pas eventuellement.

Ta mission :
- verifier les points importants,
- m'aider a diagnostiquer les images manquantes ou liens casses,
- me dire comment publier une correction,
- me faire noter la procedure de mise a jour.
```

## Resultat attendu

Tu as un lien public et sait comment publier une mise a jour.

---

# Chapitre 12 - Creer des contenus avec l'IA

## Ce chapitre sert a quoi

La creation avec IA ne se limite pas au code. Tu peux produire des textes, des directions artistiques, des prompts d'images, des fiches projet.

## Ce que tu vas apprendre

- Ecrire sans perdre sa voix.
- Creer une direction artistique.
- Generer des prompts d'images de reference.
- Critiquer un resultat IA.

## Prompt 12A - Textes de portfolio

```text
Tu es ma prof d'ecriture de portfolio.

Je veux ecrire avec l'IA sans perdre ma voix.

Contenu brut :
[COLLER NOTES / BIO / DESCRIPTION PROJET]

Objectif :
[BIO COURTE / TEXTE ACCUEIL / FICHE PROJET / A PROPOS]

Ta mission :
- extraire les idees importantes,
- proposer une version claire,
- proposer une version plus sensible,
- proposer une version tres courte,
- me dire ce qui sonne naturel,
- me dire ce qui sonne trop IA,
- me faire choisir et corriger.
```

## Prompt 12B - Direction artistique

```text
Tu es ma prof de direction artistique avec l'IA.

Projet :
[DECRIRE]

Univers :
[DECRIRE]

Aide-moi a definir :
- couleurs,
- typographies,
- rythme de mise en page,
- types d'images,
- matieres,
- ton des textes,
- choses a eviter.

Propose 3 pistes.
Puis aide-moi a choisir une piste simple pour mon portfolio.
```

## Prompt 12C - Images de reference

```text
Aide-moi a ecrire des prompts d'images de reference.

Je ne veux pas copier le style d'un artiste vivant.
Je veux explorer :
- lumiere,
- matieres,
- cadrages,
- ambiance,
- couleurs.

Projet :
[COLLER ICI]

Direction artistique :
[COLLER ICI]

Propose 5 prompts d'image.
Pour chaque prompt, explique ce qu'il permet de tester.
```

## Resultat attendu

Tu sais utiliser l'IA comme atelier de contenus, pas seulement comme outil de code.

---

# Chapitre 13 - Automatiser des petites taches creatives

## Ce chapitre sert a quoi

Tu apprends que l'IA peut aider a automatiser des gestes repetitifs : renommer, classer, preparer, generer des fiches.

## Ce que tu vas apprendre

- Choisir une petite automatisation.
- Utiliser Raccourcis, Automator ou un script seulement si necessaire.
- Tester sur des copies.
- Documenter la routine.

## Prompt 13A - Lecon guidee

```text
Tu es ma prof d'automatisation creative sur Mac.

Je veux comprendre ce que je peux automatiser sans devenir developpeuse.

Explique-moi avec exemples :
- Raccourcis,
- Automator,
- petits scripts,
- ChatGPT comme assistant de preparation.

Mes domaines :
- photo,
- graphisme,
- edition,
- artisanat,
- portfolio.

Donne-moi 10 idees d'automatisations simples.
Classe-les par difficulte et risque.
```

## Prompt 13B - Construire une automatisation

```text
Aide-moi a construire une automatisation simple.

Tache que je veux automatiser :
[COLLER ICI]

Contraintes :
- je suis debutante,
- je veux tester sur des copies,
- je prefere Raccourcis ou Automator si possible,
- je ne veux pas de script complique sauf si necessaire.

Guide-moi une etape a la fois.
Explique chaque action.
Prevois un test et une marche arriere.
```

## Prompt 13C - Verification

```text
Verifie mon automatisation.

Je vais te decrire :
- ce qu'tu dois faire,
- les etapes,
- le test effectue,
- le resultat.

Dis-moi :
- si mon automatisation est sure,
- si elle est trop compliquee,
- comment la simplifier,
- comment la documenter pour la reutiliser.
```

## Resultat attendu

Tu as une petite automatisation utile et testee sans risque.

---

# Chapitre 14 - Savoir debloquer une erreur

## Ce chapitre sert a quoi

Quand tu bloques, tu dois savoir demander un diagnostic pedagogique a l'IA : pas une avalanche de solutions.

## Ce que tu vas apprendre

- Coller une erreur correctement.
- Decrire le contexte.
- Demander une seule action suivante.
- Distinguer probleme de code, terminal, installation, publication, contenu.

## Prompt 14A - Diagnostic general

```text
Je suis bloquee.

Contexte :
[CE QUE J'ESSAYAIS DE FAIRE]

Outil utilise :
[CHATGPT / CLAUDE / TERMINAL / VS CODE / CURSOR / CODEX / CLAUDE CODE / GITHUB]

Ce que je vois :
[COLLER ERREUR OU DECRIRE]

Ce que j'ai deja essaye :
[COLLER ICI]

Ta mission :
- reformuler le probleme simplement,
- identifier le type de blocage,
- me dire ce qui est sur et ce qui est incertain,
- demander seulement l'information manquante indispensable,
- me donner une seule action suivante.
```

## Prompt 14B - Erreur terminal

```text
Traduis cette erreur terminal en francais simple.

Erreur :
[COLLER ICI]

Dis-moi :
- ce que cela veut dire,
- si c'est grave,
- quelle commande ou action a probablement cause l'erreur,
- la correction la plus sure,
- ce que je dois verifier apres.

Une seule solution a la fois.
```

## Prompt 14C - Site casse

```text
Mon site ne marche plus comme avant.

Contexte :
[CE QUE J'AI MODIFIE]

Symptome :
[CE QUE JE VOIS]

Fichiers modifies :
[SI JE SAIS]

Ta mission :
- m'aider a identifier le dernier changement important,
- me dire quoi tester dans le navigateur,
- me dire quoi regarder dans le code,
- proposer une correction minimale,
- ne pas reecrire tout le site.
```

## Resultat attendu

Tu sais transformer un blocage en prochaine action claire.

---

# Chapitre 15 - Evaluation finale

## Ce chapitre sert a quoi

Verifier que tu sais apprendre et creer avec l'IA : cadrer, installer, comprendre, demander, tester, publier.

## Ce que tu vas apprendre a prouver

- Choisir le bon outil.
- Ecrire une demande d'apprentissage.
- Faire une petite modification.
- Utiliser Git comme protection.
- Relire une modification IA.
- Publier ou expliquer la publication.

## Prompt 15A - Evaluation complete

```text
Fais-moi passer une evaluation pratique de creation avec l'IA.

Je veux verifier si je sais :
- choisir le bon outil IA,
- utiliser le terminal de base,
- comprendre Git,
- cadrer une demande pour Codex ou Claude Code,
- modifier un portfolio simple,
- relire et tester une modification,
- publier ou preparer une publication.

Donne-moi un scenario realiste.
Pose-moi les questions une par une.
Corrige mes reponses.
Donne-moi a la fin :
- une note sur 10,
- mes points forts,
- mes points fragiles,
- les 3 prochains exercices a faire.
```

## Prompt 15B - Scenario client

```text
Joue le role d'une cliente qui me demande 3 modifications sur mon portfolio.

Pour chaque modification, je dois dire :
- quel outil j'utilise,
- quel prompt j'ecris,
- quels fichiers peuvent etre concernes,
- comment je teste,
- quand je fais un commit.

Corrige-moi comme une prof.
```

## Prompt 15C - Plan de suite

```text
A partir de mon niveau actuel, construis-moi un plan de progression pour les 30 prochains jours.

Je veux continuer a apprendre :
- creation avec IA,
- portfolio,
- Codex ou Claude Code,
- automatisations Mac,
- contenus creatifs.

Donne-moi un plan simple :
- 3 objectifs,
- 1 exercice par semaine,
- 1 projet fil rouge,
- 1 critere de reussite.
```

## Resultat attendu

Tu sais continuer seule avec une methode claire.

---

# Parcours conseille

## Semaine 1 - Comprendre et preparer

- Chapitre 1 : carte des outils IA.
- Chapitre 2 : organiser son Mac.
- Chapitre 3 : terminal.
- Chapitre 4 : installer les outils.

## Semaine 2 - Bases de projet

- Chapitre 5 : Git et GitHub.
- Chapitre 6 : assistants de code IA.
- Chapitre 7 : Codex ou Claude Code.
- Chapitre 8 : plan du portfolio.

## Semaine 3 - Creer

- Chapitre 9 : HTML/CSS/JS par le portfolio.
- Chapitre 10 : travailler avec un agent de code.
- Chapitre 11 : publier.
- Chapitre 12 : contenus et direction artistique.

## Semaine 4 - Autonomie

- Chapitre 13 : automatisation.
- Chapitre 14 : depannage.
- Chapitre 15 : evaluation.

---

# Regle finale

Le guide ne sert pas a copier des reponses.

Il sert a apprendre a piloter l'IA :

- demander une lecon,
- pratiquer,
- verifier,
- corriger,
- produire,
- tester,
- publier.

Quand tu sais faire ca, tu ne depends plus d'un prompt magique. Tu sais apprendre avec l'IA.
