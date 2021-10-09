(learning)=
# Learning

I propose the following pattern to be followed in general.
Each navbar section (which are the pages listed in the index toctree)
should have an overview of the contents of the section and a hidden
toctree to the pages within that section (if any). This will make the
pages appear in the left sidebar for easy navigation while keeping the
in page toc on the right sidebar.

## Getting started

Start here to get acquainted with the core concepts of Bayesian analysis and PyMC.

::::::{grid} 1
:gutter: 1

:::::{grid-item}
::::{grid} 2
:gutter: 1

:::{grid-item-card} Bayesian Methods for Hackers
:shadow: none

By Cameron Davidson-Pilon
:::

:::{grid-item-card}
:shadow: none

Hands-on learning of  Bayesian statistics and PyMC3

[Github repo](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)

[Project homepage](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
:::
::::
:::::

:::::{grid-item}
::::{grid} 2
:gutter: 1

:::{grid-item-card} Bayesian Analysis with Python
:shadow: none

by Osvaldo Martin
:::

:::{grid-item-card}
:shadow: none

A great introductory book written by a maintainer of PyMC.

[Book website](https://www.packtpub.com/big-data-and-business-intelligence/bayesian-analysis-python-second-edition)

[Code and errata in PyMC](https://github.com/aloctavodia/BAP)
:::

::::
:::::

:::::{grid-item}
::::{grid} 2
:gutter: 1

:::{grid-item-card} Glossary
:shadow: none

:::

:::{grid-item-card}
:shadow: none

PyMC's glossary, which defines many core terms and provides references.

:ref: glossary
:::

::::
:::::
::::::


---
## Step 2 overview
Links to beginner lever notebooks. For example,
thanks to intersphinx, we can cite the getting started
notebook with {doc}`nb:getting_started` (the path in pymc-examples repo excluding
the `examples` folder, or using manual anchors if we decide to create them).

---
## Step 3 overview

Links to intermediate notebooks. {doc}`More about step 3... <learn/step3>`

:::{toctree}
:hidden:

learn/step1
learn/step2
learn/step3
:::
