# 🏦 Simulateur d'Emprunt Bancaire & Tableau d'Amortissement

Une application web simple, rapide et interactive pour simuler vos crédits (immobiliers ou à la consommation) et visualiser précisément l'échéancier de remboursement.

---

## 🌟 Fonctionnalités

- 📊 **Calculs instantanés** : Mensualités, coût total des intérêts et montant global du prêt.
- 📉 **Graphique dynamique** : Ventilation visuelle entre Capital, Intérêts et Assurance.
- 📅 **Tableau d'amortissement** : Détail mois par mois (capital amorti, intérêts payés, assurance, capital restant).
- 📥 **Export CSV** : Téléchargement du tableau d'amortissement compatible Excel / Google Sheets.
- 📱 **Interface responsive** : Thème sombre moderne optimisé pour mobile et ordinateur.

---

## 🧮 Formule appliquée

La mensualité constante $M$ est calculée selon la formule standard :

$$M = Z \cdot \frac{r(1 + r)^n}{(1 + r)^n - 1}$$

- **Z** : Capital emprunté (€)
- **r** : Taux mensuel ($\text{taux annuel } / 12 / 100$)
- **n** : Durée totale en mois ($\text{années } \times 12$)

---

## 🛠️ Technologies utilisées

- **HTML5 / CSS3** (Design responsive en Dark Mode)
- **JavaScript ES6+** (Calculs et manipulation du DOM)
- **Chart.js** (Rendu graphique interactif)

---

## 🚀 Utilisation hors ligne & GitHub Pages

Cette application ne nécessite aucun serveur ou base de données. Elle s'exécute directement dans votre navigateur et peut être hébergée gratuitement via **GitHub Pages**.
# simulateur-credit
