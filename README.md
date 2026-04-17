# eLab-Business-Case-II
Data engineering - All team members will implement data parsing individually, while 1–2 members coordinate consistency and review outputs across the team.

1.⁠ ⁠EDA – Basket analysis (2 people - Elizaveta & Beliz)

Beliz: basket size and total value
•⁠  ⁠distribution:
    * number of items
    * total price
Questions:
•⁠  ⁠what is a normal basket size?
•⁠  ⁠what is a normal spending range?

Elizaveta: time behavior (scan time, speed)
•⁠  ⁠distribution:
    * total scan time
    * average time per item in one transaction 
Questions:
•⁠  ⁠how fast do people scan?
•⁠  ⁠is there a normal speed range?

Goal: define typical customer behavior.

2.⁠ ⁠EDA – Product & Pattern Analysis (Niklas & Nicola)
Niklas: frequent departments
•⁠  ⁠most frequent departments
•⁠  ⁠% share
e.g.:
•⁠  ⁠Dairy & Eggs appears in 70% of baskets

Nicola: co-occurrence patterns
•⁠  ⁠co-occurrence:
    * which departments appear together
 e.g.:
•⁠  ⁠Fruit & Vegetables + Dairy often together

Goal: identify common purchasing patterns.

3.⁠ ⁠EDA – Anomaly Exploration (Tristan & Hannes)
Tristan: price-based anomalies
•⁠  ⁠very low / very high total price
•⁠  ⁠expensive items in small baskets

Hannes: time-based anomalies
•⁠  ⁠extremely fast scanning
•⁠  ⁠extremely slow scanning

    Goal: identify unusual transactions.
