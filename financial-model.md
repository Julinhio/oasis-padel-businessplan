# Oasis Padel Academy — Modèle Financier
**Da Nang, Vietnam · Business Plan 2026**

---

## Paramètres de base (valeurs par défaut)

| Paramètre | Valeur |
|---|---|
| Taux d'occupation | 40% |
| Loyer mensuel | 4 000 $ |
| Masse salariale / mois | 3 200 $ |
| Courts | 4 |
| Créneaux disponibles / an | 13 140 (4 courts × 9 créneaux/j × 365 j) |
| Prix / créneau | 36 $ |

---

## 1. Revenus (base : 40% d'occupation)

| Poste | Calcul | Montant annuel |
|---|---|---|
| **Courts** | 13 140 créneaux × 40% × 36 $/créneau → 5 256 créneaux utilisés | **189 216 $** |
| Restauration (F&B) | 5 256 × 4 joueurs × 40% conso × 3 $ | 25 229 $ |
| Wellness & boutique | Proportionnel à l'occupation (base 24 000 $/an à 40%) | 24 000 $ |
| **CA annuel total** | | **238 445 $** |

---

## 2. Charges mensuelles fixes

| Poste | Montant/mois |
|---|---|
| Loyer | 4 000 $ *(variable)* |
| Staff | 3 200 $ *(variable — Pascal : 2–3 pers. / Julien : 5–7 pers.)* |
| Électricité | 1 000 $ |
| Maintenance courts | 800 $ |
| Marketing | 200 $ |
| Admin + compta Vietnam | 500 $ |
| Assurance | 300 $ |
| Holding Singapour (maintenance + compta) | 145 $–470 $ |
| **Total mensuel** | **~10 200 $** |
| **Total annuel** | **~122 400 $** |

> Note : la ligne Holding Singapour est indicative (145–470 $/mois) et n'est pas incluse dans le calcul de base (200 $ de marge pris en compte).

---

## 3. Résultat (base : 40% occupation, loyer 4 000 $, staff 3 200 $)

| Indicateur | Valeur |
|---|---|
| CA annuel | 238 445 $ |
| Charges annuelles | 122 400 $ |
| **Résultat brut** | **+116 045 $** |
| **Marge** | **49%** |
| Verdict | ✓ Rentable et confortable |

**Règles de verdict :**
- Résultat > 40 000 $ → ✓ Rentable et confortable
- Résultat entre 0 $ et 40 000 $ → ⚠ Rentable mais serré
- Résultat < 0 $ → ✗ Déficitaire

---

## 4. Comparaison des scénarios

*Résultat brut annuel selon taux d'occupation et loyer (staff = 3 200 $/mois)*

| Occupation | Loyer 2 000 $ | Loyer 4 000 $ | Loyer 6 000 $ |
|---|---|---|---|
| 20% | +20 822 $ | -3 178 $ | -27 178 $ |
| 30% | +80 434 $ | +56 434 $ | +32 434 $ |
| **40%** | **+140 045 $** | **+116 045 $** | **+92 045 $** |
| 50% | +199 656 $ | +175 656 $ | +151 656 $ |
| 60% | +259 267 $ | +235 267 $ | +211 267 $ |
| 70% | +318 878 $ | +294 878 $ | +270 878 $ |

> Le seuil de rentabilité avec loyer à 4 000 $ se situe entre 20% et 30% d'occupation.

---

## 5. Investissement initial

| Poste | Montant |
|---|---|
| 4 courts + transport + taxes | 50 000 $ |
| Construction / aménagement | 120 000 $ |
| Accueil + boutique | 20 000 $ |
| Restauration rapide | 25 000 $ |
| Ice bath + sauna | 20 000 $ |
| Mobilier, déco, lumières | 25 000 $ |
| Fonds de roulement (3 mois) | 30 000 $ |
| Setup légal Vietnam (IRC + ERC + notaire) | 3 000 $–8 000 $ |
| Création Holding Singapour (Pte Ltd) | 1 500 $–2 500 $ |
| Imprévus (10%) | 29 000 $ |
| **Total estimé** | **~325 000 $ – 330 000 $** |

**Retour sur investissement estimé** (base : 40% occupation, loyer 4 000 $) : **~3 ans**

---

## 6. Fiscalité

| Taxe | Taux |
|---|---|
| Impôt sur les sociétés Vietnam (CIT) | **20%** sur bénéfices |
| TVA services sportifs | **10%** |
| Taxe annuelle de licence | ~100 $/an |

> Les zones franches de Da Nang ne s'appliquent pas à notre secteur. **Régime fiscal standard.**

---

## Formules de calcul

```
TOTAL_SLOTS     = 4 courts × 9 créneaux/j × 365 j = 13 140
usedSlots       = TOTAL_SLOTS × occ%
revCourts       = usedSlots × 36 $
revFood         = usedSlots × 4 joueurs × 40% × 3 $
revWellness     = 24 000 $ × (occ% / 40%)
revTotal        = revCourts + revFood + revWellness

costsMonthly    = loyer + staff + 1 000 + 800 + 200 + 500 + 300 + 200
costsAnnual     = costsMonthly × 12

résultat        = revTotal − costsAnnual
marge           = résultat / revTotal × 100
ROI (années)    = ~327 500 $ / résultat
```
