---
layout: post
title: "Word Embeddings"
categories: nlp
author: "Trung H. Le"
meta: "Springfield"
---

In order for the computer to understand and process information from the real world, that information must be represented in numbers. In fields such as computer vision, speech processing, etc. Data can be easily represented in their original form since almost all of these data types are real numbers (pixels, histogram of sound). In Natural Language Processing (NLP), it's difficult to represent words in the computer. For example, words like "I", "you", "learn", etc. are written in a natural language that the computer can not understand. How to represent natural language in a computer is one of the most important problems in the field of natural language processing that needs to be addressed. The numerical representation of the words in the computer is called _word representation_.

The simplest way to represent words is to number the words. To do this, we first need a set of vocabulary that is used to solve a problem. This set of vocabulary will be kept at a fixed size during the problem solving process. For example, we choose top $50000$ most frequently words from the corpus as the vocabulary set $V$. For each word in the set, we give it a number which is it's index in the vocabulary, such as "apple" = 0, "buffalo" = 1, ..., "zoo" = 49999. However, this does not entirely reflect the meaning of the word. It even made the machine misread because of this representation. Words with greater value (larger index) are either more or less important, which is not true. To avoid misleading


## Another great heading (h2)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce bibendum neque eget nunc mattis eu sollicitudin enim tincidunt. Vestibulum lacus tortor, ultricies id dignissim ac, bibendum in velit.

### Some great subheading (h3)

Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum. In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum.

Phasellus et hendrerit mauris. Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc.

### Some great subheading (h3)

Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

> This quote will change your life. It will reveal the secrets of the universe, and all the wonders of humanity. Don't misuse it.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce bibendum neque eget nunc mattis eu sollicitudin enim tincidunt.

### Some great subheading (h3)

Vestibulum lacus tortor, ultricies id dignissim ac, bibendum in velit. Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum.

``` html
<html>
  <head>
  </head>
  <body>
    <p>Hello, World!</p>
  </body>
</html>
```


In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

#### You might want a sub-subheading (h4)

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

#### But it's probably overkill (h4)

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

### Oh hai, an unordered list!!

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

- First item, yo
- Second item, dawg
- Third item, what what?!
- Fourth item, fo sheezy my neezy

### Oh hai, an ordered list!!

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

1. First item, yo
2. Second item, dawg
3. Third item, what what?!
4. Fourth item, fo sheezy my neezy



## Headings are cool! (h2)

Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc. Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc.
