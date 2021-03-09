# Assignment 7 
## Exploring R Packages

## Package title
The package is called {unmarked}: Models for Data from Unmarked Animals. 

## Location
You can install {unmarked} through [GitHub](https://github.com/rbchan/unmarked) or [CRAN](https://cran.r-project.org/web/packages/unmarked/index.html).

## Vignettes
This package has 5 vignettes available for users.

* `cap-recap` covers capture-recapture methods.
* `coltext` covers dynamic occupancy models.
* `distsamp` covers distance sampling analysis.
* `spp-dist` covers species distributions.
* `unmarked` is an overview of the whole package. 

## Application(s)
I'm not sure if this is specifically talking about web applications (?) but I couldn't find any.

## Review

This package is used for statistical modeling; specifically, this package fits models for data from non-invasive survey methods. With this package, you can build single- and multi-season occupancy models, binomial N-mixture models, multinomial N-mixture models, and several other types of models. I am only familiar with the single- and multi- season occupancy models, and have found the package relatively easy to use in conjunction with occupancy model literature and reading papers using this specific package. The package uses an S4 class called an `unmarkedFrame` to store covariate and response data as well as metadata. The user reads in their data and calls the specific type of `unmarkedFrame` based on the model-fitting function they are using, then the `unmarkedFrame` is passed to the appropriate estimation function. I would recommend it to those looking to run  single-species models with camera trap data that account for imperfect detection (i.e. occupancy models). I haven't yet used it or other occupancy modeling packages/methods enough to know what I would like it to do differently yet. 
