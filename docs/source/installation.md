# Installation guide

Move the 3 wiki pages over to here.

with sphinx_design we can have common content in a single place,
and whenever there is some specific guidance that depends on OS use
tabs, which can be syncronized. That is, if one tab is switched over to
windows, all tabs will be moved to windows. For example:

::::{tab-set}
:::{tab-item} Linux
:sync: linux

specific linux content
:::

:::{tab-item} MacOS
:sync: mac

specific macos content
:::

:::{tab-item} Windows
:sync: windows

specific windows content
:::
::::

more common content

::::{tab-set}
:::{tab-item} Linux
:sync: linux

extra specific linux content, i.e. testing the installation was successful
:::

:::{tab-item} MacOS
:sync: mac

extra specific macosx content, i.e. testing the installation was successful
:::

:::{tab-item} Windows
:sync: windows

extra specific windows content, i.e. testing the installation was successful
:::
::::
