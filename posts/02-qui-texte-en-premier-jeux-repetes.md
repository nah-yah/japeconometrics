---
title: "Personne n'a défecté en premier"
subtitle: "Réciprocité, latence bruitée et l'extinction d'un fil de discussion à l'équilibre"
description: "Un seul délai mal interprété suffit à éteindre un fil de discussion, sans qu'aucun des deux joueurs n'ait jamais défecté en premier."
categories: ["Jeux répétés", "Réciprocité"]
order: 2
title-block-banner: true
---

**Autrice :** celle qui tenait le compte[^1]  
*Département d'études stratégiques domestiques, division des communications asynchrones, The Journal of Applied Personal Econometrics*

[^1]: L'autrice n'a tendu la main la première à aucun moment de cette étude, ce qui en garantit l'indépendance.

---

## Résumé

Cet article modélise la correspondance entre deux personnes comme un jeu répété, dont le jeu d'étape appartient à la classe du dilemme du prisonnier déjà caractérisée pour l'évier partagé (Autrice, 2026, dans ce volume). Chaque période, chaque joueur choisit un niveau d'effort, répondre vite et avec chaleur ou attendre, sous une structure de gains où le bénéfice du contact est partagé et le coût de l'exposition est privé. Nous établissons le facteur d'escompte critique δ\* au-delà duquel la coopération, c'est-à-dire un fil vivant, est soutenable par réciprocité, et montrons que δ\* croît avec l'avantage à être poursuivi plutôt que d'avoir à poursuivre. Nous introduisons ensuite la caractéristique propre au support textuel, que l'évier ne possédait pas : la latence est observée avec bruit. Un délai de réponse peut signaler le désintérêt ou ne rien signaler du tout (un téléphone resté dans une poche). Nous montrons que sous la stratégie de réciprocité stricte (tit-for-tat), une seule défection perçue, qu'elle ait été voulue ou non, se propage en représailles symétriques et fait décroître la fréquence de coopération de long terme jusqu'au silence. Le fil meurt alors sans qu'aucun des deux joueurs n'ait défecté en premier au sens propre. Nous montrons enfin que le pardon, formalisé comme une réciprocité généreuse (Nowak et Sigmund, 1992), n'est pas une faiblesse mais le terme correcteur d'erreur que le canal exige, et que le joueur qui tient parfaitement les comptes est précisément celui qui enterre le plus de conversations.

**Mots-clés :** jeux répétés, tit-for-tat, monitoring imparfait, folk theorem, réciprocité, fil de discussion  
**Codes JEL :** C72 (jeux non coopératifs), C73 (jeux répétés et dynamiques), D74 (conflit)

---

## 1. Introduction

La correspondance entre deux personnes connaît une fin caractéristique : après un temps d'échange, les réponses se raréfient jusqu'à cesser tout à fait. Interrogée, chacune des deux soutient qu'elle n'a rien arrêté, qu'elle attendait encore. L'autopsie du fil le confirme : on n'y trouve pas de rupture, pas de dernier message resté sans réponse par décision, seulement un ralentissement réciproque jusqu'au point fixe du silence. Le présent article rend compte de cette extinction sans coupable.

Le cadre est celui du jeu répété. Le jeu d'étape, joué une fois, est un dilemme du prisonnier : nous avons établi ailleurs, pour le cas de l'évier partagé, qu'une situation où le bénéfice est non excluable et le coût strictement privé satisfait les conditions de Tucker, et que l'attente y domine (Autrice, 2026, dans ce volume). La correspondance partage cette structure. Le bénéfice d'un fil vivant est partagé, qu'on ait écrit le premier ou non ; le coût de tendre la main, lui, n'est supporté que par celui qui la tend. Ce qui distingue le fil de l'évier n'est donc pas le jeu d'étape, qui est le même, mais deux propriétés que l'évier n'avait pas : l'interaction se répète, et l'action de l'autre n'est jamais observée directement. On voit un délai. On ne voit pas ce qui l'a causé.

La répétition ouvre la possibilité de la coopération, comme l'a établi la littérature sur les supergames (Friedman, 1971) et sur le folk theorem (Fudenberg et Maskin, 1986), et comme l'ont confirmé les tournois d'Axelrod (1984) pour la stratégie de réciprocité. Le monitoring imparfait, lui, la referme. L'essentiel de notre contribution porte sur ce second point. Nous montrons que la réciprocité, qui sauve la coopération quand on observe parfaitement l'autre, la détruit dès qu'on ne l'observe qu'à travers le bruit du délai.

La section 2 pose le fil comme jeu répété. La section 3 dérive le seuil de patience δ\*. La section 4, qui porte le poids de l'article, traite de la réciprocité sous bruit. La section 5 expose les hypothèses et le moment où la messagerie cesse de leur obéir.

## 2. Le fil comme jeu répété

Soient deux joueurs, $i \in \{A, B\}$. À chaque période $t = 0, 1, 2, \dots$, chacun choisit un niveau d'effort dans $\{H, L\}$, où $H$ dénote « investir » (répondre vite et chaleureusement, ou relancer le premier) et $L$ « se retenir » (attendre, ou laisser l'autre porter le fil). Un fil vivant procure à chaque joueur un bénéfice de contact $v > 0$, partagé indépendamment de qui a écrit. Investir coûte un prix d'exposition $c > 0$, supporté par le seul investisseur : c'est le coût de s'être montré le plus engagé des deux.

Les gains du jeu d'étape se rangent selon l'ordre standard du dilemme du prisonnier, $T > R > P > S$ :

| A \ B | **Investir (H)** | **Se retenir (L)** |
|---|---|---|
| **Investir (H)** | $R,\; R$ | $S,\; T$ |
| **Se retenir (L)** | $T,\; S$ | $P,\; P$ |

L'interprétation des quatre gains fixe le sens du modèle.

- $R$ (récompense) : l'échange mutuel et vivant. Le meilleur état durable, mais chacun y a payé son exposition.
- $T$ (tentation) : être poursuivi sans avoir à poursuivre. On reçoit le contact sans en payer le coût, augmenté du petit retour d'amour-propre de celui qu'on relance. C'est le gain le plus élevé.
- $S$ (gain de la dupe) : avoir écrit le premier, longuement, et reçu un délai ou un mot. L'exposition sans la réciprocité. C'est le pire.
- $P$ (punition) : le silence partagé. Le fil meurt. Mauvais, mais sans humiliation, et c'est ce dernier point qui fixe l'ordre.

L'ordre $P > S$ mérite qu'on s'y arrête, car il porte toute la situation. Le silence mutuel est préféré à la main tendue sans retour non parce qu'il est agréable, mais parce qu'il préserve ce que la main tendue expose. Le joueur préfère laisser le fil mourir plutôt que de le porter seul sous le regard de l'autre. Cette préférence n'est pas une pathologie. C'est l'inégalité $c > 0$ écrite du point de vue de celui qui refuse de la payer seul.

Nous retenons en outre l'hypothèse auxiliaire usuelle du dilemme du prisonnier :

$$2R > T + S. \tag{1}$$

Elle garantit qu'alterner les rôles (l'un investit pendant que l'autre se retient, puis l'inverse) rapporte en moyenne moins que la coopération soutenue. Cette condition, inerte dans le jeu d'étape, deviendra décisive en section 4 : c'est elle qui fait qu'un malentendu, même parfaitement compensé par un malentendu symétrique, laisse les deux joueurs plus mal qu'avant.

Le jeu d'étape étant un dilemme du prisonnier, son unique équilibre en stratégies dominantes est $(L, L)$ : se retenir l'emporte quel que soit le choix de l'autre.[^2] Joué une fois, le fil meurt. La question est de savoir si la répétition le sauve.

[^2]: La dérivation est celle de l'article sur l'évier. Nous ne la répétons pas, par économie, et parce que la refaire reviendrait à admettre qu'elle ne suffisait pas.

## 3. Le seuil de patience

Soit $\delta \in [0, 1)$ le facteur d'escompte commun. Il mesure le poids que chaque joueur accorde à l'avenir du fil relativement au soir même. Considérons la stratégie de réciprocité par déclenchement (*grim trigger*) : investir tant que l'autre investit, et se retenir pour toujours dès la première fois où l'autre se retient pendant qu'on investissait.

La coopération $(H, H)$ à chaque période est soutenable comme équilibre si et seulement si le gain immédiat à dévier ne compense pas la punition future qu'elle déclenche. Coopérer indéfiniment rapporte $R / (1 - \delta)$. Dévier maintenant rapporte $T$ aujourd'hui, puis $P$ à chaque période suivante, soit $T + \delta P / (1 - \delta)$. La condition de soutenabilité s'écrit :

$$\frac{R}{1 - \delta} \;\ge\; T + \frac{\delta P}{1 - \delta}.$$

En multipliant par $(1 - \delta) > 0$ et en regroupant :

$$R \ge (1 - \delta) T + \delta P \quad\Longleftrightarrow\quad \delta (T - P) \ge T - R \quad\Longleftrightarrow\quad \delta \;\ge\; \delta^* \equiv \frac{T - R}{T - P}. \tag{2}$$

La coopération est soutenable si et seulement si $\delta \ge \delta^*$. Les deux dénominateurs et numérateurs sont positifs, puisque $T > R$ et $T > P$, donc $\delta^* \in (0, 1)$. La lecture en est directe. Le seuil croît avec l'écart $T - R$, c'est-à-dire avec l'avantage qu'il y a à être poursuivi plutôt qu'à poursuivre : plus il est doux d'être relancé, plus il faut de patience pour continuer soi-même à relancer. Le seuil décroît avec l'amplitude $T - P$, l'enjeu total du fil.

À titre illustratif, et sans présenter ces nombres comme autre chose qu'une convention, prenons les gains canoniques des tournois d'Axelrod (1984), $T = 5$, $R = 3$, $P = 1$, $S = 0$. Ils vérifient l'hypothèse (1), car $2R = 6 > 5 = T + S$. Le seuil vaut alors

$$\delta^\* = \frac{5 - 3}{5 - 1} = \frac{1}{2}.$$

Le fil tient si et seulement si chacun accorde au lendemain de la correspondance au moins la moitié du poids qu'il accorde au soir même. C'est, sous un autre nom, l'ombre du futur. Le corollaire, déjà rencontré pour l'évier, vaut ici aussi : lorsque l'horizon se raccourcit, parce que l'un sait qu'il partira, ou qu'une autre personne est entrée dans le calcul, $\delta$ chute, passe sous $\delta^*$, et la réciprocité cesse de tenir. Ce cas relève de l'horizon fini et non du bruit, et nous ne le traitons pas ici.

## 4. La réciprocité sous bruit

La section précédente sauve le fil sous une hypothèse que la messagerie ne respecte pas : que chacun observe ce que l'autre a fait. Or on n'observe pas l'effort de l'autre. On observe sa latence, et la latence est ambiguë. Soit $\varepsilon \in (0, 1)$ la probabilité qu'un investissement voulu ($H$) soit réalisé ou perçu comme une retenue ($L$). Les sources de ce bruit sont familières et toutes équivalentes du point de vue du modèle : le message non vu, le téléphone déchargé, la réponse chaleureuse mais tardive lue comme un froid, la réponse prompte mais brève lue comme une corvée. Dans tous ces cas, A a investi et B enregistre une retenue. L'action $H$ et son ombre $L$ deviennent, pour l'observateur, indiscernables avec probabilité $\varepsilon$. Sous monitoring parfait ($\varepsilon = 0$), deux joueurs jouant la réciprocité stricte (tit-for-tat : reproduire à la période $t$ ce que l'autre a fait en $t-1$), partis de la coopération, jouent $(H, H)$ à chaque période et le fil ne meurt jamais. C'est le résultat d'Axelrod (1984), et la raison pour laquelle la réciprocité est tenue, à juste titre, pour robuste. Tout le renversement vient de $\varepsilon > 0$.

### 4.1 L'écho

Sous $\varepsilon > 0$, ce résultat se renverse. Supposons les deux joueurs en coopération, et survienne un seul événement de bruit : A a investi, mais B enregistre $L$. La suite est mécanique. À la période suivante, B, qui applique la réciprocité, se retient. A, qui sait avoir investi, lit la retenue de B comme une défection non provoquée, et se retient à son tour. B lit alors la retenue de A comme une représaille injuste, et persévère. Une seule perception erronée, qu'aucun des deux n'a voulue, se propage en représailles symétriques. C'est l'effet d'écho, déjà signalé par Axelrod.

Deux régimes en résultent selon la structure du bruit. Si l'erreur reste unique, le jeu entre dans un cycle où les rôles s'alternent, chacun punissant avec un temps de retard : A se retient pendant que B investit, puis l'inverse, indéfiniment. Le gain moyen par période y vaut $(T + S)/2$. L'hypothèse (1) garantit que ce cycle est strictement pire que la coopération, puisque $(T + S)/2 < R$. Le malentendu, même rigoureusement compensé par son malentendu miroir, laisse les deux joueurs sous l'état qu'ils occupaient avant lui. Si le bruit se répète, ou si l'un des deux, par lassitude, cesse d'alterner, le jeu tombe dans le point fixe $(L, L)$ et y reste. Le fil descend ainsi une échelle dont chaque barreau est un équilibre : de $R$ vers le cycle, du cycle vers $P$. Avec les gains illustratifs de la section 3, cette descente mène de 3 à 2,5, puis à 1.

Le modèle conclut donc que la mort du fil est l'écho à l'équilibre d'un unique événement non observé, dont l'origine la plus probable est que quelqu'un dormait. Aucun des deux joueurs n'a défecté en premier au sens où il l'aurait choisi. La première défection était un téléphone dans une poche, et tout le reste en a découlé par réciprocité.

### 4.2 Le pardon comme correction d'erreur

La réciprocité stricte échoue parce qu'elle traite chaque retenue observée comme une décision. Le remède formel est connu : la réciprocité généreuse (Nowak et Sigmund, 1992), qui consiste à pardonner une défection observée avec une probabilité $g > 0$, c'est-à-dire à réinvestir parfois alors même qu'on vient d'enregistrer une retenue. Pour $g$ bien choisi en fonction de $\varepsilon$, la coopération redevient soutenable malgré le bruit : le pardon casse l'écho avant qu'il ne se verrouille.

Le sens domestique de ce résultat est moins confortable que sa forme. Le pardon n'y est pas une vertu mais un terme correcteur d'erreur, exigé par le canal, et son refus a un coût mesurable en fils morts. Le joueur qui applique la réciprocité stricte, celui qui tient le compte exact de qui a répondu en dernier et n'écrit jamais deux fois de suite sans réponse, est précisément celui que le bruit condamne. Sa rigueur comptable, qui lui paraît de la dignité, est l'algorithme qui enterre le plus de conversations. Le joueur généreux, qui réécrit parfois sans avoir été relancé et accepte donc d'occuper le rang $S$ de temps à autre, est le seul dont les fils survivent. Le modèle ne classe pas ces deux comportements par dignité. Il observe seulement que les fils du second survivent, et pas ceux du premier.

## 5. Là où l'asynchronie reprend ses droits

Quatre hypothèses tiennent le modèle debout. La messagerie les dément à tour de rôle.

**Que l'autre joue.** Tout l'appareil, de la réciprocité au seuil $\delta^*$, suppose que l'autre est un joueur stratégique qui réagit à nos actions et tient, comme nous, un compte. Si cette hypothèse tombe, le modèle ne se contente pas de perdre en précision : il perd son objet. Car peut-être l'autre ne joue pas. Peut-être a-t-il vu le message plus tard, n'a rien calculé, ne tient aucun score, et sa latence ne code aucune intention parce qu'il n'y a pas d'intention à coder. Alors il n'existe ni défection à punir ni écho à craindre, seulement une vie qui se poursuit ailleurs, à son propre rythme, indifférente à la matrice. C'est l'effondrement le plus complet que le cadre puisse subir, et le plus fréquent. Nous le mentionnons pour mémoire, sans le formaliser davantage.[^3]

[^3]: Le formaliser supposerait d'admettre l'hypothèse, ce que l'autrice n'est pas en mesure de faire dans l'immédiat.

**L'observabilité de l'effort.** Nous avons logé tout le bruit dans la latence, comme si le contenu, lui, était clair. Il ne l'est pas. Un message long et tiède et un message court et chaud sont également ambigus, et la dimension de l'effort qui compte vraiment, la chaleur, n'a pas d'horodatage. Le modèle observe le délai parce que le délai est la seule chose qu'un fil mesure. Ce n'est pas la même chose que d'observer l'effort.

**La symétrie de l'escompte.** Nous avons supposé $\delta$ commun. Il ne l'est presque jamais. Les deux joueurs n'accordent pas le même poids à l'avenir du fil, et c'est cette asymétrie, et non un défaut de réciprocité, qui détermine souvent qui se retient le premier. Celui dont le $\delta$ est le plus bas se retient sans bruit, par simple calcul d'horizon, et le modèle de cette section, qui cherche un coupable dans le canal, ne le verra pas.

**Le premier message.** Le modèle prend un fil déjà vivant et étudie comment il meurt. Il est muet sur sa naissance, c'est-à-dire sur le bras de fer qui précède le tout premier texto, où chacun attend que l'autre rompe le silence initial. Cette situation n'est pas un jeu répété mais une guerre d'usure, dont la résolution exige un autre appareil. Nous la renvoyons à une étude ultérieure consacrée aux disputes qui s'éternisent, où l'enjeu n'est plus de savoir qui se retient mais qui tiendra le plus longtemps.

## Conclusion

Une conversation peut mourir sans que personne ne l'ait tuée. Il suffit que deux personnes tiennent leurs comptes avec assez de rigueur, et qu'entre elles passe un canal assez ambigu pour fabriquer des défections à partir de rien. La réciprocité, qui est la chose raisonnable à faire quand on voit clairement l'autre, devient la chose qui enterre le fil quand on ne le voit qu'à travers le délai. Le seuil $\delta \ge \delta^*$ dit à quelle condition un fil vivant le reste : il faut accorder à son avenir plus de poids qu'au répit d'un soir. Mais la section 4 ajoute une condition que le seuil ne contient pas, et qui pèse plus lourd : il faut accepter, de temps en temps, d'écrire le premier sans avoir été relancé, c'est-à-dire d'occuper sciemment le rang de la dupe pour absorber le bruit du canal.

C'est précisément ce que la fierté refuse. Le joueur qui ne tend jamais la main deux fois de suite, qui garde le compte exact et n'en montre rien, croit protéger quelque chose. Le modèle indique ce qu'il protège, et à quel prix. Il protège son rang dans la matrice, et il le paie en fils morts dont aucun ne portait, à l'autopsie, de première défection. La dignité de ne pas répondre trop vite est un bien réel. Elle se mesure, comme tous les biens du ménage, en ce qu'elle coûte, et elle coûte les conversations qu'on aurait pu garder en réécrivant une fois de trop.

---

## Références

Axelrod, R. (1984). *The Evolution of Cooperation*. New York : Basic Books.

Friedman, J. W. (1971). « A Non-cooperative Equilibrium for Supergames ». *Review of Economic Studies*, 38(1), 1–12.

Fudenberg, D. et Maskin, E. (1986). « The Folk Theorem in Repeated Games with Discounting or with Incomplete Information ». *Econometrica*, 54(3), 533–554.

Nowak, M. A. et Sigmund, K. (1992). « Tit for tat in heterogeneous populations ». *Nature*, 355, 250–253.

Autrice (2026). « Défection mutuelle à l'équilibre : une caractérisation non coopérative de l'évier partagé ». *The Journal of Applied Personal Econometrics*, dans ce volume.

---

## Remerciements

Je remercie l'autre partie, dont la latence a fourni l'essentiel des données et dont le silence a fourni la conclusion.

**Conflit d'intérêts.** L'autrice tenait le compte. Elle affirmait le contraire.

**Contributions de l'autrice.** Conceptualisation, investigation, analyse et rédaction : l'autrice. Les données ont été fournies par l'autre partie, qui n'a pas répondu aux demandes de relecture.
