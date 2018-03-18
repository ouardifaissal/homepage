+++
title = "Extended to multi-tilde-bar regular expressions and efficient finite automata constructions"
date = "2015-09-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Faissal Ouardi", "Jean-Marc Champarnaud", "Djelloul Ziadi"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In Journal of Discrete Algorithms, 33: 58-70."
publication_short = "In *Journal of Discrete Algorithms, 33: 58-70*"

# Abstract and optional shortened version.
abstract = ""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/pdf/1306.3507.pdf"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "jda.jpg"
#caption = "My caption :smile:"

+++
Several algorithms have been designed to convert a regular expression into an
equivalent finite automaton. One of the most popular constructions, due to Glushkov
and to McNaughton and Yamada, is based on the computation of the Null, First,
Last and Follow sets (called Glushkov functions) associated with a linearized version
of the expression. Recently Mignot considered a family of extended expressions
called Extended to multi-tilde-bar Regular Expressions (EmtbREs) and he
showed that, under some restrictions, Glushkov functions can be defined for an
EmtbRE. In this paper we present an algorithm which efficiently computes the
Glushkov functions of an unrestricted EmtbRE. Our approach is based on a recursive
definition of the language associated with an EmtbRE which enlightens the
fact that the worst case time complexity of the conversion of an EmtbRE into an automaton
is related to the worst case time complexity of the computation of the Null
function. Finally we show how to extend the ZPC-structure to EmtbREs, which
allows us to apply to this family of extended expressions the efficient constructions
based on this structure (in particular the construction of the c-continuation automaton,
the position automaton, the follow automaton and the equation automaton)


