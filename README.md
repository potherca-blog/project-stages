# Badges for Project Stages

## Introduction

As any active software developer, I tend to have a lot of projects laying about.
With the advent of Github all of these projects now live in the public eye.

For me, as the author, it isn't dificult to keep track of which project is in
which state of production. For the casual visitor of my project pages this is a
different matter.

To help passers-by to identify how solid a certain project is at-a-glance, I
felt it would be prudent to offer them a "Badge". Some uniform way of knowing
what to expect of the code in the repository without even having to look at it.

## Project Stages

Before a visitor can be alerted of which stage of production a project is in,
these stages need to be defined. After some general research on what are the
most common terms used elsewhere I came up with the following list:

- C
- R
- E
- D
- .
- !
- ?

This project is in its

1. **C**oncept
2. **R**esearch
3. **E**xperiment
4. **D**evelopment
5. **Production Ready**
6. **!** Deprecated
7. **?** Unknown

stage.

## The Badges

It would be nice to be able to display these stages in an uniform manner across
projects. Preferably in a way that mirrors the look and feel of other badge
providers.

This can quite easily be achieved using the excellent service provided by
[Shields.io](https://shields.io/):

1. [![Project stage: Concept][project-stage-badge: Concept]][project-stage-page]
2. [![Project stage: Research][project-stage-badge: Research]][project-stage-page]
3. [![Project stage: Experimental][project-stage-badge: Experimental]][project-stage-page]
4. [![Project stage: Development][project-stage-badge: Development]][project-stage-page]
5. [![Project stage: Production Ready][project-stage-badge: Production Ready]][project-stage-page]
6. [![Project stage: DEPRECATED][project-stage-badge: DEPRECATED]][project-stage-page]
7. <i>no image required</i>

## Usage

One-liners for badges in markdown files are less readable and less maintainable,
so use the following instead.

The link for all badges is the same, pointing to this page.

### Concept

#### HTML

```
<img alt="Project stage: Concept" src="https://img.shields.io/badge/Project%20Stage-Concept-red.svg" />
```

#### Markdown

```
[![Project stage: Concept][project-stage-badge: Concept]][project-stage-page]

[project-stage-badge: Concept]: https://img.shields.io/badge/Project%20Stage-Concept-red.svg
[project-stage-page]: https://blog.pother.ca/project-stages/
```

### Research

#### HTML

```
<img alt="Project stage: Research" src="https://img.shields.io/badge/Project%20Stage-Research-orange.svg" />
```

#### Markdown

```
[![Project stage: Research][project-stage-badge: Research]][project-stage-page]

[project-stage-badge: Research]: https://img.shields.io/badge/Project%20Stage-Research-orange.svg
[project-stage-page]: https://blog.pother.ca/project-stages/
```

### Experimental

#### HTML

```
<img alt="Project stage: Experimental" src="https://img.shields.io/badge/Project%20Stage-Experimental-yellow.svg" />
```

#### Markdown

```
[![Project stage: Experimental][project-stage-badge: Experimental]][project-stage-page]

[project-stage-badge: Experimental]: https://img.shields.io/badge/Project%20Stage-Experimental-yellow.svg
[project-stage-page]: https://blog.pother.ca/project-stages/
```

### Development

#### HTML

```
<img alt="Project stage: Development" src="https://img.shields.io/badge/Project%20Stage-Development-yellowgreen.svg" />
```

#### Markdown

```
[![Project stage: Development][project-stage-badge: Development]][project-stage-page]

[project-stage-badge: Development]: https://img.shields.io/badge/Project%20Stage-Development-yellowgreen.svg
[project-stage-page]: https://blog.pother.ca/project-stages/
```

### Production Ready

#### HTML

```
<img alt="Project stage: Production Ready" src="https://img.shields.io/badge/Project%20Stage-Production%20Ready-brightgreen.svg" />
```

#### Markdown

```
[![Project stage: Production Ready][project-stage-badge: Production Ready]][project-stage-page]

[project-stage-badge: Production Ready]: https://img.shields.io/badge/Project%20Stage-Production%20Ready-brightgreen.svg
[project-stage-page]: https://blog.pother.ca/project-stages/
```

### DEPRECATED

#### HTML

```
<img alt="Project stage: DEPRECATED" src="https://img.shields.io/badge/Project%20Stage-%20!%20DEPRECATED%20%20%20!-ff0000.svg" />
```

#### Markdown

```
[![Project stage: DEPRECATED][project-stage-badge: DEPRECATED]][project-stage-page]

[project-stage-badge: DEPRECATED]: https://img.shields.io/badge/Project%20Stage-%20!%20DEPRECATED%20%20%20!-ff0000.svg
[project-stage-page]: https://blog.pother.ca/project-stages/
```

Any questions or feedback can be Tweeted to [@potherca](https://twitter.com/intent/tweet?screen_name=potherca)

<p class="created-by">
  The source of this page is <a href="https://github.com/potherca-blog/project-stages/">available on GitHub</a>
  under a <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>
  &mdash; Created by <a href="https://pother.ca/" class="potherca">Potherca</a>
</p>

[project-stage-badge: Concept]: https://img.shields.io/badge/Project%20Stage-Concept-red.svg
[project-stage-badge: DEPRECATED]: https://img.shields.io/badge/Project%20Stage-%20!%20DEPRECATED%20%20%20!-ff0000.svg
[project-stage-badge: Development]: https://img.shields.io/badge/Project%20Stage-Development-yellowgreen.svg
[project-stage-badge: Experimental]: https://img.shields.io/badge/Project%20Stage-Experimental-yellow.svg
[project-stage-badge: Production Ready]: https://img.shields.io/badge/Project%20Stage-Production%20Ready-brightgreen.svg
[project-stage-badge: Research]: https://img.shields.io/badge/Project%20Stage-Research-orange.svg
[project-stage-page]: https://blog.pother.ca/project-stages/
