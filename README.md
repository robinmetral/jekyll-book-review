# jekyll-book-review

Book reviews for your Jekyll site, built for Minima 📚

## In brief

The purpose of this project is to **provide Jekyll users with a simple, hackable book reviews template**.

It consists in two HTML layouts:

 - `_layouts/books.html` displays a list of book reviews beloning to a custom [Jekyll collection](https://jekyllrb.com/docs/collections/)
 - `_layouts/review.html` displays an individual book review with the book's cover, either self-hosted or imported through the [Open Library Covers API](https://openlibrary.org/dev/docs/api/covers)

It was developed for Minima (the Jekyll default theme) and can be set up on a site running Minima in minutes, but it can also be easily adapted to any theme.

## Don't tell me, show me

Okay, here's [the demo](https://robinmetral.github.io/jekyll-book-review/) (on an out-of-the-box Jekyll site running Minima).

**Books list:**

![jekyll-book-review books list](https://raw.githubusercontent.com/robinmetral/jekyll-book-review/master/examples/minima-books-list.png)

**Individual book review:**

![jekyll-book-review book review](https://raw.githubusercontent.com/robinmetral/jekyll-book-review/master/examples/minima-book-review.png)

## Installation

**Requirements**: a functional Jekyll site.

**Summary** (for the Minima theme)

 1. Set up a custom `books` [collection](https://jekyllrb.com/docs/collections/)
 2. Add the `books.html` and `review.html` layouts to your `_layout` directory
 3. Create a `books.md` page with the `books` layout
 4. Write book reviews with the `review` layout!

### 1. Set up a custom `books` collection

*(28.8.18: continuing tomorrow)*
