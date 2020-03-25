---
toc: true
layout: post
image: images/dealing-with-legacy-code.jpg
description: Dealing with Legacy Code.
categories: [Legacy Code]
title: Dealing with Legacy Code
---

Our life as developers' would be easy if we write only new code.No bug fixing or editing yesterday code It\'d be pretty nice, right?

### Definition of Legacy code 
 ![ Legacy code]({{ site.baseurl }}/images/dealing-with-legacy-code.jpg)
 
 Legacy code was defined in many ways and there is no common definition to it even in [wikipedia](https://en.wikipedia.org/wiki/Legacy_code), may by.  
 - Code that\'s part of an older version of the software.  
 - Code that relates to a no-longer supported hardware or software dependency.  
 - Code inherited from someone else.  
 - Code that isn\'t covered by automated unit tests.
 
 To me, legacy code simply codes without tests. ~ Michael Feathers
 
 Well, that is the first formal definition of the expression legacy code, published by Michael Feathers in his book [Working Effectively with Legacy Code](http://www.goodreads.com/book/show/44919.Working_Effectively_with_Legacy_Code). it seems that the Legacy code is "Difficult to change" but the term "Difficult to change" is so vague and we need a solution. But guess it mostly like this picture when refactoring legacy code.[![Refactoring legacy code](https://media.giphy.com/media/3o7ZeMt2xX1zGRDffa/giphy.gif)](https://media.giphy.com/media/3o7ZeMt2xX1zGRDffa/giphy.gif)
 
 Refactoring legacy code 

 ### Defensive strategies.
 
 1. Be conventional.

  Following standards and language conventions make code easy to work with.
 
 2. Code review.


 We took about it in the previous post but talk to your peer about code you wrote to make it more readable.

 ### Working strategies.

- **Don't make it personal** 

We always think it\'s faster to rewrite it from scratch than try to understand what other developers did.Please, don't judge other developers and speak badly about code even it worst code you ever have seen.

 -  **Testing**
 
 Automated unit tests will give developer understanding about key things: dependencies this piece of code has, input data, output results, boundary conditions so on. From here you can walk in the minefield.
 
 - **Start small**


 It always seems like a disaster at first, Fear is your worst enemy in facing legacy code. You must start from somewhere. Small bug fixes or even change variable names that make code more meaningful that makes working with old code infinitely easier.  
 
 - **Make your checklist**
 
  Checklists it underestimated but guess what it works all the time make your checklist, "Identify changes, find test points, break dependencies, write test, make a change and refactor.  
 
 Image sources
 [Photo courtesy of Pascal](https://www.flickr.com/photos/pasukaru76/9824401426/in/photolist-9DE7Wa-cd6Wxf-bW4iP-okpdNP-6TfKoP-fY9Cgu-EmbdC-7vgLWL-a5sj6k-6w5kAz-3SUkNL-878gAY-8vs4F6-i9E5k-2ybfXd-9dDY7N-4uNsCX-7iuh42-4jYxpy-9mn5PK-axFsZL-fMEpmV-koVXTM-aB4Vgf-e88nnZ-cu4nm3-pybGg-bF1XGL-4pAwWe-6cyxFq-7zWj8-eewWz-77os7A-4EjNgb-o4yuXd-e69XkS-6KipNW-7rsJvY-mdXYRC-dVJKrK-jN6RPH-8W5ooc-8TpRWe-6Qfw98-244wv2-f4PmxD-3NdDg2-5FrHwc-79taKi-4kQjJu/).