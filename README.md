## Bertrand Wilden

Hello! 👋

Here you will find a collection of solo-authored data science projects I worked on during my PhD. For more on what I am working on currently, please check out my [blog](https://www.bwilden.com/blog)!

---

#### PhD Research Projects

- [**Mis-Measuring Measurement Model Measurement Error**](https://github.com/bwilden/bayes-measurement-error)
  - The common practice of only using the mean estimate from measurement model posteriors will lead to misleading conclusions in downstream analysis. I develop a method to ameleliorate bias arising from statistical uncertainty in measurement models. And I build a set of Bayesian models in Stan to fix this type of bias. [Full paper](https://github.com/bwilden/bayes-measurement-error/blob/main/paper.pdf).
- [**Ideal Point Estimation with 99% Missing Data**](https://github.com/bwilden/abstention-ideal)
  - Ideal point models are used in political science to estimate latent traits (such as left-right ideology) of political actors. I show how commonly-used methods dramatically fail under sparse data conditions. I then develop a new Bayesian ideal point model which treats missing data as an explicit choice made by political actors, and show how this model is able to accurately recover the true latent variables using simulation analysis. [Full Paper](https://github.com/bwilden/abstention-ideal/blob/main/paper.pdf).
- [**A Geospatial Model of Political Ideology in California**](https://github.com/bwilden/irt-mrp-bym)
  - In this project I estimate county-level political ideology in California using my novel IRT-MRP-BYM—*Item-Response-Theory, Multilevel-Regression-with-Poststratification, Besag-York-Mollié* model. I combine the latest research in survey methodology to arrive at more precise small-sample latent variable estimates using Stan. [Full Paper](https://github.com/bwilden/irt-mrp-bym/blob/main/paper.pdf).
- [**bper: Bayesian Prediction for Ethnicity and Race**](https://github.com/bwilden/bper)
  - An R package for imputing race/ethnicity variables based on other individual characteristics (name, location, gender, and more). This package uses a hand-coded Naive Bayes classification algorithm in R.


<!--
**bwilden/bwilden** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
