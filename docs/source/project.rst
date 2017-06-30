The project scope
=================

A formal representation for the grammar of Esperanto
----------------------------------------------------
This project comes from the question: *which could be the best natural 
language for vocal interaction between humans and computers*?

Esperanto was therefore considered, an artificial language officially
born in 1887 for pleasure and thanks to the work of Polish Doctor
Zamenhof, a passionate linguistics studier that wanted to develop a language purely
international. From this, Esperanto was adopted by a significant
community of speakers in all the world really able to maintain a serious conversation 
in this language (see Esperanto on Wikipedia). 
The choice of Esperanto was thanks to its simplicity and regularity of 
its grammar that makes it easier for computing systems to manage 
the structure of the language.

The project "Ontology of Esperanto" is proposed as one of the first 
attempts to produce a formal representation of a *non formal* language 
(natural language), based on the Semantic Web standards.

The goal was to develop an ontology usable into NLP software 
tools that can make easy a computer understand the logical form of varying 
complexity phrases expressed in Esperanto.
From here we can imagine a scenario which on the Semantic 
Web becomes available innovative services that allow users perform 
queries in natural language for accessing data and documents, without having any expertise 
in formal query languages.

The OWL-DL ontology of Esperanto
--------------------------------

Ontology is written in OWL-DL, a version of the language recommended
by the W3C for the Semantic Web, using Protégé, the ontology editor 
developed by the University of Stanford (US), that uses the 
automated reasoning services of Racer, the semantic reasoner developed by
the University of Luebeck (D). The ontology in reality are three: one for
the *grammar analysis*, one for the *logical analysis* and one for the
*analysis of the sentence*, where the highest level ontology refers to
concepts at lower levels. In this way, once the various parts of the
text is qualified at lower levels, so the higher levels can be automatically 
inferred.

-  Download the ontologies:

   -  `Grammar Analysis <https://github.com/Epistematica/esperanto-ontology/blob/master/src/EsperantoGrammarAnalysis.owl>`__
   -  `Logical Analysis <https://github.com/Epistematica/esperanto-ontology/blob/master/src/EsperantoLogicalSyntagmaticAnalysis.owl>`__
   -  `Period Analysis <https://github.com/Epistematica/esperanto-ontology/blob/master/src/EsperantoPeriodAnalysis.owl>`__
   

 |
 |
 