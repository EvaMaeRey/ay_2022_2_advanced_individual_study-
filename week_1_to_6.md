



# Weeks 1-6:

## Task 0. Sign up for github account

Try editing this file; maybe fix a typo.  It is version control system so there are some steps. We can do together.  

## Task 1. ggplot2 background and theory

Watch https://www.youtube.com/watch?v=itChfcTx7ao and **answer the questions** (send to me in an email):

- According to Meeks, what are halmarks of each of the three modern waves of data visualization?
- Wave does he think the grammar of graphics fits into?

Leland Wilkinson identified 7 components of a statistical graphic in his seminal work, *The Grammar of Graphics*.

![Cover of Wilkinson's 1999 book](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4P5ANBcXvQ61yA7ElksWqodnd77ZMPsBN7KJ0ALyHq0XYNAqqNVYR4SgmAvJ9PkIfUbg&usqp=CAU)

> The Grammar of Graphics, or GOG, denotes a system with seven orthogonal components. By orthogonal, we mean there are seven graphical component sets whose elements are aspects of the general system and that every combination of aspects in the product of all these sets is meaningful. This sense of the word orthogonality, a term used by computer designers to describe a combinatoric system of components or building blocks, is in some sense similar to the orthogonal factorial analysis of variance (ANOVA), where factors have levels and all possible combinations of levels exist in the ANOVA design. If we interpret each combination of features in a GOG system as a point in a network, then the world described by GOG is represented in a seven-dimensional rectangular lattice. - Wilkinson

![A visual of the seven orthogonal components](https://miro.medium.com/max/1838/1*MMZuYgeC_YjXNC1r4D4sog.png)

ggplot2 allow us to manipulate these components in an orthogonal, independnet way.  Separating our decisions with a plus sign, "+".  **Answer the question - send in an email**: 

*Which ggplot2 function do you think allows analysts to make decisions about each of the seven components?*  See the 'how' column: 	https://evamaerey.github.io/ggplot2_grammar_guide/about

## Task 2. Practice using ggplot2

In R select a dataset by typing `data()` in the R console.  

Select one of the *Data sets in package ‘datasets’:*

Learn more about the data by using question mark before the dataset name, for example: `?AirPassengers` in the R console.

Have a look at the data itself, for example type `AirPassengers` and execute in the R console

Sketch out on paper the visualization you'd like to create with the data... What visual aesthetic will represent each variable?

![](https://clauswilke.com/dataviz/aesthetic_mapping_files/figure-html/common-aesthetics-1.png)

Attempt to build your plot.  For each decision, use a new line of code.  Be prepared to talk about your decisions, we'll use the app:  https://sjspielman.shinyapps.io/line_by_line/.

Morgan plot 1:

``` r

```

Morgan plot 2:

``` r

```

Morgan plot 3:

``` r

```


Madison plot 1:

``` r

```

Madison plot 2:

``` r

```

Madison plot 3:

``` r

```

## Task 3. User defined functions in R

Using functions in R lets us lighten our work.  We can bundle up an idea that has several component steps as a single task. 

Take a simple example -- finding the mean.  

We can do this as follows:

``` r
sum(1:10)/length(1:10)
sum(c(2,3,6))/length(c(2,3,6))
```

And it is good to do this a few times, to make sure we have a clear understanding of taking the mean.  But after a while, we may get tired of the computation.  We are confident of our understanding of the mean.  And other's understanding.  A single function call would be sufficient.  

Here's an example of writing a function:

``` r
my_mean <- function(x){

sum(x)/length(x)

}
```

Now **watch** this introduction to writing functions in R:  https://www.youtube.com/watch?v=u-gSj9J2wRA&t=31s

**Report one of the functions Roger Peng writes in the tutorial:**

Morgan:

``` r


```

Madison 

``` r


```


**Now write two of your own functions.**

Morgan:

``` r


```

Madison 

``` r


```

## Task 4. Model diognostics (maybe a bit more together)...

- https://joshualoftus.com/posts/2020-11-23-least-squares-as-springs/
- https://www.maths.usyd.edu.au/u/UG/SM/STAT3022/r/current/Lecture/lecture08_2020JC.html#7
- https://www.stat.berkeley.edu/~spector/s133/Lr1.html
