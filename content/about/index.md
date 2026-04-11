---
linkTitle: About
title: About This Site
# description: Rendered in html ... head ... meta.
# summary: Or use as a teaser.
# keywords: Rendered in html ... head ... meta.
# categories: [arts,health,how-to,money,politics,science,tech,travel]

menus:
  voluntary:
    parent: Home
weight: 20

date: 2020-01-01
lastmod: 2020-01-01
draft: false
# publishDate:
# expiryDate:

# resources: Maps of metadata for page resources.
markup: org
# type: subfolder-of-layouts-iff-layout-is-nested
layout: about
# outputs: The output formats to render.
---

# Fruit

## Some fruit

### Even less fruit

#### ® Published by Somebody (2020): «Apricots only!»

◉ Bookmark, Feb 21st

¢ I'd like to add that Abingdon is in Wash. County. 

∂ «Here is a subheadline»

=> https://example.org/ NYT / by John Smith

> This line is a blockquote: 1 ≤c2 ≤l3 ≤s4 ≤w5 ≤c6 ≤l7 ≤s8 ≤w9 0 9≥ 8≥ 7≥ 6≥ 5≥ 4≥ 3≥ 2≥ 1

5 Please ≤cwatch ≤nfor ≤lbits≥, and ≤lbytes≥, and≥ also ≤lun ordinateur≥! 6 Henry ≤sBob ≤nBobby≥ Bobson≥ Jr. 7 It's ≤wno longer ≤scool≥, they≥ say. 8 Melville wrote ≤wBilly Budd≥. 9 I do≥ like ≤dABC, Amer. Broadc. Co.≥ 10 ≤cSea sea sea sea sea≥ 11

## Apple


This is the content for the About page. Here is a pasteable, default, YAML frontmatter:

#+BEGIN_EXAMPLE
---
linkTitle: Abe-Bob
title: Abe, Bob (?) & Geo.
# description: Rendered in html ... head ... meta.
# summary: Or use as a teaser.
# keywords: Rendered in html ... head ... meta.
# categories: [arts,health,how-to,money,politics,science,tech,travel]

menus:
  voluntary:
    parent: Galleries
params:
  opaqueToDiveMenu: false
weight: 123456789

date: 2020-01-01
lastmod: 2020-01-01
draft: false
# publishDate:
# expiryDate:

# resources: Maps of metadata for page resources.
markup: org
# type: subfolder-of-layouts-iff-layout-is-nested
layout: overriding-the-default-template
# outputs: The output formats to render.
---
#+END_EXAMPLE

(Note: "params:" is needed only for custom params. Also, I'm ignoring Hugo's rather crude cascade feature.)

---

aleorthonym: a portmanteau of alethonym ("true name") and orthonym ("normal/proper name"). I wanted a made-up word for this front matter property key, which holds (for now) proper names.

```
The delimiters, parameterized with the letter 'a'

≤a ... «...» ---> ≤a ... <q class="article-title">...</q>

≤aSource: _Some Title ---> the underscores should be replaced by <cite class="book-title">...</cite>

≤a encloses 6 patterns, which are parsed via regexps. 

The next line is like:

=> https://www.nytimes.com/2021/04/21/technology/welcome-to-the-yolo-economy.html NYT / by Kevin Roose

there is an optional DEK after that!



When processed, the outermost quotation marks are replaced by

<q class="article-title">...</q>

And the outmost underscores are replaced by

<cite class="book-title">...</cite>

=================

≤ followed by one of these letters: a b c d k l n q s w

≤aREPORTER, writing in PERIODICAL (YEAR): "TITLE"≥

^> "..." ---> ≤b...≥ ---> <blockquote>

≤c is for title citations that require special handling, typically this means any citation of a title where ≤w shouldn't be used because it's not worthy of italics. E.g., titles of articles. Citing an article is rare, because that's usually pre-empted by being wrapped in a ≤a ... ≥

≤d is for abbreviations, which get turned into something like "<abbr>GE</abbr> (General Electric)", and definitions (none yet)

^dek: "..." ---> ≤k...≥

≤lDeep South≥ ---> any one of these: <i class="term">Deep South</i> or "word-as-word", "logical-statement", "synonym" (depending on context)

≤nFrancky≥ ---> <i class="nickname">Francky</i>

NEW: I'm replacing <q>...</q> with «...» (or ‹...› nested) -- but carefully!

≤qHello, ‘Cap’n’!≥ *or* «Hello, ‹Cap’n›!» ---> ❝Hello, ❛Cap’n❜!❞ 

≤sBad≥ ---> <i class="so-called">Bad</i>

≤w is used for the [typically italicized] title/name of a WORK, e.g. book title, newspaper title. So some are series (periodicals) and some aren't.

≤wMoby Dick≥, ≤wNew York Times≥, ≤wRubber Soul≥

≤a is used for a [typically quotation-marked] article title/headline, song, etc.

<cite>...</cite> ---> ≤a...≥ ---> <cite> once again (these are article and whitepaper titles)
3 works:
<cite class="book-title"> ---> ≤w...≥
<cite class="film-title"> ---> ≤w...≥
<cite class="artwork-title"> ---> ≤w...≥

MacOS alt keys:

1 ¡ ⁄ fraction slash
2 ™ €
3 £ ‹
4 ¢ ›
5 ∞ ﬁ
6 § ﬂ
7 ¶ ‡
8 • °
9 ª · middle dot
0 º ‚ single low-9 quotation mark
- – —
= ≠ ±
...
t † ˇ caron 0x2C7 &#711; sˇ ˇs Sˇ ˇS
...
g © ˝
...
z Ω ¸ cedilla 0xB8 &cedil; ¸S S¸
x ≈ ˛ ogonek 0x2DB &#731; A˛ a˛ ˛a ˛A
...
, ≤ ¯ macron [spacing] 0xAF &macr; o¯ ¯o O¯ ¯O
. ≥ ˘ breve [spacing] 0x2D8 &#728; a˘ ˘a ˘A A˘
```

