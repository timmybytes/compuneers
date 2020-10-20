# Contributing

**Contents**
[Adding a figure to the Figure List](#adding-a-figure-to-the-figure-list)
[Writing about a figure already in the Figure List](#writing-about-a-figure-in-the-figure-list)
[Style Guide](#style-guide)


To contribute a new figure post to the project, start by opening an issue for a specific figure according to the instructions below.

## Adding a figure to the Figure List

1. Open a new issue and fill in the required fields to discuss the proposed addition with maintainers, and to ensure the figure is a good fit for the project.
2. If approved/assigned:
   - Fork the repo
   - Add the figure to the Figure List file with the appropriate resource links in the following format:
     - `Figure Name` as h2 heading
     - `Figure ID` as first three letters of figure's last name + 001 (or 002 if 001 is taken, etc)
     - `One sentence biographical blurb`
     - `Sources`
       - `Links`
     - `Status: Not Published`
   - Submit a PR with this change (please do not create new post for a figure until this PR has been merged)

3. Continue with the below steps

## Writing about a figure in the Figure List

1. Open a new issue

You can choose a figure from the established [Figure List](#), or [open an issue to add a figure to write about](#), as long as the following criteria are met:

- The figure could be a woman, a person of color, and/or LGBTQIA+. This rule is very flexible, but keep in mind the project is specifically meant to lift up overlooked and marginalized figures in Computer Science.
- The figure will have worked in or contributed to the general field of Computer Science.
- There should be credible sources (preferably at least two separate sources) to draw from and cite for a post.
- The post adheres to the project's [Style Guide](#style-guide) and [Contributing Guidelines](#)

### Style Guide

#### Post Content

Posts should follow the [Post Template](#) format that includes the following:

- A `markdown` file titled in the following format: `YYYY-MM-DD-lowercase-name-of-figure.md` with a `YAML` style header area for relevant metadata:

  ```yaml {id="post-template" class="" data-filename="test.py"}
  ---
  layout: post                      # 'post' layout required
  title: 'Ada Lovelave (1815-1852)' # Figure name and birth-death
  author: 'Your Name'               # or leave blank if desired
  categories: figures               # 'figures' category required
  tags: [figures]                   # 'figures' tag required
  image: [image-filename]           # See Below
  figure-id: AAA000                 # See below
  ---

  ```


Posts on Compuneers should consist of an image and three `h2` header/sections, with linked, reputable sources:

- An image of the figure in question (if available), added **only** to the `compuneers/assets/img` directory. The image name should follow the convention of `Person-Name_Width-In-Pixels.ext` (ex: `Margaret-Hamilton_540px.png`). If an image is too low in resolution it may be removed during the merge process.
- An **About** section of biographical information
- A section featuring figure's **Work** in Computer Science/contributions to the field
- A **Further Reading** section with the post's sources and/or relevant links
- (Optional) A section featuring figure's awards and/or accolades
- (Optional) Trivia/Interesting facts

```yaml
---

layout: post
title: Ada Lovelave (1815-1852)
author: Jane Doe
categories: meta
tags: [programming, pioneers]
image: Ada-Lovelace_540px.px

---

## About

Augusta Ada King, Countess of Lovelace, (1815 - 1852) was an
English pioneer in the field of computing. The daughter of poet
Lord Byron, Lovelace’s influence is still prominent today from her
contributions with Charles Babbage to early programming.

Ada Lovelace is widely regarded as the first computer programmer.
She is most well-known for her work on Charles Babbage’s
[Analytical Engine](<https://en.wikipedia.org/wiki/Analytical_Engine>,
which included devising an algorithm to compute [Bernoulli
numbers](https://en.wikipedia.org/wiki/Bernoulli_number), and
anticipating modern computing a century before being realized.

## Further Reading

- [Sketch of The Analytical Engine with Notes by Ada Lovelace](http://www.fourmilab.ch/babbage/sketch.html)
- [Ada Lovelace (Retroactive) Obituary - New York Times](https://www.nytimes.com/interactive/2018/obituaries/overlooked-ada-lovelace.html)
- [Ada programming language](<https://en.wikipedia.org/wiki/Ada_(programming_language)>), named after Ada Lovelace
- [Ada Lovelace Day](https://findingada.com/)

```

<figcaption align="center">Sample post on Ada Lovelace</figcaption>

#### Pull Requests
