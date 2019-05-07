# An Introduction to Anatomy Ontologies

This website is initially an effort to compile resources for a one-day workshop introducing advanced anatomists/morphologists with no prior experience (i.e. "domain experts") to the concept of (gross) anatomy ontologies.

Because a one day workshop can only briefly touch on the depth behind the subject, we approached its organization by building a set of "10 things" lists. These lists can act as a set of talking-points for instructors.  The lists are more or less ordered so that the background required in one list is covered in the prior lists.

This is meant to be an evolving, collaborative effort, to contribute please open an issue  with your question, answer, or anything else you might find interesting (or better yet make a pull request).

These lists are not lists of "bests", they are meant to be demonstrative, and to remind the instructors what to cover.

# Goals of the introduction

There are many different ways to approach the topic, the specific goals for this resource/workshop are:

1) Give anatomists with little or no expertise in formal ontologies the background to ask meaningful questions as their next steps.  I.e. participants should be able to formulate 2-3 questions at the end of the workshop that demonstrate we have peaked their interest, but yet not answered their questions, and thjey should now know where to look next.
2) Highlight and demonstrate existing efforts that focus specifically on the development of anatomy ontologies as they are currently represented in the OBO foundary and elsewhere.
3) Build the broader community of ontology developers by generating excitement about the topic and identifying specific areas where our target participants could contribute

# License

Content here is CC-0.

# 10 Holy grails of anatomy/phenotype ontology backed research

_These are the big questions that drive the little steps forward._

* Unifying biological anatomy (facts)
* Unify biological anatomy (a semantic model)
* Linking phenotypes to genotypes via inference
* Building a global database of phenotypes
* An equivalent to BLAST for anatomy/phenotypes
* Creating native semantic species descriptions (i.e. describing species without the use of Natural Language as a first step)
* Querying genomes via anatomical terms
* Creating a phylogeny derived from a semantic anatomy graphs
* Recording our knowledge of the anatomy of life such that more directly impacts human lives
* ... your big idea here

# 10 Basic concepts about ontologies
* domain of knowledge
* formal
* concepts
* labels
* object properties 
* true path (sets!)
* URIs
* orthogonality
* deprecation
* community

# 10 other ways to represent things (anatomy)
* taxonomy
* glossary
* folksonomy
  * social tag online items
* controlled vocabulary 
* partonomy
* character/state matrix
* [Exploring Taxon Concepts](https://link.springer.com/article/10.1186/s12859-016-1352-7) format
* Property graph
* Linked data
* [RCC-5](https://dl.acm.org/citation.cfm?id=1458484.1458492)

# 10 Intermediate concepts about ontologies
* OBO and OWL
  * lossy/less 
* definitions genus/differentia
* attributes and annotations
* inverse, transitive
* equivalent and disjoint
* classes and instances - abox/tbox
* domains and ranges
* inference and classification
  * engines, limitations
* imports

# 10 Concepts for anatomy ontologies
* CARO
* RO
* PATO
* few object properties properties
* mapping between taxonically scoped ontologies
  * [Mouse-Human](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3308156/)
  * [Arthropod ontologies](https://academic.oup.com/database/article/doi/10.1093/database/bas057/328392)
* genus differentia, the X that is Y
* species names
  * VTO example as one approach, but note issues
* [Phyloreferencing](https://www.phyloref.org/) 
* Homology Ontology
  * TODO: reference ongoing new efforts

# 10 Steps in the lifespan of a term
How does a term get added to an ontology, and what happens after it gets added?  This non-linear process.

Going beyond a term to the broader concept Chris Mungal's [OBO Tools and Workflows ICBO 2018](https://docs.google.com/presentation/d/1nIybviEEJiRKHO2rkBMZsQ0QjtsHyU01_-9beZqD_Z4/edit#slide=id.p) is a nice practical overview.

* Discovery
* Background/orthogonality
* Concept development
* Placement
* Refinement
  * Citation/sensu
  * Subclassing, necessary and sufficient
* Acceptance
  * Announce request 
  * Object request brokers
* Identification
  * Formally minting a URI for the term
* Release
* Deprecation

## Notes
* Use [ontobee](http://www.ontobee.org/) to see ontologies.  
* Notice the metadata regarding how, when, and who is building these ontologies.  This will give you a feel for the diversity of approaches, the time-frames ontologies evolve over, and the tools used to create ontologies. to see ontologies.  

# 10 highlights of a case study - From Snodgrass to the Insect Anatomy Ontology
* Partonomy using Snodgrass 1935
* Literature mining
* Homology, function, development vs. spatial relationships
* Separation of labels and concepts
* Sensu system
* Homonymy
* Images / figures
* DB xrefs
* Community
* Preferred terms
* URI tables 
* Semantic statements

# 10 Tools to aid in building anatomy ontologies

Packages on this list are here because they have specifically been used during the course of developing one or more anatomy ontologies, with emphasis on those that are particularly relevant to introductory use.

* [OBO Edit](http://oboedit.org/)
* [Protégé](https://protegewiki.stanford.edu/wiki/Main_Page)
* [Visual Understanding Environment](https://vue.tufts.edu)
* [ROBOT](https://github.com/ontodev/robot)
  * Asside, other things like ROBOT, (?) not yet used for gross anatomy:
    * [Knotation](https://knotation.org/)
    * [Ontopilot](https://biss.pensoft.net/articles.php?journal_name=biss&id=20192)
* [mx](http://mx.phenomix.org)
* OntoFox
* TODO: Protége plugins 
  * (image viewer)
  * reasoners

# 10 Other software packages
* [Web Protégé](https://webprotege.stanford.edu/)
* [Noctua](http://noctua.geneontology.org/)
* ? [Gra.fo](https://gra.fo/)

# 10 Advanced concepts for (anatomy) ontologies
* [Imports / OntoFox / MIREOT](https://bmcresnotes.biomedcentral.com/articles/10.1186/1756-0500-3-175); [OntoFox](http://ontofox.hegroup.org/)
* BFO
* Manchester syntax
* [Dead simple OWL design patterns (DOS-DPs)](https://jbiomedsem.biomedcentral.com/articles/10.1186/s13326-017-0126-0)
* RDF
* SPARQL
* Vogt's papers
* Tarasov's papers 
* Homology
  * Homology Ontology

# 10 Applications of anatomy ontologies
* Phenoscape
* Phenex
* Mikó's Papers
  * URI tables
  * Manchester syntax representations
    * Targets for modelling  
* Instance anatomies (MorphDBase 2)
* Tarasov's papers 
* Washington et al.
* SCATE
 
# 10 Dos and Don'ts for anatomy ontologists
* Do not create an anatomy ontology "just because"
* Do join an existing effort
  * Do improve someone elses work instead of re-doing it
* Do announce your intentions to the OBO listserv _before_ you start developing your ontology
  * You'll get quick feedback regarding others that might be working on related ontologies
  * You'll reserve your ontology prefix so there are fewer conflicts in the long run
* Do provide definitions for all your terms
* Do anticipate that your ontology will be integrated into UBERON, and design it accordingly
* Do build a diverse community of participants (e.g. other anatomists, even in different fields, technical experts, etc.) around your ontology
* Do expose your work as early as possible via a Git repository
  * It doesn't have to be done, let others see and help you resolve problems before they get burried deep in the complexity
* Don't use too many object properties to start off with
* Do design your ontology so that inference will classify your terms for you
* Do illustrate and cite the terms in your anatomy ontology
 
# 10 things to do next 
* Read the [meeting minutes](https://docs.google.com/document/d/1mFILx6osvNQREHwJxhhnRN38g8LBqSIPGLzGMtBlOTw/edit#) from the 2019 US2TS session on "Challenges for the Semantic Web"
* Visit the OBO listserv
* Attend another workshop
 * Evolution/iEvoBio
* Checkout resources from past workshops
* See what happend at another introductory course: [ICBO 2018 Ontologies 101](http://icbo2018.cgrb.oregonstate.edu/W02)
* Join a community and contribute to their ontology


# 10 Meetings for cross-domain anatomy ontologists
* iEvoBiol ([2019](https://ievobio2019.github.io/2019-iEvoBio/)] 
  * See [call for participation](https://scate.phenoscape.org/2019-workshop-cfp.html)
* ICBO
* (?) US2TS
*
*
*
*
*
*
*

# 10 Things about US2TS
This relative new conference touches on a lot of broader topics pertinent to the broader goals of building semantics for various domains of knowledge. 
* [Biomedical session on phenotypes notes](https://docs.google.com/document/d/1LleF54_KPesC4zNaBrTCfzEbs8pXdYfSY575X79P3NE/edit#heading=h.76h2izcj164m)
* [Semantics and AI Tutorial ex US2TS](https://semanticsforxai.github.io/)
* [Minutes of the 2019 US2TS Session on Challenges on the Semantic Web](https://docs.google.com/document/d/1mFILx6osvNQREHwJxhhnRN38g8LBqSIPGLzGMtBlOTw/edit#heading=h.af4cpcyvw9hu)
* [Read a perspective on the US2TS 2019 meeting (by Juan Sequeda )](http://www.juansequeda.com/blog/2019/03/22/2nd-u-s-semantic-technologies-symposium-2019-trip-report/)
* [2018 meeting](https://docs.google.com/document/d/1r5mU26Ge6sjWa_3DWCRB5-Doy8PZoxDPL3ztUocHaDo/edit#heading=h.7ki05twz69om)


