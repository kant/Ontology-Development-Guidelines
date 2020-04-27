# Ontology Development Methodology
Documents succinctly desribing methodological aspects for developing ontologies. They present recommended guidelines and practices, which are also used for the projects contained in this GitHub account

## Sumamry of Dev Method
A generic ontology development methodology includes the following.

PURPOSE:      Identify purpose(s) or function(s) for the ontology.
USE-CASES: 		Identify use-cases for the ontology.
REQUIREMENTS: Identify what will be required to satisfy the use-cases and realize the purpose.
Select tools, e.g., ontology editor software, knowledge representation language, serialization format, etc.
SCOPE: 	      Identify the boundaries of the university of discourse  that the ontology(s) will represent.
RESEARCH:	    Research corpora from the universe of discourse.
LIST: 	      Identify & list specific things in the universe of discourse you want the ontology to represent.
              Identify & list concepts and terms needed to describe the things in universe of discourse. 
              Where a concept (idea or intended meaning) does not have a term to express it, then create one.
DEFINITIONS:  Identify the intended meaning for each of the list of things, concepts and terms.
              May be from dictionaries, publicaitons, subject-matter experts, or custom-made. 
              Identify undefined or primitive terms. 
              Write definitions in natural-language that most closely expresses that intended meaning.
              For all primitive terms, state they are undefined, but also provide a clarifying note to provide the user with
              some sense of meaning. 
STRUCTURE:	  In this process, identify how the things or terms denoting them are related (if at all).
              Create or select terms for how they are related (i.e., for the relationships between them).
              Define these relational terms.
              Use abstract distinctions and structuring relations, e.g., category vs. instance, class vs. member, class and 
              subclass, broader & narrower, etc. 
FORMALIZE:    Develop semi-formal or formal logical definitions. Translate the natural language definitions into first-order
              logic for precision. Translate the n-l def into the chosen ontology language, or ontology editor tool’s language,   
              e.g., OWL, etc.
	            Formal definitions may use the labels to better foster automation.

