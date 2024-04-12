To illustrate that the differences are statistically significant, we provide exact values in Figure 5 below. An asterisk symbol (*) next to a data entry indicates a statistically significant difference between two consecutive data splits for a given metric, with the earlier split having the asterisk. It's important to note that the final row won't have an asterisk for any metric. Here are the detailed numbers for Figure 5(a):

| Data Split | NLL      | ROC AUC   | PR AUC   |
| --------   | -------- | --------  | -------- |
| 10         | 0.3816*  | 0.8461*   | 0.6471*  |
| 20         | 0.3951*  | 0.8391*   | 0.6442*  |
| 30         | 0.4153*  | 0.8205*   | 0.6198*  |
| 40         | 0.4167*  | 0.8186*   | 0.6165*  |
| 50         | 0.4171   | 0.8170    | 0.6118   |

This table indicates that all differences are statistically significant at the 0.05 level. Additionally, each metric shows a statistically significant trend: NLL increases (p-value = 0.0318), ROC AUC decreases (p-value = 0.0219), and PR AUC decreases (p-value = 0.0166).

Next, we present the numbers for Figure 5(b):

| Data Split | NLL      | ROC AUC   | PR AUC   |
| --------   | -------- | --------  | -------- |
| -50        | 0.4171*  | 0.8170*   | 0.6118*  |
| -40        | 0.4038*  | 0.8246*   | 0.6194*  |
| -30        | 0.4000*  | 0.8296*   | 0.6256*  |
| -20        | 0.3974*  | 0.8336*   | 0.6325*  |
| -10        | 0.3878   | 0.8426    | 0.6418   |

In this table as well, all differences are deemed statistically significant at the 0.05 level. For each metric, a statistically significant trend is observed: NLL decreases (p-value = 0.0083), while ROC AUC and PR AUC both increase (p-values of 0.0009 and 0.0001, respectively).
