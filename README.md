# SAS for Finance
This is the code repository for [SAS for Finance](https://www.packtpub.com/big-data-and-business-intelligence/sas-finance?utm_source=github&utm_medium=repository&utm_campaign=9781788624565), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
SAS is a groundbreaking tool for advanced predictive and statistical analytics used by top banks and financial corporations to find insights from their financial data.

SAS for Finance offers you the opportunity to leverage the power of SAS analytics in redefining your data. Packed with real-world examples from leading financial institutions, the author discusses statistical models using time series data to solve business solutions. This book shows you how to exploit the capabilities of this high-powered package to create clean, accurate financial models. You can easily assess the pros and cons of models to suit your unique business needs.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

Chapter 1 and 6 does not contain code files as they are theoretical chapters

The code will look like the following:
```
data matrix (drop = lhand1 lhand2);
set stage2 (drop = id);
if product1 ne product2;
if product1 ne product3;
if product2 ne product3;
combo=compress(product1||product2||product3);
lhand1=scan(combo,1);
lhand2=scan(combo,2);
lhand=compress(lhand1||"|"||lhand2);
run;
```

Basic knowledge of undergraduate-level mathematics is necessary. However, no advanced mathematical degree is required to decipher how the financial industry uses time series modeling to solve problems. Functional knowledge of SAS is desirable but isn't mandatory.
SAS University Edition is free software that is used throughout the book. Download details can be found at (https://www.sas.com/en_gb/software/university-edition.html).

## Related Products
* [Machine Learning for Finance](https://www.packtpub.com/big-data-and-business-intelligence/machine-learning-finance?utm_source=github&utm_medium=repository&utm_campaign=9781789136364)

* [Big Data Analytics with SAS](https://www.packtpub.com/big-data-and-business-intelligence/big-data-analytics-sas?utm_source=github&utm_medium=repository&utm_campaign=9781788290906)

* [IBM SPSS Modeler Essentials](https://www.packtpub.com/big-data-and-business-intelligence/ibm-spss-modeler-essentials?utm_source=github&utm_medium=repository&utm_campaign=9781788291118)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
