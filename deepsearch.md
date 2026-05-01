Playbook progressif en français pour amener une créative sur Mac à maîtriser ChatGPT, Codex, le terminal et un portfolio web simple
Résumé exécutif
La forme la plus efficace pour votre mère n’est pas une collection de “prompts magiques” isolés, mais un seul parcours guidé, continu, en français, centré sur un projet réel : construire puis faire évoluer son propre site portfolio. Les documentations officielles de OpenAI, Apple, Microsoft, GitHub et le MDN de Mozilla convergent vers la même idée : pour débuter, il faut un environnement simple, des consignes explicites, une progression par petites étapes, et des vérifications fréquentes plutôt qu’une automatisation opaque d’emblée. 

Le meilleur socle technique, compte tenu de contraintes non précisées sur le budget, l’accès Internet et la formule ChatGPT, est un parcours “browser-first, local-second” : commencer dans ChatGPT sur le web, puis ajouter progressivement Terminal, Visual Studio Code, Git, Node.js et enfin Codex. Cette stratégie réduit la friction matérielle : l’app ChatGPT pour macOS exige macOS 14 et Apple Silicon, alors que Codex existe sur macOS Intel et Apple Silicon, et le CLI Codex s’installe localement via npm. L’accès à Codex dépend de la formule et peut évoluer ; au 1er mai 2026, OpenAI indique qu’il est inclus dans Plus, Pro, Business et Enterprise/Edu, et temporairement aussi dans Free et Go. 

Pédagogiquement, le playbook doit fonctionner comme un professeur particulier par prompts : chaque prompt demande à ChatGPT d’enseigner, de poser des questions, d’attendre la réponse, de faire vérifier les commandes et de proposer un mini-exercice avant de passer à l’étape suivante. Cette logique est cohérente avec les bonnes pratiques d’OpenAI sur le prompting, avec le mode étude de ChatGPT, avec les Projets pour conserver le contexte, avec Canvas pour réviser du code, et avec la recommandation officielle de Codex : lui donner un contexte explicite et une définition claire du “fini”. 

La cible réaliste en 30 jours n’est pas de “devenir développeuse”, mais de devenir autonome sur cinq gestes à forte valeur : dialoguer correctement avec l’IA, naviguer sans peur dans le terminal, installer et vérifier son environnement, créer/modifier un site portfolio statique simple, puis utiliser Codex et des automatisations légères pour gagner du temps sur des tâches créatives répétitives. Cette cible est ambitieuse mais cohérente avec les parcours officiels de démarrage web, Git, VS Code, Node.js et publication statique. 

Profil d’apprentissage, objectifs et critères d’entrée
Le profil apprenant est clair : une personne créative, à l’aise avec le Mac et les logiciels grand public, mais intimidée par l’IA quand elle semble trop rapide, trop technique ou trop sûre d’elle. Son avantage compétitif n’est pas la syntaxe, mais le goût, l’œil, le sens de l’édition, la narration visuelle et la capacité à juger si un rendu “fait sens”. Le playbook doit donc éviter de l’enfermer dans le jargon et s’appuyer au contraire sur ses univers naturels : graphisme, photo, édition littéraire et artisanat.

Les objectifs d’apprentissage pertinents sont les suivants. À la fin du parcours, elle doit savoir : cadrer une demande à ChatGPT, reformuler un besoin créatif en consigne exploitable, ouvrir Terminal sans angoisse, comprendre ce qu’elle est en train de faire avant d’exécuter une commande, installer et vérifier VS Code, Git et Node.js, créer un dépôt Git, générer puis modifier un site portfolio simple en HTML/CSS/JS, publier une version publique de ce site, puis déléguer à Codex des modifications bornées et révisables.

Les vérifications préalables doivent rester simples. Apple recommande d’utiliser le menu Pomme > “À propos de ce Mac” ou Réglages Système > Général > Informations pour vérifier le modèle et la version exacte de macOS, et Spotlight pour retrouver ou ouvrir les applications. Comme l’app ChatGPT pour macOS impose macOS 14 et Apple Silicon, il est plus prudent de prendre le web comme base et de considérer l’app de bureau comme optionnelle. 

Vérification	Ce qu’elle doit confirmer	Méthode simple	Si ce n’est pas prêt
Mac fonctionnel	Version macOS connue, espace disque raisonnable, connexion Internet	“À propos de ce Mac”, puis test navigateur	Rester sur le web et reporter les apps natives
Accès ChatGPT	Compte connecté sur le web	Ouvrir ChatGPT dans Safari/Chrome	Créer le compte avant toute autre étape
Terminal	L’app Terminal s’ouvre	Spotlight → “Terminal”	Utiliser Spotlight pour l’ouvrir à chaque séance au début
VS Code	Installé et ouvrable	Téléchargement officiel, puis test code . plus tard	Installer d’abord le .dmg, configurer le PATH ensuite
Git	Disponible	git --version	Accepter l’installation des Xcode Command Line Tools ou utiliser l’installateur Git
Node.js	Version LTS installée	node --version et npm --version	Installer la LTS officielle puis rouvrir le terminal
GitHub	Compte disponible pour publier	Connexion navigateur	Peut être différé jusqu’à la publication
Codex	Accès autorisé par son compte	Connexion Codex app/CLI/web	Si indisponible, tout le parcours reste faisable avec ChatGPT seul

Le critère d’entrée le plus important n’est pas technique mais cognitif : elle doit accepter une règle simple, “je ne colle pas un prompt pour obtenir seulement un résultat ; je colle un prompt pour apprendre à refaire le résultat.” C’est exactement ce qui différencie un playbook d’apprentissage d’une simple bibliothèque de recettes.

Architecture pédagogique du playbook
Le playbook doit être construit comme un projet unique dans ChatGPT, avec une instruction maîtresse conservée dans le même espace de travail. Les Projets de ChatGPT sont justement conçus pour regrouper des chats, des fichiers de référence et des instructions récurrentes dans un contexte durable. Canvas est utile pour retravailler du texte et du code dans un espace partagé, tandis que le mode étude ajoute un comportement socratique, pas à pas, qui correspond parfaitement à une logique “teacher prompts”. 

Sur le plan du prompting, la structure la plus solide est toujours la même : contexte, objectif, contraintes, étapes, format de sortie, vérification. OpenAI recommande explicitement de placer les instructions au début, de séparer l’instruction du contexte, et d’être spécifique sur le résultat attendu. Les guides ChatGPT rappellent aussi qu’il faut parler au modèle comme à un collaborateur humain compétent : avec des détails, un cadre et un critère de réussite. Codex pousse le même principe encore plus loin : il fonctionne mieux lorsqu’on le traite comme un coéquipier avec un contexte explicite et une définition claire de “done”. 

Le playbook doit donc avoir deux couches. La première est un prompt maître pédagogique qui règle le comportement de l’assistant pour tout le mois. La seconde est une série de sous-prompts de session, toujours courts, qui déclenchent une leçon praticable immédiatement : comprendre le terminal, installer Git, lire un git status, générer une page HTML, demander à Codex une modification circonscrite, ou créer une automatisation simple. Cette architecture diminue la charge mentale parce qu’elle évite de devoir réinventer la consigne pédagogique à chaque fois.

Voici le flux d’apprentissage recommandé :

Créer un projet ChatGPT dédié

Coller le prompt maître pédagogique

Apprendre les bases de l'IA

Comprendre Terminal et le système de fichiers

Installer VS Code, Git et Node

Créer un mini-projet web local

Versionner avec Git

Générer puis modifier le portfolio

Publier une première version

Utiliser Codex pour des changements bornés

Créer deux automatisations créatives

Évaluation finale et autonomie



Afficher le code
Le prompt maître recommandé est le suivant :

text
Copier
Tu es mon professeur particulier d'IA, de terminal Mac et de création de sites web.

Contexte sur moi :
- Je suis une créative sur Mac.
- Je travaille autour du graphisme, de la photo, de l'édition littéraire et de l'artisanat.
- Je suis à l'aise avec l'ordinateur, mais je débute en IA.
- Je me sens vite dépassée si tu vas trop vite ou si tu utilises trop de jargon.
- Mon objectif est d'apprendre à utiliser ChatGPT, Codex, le terminal et VS Code pour créer et modifier un site portfolio simple et automatiser quelques tâches créatives.

Ta mission pédagogique :
- Tu m'enseignes progressivement, comme une prof patiente et structurée.
- Tu me fais pratiquer au lieu de faire à ma place.
- Tu avances une seule étape à la fois.
- Tu commences toujours par expliquer simplement ce que l'on va faire et pourquoi c'est utile.
- Tu me donnes ensuite une action concrète à faire.
- Tu attends ma réponse avant de continuer.
- Tu me fais toujours vérifier que j'ai compris avec 2 ou 3 questions courtes ou un mini-exercice.
- Si je colle une commande terminal, tu me l'expliques avant et après.
- Si je colle une erreur, tu la traduis en français simple puis tu proposes le correctif le plus sûr.
- Si je demande du code, tu l'expliques ligne par ligne.
- Si je semble perdue, tu reformules plus simplement.

Règles :
- N'utilise pas de jargon sans définition.
- N'avance jamais de plus de 10 minutes de travail d'un coup.
- Donne-moi des checklists courtes.
- Pour chaque séance, termine par :
  1) ce que j'ai appris,
  2) ce que je dois retenir,
  3) le prochain petit pas.

Réponds d'abord par :
- un diagnostic rapide de mon niveau,
- puis la première mini-leçon la plus utile pour commencer aujourd'hui.
Curriculum progressif sur 30 jours
Le cursus le plus robuste consolide tout dans un seul projet vivant : un portfolio personnel statique, versionné dès le début, enrichi chaque semaine. Les parcours MDN, Git, VS Code, Node.js et GitHub Pages montrent qu’un enchaînement “environnement → fichiers → versioning → code → publication” est le plus naturel pour un débutant. 

Module consolidé	Jours	Objectif	Outils	Difficulté	Livrable
Démystifier l’IA	1–5	Comprendre comment dialoguer avec ChatGPT sans se sentir “bête”	ChatGPT web, Projet, éventuellement mode étude	Facile	Une routine de dialogue claire
Prendre pied sur Mac et Terminal	6–10	Comprendre le terminal, le système de fichiers et installer l’environnement	Terminal, VS Code, Git, Node	Facile à moyen	Poste prêt et vérifié
Travailler proprement	11–15	Comprendre projet, dossier, dépôt, commit, synchronisation	VS Code, Git, GitHub	Moyen	Dépôt initial du portfolio
Construire le portfolio	16–24	Générer, lire, modifier et améliorer HTML/CSS/JS	ChatGPT, VS Code, navigateur	Moyen	Version locale puis publique du site
Passer à Codex et aux automatisations	25–30	Demander des modifications bornées et créer deux gains de temps créatifs	Codex CLI/app/web, Shortcuts, Automator	Moyen à soutenu	Site amélioré + 2 automatisations

Voici une vue temporelle compacte :

01/05
03/05
05/05
07/05
09/05
11/05
13/05
15/05
17/05
19/05
21/05
23/05
25/05
27/05
29/05
31/05
Dialogue avec ChatGPT
Terminal et setup
VS Code + Git
HTML/CSS/JS + portfolio
Codex + automatisations
IA
Mac
Versioning
Web
Agentique
Timeline sur 30 jours


Afficher le code
Tableau quotidien sur 30 jours
Jour	Focus du jour	Résultat attendu
1	Découvrir ce qu’est un prompt et ce qu’on peut demander à ChatGPT	Elle sait formuler un besoin simple
2	Distinguer IA, modèle, prompt, mémoire, projet, vérification	Elle sait quand faire confiance et quand vérifier
3	Reformuler des demandes dans ses domaines créatifs	3 prompts utiles en graphisme/photo/édition
4	Mini-exercices guidés et quiz	1 session complète sans blocage
5	Récapitulatif et charte d’usage personnelle	Sa “méthode ChatGPT” écrite
6	Ouvrir Terminal, comprendre terminal/shell/commande	Plus d’anxiété face à la fenêtre noire
7	Naviguer avec cd et ls, créer des dossiers et fichiers	Un dossier de test maîtrisé
8	Installer Git et comprendre à quoi sert Git	git --version fonctionne
9	Installer Node.js LTS et comprendre node/npm	node --version et npm --version fonctionnent
10	Installer VS Code et activer code dans le terminal	code . ouvre le dossier courant
11	Créer le dossier portfolio-maman	Projet local créé
12	Initialiser Git et configurer nom/e-mail	Dépôt prêt
13	Faire le premier commit	Historique initial enregistré
14	Lire git status, staging, commit	Elle sait lire l’état du dépôt
15	Créer ou connecter un dépôt GitHub	Sauvegarde distante prête
16	Définir l’arborescence éditoriale du portfolio	Plan du site validé
17	Générer index.html avec sections claires	Page structurée
18	Générer style.css	Mise en forme de base
19	Améliorer typographie, marges, couleurs, hiérarchie	Version visuelle crédible
20	Ajouter script.js simple	Une interaction légère fonctionne
21	Lire et annoter le code ligne par ligne	Compréhension minimale acquise
22	Ajouter les vrais contenus créatifs	Site personnalisé
23	Corriger et refactorer	Code plus propre
24	Publier la première version	Portfolio en ligne
25	Installer ou ouvrir Codex et comprendre local/cloud	Premier contact sans stress
26	Demander à Codex une petite modification bornée	Changement révisé
27	Demander à Codex une amélioration visuelle ciblée	Deuxième changement propre
28	Créer une automatisation créative simple	Gain de temps concret
29	Créer une deuxième automatisation	Routine réutilisable
30	Évaluation finale et feuille de route autonome	Elle peut recommencer seule

Détail des modules avec sous-prompts, exercices et évaluations
Module d’amorçage IA

Objectif d’apprentissage. Comprendre ce qu’est un prompt, comment dialoguer avec ChatGPT, comment demander une explication, comment réclamer une reformulation, et comment vérifier une réponse plutôt que la subir. OpenAI recommande des instructions claires, détaillées et structurées ; le mode étude formalise justement ce comportement interactif, question par question. 

Pourquoi c’est important. Si elle rate cette étape, elle vivra l’IA comme une boîte noire intimidante. Si elle la réussit, l’IA devient un assistant pédagogiquement pilotable plutôt qu’un oracle.

Hiérarchie de sous-prompts à coller dans ChatGPT.

Prompt maître pédagogique.
Prompt “Explique-moi l’IA sans jargon”.
Prompt “Fais-moi reformuler mes besoins créatifs”.
Prompt “Fais-moi un mini-quiz et vérifie ma compréhension”.
Prompt “Transforme ma demande confuse en bonne demande”.
Actions attendues. Répondre à des questions simples sur ses objectifs, reformuler une demande, demander une version plus courte ou plus claire, puis faire un mini-exercice.

Exercices.

Demander trois variantes de bio d’artiste.
Demander cinq titres pour une série photo.
Demander une critique constructive d’un texte de présentation.
Terminer par un quiz de cinq questions ouvertes.
Prompts de vérification.

“Résume ce que j’ai compris en 5 phrases très simples.”
“Pose-moi 3 questions pour vérifier si j’ai bien compris la différence entre un prompt flou et un prompt précis.”
“Prends ma dernière demande et montre-moi comment la rendre meilleure.”
Dépannage.

Si la réponse est trop longue : “Réécris la même réponse en 8 lignes maximum.”
Si elle est trop technique : “Réexplique pour une débutante sur Mac, sans jargon non défini.”
Si elle n’a pas compris : “Donne-moi un exemple dans le domaine de la photo / de l’édition / de l’artisanat.”
Prompt d’évaluation.

text
Copier
Teste-moi sur les bases de l'utilisation de l'IA. Fais-moi un mini-oral écrit :
- 5 questions courtes,
- 2 exercices de reformulation de prompts,
- puis donne-moi une note sur 10 et les 3 points à améliorer.
Module Terminal et setup Mac

Objectif d’apprentissage. Comprendre ce qu’est Terminal, ce qu’est un shell, ouvrir les apps sur Mac, naviguer dans les dossiers, puis installer proprement Git, Node.js, VS Code et Codex CLI. MDN rappelle qu’un terminal est un logiciel qui se connecte à un shell, et que la ligne de commande est l’endroit où l’on saisit les commandes ; Apple documente l’ouverture des apps via Spotlight et la vérification des informations système ; Git, VS Code et Node.js documentent tous la procédure d’installation sur macOS. 

Pourquoi c’est important. Sans cette étape, tout ce qui touche à Codex, Git et aux projets web restera fragile, dépendant d’autrui et anxiogène.

Hiérarchie de sous-prompts à coller dans ChatGPT.

“Explique-moi ce qu’est Terminal sur Mac.”
“Fais-moi pratiquer cd, ls, mkdir, touch et les chemins relatifs.”
“Guide-moi pour installer Git, Node.js et VS Code pas à pas.”
“Apprends-moi à vérifier chaque installation.”
“Guide-moi pour installer Codex CLI et faire un premier test sans risque.”
Actions attendues. Ouvrir Terminal, créer un dossier d’essai, y créer un fichier, installer les outils, puis coller les sorties de vérification à ChatGPT pour interprétation.

Exercices.

Créer atelier-ia-test, puis un fichier notes.txt.
Ouvrir le dossier dans VS Code avec code ..
Vérifier git --version, node --version, npm --version.
Configurer Git avec nom et e-mail.
Prompts de vérification.

text
Copier
Je vais coller la sortie de mes commandes terminal.
Ta mission :
- me dire ce qui est OK,
- me dire ce qui bloque,
- me donner UNE seule action suivante,
- expliquer chaque message d'erreur en français simple.
Dépannage.

Si git --version déclenche une installation, c’est le comportement prévu sur beaucoup de Mac via les Xcode Command Line Tools. 
Si code . ne fonctionne pas, il faut activer la commande code dans le PATH depuis la Command Palette de VS Code, puis redémarrer le terminal. 
Si node ou npm ne sont pas reconnus, il faut rouvrir le terminal après l’installation. 
Si macOS bloque l’ouverture d’une app téléchargée hors App Store, Apple documente le contournement via Réglages Système > Confidentialité et sécurité > “Ouvrir quand même”, mais souligne que c’est moins sûr que l’App Store ou une source officielle. 
Prompt d’évaluation.

text
Copier
Fais-moi un contrôle pratique sur le terminal Mac.
Demande-moi de :
- créer un dossier,
- entrer dedans,
- créer un fichier,
- lister son contenu,
- ouvrir le dossier dans VS Code,
puis corrige-moi comme une prof patiente.
Module VS Code, Git et projet propre

Objectif d’apprentissage. Comprendre qu’un projet web n’est qu’un dossier bien organisé, qu’un dépôt Git est une mémoire de versions, et que VS Code permet de gérer beaucoup d’opérations Git sans vivre dans le terminal. Git demande de configurer d’abord user.name et user.email, et VS Code documente un flux clair : ouvrir un projet, initialiser un dépôt, relire les changements, indexer, committer, synchroniser. 

Pourquoi c’est important. Git n’est pas un rite initiatique ; c’est un pare-chocs pédagogique. Sans Git, l’erreur fait peur. Avec Git, l’erreur devient réversible.

Hiérarchie de sous-prompts à coller dans ChatGPT.

“Explique-moi Git avec une métaphore compréhensible.”
“Guide-moi pour créer mon projet portfolio-maman.”
“Aide-moi à faire mon premier commit propre.”
“Explique-moi git status, le staging et le commit avec mes vrais fichiers.”
“Guide-moi pour publier mon dossier sur GitHub.”
Actions attendues. Créer le projet, initialiser Git, faire un README, faire un premier commit, puis envoyer le dépôt sur GitHub.

Exercices.

Créer un fichier README.md qui décrit le projet.
Faire un commit “Initialisation du portfolio”.
Modifier le README et observer la différence dans VS Code.
Créer le dépôt distant et synchroniser.
Prompts de vérification.

text
Copier
Je vais te coller le résultat de `git status`.
Explique-moi :
- ce qui a changé,
- ce qui n'est pas encore enregistré,
- ce que je risque si je me trompe,
- la prochaine commande ou action VS Code la plus simple.
Dépannage.

Si Git refuse un commit à cause de l’identité, reconfigurer user.name et user.email. 
Si elle a peur du terminal, utiliser d’abord l’interface Source Control de VS Code pour voir les fichiers modifiés, relire le diff et valider visuellement. 
Si le dépôt cloné paraît “dangereux”, respecter l’avertissement de VS Code sur la confiance des dépôts et ne faire confiance qu’aux sources connues. 
Prompt d’évaluation.

text
Copier
Interroge-moi sur Git niveau débutante.
Je veux :
- 5 questions courtes,
- 1 exercice où tu me donnes un faux `git status` à interpréter,
- 1 exercice où je dois décider s'il faut committer, corriger ou annuler.
Module HTML, CSS, JavaScript et portfolio

Objectif d’apprentissage. Comprendre la logique “HTML = structure, CSS = apparence, JavaScript = interactivité”, puis l’appliquer à un site portfolio personnel. MDN définit HTML comme la structure du contenu, CSS comme la mise en forme, et JavaScript comme le langage qui ajoute l’interactivité. 

Pourquoi c’est important. Cette triade est le niveau minimum pour qu’elle ne subisse plus un site généré par IA, mais qu’elle sache l’habiter, le corriger et l’éditer.

Hiérarchie de sous-prompts à coller dans ChatGPT.

“Aide-moi à définir l’architecture éditoriale de mon portfolio.”
“Génère un index.html simple, élégant et expliqué ligne par ligne.”
“Génère un style.css cohérent avec une direction artistique douce, éditoriale et artisanale.”
“Ajoute un script.js très simple et explique-le.”
“Relis l’ensemble du projet et propose seulement les corrections nécessaires.”
Actions attendues. Valider le plan du site, créer 3 fichiers (index.html, style.css, script.js), ouvrir localement le site, corriger, enrichir avec ses vrais contenus.

Exercices.

Construire les sections : accueil, à propos, travaux, photo, édition, artisanat, contact.
Ajouter une grille de projets.
Changer palette, typo, espacements.
Ajouter une interaction légère : bouton “voir plus”, menu mobile simple, filtre de catégories ou thème clair/sombre.
Demander à ChatGPT d’expliquer chaque bloc.
Prompts de vérification.

text
Copier
Je vais te coller mon code HTML/CSS/JS.
Ta mission :
- me dire ce qui est bien,
- me dire ce qui est inutile,
- me dire ce qui est fragile,
- proposer la correction la plus simple,
- expliquer les changements en français clair.
text
Copier
Agis comme une prof de code.
N'écris pas tout de suite le nouveau code.
Commence par :
1) résumer la structure actuelle du site,
2) repérer les 3 problèmes les plus importants,
3) me demander mon accord avant toute réécriture.
Dépannage.

Si le rendu paraît “cassé”, revenir au dernier commit sain puis refaire une petite modification.
Si le CSS devient illisible, demander une réorganisation pédagogique par sections commentées.
Si JavaScript semble trop mystérieux, réduire l’ambition et garder une seule interaction.
Prompt d’évaluation.

text
Copier
Fais-moi une soutenance technique adaptée à une débutante :
- demande-moi à quoi servent HTML, CSS et JavaScript dans mon site,
- fais-moi décrire la structure de ma page,
- demande-moi où modifier un texte, une couleur et un comportement interactif,
- puis évalue mon autonomie réelle.
Module Codex, publication et automatisations créatives

Objectif d’apprentissage. Utiliser Codex comme collaborateur de code, pas comme magicien incontrôlé, puis créer deux petites automatisations créatives réutilisables. OpenAI documente trois voies principales : Codex CLI pour travailler localement dans le terminal, l’extension IDE pour VS Code, et Codex web/cloud pour déléguer en environnement cloud ; Codex web nécessite une connexion GitHub, tandis que l’app et le CLI permettent une exécution locale. Les fonctionnalités avancées varient selon le mode d’authentification et la formule. 

Pourquoi c’est important. C’est l’étape où elle passe de “je comprends un peu” à “je peux produire plus vite sans perdre la main”.

Hiérarchie de sous-prompts à coller dans ChatGPT ou Codex.

“Explique-moi quand utiliser ChatGPT et quand utiliser Codex.”
“Guide-moi pour demander à Codex une petite modification sûre et révisable.”
“Fais-moi préparer un prompt Codex avec contexte, contraintes et définition du fini.”
“Guide-moi pour publier mon site sur GitHub Pages.”
“Aide-moi à choisir deux automatisations créatives simples sur Mac.”
Actions attendues. Installer ou ouvrir Codex, travailler dans le dossier du portfolio, demander une petite modification, relire le diff, committer, publier, puis créer deux automatisations légères.

Exercices.

Demander à Codex d’ajouter une nouvelle carte projet.
Demander à Codex de changer la palette du site sans casser la structure.
Demander à Codex d’ajouter une page “À propos”.
Publier le site avec GitHub Pages.
Créer une automatisation de renommage/organisation de fichiers créatifs.
Créer une automatisation d’aide éditoriale ou de préparation de contenus.
Prompts de vérification.

text
Copier
Avant d'appliquer quoi que ce soit, reformule ma demande comme un brief de développement :
- objectif,
- fichiers concernés,
- contraintes,
- définition du "fini",
- risques éventuels,
- test de validation.
text
Copier
J'ai reçu une proposition de modification par Codex.
Agis comme une relectrice technique :
- résume ce qui change,
- dis-moi si c'est cohérent avec ma demande,
- repère les zones risquées,
- propose "valider", "corriger", ou "refuser", avec explication.
Dépannage.

Si Codex agit trop large, réduire le périmètre à “un fichier, une intention, un test”.
Si elle utilise Codex web, rappeler qu’il faut connecter GitHub. 
Si elle utilise l’app Codex en France, ignorer pour l’instant la fonction “computer use”, non disponible au lancement dans l’EEE, au Royaume-Uni et en Suisse. 
Pour l’automatisation Mac, privilégier d’abord Raccourcis et Automator, qu’Apple documente explicitement comme outils pour automatiser sans être programmeur chevronné, avec possibilité d’utiliser des scripts shell, AppleScript ou JavaScript, et même d’exécuter des raccourcis depuis la ligne de commande via shortcuts. 
Prompt d’évaluation.

text
Copier
Mets-moi en situation réelle.
Je veux que tu joues le rôle d'une cliente qui me demande 3 modifications sur mon portfolio.
Je dois :
- analyser la demande,
- décider si j'utilise ChatGPT, Codex ou moi-même,
- écrire le bon prompt,
- définir le test de validation,
- puis expliquer ma décision.
Corrige-moi ensuite.
Bibliothèque de prompts prêts à coller
Les prompts ci-dessous sont pédagogiques : ils demandent à l’IA d’enseigner, de faire pratiquer et de vérifier. Ils sont écrits pour une créative sur Mac, débutante en IA, mais déjà familière avec des logiciels courants.

Prompt de démarrage général

text
Copier
Tu es ma prof particulière d'IA et de création de sites web.

Mon profil :
- je travaille sur Mac,
- je suis créative (graphisme, photo, édition littéraire, artisanat),
- je suis à l'aise avec l'ordinateur mais débutante en IA,
- je veux apprendre à utiliser ChatGPT, Codex, Terminal, VS Code, Git et les bases du web,
- je veux comprendre ce que je fais, pas juste copier-coller des résultats.

Ta méthode :
- explique simplement,
- fais-moi pratiquer,
- va une petite étape à la fois,
- attends ma réponse avant la suite,
- reformule si je bloque,
- donne toujours un mini-exercice,
- termine chaque séance par un résumé + prochain pas.

Commence par me poser 5 questions pour évaluer mon niveau et me proposer la meilleure première séance.
Prompt pour comprendre le terminal sur Mac

text
Copier
Explique-moi ce qu'est Terminal sur Mac comme si j'étais une adulte intelligente mais débutante.
Je veux que tu m'expliques :
- ce qu'est un terminal,
- ce qu'est un shell,
- à quoi ça sert,
- pourquoi des créatifs et des développeurs l'utilisent,
- ce que je peux casser et ce que je ne risque pas de casser avec des commandes simples.

Ensuite :
- donne-moi 5 commandes ultra-débutantes à faire sur Mac,
- explique chaque commande avant que je la tape,
- attends que je te colle le résultat,
- puis corrige-moi et passe à la suivante.
Ne vas pas trop vite.
Prompt pour le setup Mac, Git, Node et VS Code

text
Copier
Guide-moi pas à pas pour préparer mon Mac au travail avec l'IA et le web.

Je veux installer et vérifier :
- Git,
- Node.js (version LTS),
- Visual Studio Code,
- puis la commande `code` dans le terminal.

Règles :
- une seule étape à la fois,
- commence toujours par me dire pourquoi on fait l'étape,
- donne-moi la commande exacte ou l'action exacte,
- attends mon retour,
- interprète mes messages d'erreur en français simple,
- à la fin, fais-moi une checklist de vérification complète.
Prompt pour apprendre Git comme une débutante

text
Copier
Apprends-moi Git avec des métaphores simples.
Explique-moi :
- ce qu'est un dépôt,
- ce qu'est un commit,
- à quoi sert l'historique,
- ce que veut dire "stager" un fichier,
- comment ne pas avoir peur de faire une erreur.

Ensuite guide-moi dans un vrai exercice :
- créer un dossier de projet,
- l'initialiser avec Git,
- créer un README,
- faire mon premier commit,
- puis me faire lire `git status`.

Corrige-moi comme une prof patiente.
Prompt pour créer le projet portfolio

text
Copier
Aide-moi à concevoir mon site portfolio personnel.

Mon univers :
- créative sur Mac,
- graphisme,
- photo,
- édition littéraire,
- artisanat,
- sensibilité éditoriale, sobre, élégante, humaine.

Je veux que tu m'aides à faire, dans cet ordre :
1) la structure éditoriale du site,
2) la liste des sections,
3) les contenus à préparer,
4) l'arborescence des fichiers,
5) une version très simple du site, facile à comprendre.

Important :
- ne me donne pas tout le code tout de suite,
- commence par l'architecture du site,
- pose-moi des questions sur mon style et mes contenus,
- puis attends ma validation avant de générer le code.
Prompt pour apprendre HTML, CSS et JavaScript en construisant

text
Copier
Tu es ma prof de code.
Je veux apprendre HTML, CSS et JavaScript en construisant mon portfolio, pas en lisant un cours abstrait.

Méthode :
- commence par m'expliquer en 5 lignes la différence entre HTML, CSS et JavaScript,
- puis génère une première version très simple de `index.html`,
- explique chaque grande partie du fichier,
- attends ma validation,
- génère ensuite `style.css`,
- explique ce qui gère la typographie, l'espacement, les couleurs et la mise en page,
- attends ma validation,
- ensuite seulement génère un `script.js` très simple,
- explique ligne par ligne.

À la fin de chaque étape, donne-moi :
- ce que je peux modifier seule,
- un mini-exercice,
- et une question de vérification.
Prompt pour relire et corriger le code

text
Copier
Je vais te coller mon code.
Ta mission n'est pas de tout réécrire d'un coup.
Je veux que tu :
- résumes d'abord ce que fait mon code,
- repères les 3 problèmes les plus importants,
- sépares clairement les erreurs de logique, de structure et de style,
- proposes la correction la plus simple,
- expliques les changements en français clair,
- puis me demandes mon accord avant de réécrire quoi que ce soit.
Prompt pour apprendre à utiliser Codex proprement

text
Copier
Apprends-moi à utiliser Codex sans perdre le contrôle.

Je veux que tu m'expliques :
- à quoi sert Codex par rapport à ChatGPT,
- quand il vaut mieux utiliser ChatGPT,
- quand il vaut mieux utiliser Codex,
- comment écrire une demande Codex claire et bornée,
- comment relire un diff avant d'accepter une modification.

Ensuite, fais-moi préparer un vrai prompt Codex pour mon portfolio.
Je veux un format avec :
- contexte,
- objectif,
- fichiers concernés,
- contraintes,
- définition du fini,
- test de validation.
Prompt pour demander une petite modification à Codex

text
Copier
Aide-moi à écrire un prompt Codex pour une petite modification sûre.

Contexte :
- je travaille sur un portfolio statique simple,
- je veux une modification limitée,
- je veux comprendre ce qui change.

Ta mission :
- reformule ma demande comme un brief développeur très clair,
- limite le périmètre à un petit nombre de fichiers,
- demande à Codex d'expliquer ce qu'il va faire,
- exige un résumé des fichiers modifiés,
- exige une explication des tests à faire,
- exige qu'aucune fonctionnalité non demandée ne soit ajoutée.

Ma demande à transformer est :
[COLLER ICI LA DEMANDE]
Prompt pour publier sur GitHub Pages

text
Copier
Guide-moi pas à pas pour publier mon portfolio sur GitHub Pages.

Je veux :
- comprendre simplement ce qu'est GitHub Pages,
- créer le dépôt nécessaire,
- envoyer mon projet,
- configurer la publication,
- vérifier que le site est en ligne,
- comprendre comment le mettre à jour ensuite.

Règles :
- une étape à la fois,
- toujours me dire pourquoi on fait l'étape,
- me faire vérifier après chaque étape,
- si quelque chose ne marche pas, me proposer le diagnostic le plus simple.
Prompt pour une automatisation créative simple sur Mac

text
Copier
Aide-moi à créer une petite automatisation utile sur Mac, adaptée à une créative débutante.

Je préfère commencer avec :
- Raccourcis,
- Automator,
- ou un mini-script très simple si nécessaire.

D'abord, propose-moi 5 idées vraiment utiles pour mon profil :
- photo,
- graphisme,
- édition,
- artisanat,
- organisation de portfolio.

Pour chaque idée, donne :
- le gain de temps réel,
- la difficulté,
- l'outil recommandé,
- le niveau de risque,
- et l'idée la plus simple pour commencer aujourd'hui.

Ensuite, une fois que j'ai choisi, guide-moi pas à pas et fais-moi tout comprendre.
Prompt pour transformer ChatGPT en coach de session

text
Copier
Pour cette séance, tu es mon coach de travail.

Je veux une session de 20 minutes maximum.
Structure obligatoire :
1) objectif du jour,
2) explication simple,
3) action concrète à faire,
4) vérification,
5) mini-exercice,
6) résumé de ce que j'ai appris.

Sujet du jour :
[COLLER ICI LE SUJET]
Dépannage, sécurité, évaluation et limites
Le rapport recommande une prudence structurée, pas une peur diffuse. Apple documente clairement les avertissements de sécurité quand une app non vérifiée tente de s’ouvrir. VS Code rappelle de ne faire confiance qu’aux dépôts connus. Git sert de filet de sécurité. OpenAI rappelle de surveiller les usages agentiques et de cadrer les permissions, tandis que Codex documente aussi les risques liés à l’accès Internet des agents, notamment l’injection de prompt et l’exfiltration de données. 

Situation	Réflexe recommandé
Réponse IA confuse	Demander une reformulation plus simple, plus courte, plus concrète
Erreur terminal	Coller l’erreur telle quelle dans ChatGPT et demander traduction + prochaine action unique
Peur de casser le projet	Faire un commit avant toute modification importante
Changement de code trop large	Réduire la demande à un seul objectif et peu de fichiers
App bloquée par macOS	Vérifier d’abord la source officielle, puis seulement envisager “Ouvrir quand même”
Codex trop autonome	Exiger périmètre, résumé des changements et test de validation
Trop de jargon	Revenir au prompt maître et imposer un mode débutante
Blocage psychologique	Ramener la séance à 10 minutes et un seul micro-résultat

L’évaluation finale devrait porter sur des tâches réelles et non sur du vocabulaire récité. Une autonomie crédible, au jour 30, signifie qu’elle sait faire seule les gestes suivants : ouvrir son projet, demander une explication ciblée à ChatGPT, créer ou modifier une section du site, faire un commit, relire un diff simple, publier une mise à jour, puis démarrer une petite automatisation documentée pour une tâche récurrente.

Open questions / limitations. Trois points restent volontairement non verrouillés, parce qu’ils dépendent de votre contexte exact et peuvent évoluer rapidement. D’abord, la formule ChatGPT disponible, car l’accès et les limites de Codex varient selon l’offre et changent dans le temps. Ensuite, la configuration précise du Mac, car l’app ChatGPT pour macOS n’est pas disponible sur tous les matériels. Enfin, la nature exacte des automatisations créatives prioritaires, qui devra être choisie entre photo, éditorial, classement de fichiers et préparation de contenus. Le playbook proposé est donc solide sans ces informations, mais il pourra être encore meilleur si vous l’adaptez ensuite à ces trois paramètres. 