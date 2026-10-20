# Revue – Analyse ROI Boutique en ligne B2B – v2

Fichier relu : `roi-boutique-en-ligne-v2.md`
Source de contrôle : *Compte rendu de projet – Lancement d'une boutique en ligne B2B* (19/10/2026)
Revue précédente : `revue-boutique-en-ligne-v1.md`
Date de la revue : 20/10/2026

## Suivi des objections de la v1

| # | Objection v1 | Traitement en v2 | Contrôle |
|---|---|---|---|
| 1 | Seuil de VAN nulle sous-estimé | Recalculé : 46,4 % (réaliste), 40,9 % (optimiste) | ✔ Recalculé : 46,4 % et 40,9 % |
| 2 | Optimiste incohérent avec le +3 % | Optimiste reconstruit (30 %, livraison sur tout le CA, trajectoire calculée) ; décomposition au § 6.2 | ✔ Décomposition recalculée à l'euro près (−114 988 → −95 429 → +24 141 → +54 447 → +106 080) |
| 2 bis | Point rejeté : « plafond par le haut + rétention » | Rejeté pour double emploi | ✔ **Le rejet est justifié.** Le CA des clients retenus fait déjà partie du CA total, donc du +3 %. Ma suggestion de la v1 était erronée : l'ajouter aurait compté la rétention deux fois. |
| 3 | Septembre 2026 non demandé, coefficient 1,7 | Donnée n° 1, 1,7 présenté comme arbitraire, recommandation n° 1 | ✔ |
| 4 | Pessimiste pas assez bas | 10 %, justifié par un effet prix de 2 % ; effet prix demandé | ✔ |
| 5 | Hypothèses non signalées | § 4.5, indexation testée, valeur d'un client retenu abandonnée | ✔ |
| 6 | Date zéro du délai de récupération | Précisée au § 4.4 | ✔ |

## Calculs vérifiés
- Scénario pessimiste : gains annuels −74 185 / −64 371 € ; ROI −354 % ; VAN −254 976 € ✔
- Scénario réaliste : inchangé, VAN −114 988 € ✔
- Scénario optimiste : CA 1 027 341 / 1 150 976 / 1 266 073 € ✔ ; gains annuels −16 617 / +137 / +6 610 € ; VAN −90 021 € ✔ ; somme sur 5 ans 3 351 € ✔
- Sur 5 ans : VAN −346 100 / −127 564 / −80 663 € ✔
- Indexation des coûts fixes de +3 %/an : VAN réaliste −119 773 € (3 ans) et −142 270 € (5 ans), VAN optimiste −94 806 € ✔
- Sensibilité livraison : environ +40 k€ de VAN, soit une VAN optimiste ≈ −50 k€ ✔ ; sensibilité publicité : +21 116 €/an ✔

---

## Objections

### 1. La trajectoire optimiste de l'an 1 n'applique pas la croissance à septembre
- **Gravité** : mineure
- **Problème** : en an 1, la croissance de +10 % s'applique à octobre–février (5 × 78 000 × 1,1), mais pas à septembre (2,41 × 78 000). L'effet est d'environ 18,8 k€ de CA, soit moins de 1 k€ de VAN. La conclusion ne change pas.
- **Correction attendue** : appliquer le même traitement à septembre, ou indiquer que la croissance ne démarre qu'en octobre.

### 2. Le scénario « réaliste » est placé au plafond
- **Gravité** : mineure
- **Problème** : le § 4.1 présente 30 % comme un **plafond**, car toute la croissance est attribuée à la boutique et la base de mars–août est probablement surestimée. Le scénario réaliste retient pourtant ce plafond, et le scénario optimiste ne diffère que par la trajectoire de CA. Le réaliste est donc en fait un scénario haut. Cela renforce la conclusion sans la modifier.
- **Correction attendue** : le dire explicitement en synthèse (« le réaliste retient déjà le maximum compatible avec les données »), ou renommer les scénarios.

### 3. Le rôle de septembre 2026 est surestimé dans la synthèse
- **Gravité** : mineure
- **Problème** : la synthèse cite le CA de septembre 2026 comme « la donnée qui peut changer la conclusion ». Or même avec la pointe maximale (coefficient 2,41) et +10 %/an, la VAN reste à −90 k€. Seule l'additionnalité peut changer le signe (seuil ≥ 41 %). Septembre affine l'annualisation, mais c'est la comparaison mensuelle 2025/2026 (donnée n° 2) et l'effet prix (donnée n° 3) qui peuvent changer la conclusion.
- **Correction attendue** : reformuler pour placer l'additionnalité en premier, avec septembre comme donnée d'annualisation.

---

## Verdict : **Validé**

Les six objections de la v1 sont traitées et le point rejeté l'est à juste titre. Tous les calculs sont exacts. Les trois remarques ci-dessus sont mineures et ne changent ni les chiffres de synthèse ni la conclusion : elles peuvent être intégrées à la prochaine mise à jour, une fois les données de septembre 2026 reçues.
