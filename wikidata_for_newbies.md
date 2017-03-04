#Wikidata for newbies

This is a work in progress. Please fork and contribute to this page to improve it.

##What is wikidata?

[Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) evolved after [Wikipedia](https://www.wikipedia.org/) had existed for some years.

Here's the definition from their website:

>Wikidata is a free and open knowledge base that can be read and edited by both humans and machines.

>Wikidata acts as central storage for the structured data of its Wikimedia sister projects including Wikipedia, Wikivoyage, Wikisource, and others.
>Wikidata also provides support to many other sites and services beyond just Wikimedia projects! The content of Wikidata is available under a free license, exported using standard formats, and can be interlinked to other open data sets on the linked data web.

##What is wikidata useful for?
Identifiying things and categorising things.
Link on website but broken links - needs more research

##Is Wikidata only used for Wikipedia? 
Sort of - growing rapidly, please don't take this as gospel

###How is Wikidata is used in Wikipedia?
What's the relationship - roughly two ways that things come into wikidata.

1. Wikipedia info boxes - these vary accordinng to the discipline. When they started they weren't systematic and a lot of effort has gone into rationalising this. Wikidata is used to update the info box, so edit Wikidata and that updates the info box 
1. From 3rd party data sources. Historically 2-3 large dbs including Freebase. A lot of Wikipedia articles have a freebase identity. Freebase has now been taken over by Wikidata. Freebased came from Semantic web an idea of Tim Berner-Lee, which describes the world in triples e.g. Okapi (object) ```<is an>``` (property) animal (object). Can have a qualifiers e.g. Britain is part of Europe until xyz (times) or Theresa May says Britain is part of Europe (authority).

In Wikidata, there are around 25million items and hundreds of millions of triples (object->property<-object).

Uses authoritative 3rd party info e.g WHO etc Listed buildings in the UK which comes from Historical England 100k listed buildings.

###Can I edit these? 
Depends on who the authority is and what has changed. Edits preferred from the producers of the information. Have to be able to hold synonyms and aliases. Drugs for example have a lot of synonyms. It means you can map use from one dictionary to another.

##Can I add my data directly to Wikidata? 
Technically yes, Wikidata doesn't just want bulk pushing. The community wants to feel happy that these are in some way important to put it. Do you want to be comprehensive (e.g. ICD10) or not (e.g. list of chemicals). May only want information if it's been cited or noted somewhere denoting importance. 

##Is it the same process for editing Wikidata as Wikipedia? 
Because it's a formal system, have to be careful not to break it. Use a good editing tool to prevent errors and be correct at semantic level.

##Is Wikidata a database in itself? 
Wikipedia holds all of the triple store information itself. All of the identifiers are copied and held in wikidata, if there is an identifier in ICD10 e.g. Cholera then you can use that identifer and either link back to ICD10 or use in Wikidata. If changed in ICD10 would have to be manually changed in Wikidata. May not be easy to pick up as publication of changes may not be structured.

##Can I do automated additions? 
Does wikimedia community think this is a good thing? There are debates about wether things are ephemeral or not and around objective merit.

##Can I create automated wikipedia articles using my existing data through wikidata? 
Maybe

##How does Wikidata know that data has changed? 
Manually edited and questions around how this is done.

#Unanswered questions

* Who's the authority behind wikidata and how is it managed?
* Is Wikidata the "Single Source of Truth" (SSOT)?
* Does wikidata record the SSOT for the data it provides?
* How skewed is the data in Wikidata?

#Pro-tip
* When you read something, don't understand it or want to challenge it, you put a talk item in and hopefully someone will respond.
* Always going to be repos and data that live outside wikipedia, how do people find them. Risk of lopsided information about certain subjects.
