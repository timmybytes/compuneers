---
layout: post
title: Post Template
author:
categories: meta
tags: [meta]
image:
figure-id:
---

This is a combination template and guide for [writing a post for **Compuneers**](https://github.com/timmybytes/compuneers/blob/main/CONTRIBUTING.md). The post itself must be saved in the `/_posts/` directory as a markdown file with a filename that includes the date in YYYY/MM/DD format, followed by the name of the figure you're writing about. Ex: `2020/10/20-Ada-Lovelace.md`

## Document Head

Each post **must** contain the following at the top of the document in order to be indexed and rendered correctly on the site.

<figcaption>Sample head</figcaption>
```yaml
---

layout: post
title: Name of Figure (birthyear - deathyear)
author: Your Name, or blank if desired
categories: post # important
tags: [post] # important
image: Resolution-Name_of_Figure.jpg # ex: 896px-Margaret_Hamilton.jpg
figure-id: AAA000 # See FIGURES list for correct ID for your subject
---

// The rest of the post

```

### Layout Tag
**Important** - This should be marked as `post` in order to display properly.

### Title Tag
**Important** - This should be written as the figure's name and birthyear/deathyear (if applicable). Ex: `Ada Lovelace (1815 - 1852)`

### Author Tag
Your name as you'd like it to appear on the site, or left black if you'd prefer not to be named

### Categories Tag
**Important** - This should be marked as `figures` in order to display properly.

### Tags Tag
**Important** - This should be marked as `figures` in order to display properly.

### Image Tag
Each figure's images should be kept within a figure-id-specific directory (ex: `assets/img/HAM001` for Margaret Hamilton). If one doesn't already exist with the figure's [id](https://github.com/timmybytes/compuneers/blob/main/FIGURES.md), create one before adding a photo there for your post. Photos should be saved in the format of resolution followed by figure name (ex: `896px-Margaret_Hamilton.jpg`). In your post head, simply add this filename at the `image: ` field.

### Figure ID Tag
**Important** - The first three letters of a figure's last name and a three-digit number, typically 001. Each [figure](https://github.com/timmybytes/compuneers/blob/main/FIGURES.md) should have one assigned.

## Writing Your Post

A figure post should contain information on a figure's work in Computer Science and their life — but you can choose to write the post itself however you'd like. Just make sure to link sources and check your spelling and grammar before submitting a Pull Request.

### Work Section

The work section should include anything available on the figure's specialty, contributions to Computer Science, etc, along with links to their work or to other aspects of CS influenced by the figure's work.

Example:

> Grace Hopper invented the [FLOW-MATIC](https://en.wikipedia.org/wiki/FLOW-MATIC) programming language, which subsequently played an important role in the creation of [COBOL](https://en.wikipedia.org/wiki/COBOL).

### Biography Section

The biography section can include anything relating to the figure's life.

Example:

> Grace Hopper was born in New York City. She was the eldest of three children. Her parents, Walter Fletcher Murray and Mary Campbell Van Horne, were of Scottish and Dutch descent, and attended West End Collegiate Church. Her great-grandfather, Alexander Wilson Russell, an admiral in the US Navy, fought in the Battle of Mobile Bay during the Civil War.
>
> Grace was very curious as a child; this was a lifelong trait. At the age of seven, she decided to determine how an alarm clock worked and dismantled seven alarm clocks before her mother realized what she was doing (she was then limited to one clock).
>
> [source](https://en.wikipedia.org/wiki/Grace_Hopper#Early_life_and_education)

### (Optional) Awards and/or Accolades Section

Examples:

> * World War II Victory Medal (1945)
> * Hopper was awarded the Society of Women Engineers Achievement Award, the Society's highest honor, "In recognition of her significant contributions to the burgeoning computer industry as an engineering manager and originator of automatic programming systems." In May 1955, Hopper was one of the founding members of the Society of Women Engineers (1964)
> * Defense Distinguished Service Medal (1986)
> * etc.
>
> [source](https://en.wikipedia.org/wiki/Grace_Hopper#Awards_and_honors)

### (Optional) Trivia/Interesting Facts Section

Examples:

> Throughout much of her later career, Grace Hopper was much in demand as a speaker at various computer-related events. She was well known for her lively and irreverent speaking style, as well as a rich treasury of early war stories. She also received the nickname "Grandma COBOL".
>
> [source](https://en.wikipedia.org/wiki/Grace_Hopper#Anecdotes)

> While she was working on a Mark II Computer at Harvard University in 1947, her associates discovered a moth that was stuck in a relay; the moth impeded the operation of the relay. While neither Hopper nor her crew mentioned the phrase "debugging" in their logs, the case was held as an instance of literal "debugging." For many years, the term bug had been in use in engineering. The remains of the moth can be found in the group's log book at the Smithsonian Institution's National Museum of American History in Washington, D.C.
>
> [source](https://en.wikipedia.org/wiki/Grace_Hopper#Anecdotes)
