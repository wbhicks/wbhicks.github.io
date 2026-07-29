---
linkTitle: Home
title: Site “Title” ‘Here’
#COMMENT description: Rendered in html ... head ... meta.
#COMMENT summary: Or use as a teaser.
#COMMENT keywords: Rendered in html ... head ... meta.
#COMMENT categories: [internal]

menus: voluntary
params:
  opaqueToDiveMenu: false
#COMMENT weight: 10000000000

date: 2020-01-01
lastmod: 2020-01-01
draft: false
#COMMENT publishDate:
#COMMENT expiryDate:

#COMMENT resources: Maps of metadata for page resources.
#COMMENT markup: org
#COMMENT type: subfolder-of-layouts-iff-layout-is-nested
layout: home
outputs:
- html
- markdown
---

This is the content for the Home page. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

<pre>
A note on Hugo's built-in "outputs" parameter:

#COMMENT "In its default configuration, Hugo will render both the html and
#COMMENT json output formats for this page. The outputs field appends to,
#COMMENT rather than replaces, the project’s configured outputs."

#COMMENT -- https://gohugo.io/configuration/outputs/

#COMMENT (The mention of "json" above is not relevant here.) In my experience,
#COMMENT I must specify both output formats (html and markdown) below.

layout: anti-almanac
outputs:
- html
- markdown

~ ~ ~ ~ ~ ~ ~

A sample frontmatter (n.b.: remove the redundancies):

THREE HYPHENS ON THIS LINE
linkTitle: OneWord
title: A Few More Words Allowed
#COMMENT description: Rendered in html ... head ... meta.
#COMMENT summary: Or use as a teaser.
#COMMENT keywords: Rendered in html ... head ... meta.
#COMMENT categories: [arts,edu,health,how-to,internal,money,pol,sci,soc-sci,tech,travel,when,where,who]

menus:
  voluntary:
    parent: SomeParent
params:
  opaqueToDiveMenu: false
weight: x0000000000
        ^
        2 toc
        3 catalogue
        4 categories
        6 anti-almanac
        7 galleries
        8 docket
        9 about

date: 2020-01-01
lastmod: 2020-01-01
draft: true
#COMMENT publishDate:
#COMMENT expiryDate:

#COMMENT resources: Maps of metadata for page resources.
#COMMENT markup: org
#COMMENT type: subfolder-of-layouts-iff-layout-is-nested
layout: category
outputs:
- html
- markdown
THREE HYPHENS ON THIS LINE

~ ~ ~ ~ ~ ~ ~
</pre>

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Sed ut perspiciatis, unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam eaque ipsa, quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt, explicabo. Nemo enim ipsam voluptatem, quia voluptas sit, aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos, qui ratione voluptatem sequi nesciunt, neque porro quisquam est, qui dolorem ipsum, quia dolor sit amet consectetur adipiscing velit, sed quia non numquam do eius modi tempora incididunt, ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrumd exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur. Quis autem vel eum irure reprehenderit, qui in ea voluptate velit esse, quam nihil molestiae consequatur, vel illum, qui dolorem eum fugiat, quo voluptas nulla pariatur.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

At vero eos et accusamus et iusto odio dignissimos ducimus, qui blanditiis praesentium voluptatum deleniti atque corrupti, quos dolores et quas molestias excepturi sint, obcaecati cupiditate non provident, similique sunt in culpa, qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerudum facilis est ert expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio, cumque nihil impedit, quo minus id, quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendaus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet, ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.