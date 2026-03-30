**Market Basket Analysis & Promotional Strategy Engine:** A data science project built on the Kaggle Market Basket Optimisation dataset (7,500 transactions) that combines Python-based association rule mining with an interactive Plotly network graph to uncover hidden product relationships and translate them into actionable retail strategies.

**What it does?** Discovers which products are frequently bought together using the Apriori algorithm Ranks product associations by support, confidence, and lift to surface the strongest rules Identifies hook products that drive cross-category purchases Recommends optimal product placement based on association strength Suggests promotional bundles pairing high-traffic products with slow-moving inventory Visualizes the entire product relationship network as an interactive graph

**Stack Layer Tools:** Data Processing Python, Pandas Association Rule Mining MLxtend (Apriori, TransactionEncoder) Visualization Plotly, NetworkX

**Key Metrics:** Support Confidence Lift Antecedent Support Consequent Support

**Top Associations:** Herb & Pepper → Ground Beef (Lift 3.29) Mineral Water & Ground Beef → Spaghetti (Lift 2.39) Soup → Milk (Lift 2.32) Ground Beef → Spaghetti (Lift 2.29) Olive Oil → Spaghetti (Lift 2.00)

**Business Recommendations:
Product Placement:**
1. Place herb & pepper adjacent to ground beef
2. Create an Italian meals section grouping spaghetti, ground beef, olive oil and red wine together
3. Position mineral water prominently as it drives cross-category purchases

**Promotional Bundling:** Bundle high-traffic products like mineral water and eggs with slower moving items like cereals and turkey to drive stock clearance


**Dataset Link:** https://www.kaggle.com/datasets/rupakroy/market-basket-optimization
