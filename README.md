# Extending ggplot2 statistical geometries
Here, laying out some objectives for independent study, MA489!

### Build grammar of graphics knowledge and ggplot2 programming know-how

- learning more about ggplot2 architechture and extension capabilities
   - grammar of graphic and waves of data visualization https://www.youtube.com/watch?v=itChfcTx7ao
   - ggplot2 book: https://ggplot2.tidyverse.org/ 
   - Thomas Lin Peterson Talk: https://www.youtube.com/watch?v=uj7A3i2fi54
   - Hadley Wickham Vingette: https://cran.r-project.org/web/packages/ggplot2/vignettes/extending-ggplot2.html
   - A set of examples made for you:  https://github.com/EvaMaeRey/ggextend  (note to self: https://twitter.com/EvaMaeRey/status/1353526310283464705)
- writing useful functions for statistical education (and for practicianers!)
  - linear model diagnostics  
    - high leverage points
    - high influence points
    - cooks distance
  - other ideas:  http://www.rossmanchance.com/ISIapplets.html
- learning about package development and architecture

### Providing a *usable* set of functions in a package (ggxmean)
- https://evamaerey.github.io/ggxmean/, https://github.com/EvaMaeRey/ggxmean
- improving and standardizing documentation, examples
- submitting package to CRAN
- soliciting feedback from potential users, experts.  Usability survey... 

### Outreach and brand
- hex sticker? https://github.com/GuangchuangYu/hexSticker
- tutorials??
- presentations - https://evamaerey.github.io/ggxmean/talk_maa_metro_ny.html#1, USMA presentation opportunties ??
- paper - https://evamaerey.github.io/ggxmean/manuscript.pdf, journal target: https://www.tandfonline.com/toc/ujse20/current



---


Weeks 1-6:

## ggplo2 background

Watch https://www.youtube.com/watch?v=itChfcTx7ao and answer the questions:

- According to Meeks, what are halmarks of each of the three modern waves of data visualization?
- Wave does he think the grammar of graphics fits into?

Leland Wilkinson identified 7 components of a statistical graphic in his seminal work, *The Grammar of Graphics*.

![text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4P5ANBcXvQ61yA7ElksWqodnd77ZMPsBN7KJ0ALyHq0XYNAqqNVYR4SgmAvJ9PkIfUbg&usqp=CAU)

> The Grammar of Graphics, or GOG, denotes a system with seven orthogonal components. By orthogonal, we mean there are seven graphical component sets whose elements are aspects of the general system and that every combination of aspects in the product of all these sets is meaningful. This sense of the word orthogonality, a term used by computer designers to describe a combinatoric system of components or building blocks, is in some sense similar to the orthogonal factorial analysis of variance (ANOVA), where factors have levels and all possible combinations of levels exist in the ANOVA design. If we interpret each combination of features in a GOG system as a point in a network, then the world described by GOG is represented in a seven-dimensional rectangular lattice. - Wilkinson

What are the functions in ggplot2 that allow us to manipulate these components in an orthogonal, independnet way?

## Practice using ggplot2

In R:

https://www.jstor.org/stable/pdf/25651297.pdf?casa_token=hCG9IQPamPkAAAAA:gFU2VFRQujXKynq98zLzTUXuLQJzaEHYGhzZnhOZoPPlVB5LBdH-t0-7YtPBPwPePZivLr94EMXDY0pkq7j8VxrGognYIRV9P0yeFe_3YPx71KVmkQf2



