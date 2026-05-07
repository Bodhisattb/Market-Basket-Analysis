# Market Basket Analysis using Apriori Algorithm

## 📌 Overview
This project performs **Market Basket Analysis** on synthetically generated grocery transaction data using the **Apriori Algorithm** implemented from scratch in Python. The goal is to discover **association rules** — patterns of items that customers frequently buy together.

---

## 📂 Dataset
- **Source:** Synthetically generated (no external dataset required)
- **Transactions:** 2,000 grocery shopping baskets
- **Products:** 25 grocery items (Bread, Milk, Coffee, Rice, etc.)
- **Design:** Affinity groups are used to simulate realistic co-purchase behaviour

---

## 🛠️ Libraries Used
- `pandas` — data handling
- `numpy` — numerical operations
- `matplotlib` — data visualization
- `seaborn` — statistical plots
- `itertools` — generating item combinations

---

## 🔢 Algorithm
The Apriori algorithm works in 3 steps:
1. Find all **frequent itemsets** whose support ≥ minimum threshold
2. Use the **Apriori property** to prune infrequent candidates
3. Generate **association rules** filtered by confidence and lift

### Thresholds Used
| Parameter | Value |
|-----------|-------|
| Min Support | 0.05 (5%) |
| Min Confidence | 0.30 (30%) |
| Min Lift | 1.20 |

---

## 📊 Visualizations
- Item frequency bar chart
- Basket size distribution
- Support vs Confidence scatter plot (coloured by Lift)
- Top 15 rules by Lift (horizontal bar chart)
- Pairwise item support heatmap
- Confidence vs Lift bubble chart

---

## 📈 Key Results
| Rule | Confidence | Lift |
|------|-----------|------|
| Rice → Vegetables | 0.40 | 2.21 |
| Coffee, Sugar → Milk | 0.59 | 2.03 |
| Jam → Bread | 0.37 | 1.98 |
| Chocolate, Biscuits → Ice Cream | 0.38 | 1.90 |

---

## 💡 Business Recommendations
1. **Store Layout** — Place associated items near each other (Rice next to Vegetables)
2. **Bundle Offers** — Create combo deals for high-lift pairs (Coffee + Sugar + Milk)
3. **Recommendation Engine** — Use rules to suggest products at checkout
4. **Inventory Planning** — Stock high-lift pairs together to avoid shelf-outs

---

## 🚀 How to Run
1. Clone or download the repository
2. Open `Apriori_Market_Basket_Analysis.ipynb` in Jupyter Notebook
3. Run All Cells (`Kernel → Restart & Run All`)
4. No external dataset needed — data is generated automatically

---

## 👤 Author
**BODHISATTB**
B.Tech CSE(A.I) 

