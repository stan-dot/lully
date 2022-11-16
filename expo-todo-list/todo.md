
# introduction
how does this relate to gamification?
it's the data model behind the game - you don't own the data, Science does. And AGI will be. Then better make it the best data you can, 
to keep our future robot overlords friendly.

games will 
- ask about your truth opinions on statements
- ask about relations on statements
- ask whether a paper confirms its link

thus it will fill in the basic support matrix for relations and truth values for statements

# details
## entities
- a set of Atomic Statements - 140 char strings - can read emotion, mention count (these are atomic in the local sense - that local debate doesn't require bringing them down right now)
- a set of Relations between the given statements - all under different Logics, it can't be otherwise. Some logics can be derivable by default from others. But the standard logic is the champion. no need to deal with nonclassical logics in the mvp. still the logic module provides possible operators

## complex entities
- Position - a coherent set of Relations under a given logic - logic is chosen separately, you can switch between them. can be compared. cam be counterfactual
- documents - ordered list of arguments, main sorting feature is the author. numbering is provided
- topics - list of arguments, main sorting feature is popularity and keywords. each of these is possibly infinite in depth! but display only up to some points
- arguments - a tree of Statements with decided Relations, finite in scope


## editor interaction
if you make AND it launches mode warning of logical errors
using [[wikilinks]]


### type of relation mechanic - from Melange
moon is made of cheese <- type of justification  <- it has holes
some logical statement <- logical justification <-

from 1 statement there can follow many justificatios for different statements, different relations
so 'is example'?
Relation always has type, and logical veracity = boolean by default

relations are ALWAYS questionable, no need to check whether given 2 nodes are attacked their relation or themselves

## supports / attacks as a basic model 
statements have a classical logic truth value, edges are binary support / attack. possibly Lickert scale. do both tbh. might compare just these two.

it truth of a claim only a product of its premises?
not during the whole duration of the discourse
in the beginning it's true somewhere.
rationally closed - can it be only if that is what it boils down to
axioms can't be rationally closed

find disagreements between sets of relations or sets of statements?

convergence quotient = measure of how much do 2 different accounts differ. there is intersection of Relations, indicating whether they have common interests. then agreement as % of leaves of the intersection that are common

- verisimilitude - correspondence to the global Topic list? or some Topic standard
get a golden NFT if epistemic status is high enough

hybrid disourses would be the best afaik
the normal discourse would be a bit different from the 
ALL syntax, 
EXISTS syntax
after a rationally valid argument is made (premise - following concession)
it's an iteration over children to find out 

mapping of the debate stucture is as such

## Logic as a subtype of relation AND a superset of the Statements, where for each one a truth value corresponds
with Classical Logic turned on, every AND Statement on enter splits into substatements

current logic is always asked for
- has name, possible operators, truth values, and rules of derivation from A and B where A, B are statements of diff truth values. 
- available operators
- computes truth functions. tension between 'supports' and 'is true' relations
- 'support' can be on the basis of formal logic, or not
- nodes connected by operators only are formal logic - compliant
- the moment you say AND, OR, XOR, etc, logic begins
- should be able to highlight that

every statement can have a link reference. but it should be a basic statement. 'this linked statement argues X'
evaluation of operators is first 20 characters and ...; unless that's not identifying enough

user chooses the logic type to display. but the argument is saved in the standard way regardless
is Logic only available in display?
there should be only 1 level of complexity allowed in the statements
now the logic module - that is the main concern
now different types of relations can occur between the arguments - short strings, up to 140 characters

### derived entities
User
- name
- positions
- topics most used
- public: if True, it's a Speaker
dynamically derived:
- verisimilitude (progress)across different topics

## search functions
can search for
- tags
- topics
- tags withign topics
- speakers

## quiz game mode
- some current relation
- quit option, yes/no or unsure (null added)

feed order is decided by an algorithm decided to drive up the size of the corpus?
or maybe competitively with quality and interconnectedness of the corpus
