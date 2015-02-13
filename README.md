GEOcrawler
==========

A web-crawler to retrieve information from GEO.

### What is for?

This repository includes a program for downloading and processing data from Gene Expression Omnibus (GEO). The results are in a table with meta-information characterizing all experiments included in a given study grom GEO.

For additional details chek out the [Wiki](https://github.com/mscastillo/GEOcrawler/wiki).

### Dependencies

All the files are downloaded from GEO using `wget`. Subsequently, they are converted to *unix* file-format using `dos2unix`. There is no additional dependencies apart from common text processing tools as: `cat`, `grep`, `wc`, etc...

### How do I get set up?

Clone this repository and update your path or symbolic links for quick access.

### How I use it?

Run `geocrawler` with the `-g` option to retrieve all the samples in a given series. For instances:

```bash
geocrawler -g GSE48086
```

For other options, type:

```bash
geocrawler --help
```


### Who do I talk to?

Sanchez-Castillo, Manuel
