<div align="center">

# Karan Homayounfar

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=15&duration=3200&pause=900&color=38BDF8&center=true&vCenter=true&width=560&lines=GB+energy+forecasting+%C2%B7+time-series+ML;Open+to+sponsored+graduate+roles;MSc+Data+Science+%C2%B7+UWE+Bristol" alt="Typing headline" />

</div>

---

MSc Data Science at UWE Bristol, working on GB electricity market forecasting with Python, C++ and SQL. BSc Computer Engineering, 1st in class (GPA 18.87/20).

Portfolio: [knhnf.com](https://knhnf.com)

## Energy and trading systems

- MSc dissertation (repository private until assessed): forecasting the official NESO daily GB balancing cost one day ahead, using only data published before the delivery day. A Ridge model is tested against simple baselines with a fixed-b Diebold-Mariano test, and every forecast is saved with a timestamp before delivery. Due January 2027.
- [GB energy forecasting reproductions](https://github.com/KNHNF/gb-energy-forecasting-reproductions): rebuilds three published GB balancing-market forecasting studies on real data. Only the Lucas MAE on its original window matched the paper; the other reproduced results were worse.
- [GB BM data](https://github.com/KNHNF/gb-bm-data): typed Python clients for Elexon BMRS, NESO and Carbon Intensity data. It raises an error on the three BMRS endpoints that ignore historical date parameters, instead of returning misdated data.
- [C++ order book simulator](https://github.com/KNHNF/cpp-order-book-simulator): price-time-priority matching, cancellation, invariant tests and seeded workloads. A single-threaded local benchmark measured median throughput from 3.36 to 5.45 million synthetic events per second.

## Data and machine learning

- [England crime and deprivation analysis](https://github.com/KNHNF/england-crime-deprivation-analysis): Spark pipeline over 17.8 million police records. It found a 4.8 times crime-rate gap across deprivation deciles and identified Greater Manchester as missing data rather than a low-crime result.
- [EPC retrofit potential](https://github.com/KNHNF/epc-retrofit-potential-ml): compares four classifiers under nested cross-validation and a temporal holdout. Random Forest reached 0.9721 ROC-AUC and 0.8423 macro F1 on the held-out period.

## Tools

Python, C++, SQL, Apache Spark, scikit-learn, XGBoost, pandas, FastAPI, MongoDB and GitHub Actions.

[LinkedIn](https://linkedin.com/in/karan-homayounfar) | [Email](mailto:karanhomayounfar2@gmail.com) | [knhnf.com](https://knhnf.com)
