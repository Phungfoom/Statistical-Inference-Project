# Research Questions

### Oumayma - Questions 2 & 4

### John - Questions 1 & 5

### Phung - Questions 3 & 7

### Thomas - Questions 6 & 8

### Statistical Inference Final — Variable Descriptions, Analysis Methods, and Hypotheses

| **\#** | **Research Question** | **Variables (Description)** | **Data Type** | **Planned Method of Analysis** | **Hypotheses (H₀ / Hₐ)** |
|:--:|:---|:---|:---|:---|:---|
| **1** | Does expiration length affect acceptance? | `expiration` (categorical: 1 day vs 2 hours); `acceptance` (binary: yes/no) | Two-level categorical predictor on binary response | **Bootstrap test** for difference in proportions between expiration groups | **H₀:** Mean acceptance is equal for 1-day and 2-hour coupons.<br>**Hₐ:** Mean acceptance differs between expiration lengths. |
| **2** | Does time of day relate to acceptance? | `time` (categorical: 5 levels — morning, afternoon, evening, late night, unknown); `acceptance` (binary) | Multi-level categorical on binary outcome | **One-way ANOVA** on mean acceptance rates by time of day | **H₀:** Mean acceptance is the same across all times of day.<br>**Hₐ:** At least one time-of-day group has a different mean acceptance. |
| **3** | Do travel time/direction costs matter? | Four binary predictors: `≥15 min`, `≥25 min`, `same direction`, `opposite direction` (1 = yes, 0 = no) | Multiple binary predictors | **Multiple bootstrap comparisons** or **two-way ANOVA** to test travel-cost effects | **H₀:** Travel time and direction have no effect on mean acceptance.<br>**Hₐ:** Travel time or direction significantly affect acceptance rates. |
| **4** | Is acceptance different by coupon type? | `coupon` (categorical: 4 levels — bar, coffee house, \<\$20 restaurant, \$20–\$50 restaurant); `acceptance` (binary) | Categorical predictor with four levels | **One-way ANOVA** on acceptance means by coupon category | **H₀:** Mean acceptance is equal across all coupon types.<br>**Hₐ:** At least one coupon type has a different mean acceptance. |
| **5** | Do past visit frequencies predict accepting the matching coupon type? | `coupon type` (4 levels) and visit-frequency columns for bar, coffee house, \<\$20 restaurant, \$20–\$50 restaurant (each 6 levels) | Multi-factor categorical predictors | **Two-way ANOVA** or **bootstrap comparison** of acceptance by frequency × coupon type | **H₀:** Visit frequency and coupon type have no effect on mean acceptance.<br>**Hₐ:** Visit frequency or coupon type significantly affect acceptance. |
| **6** | Does who’s in the car relate to acceptance? | `passenger` (categorical: 4 levels — alone, partner, friends, kids); `acceptance` (binary) | Multi-level categorical predictor | **One-way ANOVA** on mean acceptance across passenger groups | **H₀:** Mean acceptance is equal across all passenger groups.<br>**Hₐ:** At least one passenger group has a different mean acceptance. |
| **7** | Are there weather effects? | `weather` (3 values — sunny, rainy, snowy); `temperature` (3 values — cold, mild, hot) | Two categorical predictors | **Two-way ANOVA** for main and interaction effects of weather and temperature | **H₀:** Weather and temperature have no effect on acceptance (no main or interaction effects).<br>**Hₐ:** Weather or temperature significantly affect acceptance. |
| **8** | Do age or income bands relate to acceptance? | `age` (8 bands) and `income` (9 bands); `acceptance` (binary) | Multi-level categorical predictors | **Two-way ANOVA** comparing acceptance means across age × income groups | **H₀:** Age and income have no effect on mean acceptance.<br>.**Hₐ:** Age or income significantly affect acceptance rates. |
