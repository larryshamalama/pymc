(learning)=
# Learning

I propose the following pattern to be followed in general.
Each navbar section (which are the pages listed in the index toctree)
should have an overview of the contents of the section and a hidden
toctree to the pages within that section (if any). This will make the
pages appear in the left sidebar for easy navigation while keeping the
in page toc on the right sidebar.

## Step 1 overview
Links to books and pymc-devs/resources.

---
## Step 2 overview
Links to beginner lever notebooks. For example,
thanks to intersphinx, we can cite the getting started
notebook with {doc}`nb:getting_started` (the path in pymc-examples repo excluding
the `examples` folder, or using manual anchors if we decide to create them).

---
## Step 3 overview

Links to intermediate notebooks. {doc}`More about step 3... <learn/step3>`

```{toctree}
:hidden:

learn/step1
learn/step2
learn/step3
```
