Module 12 - R Markdown
================

RMarkdown
---------

I have used R Markdown ever since the first day I started using RStudio and I much prefer it over the regular R console. I find it much more intuitive as well as organized and it makes creating neat documents with text and descriptions very easy and have used it for every assignment I have submitted thus far. I even use it for papers for non-R related classes such as for a paper in a writing class.

There are a ton of different formatting and output options in R Markdown such as *italics*, **bold**

Different
=========

Heading
-------

### Styles

[Embedded Links](www.google.com) and

![images](https://i.gyazo.com/75dd5197915af5dc9174dd5b24fed389.png)

And of course the ability to insert code and either hide the code itself, the output, both or neither through the parameters of the chunk.

``` r
str(mtcars)
```

    ## 'data.frame':    32 obs. of  11 variables:
    ##  $ mpg : num  21 21 22.8 21.4 18.7 18.1 14.3 24.4 22.8 19.2 ...
    ##  $ cyl : num  6 6 4 6 8 6 8 4 4 6 ...
    ##  $ disp: num  160 160 108 258 360 ...
    ##  $ hp  : num  110 110 93 110 175 105 245 62 95 123 ...
    ##  $ drat: num  3.9 3.9 3.85 3.08 3.15 2.76 3.21 3.69 3.92 3.92 ...
    ##  $ wt  : num  2.62 2.88 2.32 3.21 3.44 ...
    ##  $ qsec: num  16.5 17 18.6 19.4 17 ...
    ##  $ vs  : num  0 0 1 1 0 1 0 1 1 1 ...
    ##  $ am  : num  1 1 1 0 0 0 0 0 0 0 ...
    ##  $ gear: num  4 4 4 3 3 3 3 4 4 4 ...
    ##  $ carb: num  4 4 1 1 2 1 4 2 2 4 ...

It also knits the documents in a neatly organized PDF, HTML or other downloadable templates such as APA format or as a GitHub export.

There are countless ways to modify a document in RMarkdown but its flexibility and intuitiveness lets it create nearly any formatted document that you could imagine.
