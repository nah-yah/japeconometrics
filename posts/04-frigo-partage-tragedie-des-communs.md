---
title: "Le yaourt portait un prénom"
subtitle: "Le réfrigérateur partagé comme ressource commune, avec une caractérisation de la dissipation du surplus en fonction de la taille du foyer"
description: "Le réfrigérateur partagé comme ressource commune : la surexploitation et la dissipation du surplus croissent avec la taille du foyer."
categories: ["Tragédie des communs", "Ressource commune", "Externalités"]
order: 4
title-block-banner: true
include-in-header:
  text: |
    <style>
      .quarto-title-banner { background: linear-gradient(135deg, #1b3a4b 0%, #2f6690 55%, #6ea8c9 100%); }
    </style>
---

**Autrice :** celle qui a fini le lait[^1]  
*Département d'études stratégiques domestiques, section des ressources communes, The Journal of Applied Personal Econometrics*

[^1]: L'autrice a fini le lait à plusieurs reprises au cours de l'étude et ne l'a pas racheté, ce qu'elle a longtemps imputé à l'oubli.

---

## Résumé

Un réfrigérateur partagé est une ressource commune : rivale, puisque le dernier yaourt ne se mange qu'une fois, et non excluable, puisque rien n'arrête la main d'un colocataire. Nous le traitons comme un problème de propriété commune (Gordon, 1954 ; Hardin, 1968), où chaque membre du foyer choisit l'intensité de son usage et touche tout le bénéfice privé de ce qu'il prélève, mais ne supporte qu'une fraction du coût de congestion qu'il impose aux autres. À l'équilibre de Nash, le prélèvement total excède l'optimum social d'un facteur $2n/(n+1)$, qui croît de $1$ pour une personne seule vers $2$ quand le foyer s'agrandit, et la part du surplus effectivement réalisée, $4n/(n+1)^2$, décroît vers zéro. À six colocataires, le frigo rend moins de la moitié de ce qu'il pourrait. Nous montrons ensuite que la réponse spontanée à cette dissipation n'est pas la coopération mais l'enclosure : on étiquette son nom, on revendique une étagère, on se retire du partage. L'enclosure restaure l'efficacité privée et détruit le surplus que seul le partage produisait. C'est la solution de Hardin, et précisément celle qu'Ostrom (1990) montre évitable lorsque le foyer est assez petit et assez durable pour se gouverner lui-même.

**Mots-clés :** ressource commune, tragédie des communs, externalité, dissipation de rente, enclosure, taille du foyer  
**Codes JEL :** C72 (jeux non coopératifs), D62 (externalités), Q22 (ressources communes)

---

## 1. Introduction

Il restait du lait ce matin, et il n'en reste plus, sans que personne ait vu qui l'a fini. La scène est familière : un contenant que nul ne réclame et que nul ne jette, une étagère où chaque chose appartient à quelqu'un d'autre. On impute d'ordinaire l'état d'un frigo partagé au caractère de ses usagers, à leur négligence ou à leur égoïsme. Nous soutenons que sa dégradation est un résultat d'équilibre, et qu'elle s'aggrave non avec le défaut moral des colocataires mais avec leur nombre.

Le réfrigérateur partagé est une ressource commune, et il importe de le distinguer du bien public étudié pour l'évier (Autrice, 2026a). L'évier propre est non rival : qu'un occupant en jouisse n'en retire rien à l'autre, et le bénéfice, une fois produit, est disponible pour tous sans s'épuiser. Le frigo ne possède pas cette propriété. Sa place est limitée, son contenu se mange, et ce qu'un colocataire prélève, un autre ne le prélèvera pas. Le bien y est rival, et c'est cette rivalité, absente de l'évier, qui change le problème : il ne s'agit plus de savoir qui produira un bien partagé, mais qui épuisera le premier un stock partagé.

La structure est celle que Gordon (1954) a dégagée pour la pêcherie en propriété commune, et que Hardin (1968) a popularisée sous le nom de tragédie des communs. Chaque usager d'une ressource non gardée en retire le bénéfice privé entier, mais n'en supporte le coût de déplétion qu'au prorata de sa part. Il prélève donc au-delà de ce qui serait collectivement souhaitable, et la ressource se dégrade. La prédiction n'est pas que le partage est difficile, mais qu'il est instable, et qu'il l'est davantage à mesure que le nombre d'ayants droit augmente. Ostrom (1990) a montré que cette issue n'est pas fatale, et nous y reviendrons : certaines communautés gouvernent leurs communs sans les détruire ni les clôturer. La plupart des colocations ne sont pas de celles-là.

La section 2 pose le modèle et établit l'écart à l'optimum. La section 3 décrit la réponse que le foyer oppose spontanément à cet écart, qui n'est pas le partage réglé mais sa fin. La section 4 expose les hypothèses et les cas où le frigo, contre le modèle, tient.

## 2. La ressource commune et son équilibre

### 2.1 Le modèle

Soient $n \ge 1$ colocataires. Chacun choisit l'intensité $x_i \ge 0$ de son usage du frigo, grandeur qui agrège ce qu'il y stocke et ce qu'il y prélève. Soit $X = \sum_{j} x_j$ l'usage total. La valeur que le frigo rend par unité d'usage décroît avec l'encombrement collectif : un frigo peu sollicité garde au frais et laisse trouver ce qu'on y cherche, un frigo saturé périme, masque et déborde. Nous représentons cette valeur unitaire par $a - bX$, avec $a > 0$ et $b > 0$. Chaque colocataire supporte par ailleurs un coût privé $c \in (0, a)$ par unité d'usage, qui mesure l'effort d'approvisionner et de ranger. Le gain de $i$ s'écrit

$$u_i = x_i\,(a - bX) - c\,x_i = x_i\,(a - c - bX). \tag{1}$$

L'externalité est lisible dans cette expression. En augmentant $x_i$ d'une unité, le colocataire $i$ abaisse de $b$ la valeur unitaire de chacune des unités prélevées par les autres, soit une perte $b\,X_{-i}$ qu'il n'inscrit pas à son calcul, puisqu'elle tombe sur eux. C'est tout l'écart entre ce qu'il fait et ce qu'il faudrait.

### 2.2 L'écart à l'optimum

Chaque colocataire maximise (1) en $x_i$, l'usage des autres étant tenu pour donné. La condition du premier ordre est $a - c - bX - b x_i = 0$. En imposant la symétrie $x_i = x$ et $X = nx$, on obtient

$$x^{N} = \frac{a - c}{b\,(n+1)}, \qquad X^{N} = \frac{n\,(a - c)}{b\,(n+1)}. \tag{2}$$

L'optimum social maximise le surplus agrégé $W = X\,(a - c - bX)$ en traitant $X$ comme une seule variable, c'est-à-dire en internalisant l'externalité. Sa condition du premier ordre, $a - c - 2bX = 0$, donne

$$X^{*} = \frac{a - c}{2b}. \tag{3}$$

Le rapport des deux ne dépend ni de $a$, ni de $b$, ni de $c$, mais du seul nombre de colocataires :

$$\frac{X^{N}}{X^{*}} = \frac{2n}{n+1}. \tag{4}$$

Le prélèvement d'équilibre vaut l'optimum pour une personne seule, le dépasse d'un tiers à deux, de moitié à trois, et tend vers le double quand le foyer croît. La perte se mesure mieux encore sur le surplus effectivement réalisé. En reportant (2) et (3) dans $W$, la fraction de l'optimum que le foyer atteint vaut

$$\frac{W^{N}}{W^{*}} = \frac{4n}{(n+1)^2}, \tag{5}$$

quantité elle aussi sans paramètre, qui décroît vers zéro. Les deux expressions se lisent dans le tableau suivant, dont les valeurs sont des conséquences exactes du modèle et non une convention.

| Colocataires $n$ | Surexploitation $\dfrac{2n}{n+1}$ | Surplus réalisé $\dfrac{4n}{(n+1)^2}$ |
|---|---|---|
| 1 | $1{,}00$ | $1{,}00$ |
| 2 | $1{,}33$ | $0{,}89$ |
| 3 | $1{,}50$ | $0{,}75$ |
| 4 | $1{,}60$ | $0{,}64$ |
| 6 | $1{,}71$ | $0{,}49$ |

Une personne vivant seule gère son frigo sans perte : il n'y a pas de commun, donc pas de tragédie. À deux, le foyer renonce déjà à un dixième de la valeur que le frigo pourrait rendre. À six, il en abandonne plus de la moitié. La ressource ne disparaît pas d'un coup ; elle rend simplement de moins en moins, et chacun le constate sans pouvoir, seul, l'enrayer, puisque modérer son propre usage ne ferait que céder de la place à celui des autres.

## 3. L'enclosure

Le modèle de la section 2 prédit la dissipation, non la manière dont le foyer y réagit. L'intuition voudrait que les colocataires s'accordent pour préserver la valeur commune qu'ils voient fondre. C'est rarement ce qui s'observe. La réponse spontanée à la tragédie n'est pas le partage réglé, c'est son retrait.

Elle commence par une étiquette. Un prénom au feutre sur un contenant retire celui-ci du commun et le déclare propriété privée.[^2] Vient ensuite la revendication d'une étagère, puis d'un tiroir, puis l'achat en double de ce qui était mutualisé, jusqu'à ce que le frigo, sans avoir changé de taille, ne contienne plus que des stocks privés juxtaposés dans un même froid. C'est l'enclosure, au sens exact que le mot a dans l'histoire des communs : la conversion d'une ressource partagée en parcelles appropriées.

L'enclosure fonctionne. À l'intérieur de sa parcelle, chacun retrouve la situation de la personne seule, sans externalité, et son usage redevient efficace. C'est la solution que Hardin (1968) tenait pour la seule issue, et le modèle lui donne raison sur un point : la propriété privée supprime la tragédie. Mais elle la supprime en supprimant le commun. Le surplus que seul le partage produisait, le condiment qu'un seul achète et dont tous usent, la confiance qui dispensait d'étiqueter, tout cela n'était pas dans les parcelles. Il était dans ce que l'enclosure défait. Le foyer clôturé est plus efficace que le foyer dissipé, et il a cessé d'être autre chose qu'un entrepôt réfrigéré que plusieurs personnes se trouvent partager.

## 4. Les frigos qui tiennent

Le modèle tient le frigo pour un jeu à un coup entre usagers anonymes d'un bien purement rival. Aucune de ces trois hypothèses n'est exacte, et c'est par leurs défauts que certains frigos échappent à la prédiction.

**Le jeu se répète, et les usagers se connaissent.** Le modèle est statique. Or un foyer dure, et ses membres se revoient chaque jour devant la même porte. La répétition autorise ce que le coup unique exclut, comme nous l'avons vu pour la correspondance (Autrice, 2026b) : une coopération soutenue par la perspective des lendemains et par la menace de représailles. C'est sur ce terrain qu'Ostrom (1990) a réfuté le caractère fatal de la tragédie, en relevant les communs réels que des communautés gouvernent durablement sans les clôturer. Les conditions qu'elle dégage sont restrictives, un groupe restreint et un suivi mutuel peu coûteux, mais elles décrivent assez bien une colocation petite et stable, et expliquent pourquoi certaines partagent un frigo des années sans une seule étiquette.

**L'action est en partie observable.** Le modèle suppose qu'on ne sait pas qui a prélevé quoi. La réalité du frigo offre davantage. On voit le niveau baisser, on date un reste, on devine à qui manquait le beurre. L'étiquette elle-même est une technologie de surveillance avant d'être une clôture : elle rend l'action visible, donc punissable, et c'est cette visibilité, plus que la propriété qu'elle proclame, qui discipline. Le mot laissé sur la porte appartient au même registre. Il suppose un coupable identifiable, ce que le modèle, lui, n'autorise pas.

**Tout n'y est pas rival.** Nous avons traité le frigo comme un stock entièrement rival. Une part de ce qu'il rend ne l'est pourtant pas : le froid lui-même, la lumière, le sel qui ne s'épuise jamais, relèvent du bien public non rival de l'évier, non de la ressource commune. Le modèle les confond avec le lait. Seuls les biens que l'un prive l'autre en les prenant fondent réellement la tragédie ; le reste coexiste sans conflit, et c'est pourquoi nul n'a jamais étiqueté la lumière du frigo.

## Conclusion

Un frigo partagé ne se dégrade pas parce que ceux qui s'en servent sont malhonnêtes. Il se dégrade parce que chacun y prend ce qui lui est utile et que le coût en revient au froid commun, c'est-à-dire à personne en particulier et à tout le monde un peu. La tragédie n'a pas besoin de voleur. Il lui suffit d'usagers ordinaires et d'une ressource que nul ne garde, et elle s'approfondit à mesure que les usagers se multiplient, jusqu'à ce que le frigo ne rende plus qu'une fraction de ce qu'il pourrait. La sortie que le foyer trouve presque toujours n'est pas de mieux partager, mais de cesser de partager : étiqueter, se replier sur une parcelle où l'on est enfin seul. Cette sortie est efficace, et le modèle ne lui trouve rien à redire. Elle rend seulement visible ce que le partage coûtait et ce qu'il valait. Le prénom au feutre sur le yaourt est une petite borne plantée sur un terrain qui était commun, et il marque, à la quantité de lait près, la date à laquelle un foyer a cessé d'en être un.

---

## Références

Gordon, H. S. (1954). « The Economic Theory of a Common-Property Resource: The Fishery ». *Journal of Political Economy*, 62(2), 124–142.

Hardin, G. (1968). « The Tragedy of the Commons ». *Science*, 162(3859), 1243–1248.

Ostrom, E. (1990). *Governing the Commons: The Evolution of Institutions for Collective Action*. Cambridge : Cambridge University Press.

Autrice (2026a). « Défection mutuelle à l'équilibre : une caractérisation non coopérative de l'évier partagé ». *The Journal of Applied Personal Econometrics*, dans ce volume.

Autrice (2026b). « Personne n'a défecté en premier : réciprocité, latence bruitée et l'extinction d'un fil de discussion à l'équilibre ». *The Journal of Applied Personal Econometrics*, dans ce volume.

---

## Remerciements

Je remercie mes colocataires, dont la confiance a constitué la principale ressource épuisée au cours de cette étude.

**Financement.** Aucun. Le lait a été racheté, les rares fois où il le fut, par quelqu'un d'autre.

**Disponibilité du matériel.** Le seul matériel subsistant de l'étude est une étagère, que l'autrice continue de désigner comme commune.

[^2]: L'étiquette nominative au feutre est, dans nos relevés, le premier signe clinique de l'enclosure, et le plus fiable.
