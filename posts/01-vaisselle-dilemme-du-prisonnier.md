---
title: "Défection mutuelle à l'équilibre"
subtitle: "Une caractérisation non coopérative de l'évier partagé"
description: "L'évier déborde par rationalité : un dilemme du prisonnier ordinaire, avec son seuil de patience δ*."
categories: ["Dilemme du prisonnier", "Biens publics", "Passager clandestin", "Coopération"]
order: 1
title-block-banner: true
include-in-header:
  text: |
    <style>
      .quarto-title-banner { background: linear-gradient(135deg, #1d2b4f 0%, #3c3163 55%, #8a4b6b 100%); }
    </style>
---

**Autrice :** celle qui a lavé[^1]  
*Département d'études stratégiques domestiques, The Journal of Applied Personal Econometrics*
 
[^1]: L'unique autrice a financé cette recherche en nature, c'est-à-dire en faisant la vaisselle.
 
---
 
## Résumé
 
Partager un évier entre deux colocataires est un jeu non coopératif à information complète, dont la structure de gains est celle du dilemme du prisonnier : laver l'évier produit un bénéfice non excluable (un évier propre profite aux deux occupants indépendamment de l'identité de celui qui a lavé), tandis que l'effort reste, lui, parfaitement excluable. Il en résulte que « Attendre » constitue une stratégie strictement dominante pour chaque joueur, et que l'unique équilibre de Nash en stratégies pures, (Attendre, Attendre), est Pareto-dominé par le profil coopératif (Laver, Laver). Autrement dit, l'évier déborde non par paresse mais par rationalité. Nous établissons le seuil de patience δ\* au-delà duquel la coopération devient soutenable dans la version répétée du jeu, et discutons des conditions (réalistes) dans lesquelles ce seuil n'est jamais atteint. Une recommandation de politique domestique est proposée : l'introduction d'un dispositif d'engagement (un tableau de tâches), dont nous notons toutefois qu'il est lui-même un bien public, et donc sujet au problème qu'il prétend résoudre.
 
**Mots-clés :** dilemme du prisonnier, biens publics, passager clandestin, coopération, évier  
**Codes JEL :** C72 (jeux non coopératifs), D10 (comportement du ménage), D74 (conflit)
 
---
 
## 1. Introduction
 
L'évier partagé occupe une place curieusement modeste dans la littérature économique, alors même qu'il réunit, sur une surface inférieure à un demi-mètre carré, l'essentiel des pathologies que cette littérature s'emploie par ailleurs à étudier : un bien public, un coût privé, une information complète, et deux agents qui s'observent quotidiennement sans jamais coopérer. Le présent article entreprend de combler ce vide.
 
La situation est familière. Deux personnes partagent une cuisine. La vaisselle s'accumule. Chacune préférerait un évier propre à un évier sale ; chacune préférerait, plus encore, que ce soit l'autre qui le rende propre. Le résultat observé (un évier durablement saturé, ponctué d'épisodes de capitulation unilatérale) est généralement attribué à un défaut de caractère. Nous soutenons qu'il s'agit, au contraire, d'un comportement d'équilibre. L'évier ne déborde pas malgré la rationalité des occupants ; il déborde à cause d'elle.
 
Nos contributions sont au nombre de trois. Premièrement, nous formalisons le problème comme un jeu 2×2 et montrons qu'il appartient à la classe du dilemme du prisonnier (Tucker, *circa* 1950 ; Nash, 1951). Deuxièmement, nous dérivons l'équilibre en stratégies dominantes et établissons sa sous-optimalité parétienne. Troisièmement, nous étendons l'analyse au jeu répété et caractérisons le facteur d'escompte critique δ\* en deçà duquel la défection demeure l'unique issue, un résultat qui prépare le terrain pour une étude ultérieure du même ménage observé sur une plus longue durée.[^2]
 
[^2]: Cette étude ultérieure est déjà en cours. Elle ne se passe pas bien.
 
La section 2 situe le problème dans la littérature. La section 3 pose le jeu. La section 4 le résout. La section 5 examine les hypothèses, et le moment précis où la cuisine cesse de leur obéir.
 
## 2. Littérature
 
Le cadre que nous mobilisons remonte à la formalisation du dilemme du prisonnier attribuée à Tucker et à la caractérisation de l'équilibre non coopératif par Nash (1950, 1951). La structure de bien public de l'évier (un évier propre bénéficie à tous, qu'on ait lavé ou non) relève directement de Samuelson (1954) : la propreté est non rivale (votre jouissance d'un évier vide ne diminue pas la mienne) et non excluable (je ne peux pas vous empêcher d'en profiter). Hardin (1968) a décrit la dégradation prévisible des ressources soumises à un tel régime ; nous nous bornons à observer qu'une cuisine est un communal de très petite taille.
 
La question de savoir si la répétition de l'interaction restaure la coopération a été tranchée, pour l'essentiel, par Axelrod (1984), dont les tournois ont établi la robustesse des stratégies réciproques. Nous y revenons en section 4.3. La littérature antérieure pertinente inclut également Mère (1994, communication personnelle répétée), dont les contributions, quoique non publiées, furent insistantes.
 
## 3. Le jeu
 
Soient deux joueurs, $i \in \{A, B\}$, qui partagent un évier. Chacun choisit simultanément une action dans l'ensemble $\{L, W\}$, où $L$ dénote « Laver » et $W$ « Attendre » (*wait*). Le jeu est à information complète : les préférences décrites ci-dessous sont connaissance commune.
 
Un évier propre procure à chaque joueur un bénéfice $b > 0$, indépendamment de l'identité de celui qui l'a rendu propre : c'est la propriété de non-exclusion. Laver impose un coût d'effort $\gamma > 0$ à qui lave. Lorsque les deux lavent, l'effort se partage : chacun supporte $\gamma/2$. Lorsque personne ne lave, l'évier reste sale, le bénéfice $b$ n'est pas réalisé, et chaque joueur subit en outre une désutilité $d > 0$ liée à la contemplation prolongée de l'évier.
 
Les gains se résument dans la matrice suivante (gains de A, gains de B) :
 
| A / B | **Laver (L)** | **Attendre (W)** |
|---|---|---|
| **Laver (L)** | $\;b - \tfrac{\gamma}{2},\; b - \tfrac{\gamma}{2}\;$ | $\;b - \gamma,\; b\;$ |
| **Attendre (W)** | $\;b,\; b - \gamma\;$ | $\;-d,\; -d\;$ |
 
Nous posons l'hypothèse de paramètres suivante, qui correspond au cas empiriquement saillant :
 
$$\gamma > 0, \quad b > \tfrac{\gamma}{2}, \quad d > 0. \tag{1}$$
 
La condition $b > \gamma/2$ garantit que le profil coopératif (L, L) procure un gain net positif : un évier propre vaut la moitié d'un effort. Si cette condition échoue (c'est-à-dire si l'on déteste laver plus qu'on n'aime la propreté), le ménage relève d'une analyse différente, que nous n'abordons pas ici.[^3]
 
[^3]: On la rencontre néanmoins. Elle se reconnaît à l'odeur.
 
## 4. Résolution
 
### 4.1 Stratégie dominante
 
Considérons le choix de A, action par action, selon ce que peut faire B.
 
*Si B lave (L).* A compare son gain à Laver, $b - \gamma/2$, à son gain à Attendre, $b$. Puisque $\gamma/2 > 0$, on a $b > b - \gamma/2$. **Attendre l'emporte.**
 
*Si B attend (W).* A compare son gain à Laver, $b - \gamma$, à son gain à Attendre, $-d$. Sous l'hypothèse (1), Attendre l'emporte si et seulement si $-d > b - \gamma$, soit $\gamma > b + d$. Nous distinguons deux régimes :
 
- **Régime de défection franche** ($\gamma > b + d$) : Attendre l'emporte quoi que fasse B. La stratégie est strictement dominante.
- **Régime de capitulation** ($\gamma < b + d$) : si B attend, A préfère laver plutôt que subir l'évier saturé. La dominance stricte est rompue.
Le régime empiriquement dominant (celui où l'évier finit *toujours* par être lavé, mais tard, et par la même personne) est le régime de capitulation. Nous l'examinons en 4.2. Le régime de défection franche, plus rare, correspond aux ménages qui achètent de la vaisselle jetable.
 
### 4.2 Équilibre de Nash
 
Dans le régime de capitulation, la dominance stricte ne tranche pas, mais le jeu conserve un unique équilibre de Nash en stratégies pures. Vérifions les profils.
 
Le profil (W, W) n'est *pas* un équilibre : face à W, chaque joueur préfère dévier vers L (puisque $b - \gamma > -d$). Les profils (L, L) ne sont pas non plus des équilibres : face à L, chacun préfère dévier vers W (puisque $b > b - \gamma/2$). Restent les profils asymétriques. Dans (L, W), A lave et B attend : A obtient $b - \gamma$, et ne peut améliorer son sort en déviant (dévier le ramènerait à $-d < b - \gamma$) ; B obtient $b$, son meilleur gain possible, et ne dévie pas. **(L, W) est un équilibre de Nash.** Par symétrie, (W, L) l'est aussi.
 
Le jeu possède donc deux équilibres asymétriques, dans chacun desquels une seule personne lave et l'autre profite. L'identité du laveur n'est pas déterminée par le modèle. Elle est déterminée, dans la pratique, par celui des deux qui a le seuil de tolérance $d$ le plus bas, c'est-à-dire par la personne que l'évier dérange en premier. Le modèle prédit ainsi un résultat que nos données autobiographiques confirment sans réserve : ce n'est jamais la même personne qui craque, sauf que si.
 
### 4.3 Le jeu répété et le seuil de patience
 
L'évier n'est pas lavé une fois. Il est lavé, ou non, chaque jour, indéfiniment, par les mêmes deux personnes. Cette répétition change-t-elle l'analyse ?
 
Soit $\delta \in [0, 1)$ le facteur d'escompte commun, qui mesure le poids accordé au bien-être futur du ménage. Considérons la stratégie de réciprocité (*grim trigger*) : « je lave tant que tu as lavé ; à la première fois où tu attends pendant que je lave, j'attends pour toujours ». La coopération (L, L) à chaque période est soutenable comme équilibre si et seulement si le gain de la défection unique ne compense pas la punition future qu'elle déclenche. Le gain immédiat à dévier est $b - (b - \gamma/2) = \gamma/2$ ; la perte future, actualisée, est la différence entre le flux coopératif et le flux de défection mutuelle. La condition de soutenabilité s'écrit :
 
$$\frac{\gamma/2}{1 - \delta} \;\le\; \frac{(b - \gamma/2) - (-d)}{1-\delta} \cdot \delta \quad\Longleftrightarrow\quad \delta \;\ge\; \delta^\* \equiv \frac{\gamma/2}{\,b + d - \gamma/2\,}. \tag{2}$$
 
La coopération est soutenable si et seulement si $\delta \ge \delta^\*$. Le seuil $\delta^\*$ croît avec le coût de l'effort $\gamma$ et décroît avec le bénéfice de la propreté $b$ et la désutilité de l'évier sale $d$. La lecture est directe : la vaisselle partagée tient lorsque les deux personnes accordent assez de poids à l'avenir de leur cohabitation. C'est ce que l'on nomme, dans la littérature, *l'ombre du futur*.
 
Le corollaire est moins réconfortant. Lorsque l'horizon se raccourcit (l'un des deux s'apprête à déménager, ou la relation se dégrade), δ chute, finit par passer sous δ\*, et la coopération s'effondre. Le modèle prédit que l'évier se remplit dans les semaines qui précèdent une séparation. Nous ne commentons pas ce résultat.
 
## 5. Où le modèle casse
 
Le modèle repose sur trois hypothèses qu'il convient d'exposer, car la cuisine les viole régulièrement.
 
**Simultanéité.** Nous avons supposé les actions choisies simultanément. En réalité, l'évier est un jeu séquentiel à information imparfaite : on observe l'état de l'évier, non l'intention de l'autre. Une assiette laissée le matin peut être un acte de défection ou une promesse de retour. Le modèle ne distingue pas les deux. Les occupants non plus, ce qui est l'origine de la plupart des conflits.
 
**Symétrie des gains.** Nous avons supposé $b$, $\gamma$ et $d$ identiques entre joueurs. C'est faux. La désutilité $d$ de l'évier sale varie considérablement d'une personne à l'autre, et c'est précisément cette asymétrie, et non un quelconque sens des responsabilités, qui détermine qui lave. La personne au $d$ élevé n'est pas plus vertueuse. Elle est simplement moins capable de ne pas voir.
 
**Connaissance commune des préférences.** Nous avons supposé que chacun connaît les gains de l'autre. Mais une part substantielle du conflit domestique consiste, justement, à contester l'évaluation que l'autre fait de $d$ (« ça ne te dérange donc pas ? »), c'est-à-dire à renégocier la matrice elle-même. Le modèle prend la matrice comme donnée. Le ménage la prend comme sujet de dispute.
 
Enfin, le modèle est muet sur le cas, théoriquement marginal mais empiriquement décisif, où l'un des deux lave *en silence et de façon ostentatoire*, ce qui transforme un acte coopératif en signal, voire en représailles. Cette configuration relève de la signalisation coûteuse, et nous la renvoyons à un article ultérieur.
 
## 6. Conclusion
 
L'évier déborde parce que chacun, de son propre point de vue, agit raisonnablement. C'est le scandale tranquille du dilemme du prisonnier : deux personnes parfaitement raisonnables fabriquent ensemble un résultat qu'aucune des deux ne veut. La propreté est un bien que l'on partage, l'effort un coût que l'on porte seul, et tant que cette asymétrie tient, attendre reste la réponse individuellement juste. Une seule chose retient la coopération de s'effondrer, la condition $\delta \ge \delta^*$ : il faut que les deux accordent à l'avenir de leur cohabitation plus de poids qu'au répit d'un soir. Sous ce seuil, la vaisselle gagne, et elle gagne souvent.
 
En matière de politique domestique, la théorie suggère un dispositif d'engagement : un tableau de répartition des tâches, qui attache un coût de réputation à la défection et transforme ainsi le jeu. Nous notons toutefois, sans pouvoir le résoudre, que la tenue à jour d'un tel tableau est elle-même un bien public non excluable, et donc soumise exactement au dilemme qu'il est censé dissoudre. Le tableau, dans nos observations, n'a jamais été rempli au-delà du jeudi de la première semaine.
 
---
 
## Références
 
Axelrod, R. (1984). *The Evolution of Cooperation*. New York : Basic Books.
 
Hardin, G. (1968). « The Tragedy of the Commons ». *Science*, 162(3859), 1243–1248.
 
Nash, J. F. (1950). « Equilibrium Points in n-Person Games ». *PNAS*, 36(1), 48–49.
 
Nash, J. F. (1951). « Non-Cooperative Games ». *Annals of Mathematics*, 54(2), 286–295.
 
Samuelson, P. A. (1954). « The Pure Theory of Public Expenditure ». *Review of Economics and Statistics*, 36(4), 387–389.
 
Mère (1994). Communication personnelle. Récurrente.
 
---
 
## Remerciements
 
Je remercie l'autre occupant, sans qui ce problème n'existerait pas, et grâce à qui il existe. Aucun financement extérieur n'a été reçu ; le coût $\gamma$ a été supporté intégralement par l'autrice, comme le prévoit l'équilibre (L, W). L'autrice déclare un conflit d'intérêts : elle voulait que le modèle donne raison à une seule des deux parties, et constate avec une certaine froideur que c'est le cas.