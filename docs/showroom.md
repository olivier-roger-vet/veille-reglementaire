# Home

## 1. Buttons

[Link to my website](https://www.horlogerie-du-web.com){ .md-button }

[Link to my website](https://www.horlogerie-du-web.com){ .md-button .md-button--primary }

[Send me a message :fontawesome-solid-paper-plane:](mailto:olivier.roger@horlogerie-du-web.com){ .md-button }

[See my :fontawesome-brands-youtube:{ .youtube } channel](#){ .md-button }

## 2. Syntax highlighting

### 2.1 With blocks

```mysql title="script.sql" linenums="1"
-- This is a comment
SELECT firstname, lastname FROM contact WHERE age > 10; -- (1)!
```

1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.

```sqlite3 hl_lines="3-5 7"
sqlite> .headers on
sqlite> .mode csv
sqlite> .once c:/work/dataout.csv
sqlite> SELECT * FROM tab1;
sqlite> .system c:/work/dataout.csv   # on Windows
sqlite> .system open dataout.csv      # on macOS
sqlite> .system xdg-open dataout.csv  # on Linux
```

#### 2.1.1 title 4 rendered in toc

<h4>2.1.2. title 4 not renderd in toc</h4>

### 2.2 Inline

When using the statement `#!mysql SELECT * FROM name WHERE age > 10`, the `#!mysql SELECT` keyword[^1] is used from selecting the columns[^2] to project.

## 3. Using tabs

### 3.1 Basic case

=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

### 3.2 Embedded tabs

!!! example

    === "Unordered List"

        ``` markdown
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
        ```

    === "Ordered List"

        ``` markdown
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci
        ```

## 4. Tables

|  Center  | Left                                 | align right |
|:--------:|:-------------------------------------|------------:|
|  `GET`   | :material-check:     Fetch resource  |           1 |
|  `PUT`   | :material-check-all: Update resource |           2 |
| `DELETE` | :material-close:     Delete resource |           3 |


## 5. Formatting

Lorem ipsum dolor sit amet, ==consectetur adipiscing elit==. Vivamus dictum nisi metus, a rutrum erat pellentesque a. 
Suspendisse in velit pellentesque, ^^tempor tellus at^^, efficitur ipsum. Aliquam erat volutpat. 
Proin a ipsum consequat, euismod ante a, efficitur purus. ~~Maecenas lacinia~ posuere velit quis malesuada. 
Mauris finibus quam massa, vel fermentum massa dignissim eu. 
Quisque varius, felis eu tempor varius, magna urna dictum lorem, vel sodales mauris turpis eu sem. 

H~2~0

y=2x^2

Il est également possible d'ajouter des touches (1)
{ .annotate }

1.  Pour connaître la liste des codes, voir [ce lien](https://facelessuser.github.io/pymdown-extensions/extensions/keys/#extendingmodifying-key-map-index)

++ctrl+c++

Pour utiliser le caractère `~` sur mac, utilisez ++opt+n++

Pour utiliser le caractère `|` sur mac, utilisez ++shift+cmd+l++

## 6. Grids:

### 6.1. Basic example

<div class="grid cards" markdown>

- :fontawesome-brands-html5: __HTML__ for content and structure
- :fontawesome-brands-js: __JavaScript__ for interactivity
- :fontawesome-brands-css3: __CSS__ for text running out of boxes
- :fontawesome-brands-internet-explorer: __Internet Explorer__ ... huh?

</div>

### 6.2 Sth more advanced

<div class="grid cards" markdown>

-   :material-clock-fast:{ .lg .middle } __Set up in 5 minutes__

    ---

    Install [`mkdocs-material`](#) with [`pip`](#) and get up
    and running in minutes

    [:octicons-arrow-right-24: Getting started](#)

-   :fontawesome-brands-markdown:{ .lg .middle } __It's just Markdown__

    ---

    Focus on your content and generate a responsive and searchable static site

    [:octicons-arrow-right-24: Reference](#)

-   :material-format-font:{ .lg .middle } __Made to measure__

    ---

    Change the colors, fonts, language, icons, logo and more with a few lines

    [:octicons-arrow-right-24: Customization](#)

-   :material-scale-balance:{ .lg .middle } __Open Source, MIT__

    ---

    Material for MkDocs is licensed under MIT and available on [GitHub]

    [:octicons-arrow-right-24: License](#)

</div>

## 7. Images

default

![Image title](https://dummyimage.com/600x400/)

full width

![Image title](https://dummyimage.com/600x400/){ width="100%" }

left alignment

![Image title](https://dummyimage.com/300x150/eee/aaa){ align=left }

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus dictum nisi metus, a rutrum erat pellentesque a. Suspendisse in velit pellentesque, tempor tellus at, efficitur ipsum. Aliquam erat volutpat. Proin a ipsum consequat, euismod ante a, efficitur purus. Maecenas lacinia posuere velit quis malesuada. Mauris finibus quam massa, vel fermentum massa dignissim eu. Quisque varius, felis eu tempor varius, magna urna dictum lorem, vel sodales mauris turpis eu sem. Etiam vitae ante elit. Integer eleifend in mauris ac vulputate. Aenean id hendrerit enim. Sed posuere urna sem. Proin aliquam, dolor in efficitur eleifend, libero felis fringilla tellus, id maximus odio leo sit amet orci. Pellentesque auctor sapien metus, quis placerat quam tristique sit amet. Sed blandit dapibus arcu sed tristique. Aliquam erat volutpat.

right alignment

![Image title](https://dummyimage.com/300x150/eee/aaa){ align=right }

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus dictum nisi metus, a rutrum erat pellentesque a. Suspendisse in velit pellentesque, tempor tellus at, efficitur ipsum. Aliquam erat volutpat. Proin a ipsum consequat, euismod ante a, efficitur purus. Maecenas lacinia posuere velit quis malesuada. Mauris finibus quam massa, vel fermentum massa dignissim eu. Quisque varius, felis eu tempor varius, magna urna dictum lorem, vel sodales mauris turpis eu sem. Etiam vitae ante elit. Integer eleifend in mauris ac vulputate. Aenean id hendrerit enim. Sed posuere urna sem. Proin aliquam, dolor in efficitur eleifend, libero felis fringilla tellus, id maximus odio leo sit amet orci. Pellentesque auctor sapien metus, quis placerat quam tristique sit amet. Sed blandit dapibus arcu sed tristique. Aliquam erat volutpat.

With caption

<figure markdown="span">
  ![Image title](https://dummyimage.com/600x400/){ width="300" }
  <figcaption>Image caption</figcaption>
</figure>

## 8. Lists : 

### 8.1 Definition lists : 

`Lorem ipsum dolor sit amet`

:   Sed sagittis eleifend rutrum. Donec vitae suscipit est. Nullam tempus
    tellus non sem sollicitudin, quis rutrum leo facilisis.

`Cras arcu libero`

:   Aliquam metus eros, pretium sed nulla venenatis, faucibus auctor ex. Proin
    ut eros sed sapien ullamcorper consequat. Nunc ligula ante.

    Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
    Nam vulputate tincidunt fringilla.
    Nullam dignissim ultrices urna non auctor.

### 8.2. Tasks lists: 

- [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
- [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [ ] Praesent sed risus massa
- [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque


[^1]: Single ligne footnote 
[^2]:
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

## 9. Admonitions / call-outs:

Default

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

With no title

!!! note ""

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

With custom title

!!! note "Phasellus posuere in sem ut cursus"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

Collapsible, collapsed by default

??? note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

Collapsible, expanded by default

???+ note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

On right side

!!! note inline end

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus dictum nisi metus, a rutrum erat pellentesque a. Suspendisse in velit pellentesque, tempor tellus at, efficitur ipsum. Aliquam erat volutpat. Proin a ipsum consequat, euismod ante a, efficitur purus. Maecenas lacinia posuere velit quis malesuada. Mauris finibus quam massa, vel fermentum massa dignissim eu. Quisque varius, felis eu tempor varius, magna urna dictum lorem, vel sodales mauris turpis eu sem. Etiam vitae ante elit. Integer eleifend in mauris ac vulputate. Aenean id hendrerit enim. Sed posuere urna sem. Proin aliquam, dolor in efficitur eleifend, libero felis fringilla tellus, id maximus odio leo sit amet orci. Pellentesque auctor sapien metus, quis placerat quam tristique sit amet. Sed blandit dapibus arcu sed tristique. Aliquam erat volutpat.

On left side

!!! note inline start

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus dictum nisi metus, a rutrum erat pellentesque a. Suspendisse in velit pellentesque, tempor tellus at, efficitur ipsum. Aliquam erat volutpat. Proin a ipsum consequat, euismod ante a, efficitur purus. Maecenas lacinia posuere velit quis malesuada. Mauris finibus quam massa, vel fermentum massa dignissim eu. Quisque varius, felis eu tempor varius, magna urna dictum lorem, vel sodales mauris turpis eu sem. Etiam vitae ante elit. Integer eleifend in mauris ac vulputate. Aenean id hendrerit enim. Sed posuere urna sem. Proin aliquam, dolor in efficitur eleifend, libero felis fringilla tellus, id maximus odio leo sit amet orci. Pellentesque auctor sapien metus, quis placerat quam tristique sit amet. Sed blandit dapibus arcu sed tristique. Aliquam erat volutpat.

Various types 

!!! info

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! tip

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! question

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! warning

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! danger

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! example

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! quote

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.