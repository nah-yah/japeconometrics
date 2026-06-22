---
title: "Moi, ça m'est égal"
subtitle: "Le choix collectif d'un restaurant comme dilemme du volontaire, avec dérivation de l'effet de la taille du groupe sur la probabilité qu'une décision soit prise"
description: "Choisir un restaurant en groupe est un dilemme du volontaire : nul ne veut être celui qui décide, et le groupe décide d'autant moins qu'il est nombreux."
categories: ["Dilemme du volontaire", "Biens publics", "Diffusion de la responsabilité"]
order: 3
title-block-banner: true
include-in-header:
  text: |
    <style>
      .quarto-title-banner { background: linear-gradient(135deg, #6b3a2f 0%, #b85c38 55%, #e8a33d 100%); }
    </style>
---

**Autrice :** celle à qui c'était égal[^1]  
*Département d'études stratégiques domestiques, section de la décision collective, The Journal of Applied Personal Econometrics*

[^1]: L'autrice certifie n'avoir émis aucune préférence durant la collecte des données, ce qu'elle présente comme un gage de neutralité.

---

## Résumé

Le choix collectif d'un lieu où manger échoue plus souvent qu'on ne l'admet, et d'autant plus que les convives sont nombreux. Cet article en rend compte au moyen du dilemme du volontaire (Diekmann, 1985). Le groupe profite qu'une décision soit prise, mais celui qui la prend devient celui qui a choisi, et porte seul le reproche si l'on a mal mangé. Personne ne veut ce rôle, et l'abstention se déguise en absence de préférence : « moi, ça m'est égal ». Nous résolvons le jeu. Outre les $n$ équilibres où une seule personne se dévoue, il en existe un où chacun s'en remet au hasard et se dévoue avec probabilité $p^* = 1 - (K/U)^{1/(n-1)}$. Cette probabilité décroît avec la taille du groupe, et la probabilité que personne ne tranche, $(K/U)^{n/(n-1)}$, croît avec $n$ vers la limite $K/U$. Plus on est nombreux à choisir, moins on choisit : le couple connaît la chose à deux, la tablée de huit la subit. C'est, sous un autre nom, la diffusion de la responsabilité (Darley et Latané, 1968). Nous montrons enfin que se parler n'y change rien, puisque décider qui décidera est encore un dilemme du volontaire, en général plus long que celui qu'il prétend clore.

**Mots-clés :** dilemme du volontaire, biens publics, diffusion de la responsabilité, équilibre en stratégies mixtes, taille du groupe  
**Codes JEL :** C72 (jeux non coopératifs), H41 (biens publics), D71 (décision collective)

---

## 1. Un résultat, et la scène qui le produit

Un groupe doit choisir où manger, et n'y arrive pas. Chacun renvoie la question à l'autre, « comme tu veux » ou « décide, toi », et elle revient sans réponse jusqu'à ce que l'heure tourne ou qu'un convive excédé tranche pour tout le monde. On met d'ordinaire ce blocage sur le compte de l'indécision ou d'un excès de courtoisie. Nous soutenons qu'il s'agit d'un comportement d'équilibre, et nous en tirons une prédiction que l'intuition refuse : la probabilité qu'un groupe ne s'arrête à aucun restaurant croît avec le nombre de personnes qui en délibèrent. Plus on est à décider, moins on décide.

Le cadre est celui du dilemme du volontaire (Diekmann, 1985). Un bien public y est produit dès qu'au moins une personne accepte d'en payer le coût, et il bénéficie ensuite à tous, qu'ils aient payé ou non. Ici, le bien est qu'une décision existe, et le coût est de la prendre. Celui qui nomme un restaurant rend un service à tout le monde, mais il devient aussi celui qui a choisi : si le repas déçoit, la responsabilité lui revient, sans partage. C'est ce coût, et non un quelconque manque d'avis, que la phrase « moi, ça m'est égal » sert à esquiver.[^2]

[^2]: La phrase « ça m'est égal » est, dans nos données, la plus fréquente et la moins exacte.

La psychologie sociale avait décrit le phénomène avant qu'on le formalise, sous le nom de diffusion de la responsabilité (Darley et Latané, 1968) : plus les témoins d'une urgence sont nombreux, moins chacun se sent tenu d'agir, et l'intervention peut devenir moins probable à mesure que la foule grossit. Le choix d'un restaurant est une urgence de très faible intensité. Sa structure stratégique est la même.

La suite est brève. La section 2 pose le jeu et le résout, équilibres purs puis mixtes, et établit l'effet de la taille du groupe. La section 3 soumet le résultat à deux épreuves. La section 4 expose les hypothèses et le moment où quelqu'un, à table, cesse de leur obéir.

## 2. Le jeu et ses équilibres

Soient $n \ge 2$ joueurs. Chacun choisit, simultanément, entre se dévouer ($V$), c'est-à-dire arrêter le choix et le porter, et s'abstenir ($A$), c'est-à-dire déclarer que cela lui est égal. Si au moins une personne se dévoue, une décision est prise et chaque joueur reçoit le bénéfice $U > 0$ d'un repas décidé. Celui qui s'est dévoué supporte en outre le coût $K > 0$ d'avoir choisi.[^3] Si personne ne se dévoue, aucune décision n'est prise et chaque joueur reçoit un gain normalisé à zéro, qui représente le groupe encore debout sur le trottoir.

[^3]: Ce coût se paie surtout après, au premier silence devant une assiette décevante, quand les regards convergent sans un mot vers celui qui a proposé l'endroit.

Nous posons l'hypothèse :

$$U > K > 0. \tag{1}$$

Elle garantit que se dévouer seul vaut mieux que l'absence de décision ($U - K > 0$) : il est préférable de choisir, même sous le poids d'avoir choisi, que de ne pas manger. Les gains de chaque joueur se résument ainsi :

- se dévouer rapporte $U - K$, quel que soit le choix des autres, puisque la décision est alors acquise ;
- s'abstenir rapporte $U$ si au moins un autre joueur se dévoue, et $0$ si aucun ne le fait.

Le concept de solution est l'équilibre de Nash. Nous en exhibons deux familles.

**Les équilibres en stratégies pures.** Tout profil où exactement une personne se dévoue est un équilibre. Le volontaire, s'il déviait vers l'abstention, ferait tomber la décision et passerait de $U - K$ à $0$, ce que l'hypothèse (1) lui interdit. Chacun des abstentionnistes, lui, reçoit déjà $U$, son meilleur gain possible, et n'a aucune raison de se dévouer à la place de l'autre. Il existe donc $n$ tels équilibres, un par volontaire désigné. Le modèle ne dit pas lequel des convives se dévoue. Comme pour l'évier partagé (Autrice, 2026a), l'identité du volontaire n'est pas fixée par les gains mais par l'asymétrie des seuils : se dévoue celui que l'attente coûte le plus, c'est-à-dire celui qui a faim le premier.

**L'équilibre symétrique en stratégies mixtes.** Quand aucun convive n'est désigné d'avance, et c'est le cas ordinaire, le profil pertinent est celui où chacun se dévoue avec une même probabilité $p$. À l'équilibre, chaque joueur doit être indifférent entre ses deux actions. Se dévouer rapporte $U - K$ avec certitude. S'abstenir rapporte $U$ multiplié par la probabilité qu'au moins un autre se dévoue, soit $U\big[1 - (1-p)^{n-1}\big]$. L'indifférence s'écrit :

$$U - K = U\big[1 - (1-p)^{n-1}\big].$$

En simplifiant, $K = U(1-p)^{n-1}$, d'où $(1-p)^{n-1} = K/U$, et enfin :

$$p^* = 1 - \left(\frac{K}{U}\right)^{\frac{1}{n-1}}. \tag{2}$$

La probabilité qu'un convive donné se dévoue est donc entièrement fixée par le rapport $K/U$ et par le nombre de convives. Sa lecture est l'objet de tout l'article.

**L'effet de la taille du groupe.** Lorsque $n$ croît, l'exposant $1/(n-1)$ tend vers zéro, et comme $K/U \in (0,1)$, le terme $(K/U)^{1/(n-1)}$ tend vers $1$. La probabilité individuelle $p^*$ décroît donc vers zéro : plus le groupe est grand, moins chacun se dévoue. Ce n'est pas encore le résultat. Le résultat porte sur l'issue collective. La probabilité qu'aucun convive ne se dévoue vaut

$$P(\text{aucune décision}) = (1 - p^*)^{n} = \left(\frac{K}{U}\right)^{\frac{n}{n-1}}. \tag{3}$$

L'exposant $n/(n-1)$ décroît de $2$ (à $n = 2$) vers $1$ (quand $n \to \infty$). Une base inférieure à $1$ élevée à un exposant qui diminue donne une valeur qui augmente. La probabilité que le groupe ne décide de rien croît donc avec $n$, et tend vers $K/U$. L'ajout d'un convive n'accélère pas la décision : il la rend moins probable.

À titre illustratif, et en présentant ces nombres pour ce qu'ils sont, une convention et non des données, fixons $U = 1$ et $K = 1/2$, de sorte que $K/U = 1/2$. La formule (2) et la formule (3) donnent alors :

| Convives $n$ | $p^*$ (chacun se dévoue) | $P(\text{aucune décision})$ |
|---|---|---|
| 2 | $0{,}500$ | $0{,}250$ |
| 3 | $0{,}293$ | $0{,}354$ |
| 5 | $0{,}159$ | $0{,}420$ |
| 10 | $0{,}074$ | $0{,}463$ |

Un couple échoue à décider une fois sur quatre. À cinq, le groupe reste sur le trottoir deux fois sur cinq. La valeur limite $K/U = 1/2$ majore cette probabilité : avec ce rapport de coûts, un très grand groupe ne décide pas une fois sur deux. On notera enfin que le dévouement, lorsqu'il survient, peut être redondant : il arrive que deux convives nomment un restaurant en même temps, chacun ayant cru devoir s'y résoudre, et paient alors tous deux le coût $K$ là où un seul aurait suffi.

## 3. Robustesse

Nous soumettons le résultat à deux épreuves, l'une qui met en doute le concept de solution, l'autre qui examine un cas limite.

**La parole change-t-elle l'issue ?** Le jeu suppose des choix simultanés et muets. En pratique, les convives parlent avant de choisir. La communication préalable, ou *cheap talk*, permet en principe au groupe de se coordonner sur l'un des équilibres en stratégies pures, c'est-à-dire de désigner un volontaire et d'échapper ainsi au risque d'inaction de l'équilibre mixte. Mais la désignation ne supprime pas le coût $K$, elle ne fait que décider qui le portera. La question « qui décide ? » a exactement la structure de la question « qui se dévoue ? » : chacun préfère que ce soit un autre. La conversation ne dissout donc pas le dilemme, elle le remonte d'un cran, du choix du restaurant au choix de celui qui choisira le restaurant. On observe d'ailleurs que cette conversation-là dure souvent plus longtemps que celle qu'elle était censée abréger.

**Le cas limite $n = 1$.** La formule (2) n'est pas définie en $n = 1$ : l'exposant y exigerait une division par zéro. Nous traitons donc ce cas directement. Une personne seule qui doit choisir où manger ne joue contre personne : il n'y a ni bien public à produire, ni personne sur qui reporter le coût. Elle décide. Le modèle prédit par conséquent qu'une personne dînant seule n'éprouve aucune paralysie devant le choix d'un restaurant. Cette prédiction est, à notre connaissance, vérifiée sans exception.

## 4. Quand quelqu'un finit par avoir faim

Le modèle repose sur trois hypothèses que la table dément l'une après l'autre.

**La symétrie des coûts.** Nous avons supposé $U$ et $K$ identiques entre convives. Ils ne le sont pas. Le coût de l'attente varie d'une personne à l'autre, et c'est cette variation qui sélectionne le volontaire parmi les équilibres en stratégies pures : se dévoue non pas le plus généreux, mais celui dont la faim, ou l'agacement, franchit son seuil en premier. La personne qui finit par dire « bon, on va là » n'a pas plus le sens du collectif que les autres. Elle a simplement atteint avant eux le point où ne pas décider coûte plus cher que décider.

**L'absence réelle de préférence.** Le jeu prend la déclaration « ça m'est égal » au sérieux, comme si l'indifférence était vraie. Or elle l'est rarement. La plupart des convives ont une préférence et la taisent, précisément pour ne pas avoir à la défendre ni à en répondre. Le modèle ne distingue pas celui qui n'a pas d'avis de celui qui en a un et le retient, parce que les deux jouent $A$. Cette indistinction n'est pas un défaut du modèle. C'est le mécanisme même qu'il décrit : l'abstention rend les deux cas identiques, ce qui est tout l'intérêt, pour qui s'abstient, de s'abstenir.

**Le jeu se répète.** Un groupe d'amis ne choisit pas une fois où manger, il choisit chaque fois qu'il se retrouve. La répétition introduit ce que le jeu à un coup ignore : la mémoire de qui s'est dévoué la dernière fois, et la norme « c'est ton tour ». Comme nous l'avons vu pour la correspondance (Autrice, 2026b), la répétition peut soutenir une coopération que le coup unique exclut, ici sous la forme d'une rotation du volontaire. Le modèle de cet article décrit donc surtout les groupes neufs, ou ceux dont la rotation s'est rompue, ce qui revient parfois au même.

## Conclusion

« Ça m'est égal » n'est pas une amabilité. C'est la formule par laquelle on décline de payer le coût d'avoir choisi tout en gardant le bénéfice qu'un autre choisisse. Elle a la forme de la déférence et la fonction de l'esquive, et sa réussite tient à ce que ces deux faces sont indiscernables : nul ne peut prouver que votre indifférence est feinte, puisqu'une indifférence vraie produit exactement les mêmes mots. Le dilemme du volontaire donne à cette esquive son prix collectif. Tant qu'on est deux, il reste modéré. Mais il se multiplie avec le nombre, car chacun compte un peu plus sur les autres pour vouloir à sa place, et l'inaction devient le résultat le plus probable au moment précis où le groupe est le plus fourni. La politesse de n'avoir aucune préférence est, à table, ce qu'un convive peut faire de plus coûteux pour le groupe, et le groupe le lui rend en ne mangeant pas. Il reste alors à attendre que l'un d'eux ait assez faim pour renoncer à être poli.

---

## Références

Darley, J. M. et Latané, B. (1968). « Bystander Intervention in Emergencies: Diffusion of Responsibility ». *Journal of Personality and Social Psychology*, 8(4), 377–383.

Diekmann, A. (1985). « Volunteer's Dilemma ». *Journal of Conflict Resolution*, 29(4), 605–610.

Autrice (2026a). « Défection mutuelle à l'équilibre : une caractérisation non coopérative de l'évier partagé ». *The Journal of Applied Personal Econometrics*, dans ce volume.

Autrice (2026b). « Personne n'a défecté en premier : réciprocité, latence bruitée et l'extinction d'un fil de discussion à l'équilibre ». *The Journal of Applied Personal Econometrics*, dans ce volume.

---

## Remerciements

Je remercie le groupe, qui n'a, lui non plus, rien décidé.

**Disponibilité des données.** Les délibérations ayant servi d'illustration n'ont abouti à aucun restaurant. Le groupe a fini par manger séparément, ce qui a clos l'observation.

**Conflit d'intérêts.** L'autrice avait une préférence. Elle ne l'a pas formulée.

**Financement.** Aucun. Personne n'a voulu décider qui paierait.
