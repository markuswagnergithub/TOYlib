# TOYlib

## First dataset: Kinder Surprise 2019

Kinder Surprise are chocolate eggs that house a small toy. Fans of the toys across the world are collecting and trading these toys, with some toys being very rare and highly priced.

We present and publish a dataset that was extracted from the German Kinder Surprise pricing guide for 2019 - with kind approval of the publisher. The dataset contains prices and photos of 187 sets of figurines produced between 1979 and 2018. In total 2366 items are included.

In addition to a characterisation of the dataset, we provide a few first ideas for using this data as a benchmark dataset.

For us as researchers, the appeal of the figurines is manifold:
- For each figurine, the data set provides an anonymised name, a price and a set identifier. This enables the use in set-based and graph-based problems.
- For each item in the catalog, we include at least one low-resolution photo. This allows us to consider aspects such as shapes and brightness into complex fitness functions. 
- Lastly, quite of few of us can relate to small collectible items, independent of whether these are toys, postal stamps, trading cards, or others.

The subfolder https://github.com/markuswagnergithub/TOYlib/tree/master/KinderSurprise2019 contains a technical report, the data in CSV format, a subfolder with images, and a Python Jupyter Notebook the demonstrate the use with Gurobi.

# Citation

If you'd like to use this, please go ahead!

Please cite this collection in the following way:

```
@misc{toylib,
  author =	{Markus Wagner},
  title =	{{TOYlib - A Library of Real-World Toy Problems}},
  year = 	"2019",
  howpublished = {\url{https://github.com/markuswagnergithub/TOYlib}},
}
```

If you have any questions, please contact me: markus.wagner'@'adelaide.edu.au
