# Quick introductory exercises

_Targets a group of 6-10 participant anatomists._

## A. "Naive" ontology building 

* Everyone in the room will write down 1-3 general anatomical labels (depending on group size); do this without overthinking it, random is good, do it without sharing your concepts to start
* Share/compile your labels with the rest of the group, record them in one place (whiteboard/Google doc) so that everyone has access to them

* For a strict 10 minutes only:
  * In partners, develop an "ontology" that begins to turn these labels into terms (add concepts), use [Vue](https://vue.tufts.edu/) or another concept mapper to do this
  * Background knowledge is only what has been covered prior 
* As a group:
  * Use a stand-up format to have each group spend one minute to describe their ontology and the reasoning behind it.
  * Discuss how the ontologies differed.
    * After seeing other's ontologies how would you change yours?
    * What was particularly difficult in designing the ontology?

## B. From concept to ontology

* In partners define 3 structures (from A) however you want (randomly chosen). Be technical, express your understanding as you would to other experts in the field.
* Compile these terms into the Google doc table 
* In Protégé instructor will
  * Add three classes, head, thorax and abdomen (or very generally understood concepts pertinent to domain experts experience)
  * Create one object property `part_of`
* With one of the instructor sharing their screen
* Instructor will choose 3 terms and demonstrate accessioning it in the ontologies
  * Highlights:
    * Set the default IRI
    * Create a class
    * Create an object property
    * Create a subclass relationship
    * Demonstrate creating at least one NL definition
    * Demonstrate re-use of existing URIs/concepts/object properties
    * Demonstrate creation of an individual
* Save and share the work as it exists
* Create groups of 2-3. Each group will:
  * Load the initially saved file
  * Change the IRI
  * Accession an assigned concept of the remaining concepts 
  * Save and share their ontology with a new filename
* Instructor then uses Imports to load all files
  * Demonstrate duplicates and problems
  * Discuss with the group how Import patterns might be setup early in ontology design stage
  
### Learning points
* Difference b/w filename and IRI of ontology
* How might you merge the individual ontologies?
* How do we do this in real life? Highlight the [the GO approach](http://geneontology.org/docs/contributing-to-go-terms/) 

### Tips
* Don't get caught arguing about definitions, try to accession "what is asserted", accept the terms as they are

