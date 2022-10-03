---
layout: default
---

# About me
Born 1998, in Moscow, I moved to the States at two years old. My favorite pastimes as a child were legos and video games, which eventually transformed into computing and electronics. I went on to study Computer Engineering with a focus in Digital Hardware at UCSC. After my graduation in 2021 I went to work as a design verification engineer at Esperanto Technologies, where I honed my skills and prepared to pursue a graduate degree. In 2022 I was accepted back into UCSC. This time for the MS program with the CSE department, under the tutelage of Professor Jose Renau. 

![me](./docs/assets/IMG_6311.jpg)

## Current work
[Dromajo - MASC/UCSC](https://github.com/masc-ucsc/dromajo).
As supply chain issues rattle the world of computing, now more than ever do engineers need chip designs that do more but are (physically) less. My research aims to help CPU designers meet both of these goals, specifically through my RISC-V Vector Processing Unit (VPU) co-simulation environment. An extension to the open source tool Dromajo, my model of the VPU is meant to provide designers with a “golden standard” as to how their design should function to be RISC-V compliant. Functionally, it will run its software model in parallel with a hooked RTL design, and will inform the user if any discrepancies are detected during runtime of RISC-V binaries.

### Why a VPU?
The modern demand for highly parallelized computation is becoming increasingly popular, as machine learning and artificial intelligence models have come into the mainstream. The VPU is a simple, and highly configurable solution to these problems. This is because at design time, the engineers decide how large to make the word size as well as the vector register size. Then during run-time, it can dynamically switch between various element sizes, allowing a great deal of optimization for wildly different workloads.

## Past work
[Dromajo - Chips Alliance](https://github.com/chipsalliance/dromajo).
My first major assignment at Esperanto Technologies was the patching and improvement of their contribution to the RISC-V ecosystem as a part of the Chips Alliance. This software is Dromajo, and working on it forced me to read the RISC-V official specification manual over and over again, until I understood the semantics perfectly. Since then I have done some small RTL development as well as helped with Linux bring-up for one of the company's major designs.

### Why RISC-V?
My time at Esperanto Technologies greatly helped develop my engineering skills. What it also did was expose me to the highly collaborative and tightly-knit RISC-V community. By open sourcing many parts of the design process, from RTL to compiler, the RISC-V ecosystem is constantly evolving on a global scale. This lowers the bar of entry for newcomers to the CPU design community, as well as encourages the old guard to share (and argue about) their latest and greatest ideas.


### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
