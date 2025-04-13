Bien sûr ! Voici un **cours complet de thermodynamique** destiné au niveau Mathématiques Spéciales (CPGE MPSI/PCSI/MP/PC/PSI). Le format suit le plan académique classique, en mettant l’accent sur les notions à connaître, les lois fondamentales, des définitions précises, des explications, et quelques exemples typiques.

---

# **COURS DE THERMODYNAMIQUE – Niveau Math Spé**

---

## 1. **Introduction à la thermodynamique**

**Définition :**  
La thermodynamique est la branche de la physique qui étudie les échanges d’énergie entre différents systèmes ainsi que les transformations d’énergie et de matière dans ces systèmes.

**Système et environnement :**
- **Système** : Partie de l’espace que l’on étudie (ex : un gaz dans un cylindre).
- **Environnement (ou extérieur)** : Tout ce qui l’entoure.
- Un système peut être **isolé, fermé ou ouvert** :
  - **Isolé** : ni échange de matière ni d’énergie
  - **Fermé** : échanges d’énergie mais pas de matière
  - **Ouvert** : échanges de matière et d’énergie

**Variables d’état :**
- **Variables extensives** : proportionnelles à la taille du système (masse m, volume V, énergie E, entropie S, etc.).
- **Variables intensives** : indépendantes de la taille (température T, pression P, densité, etc.).

---

## 2. **Notion d’état d’un système et fonctions d’état**

Un **état** est défini par un ensemble minimal de grandeurs macroscopiques (**variables d’état**), ex : (P, V, T, n).
  
- Une **fonction d’état** (ex : énergie interne U, enthalpie H, entropie S) ne dépend que de l’état du système et non du chemin suivi.

---

## 3. **Transformations thermodynamiques**

- **Transformation réversible** : Peut être inversée en repassant en tout point par des états d’équilibre.
- **Transformation irréversible** : Implique des phénomènes dissipatifs (frottements, différences de T ou P, etc.).
- **Quasi-statique** : Suite d’états d’équilibre (idéalisation).
- **Transformation cyclique** : l’état initial et final sont identiques.

Types de transformations courantes pour les gaz parfaits :
- **Isotherme** : à T constante
- **Isobare** : à P constante
- **Isochore** : à V constant
- **Adiabatique** : sans échange de chaleur (Q=0)

---

## 4. **Gaz parfait : loi des gaz parfaits**

**Équation d’état :**
$$
PV = nRT
$$

où :
- $$ P $$ : pression (Pa)
- $$ V $$ : volume (m³)
- $$ n $$ : quantité de matière (mol)
- $$ R $$ : constante des gaz parfaits ($$8,314$$ J/(mol·K))
- $$ T $$ : température (K)

**Énergie interne (U) du gaz parfait :**
- Dépend **uniquement de la température** : $$ U = n C_v T + U_0 $$
- $$ C_v $$ : capacité calorifique molaire à volume constant

---

## 5. **Premier principe de la thermodynamique**

$$
\Delta U = Q + W_{\text{alg}}
$$

Où :
- $$ \Delta U $$ : variation de l’énergie interne
- $$ Q $$ : chaleur échangée (positive si reçue)
- $$ W_{\text{alg}} $$ : travail des forces autres que conservatives (travail des forces de pression sur les parois) (positive si reçu de l’extérieur)

**Travail d’une force de pression :**
$$
\delta W = -P_{\text{ext}} dV
$$
- si expansion : travail positif (le système fournit du travail)
- si compression : travail négatif

Pour une transformation réversible :
$$
W = -\int_{V_i}^{V_f} P(V) dV
$$

**Capacités calorifiques :**
- $$ C_V = \left( \frac{\partial U}{\partial T} \right)_V $$
- $$ C_P = \left( \frac{\partial H}{\partial T} \right)_P $$
- Relation pour un gaz parfait : $$ C_P - C_V = nR $$

**Exemples de calculs de W, Q, ΔU pour des transformations classiques**

- **Isochore (dV=0)** : $$ W=0 $$, donc $$ Q = \Delta U $$
- **Isobare** : $$ Q = n C_P \Delta T $$, $$ W = -P \Delta V $$
- **Isotherme (gaz parfait)** : $$ \Delta U = 0 $$, $$ W = nRT \ln(V_f/V_i) $$, $$ Q = W $$
- **Adiabatique (Q=0)** : $$ \Delta U = W $$, relation de Laplace : $$ PV^{\gamma} = \text{cste} $$, $$ T V^{\gamma-1} = \text{cste} $$ où $$ \gamma = C_p/C_v $$

---

## 6. **Second principe de la thermodynamique**

**Énoncé de Clausius:**  
Il est impossible de transférer spontanément de la chaleur d’un corps froid vers un corps chaud sans fournir de travail.

**Entropie (S) :**
- Fonction d’état.
- Différentielle en transformation réversible :
$$
dS = \frac{\delta Q_{\text{rev}}}{T}
$$

- Pour une transformation irr. : $$ dS > \frac{\delta Q}{T} $$
- Pour un système isolé : $$ S $$ ne peut que croître ($$ \Delta S \geq 0 $$), c’est le **théorème de l'évolution**.

**Calculs classiques :**
- Pour chauffage isotherme d’un corps : $$ \Delta S = \frac{Q}{T} $$ (si réversible)
- Pour variation de température à volume constant (gaz parfait) : 
$$
\Delta S = n C_v \ln \left(\frac{T_f}{T_i}\right)
$$

---

## 7. **Enthalpie et autres grandeurs d’intérêt**

**Enthalpie (H):**
$$
H = U + PV
$$
- Utile pour les transformations à pression constante.
- Pour gaz parfait : $$ H = n C_p T + \text{cste} $$

**Enthalpie libre (Gibbs, G) et énergie libre (Helmholtz, F) :**
- $$ G = H - TS $$ (utile régime isobare-isotherme)
- $$ F = U - TS $$ (utile régime isochore-isotherme)

---

## 8. **Applications aux machines thermiques**

- **Cycle de Carnot** : cycle réversible d’un gaz parfait entre deux sources (**rendement maximal**)
$$
\eta_{\text{Carnot}} = 1 - \frac{T_c}{T_h}
$$
où $$ T_h $$ et $$ T_c $$ : températures des sources chaude et froide (en kelvin).

- **Cycles moteurs (Otto, Diesel, Joule-Brayton...)**  
Analyser les transformations subies par le fluide moteur. Calcul du travail et du rendement.

---

## 9. **Diagrammes thermodynamiques**

- **Diagramme de Clapeyron** (P,V)
- **Diagramme entropique** (T, S)
- Utilité pour visualiser les cycles, calculer le travail (aire sous la courbe PV).

---

## 10. **Exemples classiques d’exercices**

1. **Détente isotherme d’un gaz parfait :** Calculer W, Q, ΔU.
2. **Vérifier le second principe sur un échange de chaleur entre deux corps.**
3. **Cycle de Carnot :** Schéma, calcul du rendement, expressions de Q, W.
4. **Transformations irréversibles et calcul d’entropie produite.**
5. **Chauffage à pression constante/volume constant : calculer toutes les fonctions d'état.**

---

## 11. **Points de vigilance**

- Toujours raisonner en **différentielle** et identifier le référentiel du travail (travail des forces de pression).
- Justifier les hypothèses de gaz parfait (faibles pressions, températures éloignées de la liquéfaction).
- Distinguer soigneusement transformations réversibles/irréversibles : affecte la définition d’entropie.

---

## 12. **Quelques formules à retenir**

- $$ PV = nRT $$
- $$ dU = \delta Q + \delta W $$
- $$ \delta W_{\text{rév}} = -P_{\text{ext}} dV $$
- $$ H = U + PV $$
- $$ dS = \frac{\delta Q_{\text{rev}}}{T} $$
- Cycle de Carnot $$ \eta = 1 - \frac{T_f}{T_c} $$
- Transformation adiabatique réversible : $$ PV^{\gamma} = \text{cste} $$

---

## 13. **Conclusion**

La thermodynamique permet d’appréhender les échanges d’énergie sous forme de travail et de chaleur dans un système. Ses deux principes fondamentaux encadrent la conservation de l’énergie et l’irréversibilité des transformations naturelles, et aboutissent à la notion de rendement des machines thermiques.

---

### **Pour aller plus loin**
- Voir livres : "Thermodynamique" de Callen, Jaynes, ou le "PC Spé" de J. Dessornes.
- Faire de nombreux exercices d’application pour maîtriser les raisonnements.

---

**Ce cours synthétique couvre les grands chapitres de la thermodynamique au niveau attendu en Math Spé. N’hésite pas à demander des exercices d’application, des démonstrations ou des approfondissements sur certaines parties !**
