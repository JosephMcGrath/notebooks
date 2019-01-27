# Metadata Massive Open Online Course: Unit 1 - Organizing Information

Series by Jeffrey Pomerantz, University of North Carolina

## [1-1: Introduction](https://www.youtube.com/watch?v=fEGEJhJzrB0)

Metadata tells us about things. Can be simple things like title, author etc but can include much more information (e.g. the sensor used to collect data). In the internet, metadata's recorded all over the place (and a lot of information is often recorded behind the scenes).

The metadata can be created either by the creator of the data itself, other people or automatically by the system. Additional metadata can be created on top of other data (ad. infinitum.).

Different metadata schemes have shared elements, and also information more specific to an individual application.

## [1-2: The NSA](https://www.youtube.com/watch?v=QC5I1vEI0tc)

At the time the course went up, a story about [the NSA](https://en.wikipedia.org/wiki/National_Security_Agency) collecting metadata on phone calls was big in the news. This meant they could get around the wiretapping regulations. The metadata being covered most was:

* Number making the call,
* Number being called,
* ID of the cell tower (so some location information too),
* Time & duration of the call,

This can basically be used over accumulated data to track a wide range of people. The take-home message here is that metadata alone can have a large impact:

> Metadata *is* data.

See also traffic analysis of Enigma messages in WWII, where message headers were used to build up a map of German military organisations.

## [1-3: OSX Mavericks](https://www.youtube.com/watch?v=wHlP-gwHFZA)

Another example of metadata in the news. *OSX Mavericks* was Apple's latest opertating system at the time. This introduced a system of 'tags' that allows **descriptive metadata** to be assigned to files at an operating-system level.

This is also a case of metadata being used under another name, which often happens in the wild.

## [1-4: Data About Data](https://www.youtube.com/watch?v=-d_8X5zAMVw)

An unhelpful definition of metadata is that metadata is data about data. This is accurate, but doesn't tell us much. Another version might be:

> Metadata is description.

Though raises 2 questions:

1. Description of what?
2. What does it mean to describe something?

The second is handled in the next video. As for the first, the 'what' can be pretty much anything. You can divide things up as you like (e.g. natural vs artificial or physical vs digital) but it doesn't matter, though the nature of the metadata might change.

When you describe something you make a statement about it. In any natural language you have a **subject**, the **object** (the thing acted upon by the subject) and the **predicate** (the relationship between the subject and the object). This three-part relationship will become more important later. The thing being described can be an information object too (so the 'data about data' definition can become recursive).

Not all statements are descriptive (e.g. 'this side up' is an instruction). They can be useful in metadata, but aren't relevant at this stage. (**Reference out where this is used later.**)

## [1-5: Description](https://www.youtube.com/watch?v=og4nUn_Nec0)

There's a lot of overlap in ideas about description between 'Information Science' and 'Library Science' (though the link between the two is [not without controversy](http://people.ischool.berkeley.edu/~buckland/20THCENT.pdf), reading around this looks to be about how the similar concepts are approached). Quite often they are combined to 'Library and Information Science'.

Because librarians have been describing things for such a long time they're quite effective at applying descriptions to things, defined as:

> For the purposes of storage and later retrieval and use.

Particularly in large collections, finding anything is going to be difficult without *access points* (library jargon). The most common access points would be:

* Title,
* Author,
* Subject,

These come from a long history of libraries working out that simple description is effective.

Depending on your worldview, things like house numbers or packaging labels could be considered metadata. These are *Administrative Metadata*.

### Subject Analysis

In Information Science, determining what something's about is *subject analysis* (what are the significant characteristics). Sometimes this is easy, but often it's difficult (title is often not related to the subject directly e.g. Moby Dick is not just about the one whale). The tricky thing is working out what is significant and what is a characteristic? This can be subjective and is context-sensitive.

Some things might not have a subject (a lot of music isn't *about* something). There's ways around that **Reference out where this is used later.**).

The word *aboutness* is sometimes used here as it comes with less baggage than *subject*. Not returning to that here.

## [1-6: Item vs. Collection](https://www.youtube.com/watch?v=bexOzdR0vxc)

There is a distinction between *item-level* description and *collection level* description.

* Item = single object
* Collection = aggregation of objects
    * May be the same type of thing

As an example using [scientific papers](https://firstmonday.org), the abstract is item-level description whereas information about the journal is collection-level metadata.

[Europeana](https://www.europeana.eu/portal/en) - interesting project that contains a collection of projects. Has online collections that cut across multiple different institutions.

## [1-7: Library of Congress Subject Headings (LCSH)](https://www.youtube.com/watch?v=gCgA5ZHUkN4)

A real-world example, but an mature and widely applicable one. It's a *very* comprehensive set of subjects to apply to books. In this context 'subject' can also be 'index term', 'descriptor'. It's also different to the Library of Congress classification which is a way pf assigning a 'call number' to each item.

The [full list](https://www.loc.gov/aba/publications/FreeLCSH/freelcsh.html) is *huge*. This is basically a 'controlled vocabulary' - a set of words that are the *entire* set of acceptable words to be used. This is different to dictionaries which are a list of words but don't claim to be all the words that *can* be used.

## [1-8: Thesauri](https://www.youtube.com/watch?v=iN29TaNo6Fw)

In this context, 'Thesaurus' is almost synonymous with 'Controlled Vocabulary'. The traditional thesaurus is just a list of synonyms and antonyms for words or phrases. For a controlled vocabulary there's still a list of words and relationships between words. These words are carefully selected.

The list of words used is suited to the specific use case. Vocabularies vary both in terms of breadth and depth. More specific applications will be deeper.

A controlled vocabulary is to define the entire set of entities we care about. They can be linked, e.g. in the Library of Congress Subject Headings define relationships between terms. One particular link here is the 'Use For' and 'Use' relationships, which define the proper terms to use instead of other items (very useful for maintaining a controlled vocabulary).

An example term here is:

* Term - Information Science
* Scope note - Study of the gathering, organizing, storing, retrieving and dissemination of information
* Broader term: (fields and discipline)
* Narrow term: Archival Science, Informatics...
* Related term: Cognitive Science, Computer Science...
* Use for: Library and Information Science....

So this defines a tree-structure of the terms. One snag is that different use-cases will determine the definitions.

> The bias of that organisation tends to affect the hierarchy.

This is discussed in more detail in [Sorting Things Out, Classification and Its Consequences](https://mitpress.mit.edu/books/sorting-things-out﻿) by Geoffrey C. Bowker and Susan Leigh Star.

## [1-9: Faceted Classification](https://www.youtube.com/watch?v=90eU5Pa5KAs)

It's possible to use multiple controlled vocabulary to describe one thing. This allows for *faceted classification* - description of one thing in several ways. This is particularly useful to have standardised ways to describe a particular aspect of something (e.g. a language or a colour).

As before, the controlled vocabulary you choose is dependent on the context - what we want to know about each thing. This maintains the ease of producing precise queries.

## [1-10: Ontologies](https://www.youtube.com/watch?v=oTMJa1Q08IY)

> Ontology: Formal representation of a set of concepts within a domain.

This goes beyond controlled vocabularies, which go beyond just a list of entities. The ontology basically describes a set of entities that exist when you're talking about a specific context. The example given here is the [Beer Ontology](https://www.cs.umd.edu/projects/plus/SHOE/onts/beer1.0.html) that outlines a way of describing beers.

This goes beyond just a set of properties for *an item*, describing a series of related items (e.g. breweries for the Beer Ontology) and also defines logic about the relationships between these items. There seems to be a bit of crossover with relational databases here.

Another example is the [Personal Ontology](https://www.cs.umd.edu/projects/plus/SHOE/onts/personal1.0.html) that describes a bunch of entities, their relationships and inferences that can be made from those relationships.

## [1-11: Uncontrolled Vocabulary](https://www.youtube.com/watch?v=xAemTzf5lYI)

Uncontrolled vocabularies are basically a free text field for metadata. One of the most common types of these is a *tag*, which a lot of different sites use. They are generally used to make searching easier but because they're Uncontrolled there can be a lot of duplication on the tags that get applied to a single person.

With things like hashtags, the tags aren't always describing the tweet itself, but more the motivation / background of the tweet - or even some user-specific applications. They are also be *part* of the tweet and so are part of the data *and* part of the metadata.

In uncontrolled vocabularies, patterns still emerge between users, but also tags diverge (even with typos etc). In live systems these systems are useful to track unpredicted trends. Some of these patterns can be a bit opaque to outside users (acronyms etc).

There's also some ongoing work into using uncontrolled vocabularies to update controlled ones.

## [1-12: The map is not the territory](https://www.youtube.com/watch?v=gqtuUie03wY)

This lecture points out that the relationship between metadata and the thing it describes is a simplification. This relationship is similar to the relationship between maps and the real world. It's a massive simplification but it is a *very useful* simplification that lets us work with a large and complex space and the features may be selected or muted depending on the context.

The same is also true of the relationship between a vocabulary and natural language.

> The map is not the territory but the map is more useful under certain conditions.

## [1-13: Purposes of Metadata](https://www.youtube.com/watch?v=rxm5pH_e6pE)

Metata isn't always describing the features of a thing, but is the structure of a thing or what you can do with it. The three main categories of metadata here are:

* Descriptive - Information about a resource,
    * E.g. title, author, published date, file format
* Structural - Information on how a resource is organised,
    * Often describing compound objects (e.g. book, chapters, sections, pages),
    * Provides a map of the structure / organisation of the resource,
* Administrative - How an object should be stored / cared for,
    * E.g. copyright / IP, access, origin (*provenience*),
    * Subcategories are *Rights* and *Preservation*,

And also subcategories, but that's later.

## [1-14: Important distinctions](https://www.youtube.com/watch?v=uQ2dd2L25yc)

Important distinctions for metadata:

* Level - item or collection,
    * Some semantics here (is a book an item or a collection of chapters or pages),
* Embedded or linked: Is the metadata in the object,
    * E.g. the copyright page in a book vs a card catalog,
* Human or machine readable,
    * Not a hard distinction (e.g. HTML can be readable),

## [1-15: Metametadata](https://www.youtube.com/watch?v=5HXah6IMyq8)

## [1-16: Introduction to Information Science](https://www.youtube.com/watch?v=Y-PbRKHKoU8)

## [1-17: What is information?](https://www.youtube.com/watch?v=vkPyJNEv1Dk)

## [1-18: Conclusion](https://www.youtube.com/watch?v=Ac8nZOzjprE)
