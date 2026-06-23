---
title: "Avoir le dernier mot"
subtitle: "La dispute prolongée comme guerre d'usure, avec la dissipation intégrale de l'enjeu à l'équilibre"
description: "Tenir bon dans une dispute est une guerre d'usure : à l'équilibre, l'attente consume exactement ce qu'il y avait à gagner, et le dernier mot ne vaut plus rien."
categories: ["Guerre d'usure", "Jeu de temporisation", "Dissipation de rente", "Conflit"]
order: 5
title-block-banner: true
---

**Autrice :** celle qui a eu le dernier mot[^1]  
*Département d'études stratégiques domestiques, section des conflits domestiques prolongés, The Journal of Applied Personal Econometrics*

[^1]: L'autrice a eu le dernier mot dans la dispute ayant servi d'illustration. Elle ne se rappelle plus de quoi il s'agissait.

---

## Résumé

Une dispute qui s'éternise est une guerre d'usure (Maynard Smith, 1974). Deux personnes se disputent un enjeu, avoir raison ou obtenir que l'autre cède, et chacune choisit combien de temps tenir avant de lâcher. Celle qui tient le plus longtemps l'emporte, mais les deux paient, à chaque instant où le conflit dure, un coût qu'aucune concession ne leur rend. Nous montrons d'abord qu'aucun équilibre symétrique en stratégies pures n'existe : si l'une savait quand l'autre cédera, elle tiendrait un instant de plus. Il reste deux types d'équilibres. Dans les équilibres asymétriques, l'une cède d'emblée et l'autre jamais, et le conflit se résout sans coût parce que les rôles sont connus. Dans l'équilibre symétrique en temps continu, chacune cède selon un instant aléatoire de taux constant $\lambda = c/v$, de sorte que la durée de la dispute est sans mémoire : sa probabilité de finir dans la minute qui vient ne dépend pas du temps déjà écoulé. Surtout, le gain espéré de cet équilibre est nul. La guerre consomme en moyenne l'enjeu tout entier, et avoir le dernier mot vaut, en espérance, exactement ce qu'il a coûté, c'est-à-dire rien. Nous montrons enfin que rien dans le modèle ne relie la victoire au fait d'avoir raison, et que l'enjeu lui-même se dégrade à mesure qu'on se le dispute.

**Mots-clés :** guerre d'usure, jeu de temporisation, équilibre en stratégies mixtes, dissipation de rente, conflit, absence de mémoire  
**Codes JEL :** C72 (jeux non coopératifs), C73 (jeux dynamiques), D74 (conflit)

---

## 1. Introduction

Certaines disputes ne se terminent pas, elles s'arrêtent. La différence n'est pas mince. Une dispute qui se termine a été tranchée par un argument ; une dispute qui s'arrête a simplement épuisé l'un des deux, sans que rien soit résolu, souvent sans qu'on se souvienne encore du grief initial. Le présent article traite de la seconde, et la tient pour le résultat d'équilibre d'un jeu où l'on ne gagne pas en ayant raison mais en restant le dernier.

Le jeu n'est pas celui des articles précédents. Pour la correspondance (Autrice, 2026b), la question était de savoir qui rendrait l'effort de l'autre, et la coopération restait possible. Ici, l'effort des deux parties va dans le même sens, tenir, et c'est précisément ce parallélisme qui rend le conflit coûteux : tant que ni l'une ni l'autre ne cède, le coût court pour les deux. La structure est celle de la guerre d'usure, introduite par Maynard Smith (1974) pour les conflits animaux, généralisée par Bishop et Cannings (1978), et portée en économie par Bulow et Klemperer (1999), où deux agents se disputent un bien indivisible en supportant un coût qui croît avec la durée du litige. Le dernier debout l'emporte. Les deux ont saigné.

La section 2 pose le jeu et montre qu'il n'a pas de solution déterminée. La section 3 caractérise son équilibre symétrique, sans mémoire et sans gain. La section 4 examine qui l'emporte, et établit que ce n'est pas qui l'on croit ni pour les raisons qu'on croit. La section 5 expose les hypothèses, dont la première à céder est que l'enjeu reste intact pendant qu'on se le dispute.

## 2. Le jeu sans fin déterminée

Deux joueurs, $i \in \{A, B\}$, se disputent un enjeu de valeur $v > 0$, qui revient à celui qui tient quand l'autre cède. Chacun choisit un instant de concession $t_i \ge 0$. Tant que les deux tiennent, chacun supporte un coût au taux $c > 0$ par unité de temps : c'est la pénibilité du conflit ouvert, la tension et la soirée gâchée, payée des deux côtés aussi longtemps que dure le différend. Si $i$ cède le premier, à l'instant $t_i < t_j$, alors $i$ a payé $c\,t_i$ et n'obtient rien, tandis que $j$ obtient l'enjeu en ayant payé le même $c\,t_i$. Les gains sont donc

$$u_i = -\,c\,t_i \quad \text{si } i \text{ cède le premier}, \qquad u_i = v - c\,t_j \quad \text{si } j \text{ cède le premier}. \tag{1}$$

Aucun profil symétrique en stratégies pures n'est un équilibre. Supposons que les deux prévoient de céder à un même instant déterminé $T$. Chacun gagnerait alors à tenir un instant de plus : pour un coût supplémentaire négligeable, il fait céder l'autre et empoche $v$. La concession à $T$ ne résiste donc pas, et comme l'argument vaut pour tout $T$, il n'existe pas d'instant déterminé auquel les deux cèdent. La dispute n'a pas de fin prévisible.

Deux familles d'équilibres subsistent, que les sections suivantes traitent séparément. Dans les équilibres asymétriques, l'un cède à l'instant initial et l'autre ne cède jamais : le premier obtient zéro, le second obtient $v$, et nul coût n'est encouru puisque le conflit se résout avant d'avoir duré. Dans l'équilibre symétrique, chacun cède selon une loi de probabilité. La première famille décrit la dispute qui n'a pas lieu, parce qu'on sait d'avance qui pliera. La seconde décrit celle qui s'éternise.

## 3. Sans mémoire et sans gain

Cherchons l'équilibre symétrique, dans lequel chaque joueur cède selon une même loi sur $[0, \infty)$. Pour que mélanger soit rationnel, chaque joueur doit être indifférent entre céder maintenant et tenir encore un instant, à tout moment où le conflit dure. Tenir un instant $dt$ de plus coûte $c\,dt$ avec certitude. Le bénéfice de tenir est la probabilité que l'autre cède dans cet instant, soit $\lambda\,dt$ si l'adversaire cède au taux $\lambda$, multipliée par l'enjeu $v$. L'indifférence s'écrit

$$c\,dt = \lambda\,v\,dt \quad\Longleftrightarrow\quad \lambda = \frac{c}{v}. \tag{2}$$

À l'équilibre symétrique, chacun cède donc à taux constant $\lambda = c/v$, c'est-à-dire que son instant de concession suit une loi exponentielle de paramètre $c/v$. Deux conséquences en découlent, qui forment le cœur de l'article.

La première est l'absence de mémoire. La loi exponentielle est la seule qui la possède : la probabilité que la dispute s'arrête dans la minute qui vient est la même qu'elle dure depuis dix minutes ou depuis trois heures. La durée déjà écoulée n'informe en rien sur la durée restante, qui garde la même espérance. La conviction, au cœur d'une dispute longue, que « ça ne peut plus durer bien longtemps » est sans fondement : le conflit n'a pas d'âge, et chaque minute s'ouvre sur la même attente que la première. La dispute ne se rapproche pas de sa fin en durant ; elle dure, simplement.

La seconde conséquence est la dissipation. Céder à l'instant initial appartient au support de la loi d'équilibre, et procure un gain nul, puisqu'on ne paie alors aucun coût et n'obtient aucun enjeu. Or à l'équilibre en stratégies mixtes, toutes les actions du support procurent le même gain. Le gain d'équilibre de la guerre d'usure est donc nul, pour chacun des deux joueurs. L'enjeu $v$, tout entier, est consommé en moyenne par le coût du conflit. Avoir le dernier mot rapporte, en espérance, exactement zéro : non parce que le dernier mot n'a pas de valeur, mais parce que la guerre qu'il faut livrer pour l'obtenir en coûte autant.

À titre illustratif, et sans donner à ces nombres d'autre statut que celui d'une convention, posons $v = 10$ et $c = 1$. Le taux de concession vaut $\lambda = 0{,}1$ par heure, et la dispute, qui s'arrête à la première des deux concessions, dure en moyenne $v/(2c) = 5$ heures. Au terme de ces cinq heures, en moyenne, le vainqueur a obtenu un enjeu qui valait dix et payé un conflit qui coûtait autant, pour un gain net que le modèle chiffre à zéro de part et d'autre.

## 4. Le vainqueur

Reste à savoir qui l'emporte, et la réponse tient en deux temps.

Lorsque les rôles sont connus, l'un des équilibres asymétriques s'impose, et le conflit se résout à l'instant initial : celui dont il est établi qu'il pliera plie, sans qu'on en arrive à la guerre. C'est le cas des disputes qui n'éclatent jamais vraiment, parce que les deux savent déjà laquelle des deux cédera. Ce savoir n'est pas inscrit dans les gains. Il vient d'ailleurs, de l'histoire des disputes passées et de la réputation qu'elles ont laissée, c'est-à-dire de la répétition (Autrice, 2026b) : on plie vite aujourd'hui parce qu'on a toujours plié, et la rapidité de la résolution mesure alors moins une entente qu'une hiérarchie acquise. Les couples qui ne se disputent jamais ne sont pas nécessairement ceux qui s'accordent. Ce sont parfois ceux où il a été tranché, une fois pour toutes, qui aurait le dernier mot.

Lorsque les rôles ne sont pas connus, on tombe dans l'équilibre symétrique de la section 3, et la dispute s'éternise. Mais dans aucun des deux cas la victoire ne récompense la justesse. L'enjeu $v$ mesure ce que vaut, pour chacun, le fait de l'emporter, et le coût $c$ ce que lui pèse le conflit ; ni l'un ni l'autre n'encode le fait d'avoir raison. Le modèle est donc muet, par construction, sur la question que les disputeurs croient trancher. Il dit qui tiendra le plus longtemps, jamais qui méritait de gagner, et ces deux choses n'ont aucune raison de coïncider.[^2]

[^2]: On pourrait espérer que la dépendance entre l'issue et les paramètres rétablisse au moins une logique, par exemple que le plus endurant l'emporte. La guerre d'usure est précisément célèbre pour résister à cette lecture : son équilibre mixte admet des statiques comparatives contraires à l'intuition, et plusieurs équilibres coexistent. Nous nous en tenons donc à l'énoncé négatif, le seul qui soit robuste : ce n'est pas la raison qui gagne.

## 5. L'enjeu se consume

Trois hypothèses tiennent le modèle, et la dispute réelle les dément dans l'ordre où elle dure.

**L'enjeu est fixe.** Nous avons tenu $v$ pour constant. Il ne l'est pas. À mesure que le conflit dure, ce qu'on gagnerait à l'emporter se dégrade : la soirée qu'on défendait est déjà perdue, et l'excuse qu'on attendait n'aurait plus le même prix passé minuit. La guerre d'usure à enjeu décroissant a ses propres équilibres, plus brefs, parce que tenir devient inutile quand il n'y a plus rien à tenir. Le modèle à enjeu fixe surestime donc ce que les deux parties croient encore défendre à la troisième heure.

**Le terrain n'est pas l'enjeu.** Nous avons supposé l'enjeu séparable du conflit, comme une terre qu'on se dispute sans l'abîmer. Entre deux personnes liées, l'enjeu et le champ de bataille se confondent : ce qu'on se dispute, le lien, est aussi ce que la dispute use. Le vainqueur l'emporte donc sur un bien que sa victoire a entamé, et la dissipation de la section 3 sous-estime le coût réel, puisqu'elle compte les heures perdues mais non l'objet, commun, qu'elles ont endommagé. C'est la même configuration que pour le frigo (Autrice, 2026d) : le terrain partagé est ce qu'on épuise en s'en servant.

**On ignore la résolution de l'autre.** Le modèle suppose chaque joueur informé de l'enjeu et du coût de l'autre. En pratique on ignore combien l'autre tient à l'emporter, et tenir devient alors un signal : durer, c'est prétendre qu'on durera. La dispute est aussi un jeu d'information, où l'on ne se bat pas seulement pour l'enjeu mais pour faire croire qu'on le valorise assez pour ne jamais céder. Cette dimension, que nous laissons à une étude ultérieure, n'allège pas la guerre. Elle lui donne une raison de plus de commencer.

## Conclusion

Une dispute s'éternise non parce que l'un des deux a tort et s'entête, mais parce que tenir est, pour chacun, une réponse rationnelle tant que l'autre tient. Le coût court pour les deux, l'enjeu ne revient qu'à un seul, et entre ces deux faits s'ouvre exactement l'espace où une soirée se consume sans que rien se décide. Le modèle en tire la conséquence que l'on préférerait ignorer : le gain espéré de la victoire est nul, parce que la guerre qu'elle exige coûte, en moyenne, tout ce qu'elle rapporte. Avoir le dernier mot n'est pas sans valeur. C'est seulement un bien dont le prix, payé en heures et en silence, égale ce qu'il vaut, et qui se prélève sur la chose même que les deux croyaient défendre. Le vainqueur d'une dispute prolongée tient à la fin quelque chose d'exactement aussi cher que ce qu'il a dépensé pour l'obtenir, et il le tient seul, dans une pièce où l'autre s'est tu.

---

## Références

Bishop, D. T. et Cannings, C. (1978). « A Generalized War of Attrition ». *Journal of Theoretical Biology*, 70(1), 85–124.

Bulow, J. et Klemperer, P. (1999). « The Generalized War of Attrition ». *American Economic Review*, 89(1), 175–189.

Maynard Smith, J. (1974). « The Theory of Games and the Evolution of Animal Conflicts ». *Journal of Theoretical Biology*, 47(1), 209–221.

Autrice (2026b). « Personne n'a défecté en premier : réciprocité, latence bruitée et l'extinction d'un fil de discussion à l'équilibre ». *The Journal of Applied Personal Econometrics*, dans ce volume.

Autrice (2026d). « Le yaourt portait un prénom : le réfrigérateur partagé comme ressource commune ». *The Journal of Applied Personal Econometrics*, dans ce volume.

---

## Remerciements

Je remercie l'autre partie, qui a cédé la première, et que je remercie surtout de me laisser l'écrire.

**Préenregistrement.** L'autrice certifie avoir formé l'hypothèse qu'elle avait raison avant la dispute, et non après l'avoir gagnée. Cette antériorité ne lui a servi à rien.

**Approbation éthique.** Aucun comité n'a supervisé la dispute. Aucun, du reste, n'aurait pu l'interrompre.
