
mapping of the debate stucture is as such

## entities
- a set of Statements - 140 char strings - can read emotion, mention count
- a set of Relations between the given statements - all under different Logics, it can't be otherwise. Some logics can be derivable by default from others. But the standard logic is the champion. no need to deal with nonclassical logics in the mvp. still the logic module provides possible operators

### example
moon is made of cheese <- type of justification (tbh that's from Melange's notes!) <- it has holes

some logical statement <- logical justification <-

if you make AND it launches mode warning of logical errors


relations are ALWAYS questionable, no need to check whether given 2 nodes are attacked their relation or themselves

## Logic 
current logic is always asked for
- has name, possible operators, truth values, and rules of derivation from A and B where A, B are statements of diff truth values. 
standard logic = 

- available operators
- computes truth functions. tension between 'supports' and 'is true' relations
- 'support' can be on the basis of formal logic, or not
- nodes connected by operators only are formal logic - compliant
- the moment you say AND, OR, XOR, etc, logic begins
- should be able to highlight that

every statement can have a link reference

evaluation of operators is first 20 characters and ...; unless that's not identifying enough

user chooses the logic type to display. but the argument is saved in the standard way regardless




### what people get displayed
is decided by an algorithm decided to drive up the size of the corpus?
or maybe competitively with quality and interconnectedness of the corpus

### population features
- Population view - set of relations with mappings of numbers about who agrees about what
- Position - a coherent set of Relations under a given logic - logic is chosen separately, you can switch between them. can be compared. cam be counterfactual
- documents - ordered list of arguments, main sorting feature is the author. numbering is provided
- topics - list of arguments, main sorting feature is popularity and keywords. each of these is possibly infinite in depth! but display only up to some points
- arguments - a tree of Statements with decided Relations, finite in scope. 
- Jain logic view - it is a function of a set of arguments and their popularity data
document metadata


### derived entities
User
- name
- positions
- topics most used
- public: if True, it's a Speaker
- 



### using the ghost api to drive real stories, linked to Lully content
https://ghost.org/docs/content-api/




## exports
everything can be changed to 
- json
- csv
- string
- avro https://www.npmjs.com/package/avro-js
- GML

roles
- writer - creating a Document
- scroller - performing exploration by topics, getting a feed of arguments


a quill option for the writer role
different argument windows

https://www.reddit.com/r/reactnative/comments/hvxc4s/what_is_the_best_rich_text_editor/
https://stackblitz.com/edit/github-rgxgkc?file=pages%2Findex.js

now the logic module - that is the main concern
now different types of relations can occur between the arguments - short strings, up to 140 characters

## logic consideration
is Logic only available in display?


there should be only 1 level of complexity allowed in the statements


## from definitions
it can't be

why are defintions like mental objects?
what are physical objects?
what are their properties?
- persistent in time
- can be accessed by different people

so that if talking about chairs is in some sense valid, same appplies to out mental representations, so to speak

but here we just talk about defintions when there is some problem with
the default, implicit ones

about definition
it needs to be exhaustive set of places that it belongs;
so we have the primary definition and exhaustive Definition
but the unique identifiers = by author and timstamp = context sensitive


## from diff
TODO: must get the available logic modules and judge all statements by //
different logics

the module should show aprallel lines, divided by topic
like in 5d chess, isntead of timelines different topics
by default colapsed,so the statements not exactly at the same
and can select just one topic and see it in other works

## search functions
can search for
- tags
- topics
- tags withign topics
- speakers

## quiz game mode
- some current relation
- quit option, yes/no or unsure (null added)
- 