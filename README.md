# Hey there 👋 I'm Rahini

I work with data: BI, analytics engineering, performance dashboards, and NLP. This page is a tour of what I'm building now, followed by older projects.

## 🔭 What I'm building now

### 💶 [net-worth-engine](https://github.com/rahinic/net-worth-engine)
A synthetic-persona net worth simulation, built end to end with free tools.

- **Messy German bank exports**: a generator writes two realistic CSV exports (semicolons, ISO-8859-1, `1.234,56` amounts, duplicates, umlaut and spacing noise) along with an answer key.
- **dbt-core + DuckDB**: staging, intermediate and mart models clean the exports into one ledger and a monthly net worth timeline. Tests check the result against the answer key.
- **Monte Carlo**: 10,000 paths comparing a 2-ETF and a 4-ETF portfolio, with fund fees, German tax (Abgeltungsteuer, Teilfreistellung, Vorabpauschale) and random switching. Sensitivity runs show which assumptions drive the result.
- **Next**: Indian versus German gold comparison and dashboards.

`Python` · `DuckDB` · `dbt` · `GitHub Actions`

### 🍳 [kitchen-grimoire](https://github.com/rahinic/kitchen-grimoire)
My recipe site, with illustrated recipe leaflets and a green-witch, cottage-witch feel. It's built with Jekyll on GitHub Pages. Adding a recipe means uploading an image and one Markdown file, all from github.com.

`Jekyll` · `GitHub Pages` · `Liquid` · `CSS`

## 🗂️ Earlier projects

### Data acquisition
- [RSS Aggregator](https://github.com/rahinic/articles-aggregator-with-rss): newspaper feeds (e.g. CNN) in the terminal, and data science blogs (e.g. KDNuggets) in a Streamlit app.
- [Web Scraper](https://github.com/rahinic/news-article-web-scraper-py): scrapes the content of CNN news articles.

### Data analysis
- [Google Playstore Analysis](https://github.com/rahinic/googleplaystore_analysis): download statistics of paid vs free apps.

### Neural networks and NLP
Projects I built to learn PyTorch and neural networks for NLP.
- [PyTorch examples](https://github.com/rahinic/nn-pytorch-examples): DBPedia classifier and emotions classifier.
- [Syntax parsing with LSTMs](https://github.com/rahinic/syntax-parsing-lstm), [syntax trees](https://github.com/rahinic/syntax-tree) and [POS tagging](https://github.com/rahinic/WSJ-POS-tagger).

### Automations
- [BIO to BIOES tagger](https://github.com/rahinic/BIO-to-BIOES-tagger): converts the Begin-Inside-Outside tagging scheme to Begin-Intermediate-End-Other-Single for NLP.

## 🌐 Elsewhere
- Portfolio and journal: [rahinic.github.io](https://rahinic.github.io)
