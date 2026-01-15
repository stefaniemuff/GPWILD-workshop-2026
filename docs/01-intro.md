# Introduction {#intro}


## What is Error?

In our interactions with applied scientists, we sometimes realized that ``error'' is either regarded as something systematic, in the sense of a bias, or as the result of an erroneous step during data collection, like writing down a wrong number into the lab journal. However, the measurement error that we are talking about in this book is something much more universal. It should me understood as an *uncertainty* of measurements, which, so some degree, is present in virtually all data. To paraphrase Max Planck (in *The Meaning and Limits of Exact Science*, 1949):

> Measurement error is an uncertainty in our recording of Nature’s answer to our questions

Measurement error is caused by in wide variety of reasons, such as

* Measurement *imprecision* in the field or the lab, which may arise due to limited accuracy of an instrument, or because the targeted value is difficult to measure or volatile, for example blood pressure, body weight etc.
* *Incomplete* or *biased* observations, for example due to preferential sampling.
* Misclassification of categorical variables.
* Misassigned paternities in pedigrees.
* Rounding or digit preference.
* Temporal or spatial misalignments of observations, e.g. in interval samples GPS observations of telemetry studies.

This is of course by no means a comprehensive list, and we are sure many readers could immediately come up with more examples. We put on the record that measurement errors should not, in generaly, merely be seen as `mistakes', but as uncertainty that is inherently present due to the limitations of how we collect information in the real world. 


## Why and When do I Have to Worry?

An important question, and one that is central to this book, concerns the effect measurement error in the data, given that the aim is to estimate the parameters of a model. Measurement error has essentialy three effects, which @carroll.etal2006 denote as the **Triple Whammy of Measurement Error**:

* Parameter estimators of statistical models are biased.
* It leads to loss of statistical power to detect relationships.
* Features of the data are masked in graphical analyses.

To be illustrated with simple and/or real examples for classical measurement error, with reference to Section \@ref(sec:errortypescl).

Further points

### When is Error a Problem?


```r
x <- rnorm(100)
```

### Bias Versus Variance 

Todo: Look at bias vs variance part in Carroll book, but then point out that the (typically) larger variance is also the more *honest* estimate, because error obscures information, and by ignoring it we pretend to be more certain about a (potentially biased) estimate than we really are.

### Is it sometimes better not to model the error?




It is surprising how many phenomena in statistics and its applications can be viewed through the measurement error lens. A prominant example is the concept of heritability in genetics and evolutionary biology, as we will explain in Section \@ref(sec:heritability).

## Organization and Take-Home Messages of This Book

* How the book is organized
* Examples and R code (how will it be made available?)
* What we are going to do, outlook to chapters.

 

