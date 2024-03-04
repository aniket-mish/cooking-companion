# Stacked

![](assets/food-banner.jpg)

## Introduction

Stacked is a side project that I am working on. It's an app that recommends recipes (vibe-search). I always struggle to find something to cook. Stacked is a semantic search engine.

[Vicki boykis](https://vickiboykis.com/2024/01/05/retro-on-viberary/) and [Simon willison](https://simonwillison.net/2023/Jan/13/semantic-search-answers/) inspired me to build this project. They used the exact same term i.e. vibe search. I am building it to solidify my understanding of a production-grade system. I aim to build it end to end with minimal and clean code.

What I want here is semantic search - we want to find the recipes that match the meaning of the user's search term, even if the matching keywords are not present. With this functionality, we will be able to search our database for "a french onion appetizer" and get back highly useful results. This is an odd looking search query but semantic search just gets what we mean.


## Setup

In this project, I will build a transformer-based machine learning search system.


## Architecture


## Training Data

The recipes data comes from [RecipeNLG](https://recipenlg.cs.put.poznan.pl) - a dataset of cooking recipes. The dataset has >2 million cooking recipes.


## Model


## Indexing


## Lookup


## UI


## Production


## Citations

```bibtex
@inproceedings{bien-etal-2020-recipenlg,
    title = "{R}ecipe{NLG}: A Cooking Recipes Dataset for Semi-Structured Text Generation",
    author = "Bie{\'n}, Micha{\l}  and
      Gilski, Micha{\l}  and
      Maciejewska, Martyna  and
      Taisner, Wojciech  and
      Wisniewski, Dawid  and
      Lawrynowicz, Agnieszka",
    booktitle = "Proceedings of the 13th International Conference on Natural Language Generation",
    month = dec,
    year = "2020",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.inlg-1.4",
    pages = "22--28",
}
```

## Resources

[1] [http://viberary.pizza/how](https://vickiboykis.com/2024/01/05/retro-on-viberary/)

[2] [Implement Semantic Search using Datasette](https://github.com/josephrmartinez/recipe-dataset/blob/main/tutorial.md)
