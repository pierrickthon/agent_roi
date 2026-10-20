# Revue – Analyse ROI Boutique en ligne B2B – v1

Fichier relu : `roi-boutique-en-ligne-v1.md`
Source de contrôle : *Compte rendu de projet – Lancement d'une boutique en ligne B2B* (19/10/2026)
Date de la revue : 20/10/2026

## Appréciation générale

L'analyse est de bonne qualité. Le CA en ligne est bien distingué de la marge additionnelle. Le déplacement de canal est traité, le temps libéré n'est pas monétisé, et les coûts ponctuels, fixes et variables sont tous repris. J'ai refait tous les calculs des § 4 et 5 et les VAN à 5 ans : ils sont justes, aux arrondis près. La conclusion du scénario réaliste (projet non rentable sur 3 ans) est solide.

Les objections portent surtout sur le **scénario optimiste**, qui est le seul scénario rentable et qui repose sur des hypothèses favorables empilées. Elles portent aussi sur le **seuil de rentabilité affiché en synthèse** et sur une **donnée disponible qui n'est pas exploitée** (septembre 2026).

---

## Objections

### 1. Le seuil de VAN nulle est sous-estimé (44 % au lieu d'environ 46 %)
- **Gravité** : importante
- **Problème** : au § 6, le seuil est calculé comme une annuité constante égale au gain de l'an 2 (80 000 / 2,577 = 31 043 €). Ce calcul ignore que l'an 1 est plus faible (CA de 932 600 € au lieu de 990 600 €, plus la remise de 9 800 €). J'ai recalculé avec la trajectoire réaliste réelle (an 1, puis ans 2 et 3) :
  - VAN(r) = −80 000 + (261 128 r − 100 284) / 1,08 + (277 368 r − 92 094) × (1/1,08² + 1/1,08³)
  - VAN(r) = 699 768 r − 324 919, qui s'annule pour **r ≈ 46,4 %**.
  La synthèse affirme que « ce niveau correspond au scénario optimiste ». Or à 45 % d'additionnalité, avec les coûts et le CA réalistes, la VAN reste négative. Le scénario optimiste n'est rentable que grâce à ses autres hypothèses favorables (voir objection 2).
- **Correction attendue** : recalculer le seuil sur la trajectoire réelle des 3 ans et corriger la synthèse (« plus de 46 % »). Préciser que 45 % d'additionnalité seule ne suffit pas.

### 2. Le scénario optimiste empile des hypothèses favorables et contredit la mesure observée
- **Gravité** : importante
- **Problème** : c'est le seul scénario rentable (ROI +174 %, VAN +106 k€), et il cumule cinq hypothèses favorables :
  1. **45 % d'additionnalité, alors que les données observées l'infirment.** Sur mars–août, 45 % de 410 000 € donne 184 500 €, plus la rétention (7 clients × 5 111 € = 35 800 € de CA), soit environ 220 000 € de CA additionnel. La croissance totale observée n'est que de ≈ 123 000 €. Le scénario suppose donc, sans le dire, que le reste de l'activité a reculé d'environ 100 000 € pour d'autres raisons. L'analyse s'appuie elle-même sur cette « vérification par le haut » au § 3.1 pour écarter ce cas.
  2. **La rétention (+20 036 €/an) est ajoutée** alors que le lien de cause à effet n'est pas prouvé (donnée manquante n° 10).
  3. **La livraison est supposée déjà offerte par téléphone.** Rien dans le compte rendu ne l'indique. Même dans ce cas, le panier plus petit (186 € contre 240 €) multiplie par 1,29 le nombre de commandes pour un même CA. Le coût de livraison des ventes déplacées n'est donc pas nul.
  4. **Le CA atteint 1,1 M€ puis 1,2 M€** sans calcul ni justification. Le chiffre de l'an 3 reprend simplement l'objectif de la direction.
  5. **La part additionnelle reste fixe à 45 %** alors que le CA en ligne augmente. Or une croissance en ligne qui vient surtout de la migration des clients existants fait baisser la part additionnelle.
- **Correction attendue** : soit justifier chacune de ces hypothèses par une donnée, soit construire un optimiste cohérent avec la croissance observée de +3 % (par exemple, additionnalité plafonnée à ce que permet la mesure par le haut, plus rétention). Montrer séparément l'effet de chaque levier, ce qui donne une décomposition de la VAN optimiste. Ajouter en synthèse que le scénario optimiste est en contradiction avec la croissance mesurée.

### 3. La donnée de septembre 2026 existe déjà mais n'est ni exploitée ni demandée
- **Gravité** : importante
- **Problème** : l'annualisation dépend surtout de la pointe de septembre (coefficient 1 / 1,7 / 2,41 selon le scénario, pour un écart d'environ 100 k€ de CA en an 1). Le compte rendu date du 19/10/2026, donc septembre 2026 est écoulé. La recommandation n° 4 (« nouvelle analyse après septembre 2026 ») et la liste des données manquantes (§ 2.4) ne demandent pas ce chiffre. Le coefficient de 1,7 du scénario réaliste n'est par ailleurs pas justifié.
- **Correction attendue** : ajouter au § 2.4 la demande du **CA en ligne et du CA total de septembre 2026**, ainsi que du CA mensuel de mars à septembre. Justifier le coefficient de 1,7 ou le présenter explicitement comme une hypothèse arbitraire. Reformuler la recommandation n° 4.

### 4. Le scénario pessimiste n'est pas assez bas
- **Gravité** : mineure
- **Problème** : 20 % d'additionnalité suppose qu'environ deux tiers de la croissance de +3 % sont dus à la boutique. Une hausse des prix catalogue de 2 à 3 % en 2026, courante dans les fournitures de bureau, suffirait à expliquer à elle seule toute la croissance. L'additionnalité serait alors proche de 0 %. Le pessimiste n'inclut pas non plus les coûts logistiques du petit panier (donnée manquante n° 8).
- **Correction attendue** : demander l'effet prix 2026 et soit abaisser le pessimiste (10 % par exemple), soit justifier pourquoi 20 % est un plancher.

### 5. Plusieurs hypothèses ne sont pas présentées comme telles
- **Gravité** : mineure
- **Problème** :
  - Le **taux d'actualisation de 8 %** figure en en-tête, sans source ni justification (coût du capital, taux de financement).
  - La **valeur d'un client retenu** (9 200 000 / 1 800 = 5 111 €) suppose que les clients partis vers les plateformes sont des clients moyens. Le compte rendu les qualifie de « clients réguliers ».
  - Les **coûts fixes sont supposés constants** sur 3 et 5 ans, sans test de sensibilité. Des hausses contractuelles sont plausibles (plateforme, maintenance, publicité).
- **Correction attendue** : signaler ces trois points comme des hypothèses. Ajouter une sensibilité d'indexation des coûts fixes (+3 %/an par exemple) pour en montrer l'effet, même faible.

### 6. Le délai de récupération ne part pas du début de l'investissement
- **Gravité** : mineure
- **Problème** : le délai de 1,3 an (« vers juin 2027 ») est compté à partir de la mise en ligne (mars 2026). Les dépenses ont commencé en septembre 2025.
- **Correction attendue** : préciser le point de départ du délai, ou l'exprimer aussi à partir du lancement du projet (soit environ 1,8 an).

---

## Calculs vérifiés (aucun écart significatif)
- Totaux des coûts : 80 000 € et 64 600 € ✔
- Base mars–août 2025 : 4 114 909 € ; +3 % = 123 447 € ; 30,1 % du CA en ligne ✔
- Coefficient de septembre : 18 % × 11 / 82 % = 2,41 ✔ ; CA annualisés 878 000 / 932 600 / 990 600 / 1 027 341 € ✔
- Coûts variables : 2,7755 % (contrôle sur le semestre : 11 378 €) ✔ ; 1,711 % en optimiste ✔
- Gains annuels, ROI et VAN des 3 scénarios (§ 5) ✔ ; VAN à 5 ans ✔
- Seuil de rentabilité annuelle : 33,2 % ✔ ; seuil de VAN nulle : **faux, voir objection 1**
- Temps libéré : 10 080 € ✔, correctement exclu du ROI

---

## Verdict : **À corriger**

Il n'y a pas d'objection bloquante, et la conclusion du scénario réaliste (projet non rentable sur 3 ans) n'est pas remise en cause. Les objections 1 à 3 doivent être traitées avant diffusion : elles modifient le seuil affiché en synthèse et la crédibilité du seul scénario rentable.
