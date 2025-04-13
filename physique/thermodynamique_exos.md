Bien sûr ! Voici une série d’**exercices corrigés de thermodynamique** adaptés au niveau Math Spé, couvrant les principaux points du programme.

---

## **Exercice 1 : Travail d’expansion isotherme d’un gaz parfait**

**Énoncé :**  
Un gaz parfait monoatomique ($$ n = 1\,\mathrm{mol} $$) initialement à $$ T = 300\,\mathrm{K} $$ et $$ V_1 = 10\,\mathrm{L} $$ subit une expansion isotherme et réversible jusqu’à un volume de $$ V_2 = 20\,\mathrm{L} $$.  
1. Calculez le travail $$ W $$ reçu par le gaz.  
2. Calculez la quantité de chaleur $$ Q $$ échangée.  
3. Calculez la variation d’énergie interne $$ \Delta U $$.

---

**Correction :**

**1. Travail reçu**  
Pour une expansion isotherme réversible :
$$
W = nRT \ln\left(\frac{V_2}{V_1}\right)
$$
avec $$ n = 1 $$, $$ R = 8{,}314\,\mathrm{J/mol\,K} $$, $$ T = 300\,\mathrm{K} $$, $$ \frac{V_2}{V_1} = 2 $$:

$$
W = 1 \times 8{,}314 \times 300 \times \ln(2) \approx 2494 \times 0,693 \approx 1727\,\mathrm{J}
$$

**2. Chaleur échangée**  
Isotherme pour un gaz parfait : $$ \Delta U = 0 $$ donc $$ Q = W $$

Donc :  
$$
Q = 1727\,\mathrm{J}
$$

**3. Variation de l’énergie interne**  
Pour un gaz parfait, à température constante :
$$
\Delta U = n C_v \Delta T = 0
$$

---

## **Exercice 2 : Entropie lors d’un transfert de chaleur**

**Énoncé :**  
Un solide de chaleur massique $$ C = 500\,\mathrm{J/K} $$ est porté de $$ 300\,\mathrm{K} $$ à $$ 400\,\mathrm{K} $$ de façon réversible par contact avec des thermostats à température adéquate.  
Calculer la variation d’entropie du solide.

---

**Correction :**

Pour une transformation réversible à température variable :
$$
\Delta S = \int_{T_i}^{T_f} \frac{\delta Q_{\text{rev}}}{T} = \int_{T_i}^{T_f} \frac{C\, dT}{T} = C \ln\left(\frac{T_f}{T_i}\right)
$$

Avec $$ C = 500\,\mathrm{J/K} $$, $$ T_i = 300\,\mathrm{K} $$, $$ T_f = 400\,\mathrm{K} $$:

$$
\Delta S = 500 \times \ln\left(\frac{400}{300}\right) = 500 \times \ln\left(\frac{4}{3}\right) \approx 500 \times 0,2877 \approx 144\,\mathrm{J/K}
$$

---

## **Exercice 3 : Détente adiabatique d’un gaz parfait**

**Énoncé :**  
On considère 2 mol de gaz parfait diatomique ($$ C_v = \frac{5}{2}R $$, $$\gamma = 1{,}4$$), initialement à $$ T_1 = 400\,\mathrm{K} $$ et $$ V_1 = 5,0\,\mathrm{L} $$.  
Le gaz subit une détente adiabatique réversible jusqu’à $$ V_2 = 10,0\,\mathrm{L} $$.  
Trouver :  
1. La température finale $$ T_2 $$.  
2. Le travail fourni par le gaz.

---

**Correction :**

**1. Température finale**  
Dans une détente adiabatique réversible :
$$
T V^{\gamma-1} = \text{constante}
$$
Donc :
$$
\frac{T_2}{T_1} = \left( \frac{V_1}{V_2} \right)^{\gamma-1}
$$
$$
\frac{T_2}{400} = \left( \frac{5}{10} \right)^{0,4} = (0,5)^{0,4}
$$
Calculons $$ (0,5)^{0,4} $$:

$$
\ln(0,5) = -0,6931 \\
-0,6931 \times 0,4 = -0,2772 \\
e^{-0,2772} \approx 0,7577
$$
Donc :
$$
T_2 = 400 \times 0,7577 \approx 303\,\mathrm{K}
$$

**2. Travail fourni**  
Dans une adiabatique réversible pour un gaz parfait :
$$
W = n C_v (T_2 - T_1)
$$
Ici, $$ n = 2 $$, $$ C_v = \frac{5}{2} R $$, $$\Delta T = T_2 - T_1 = 303 - 400 = -97\,\mathrm{K}$$:

$$
W = 2 \times \frac{5}{2} \times 8,314 \times (-97)
$$
$$
= 5 \times 8,314 \times (-97) \\
= 41,57 \times (-97) = -4032\,\mathrm{J}
$$

Le travail $$ W $$ **fourni** par le gaz (travail reçu par l'extérieur négatif, donc le gaz a fourni $$ 4032\,\mathrm{J} $$ à l'extérieur).

---

## **Exercice 4 : Cycle de Carnot et rendement**

**Énoncé :**  
Une machine de Carnot fonctionne entre deux sources à $$ T_h = 500\,\mathrm{K} $$ et $$ T_c = 300\,\mathrm{K} $$.  
Elle reçoit $$ Q_h = 1200\,\mathrm{J} $$ de la source chaude à chaque cycle.  
1. Calculer le rendement et le travail fourni.  
2. Quelle est la chaleur rejetée à la source froide ?

---

**Correction :**

**1. Rendement et travail**

Rendement Carnot :
$$
\eta = 1 - \frac{T_c}{T_h} = 1 - \frac{300}{500} = 1 - 0,6 = 0,4 = 40\,\%
$$

Travail fourni par cycle :
$$
W = \eta Q_h = 0,4 \times 1200 = 480\,\mathrm{J}
$$

**2. Chaleur rejetée**

$$
Q_c = Q_h - W = 1200 - 480 = 720\,\mathrm{J}
$$

---

## **Exercice 5 : Variation d’entropie lors du mélange de deux corps**

**Énoncé :**  
On place en contact thermique un bloc de cuivre de **400 g** à **373 K** ($$c_{Cu} = 380\,\mathrm{J/kg\,K}$$) et un bloc identique à **273 K** dans un calorimètre isolé.  
1. Calculer la température d’équilibre finale.  
2. Calculer la variation totale d’entropie du système.

---

**Correction :**

**1. Température finale**

Le système est isolé : conservation de l'énergie. Masse $$m=0,4\,\mathrm{kg}$$.

Chaleur perdue = chaleur gagnée:
$$
m c (T_f - 273) + m c (T_f - 373) = 0
$$
$$
2 m c T_f - m c (273+373) = 0 \implies T_f = \frac{273+373}{2} = 323\,\mathrm{K}
$$

**2. Variation d’entropie**

Chaque bloc voit sa température changer à chaleur massique constante.

Pour le bloc chaud ($$ T_1 = 373 \to 323 $$):
$$
\Delta S_1 = m c \ln\left( \frac{323}{373} \right)
$$
Pour le bloc froid ($$ T_2 = 273 \to 323 $$):
$$
\Delta S_2 = m c \ln\left( \frac{323}{273} \right)
$$

Numériquement:
- $$ m c = 0,4 \times 380 = 152\,\mathrm{J/K} $$

Bloc chaud:
$$
\Delta S_1 = 152 \times \ln (323/373) = 152 \times \ln(0,866) = 152 \times (-0,144) = -21,9\,\mathrm{J/K}
$$

Bloc froid:
$$
\Delta S_2 = 152 \times \ln (323/273) = 152 \times \ln(1,183) = 152 \times 0,168 = +25,5\,\mathrm{J/K}
$$

Variation totale:
$$
\Delta S_{total} = -21,9 + 25,5 = +3,6\,\mathrm{J/K}
$$
L’entropie totale a augmenté : c’est conforme au second principe.

---

### **Tu peux demander des exercices sur un point précis, un type de transformation ou approfondir !**
Si tu veux d’autres exercices – points particuliers : machines réelles, cycles moteurs, irréversibilité, entropie de l’Univers, etc., n’hésite pas.
