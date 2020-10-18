# Compuneers

**Compuneers** ("Computer" + "Pioneers") is a project designed to highlight the unsung contributions of women, BIPOC, and/or LGBT+ figures to the field of Computer Science. Each figure is featured in their own post on the [Compuneers site](#), and indexed in the [Figure List](#).

## Contributing

Contributions are welcome, encouraged, and needed! There are so many people who's stories need to be told; please consider joining in by writing a post for a figure or tackling an issue in the codebase.

### Figure Post

You can choose a figure from the established [Figure List](#), or [open an issue to add a figure to write about](#), as long as the following criteria are met:

- Figure should identify as a woman, person of color, and/or LGBT+. This rule is very flexible, but keep in mind the project is specifically meant to lift up overlooked figures in Computer Science.
- Figure will have worked in or contributed to the general field of Computer Science.
- There should be credible sources (preferably two separate sources) linked to or cited in your post.
- Adheres to the project's [Style Guide](#style-guide) and [Contributing Guidelines](#)

### Style Guide

When writing a figure post, please do not just copy and paste information from source material—posts about these important figures should be somewhat in your own words (though it's fine if you want to quote liberally, just include sources). Posts should follow the [Post Template](#) format that includes the following:

- A `markdown` file titled in the following format: `YYYY-MM-DD-lowercase-name-of-figure.md` with a `YAML` style header area for relevant metadata:

  ```yaml {id="post-template" class="" data-filename="test.py"}
  ---
  layout: post # 'Post' layout required
  title: Post Template # 'Ada Lovelave (1815-1852)'
  author: 'Your Name' # 'Jane Doe'
  categories: meta # See below
  tags: [meta] # See below
  image: [image-filename] # See Below
  ---

  ```

#### Post Content

Posts on Compuneers should consist of an image and three `h2` header/sections, with linked, reputable sources:

- An image of the figure in question (if available), added **only** to the `compuneers/assets/img` directory. The image name should follow the convention of `Person-Name_Width-In-Pixels.ext` (ex: `Margaret-Hamilton_540px.png`). If an image is too low in resolution it may be removed during the merge process.
- An **About** section of biographical information
- A section featuring figure's **Work** in Computer Science/contributions to the field
- A **Further Reading** section with the post's sources and/or relevant links
- (Optional) A section featuring figure's awards and/or accolades
- (Optional) Trivia/Interesting facts

---

layout: post
title: Ada Lovelave (1815-1852)
author: Jane Doe
categories: meta
tags: [programming, pioneers]
image: Ada-Lovelace_540px.px

---

## About

Augusta Ada King, Countess of Lovelace, (1815 - 1852) was an English pioneer in the field of computing. The daughter of poet Lord Byron, Lovelace’s influence is still prominent today from her contributions with Charles Babbage to early programming.

Ada Lovelace is widely regarded as the first computer programmer. She is most well-known for her work on Charles Babbage’s [Analytical Engine](https://en.wikipedia.org/wiki/Analytical_Engine), which included devising an algorithm to compute [Bernoulli numbers](https://en.wikipedia.org/wiki/Bernoulli_number), and anticipating modern computing a century before being realized.

## Further Reading

- [Ada programming language](<https://en.wikipedia.org/wiki/Ada_(programming_language)>)

<figcaption align="center">Sample post on Ada Lovelace</figcaption>

---

<!-- TODO: Finish before initial push -->

## To Do

- Create Figure List
  - Name
  - Resources
- Create ~5 sample posts
- Remove all Millenium boilerplate
- Refactor SCSS
