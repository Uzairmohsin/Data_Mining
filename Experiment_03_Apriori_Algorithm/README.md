# Apriori Algorithm

This experiment focuses on understanding the **Apriori Algorithm**, a fundamental data mining technique used for discovering frequent itemsets and generating association rules, commonly applied in Market Basket Analysis.

---

## Experiment Overview

- Studied the working of the Apriori Algorithm for frequent itemset generation
- Learned how frequent k-itemsets are generated using prior knowledge of (k−1)-itemsets
- Analyzed the importance of **joining and pruning** steps
- Understood the practical applications of Apriori in retail and healthcare

---

## Key Concepts Covered

### Apriori Algorithm
- Iterative generation of frequent itemsets (1-itemset, 2-itemset, 3-itemset, etc.)
- Uses prior knowledge of previously discovered frequent itemsets
- Efficient for discovering item associations in transactional databases

### Apriori Property
> *All non-empty subsets of a frequent itemset must also be frequent.*

This property helps reduce the search space by eliminating candidate itemsets that contain infrequent subsets.

---

## Joining and Pruning

- **Joining:** Combines frequent (k−1)-itemsets to generate k-itemset candidates
- **Pruning:** Removes candidate itemsets that contain infrequent subsets to reduce computation

---

## Limitations of Apriori

- Large number of candidate itemsets
- High computational cost due to repeated database scans

---

## Learning Outcome

- Gained understanding of frequent pattern mining
- Learned how Apriori optimizes search using pruning
- Understood real-world use cases of association rule mining

---

## Author
**Uzair Shaikh**
