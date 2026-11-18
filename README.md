# Machine Learning Is Easy

Slides, notebooks and projects for the **Machine Learning Is Easy** YouTube series: a free, beginner-friendly course that takes you **from scratch to real projects**, using Python.

▶️ **Watch the series:** [YouTube playlist link](https://www.youtube.com/playlist?list=PLQdUQTNHcQY4)

---

## 📚 Episodes and projects

| # | Episode | Project | Notebook |
|---|---------|---------|----------|
| 1 | What is machine learning? | – | – |
| 2 | Python + your ML toolkit | First notebook with pandas | [`02-python-toolkit/`](02-python-toolkit/) |
| 3 | Your first ML model | **Dublin house prices** with linear regression | [`03-dublin-house-prices/`](03-dublin-house-prices/) |
| 4 | Predicting categories | **SMS spam filter** with logistic regression | [`04-sms-spam/`](04-sms-spam/) · [`04-mushrooms/`](04-mushrooms/) |
| 5 | Decision trees + random forests | **Obesity level** prediction | [`05-heart-disease/`](05-heart-disease/) |
| 6 | Collecting + labeling data | **Scraping** hockey teams and Oscar films, then labeling | [`06-scrape-this-site/`](06-scrape-this-site/) |
| 7 | Data cleaning + feature engineering | **Dublin Airbnb prices** | [`07-airbnb-dublin/`](07-airbnb-dublin/) |
| 8 | Model validation | *coming soon* | |
| 9 | Boosting + stacking | *coming soon* | |
| 10 | Hyperparameter tuning | *coming soon* | |
| 11 | Neural networks | *coming soon* | |
| 12 | CNNs + transfer learning | *coming soon* | |
| 13 | Explainability + fairness | *coming soon* | |
| 14 | Your first full project | *coming soon* | |
| 15 | Ship your model | *coming soon* | |

**Extra episodes (slides):** clustering, dimensionality reduction, pattern search, Apriori, Naive Bayes, k-nearest neighbors, a CNN deep dive, and RNNs. See [`slides/`](slides/).

---

## 🚀 Getting started

```bash
git clone https://github.com/sarinanemati/machine-learning-is-easy.git
cd machine-learning-is-easy

python -m venv ml-env
source ml-env/bin/activate        # Windows: ml-env\Scripts\activate

pip install -r requirements.txt
jupyter notebook
```

Open the folder of the episode you're watching, and run the notebook from top to bottom.

**Prefer not to install anything?** Open a notebook in Google Colab: `https://colab.research.google.com/github/sarinanemati/machine-learning-is-easy/blob/main/<path-to-notebook>.ipynb`. Notebooks that read a local data file (episodes 3, 5 and 7) need you to upload that file in Colab first.

---

## 📊 Data: where it comes from

Some notebooks download their data, others read a file you provide. Raw data is **not** stored in this repo. Please follow each dataset's license and credit its authors.

| Project | How the notebook gets its data | Source and license |
|---|---|---|
| Dublin house prices | Reads a local file | [source and license] |
| SMS spam | Downloads from UCI (or reads a local file) | Almeida, T. & Hidalgo, J. (2011). SMS Spam Collection, UCI Machine Learning Repository. [doi:10.24432/C5CC84](https://doi.org/10.24432/C5CC84). CC BY 4.0 |
| Obesity level | Reads **your Excel file** (set `EXCEL_PATH`) | [Janosi, A., Steinbrunn, W., Pfisterer, M. & Detrano, R. (1989). Heart Disease, UCI Machine Learning Repository. [doi:10.24432/C52P4X](https://doi.org/10.24432/C52P4X). CC BY 4.0](https://doi.org/10.24432/C5H31Z) |
| Scrape This Site | **Scrapes live** from [scrapethissite.com](https://www.scrapethissite.com/), a practice sandbox | Read the site's terms before running |
| Airbnb Dublin | Reads a local file (`listings.csv.gz`) | [Inside Airbnb](https://insideairbnb.com/get-the-data/). Check the site for the license |

---

## ⚠️ Please read

- **Scrape politely.** The scraping notebook checks `robots.txt` and waits between requests. Keep those safeguards if you adapt the code.
- Results depend on your data and library versions, so your numbers may differ from the videos.

---

## 🤝 Contributing

Found a bug or a typo? Open an issue or send a pull request. Ideas for future episodes are welcome too.

## 📄 License

Code is released under the MIT License. Datasets keep their original licenses.

## 📬 Contact

- YouTube: [[channel link](https://www.youtube.com/@buildwithsarina)]
- GitHub: [@sarinanemati](https://github.com/sarinanemati)

If this repo helped you, give it a ⭐ and subscribe to the channel!
