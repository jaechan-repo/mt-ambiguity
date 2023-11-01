<!-- PROJECT LOGO -->
# Are Translation Systems Sensitive to Disambiguating Context?

<!-- TABLE OF CONTENTS -->
<!-- <details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details> -->

This repo contains the $\text{TIDE}$ dataset (a corpus of 512 contrastive idiom usage triples), the translations performed on $\text{TIDE}$ by automatic translation systems, and scripts used for evaluating the translation systems. For details, please refer to the paper: [PAPER](https://arxiv.org/abs/2310.14610).

<!-- ABOUT THE PROJECT -->
## About

The translation of ambiguous text presents a challenge for translation systems, as it requires using the surrounding context to disambiguate the intended meaning as much as possible. While prior work has studied ambiguities that result from different grammatical features of the source and target language, we study semantic ambiguities that exist in the source (English in this work) itself. In particular, we focus on idioms that are open to both literal and figurative interpretations (_e.g., goose egg_), and collect $\text{TIDE}$, a dataset of 512 pairs of English sentences. Each triple consists of an ambiguous subsentence and and a pair of contrastive sentences that contain the subsentence but add disambiguating context: one to produce a figurative interpretation of the idiom, and another to produce a literal interpretation of it.
