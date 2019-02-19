# Week4 - Object Relational Mapping (ORM)with JPA (Java Persistence API)

## Business Competences
This week will enable you to work with databases through an Object Relational Mapping Framework. The focus is on
java/JPA, but the core concepts are widely applicable in almost all technologies "out there".

## Readings for this week

[:book: Java Persistence](https://en.wikibooks.org/wiki/Java_Persistence) (Wikibook). This should be your main reference for most of you JPA-related questions. See detailed instructions for how to read below, and what to read under the section for each day 

**Important when you read the Wiki** _In most of the "technical" sections, you will find two examples. One, who specifies the mapping with annotations and another (the old way) who does it via XML-mappings *We will ONLY use annotation based mappings, so you can ALWAYS skip the XML-parts*. Don't be scared about "all" the links in the following. They are all just small sections in the same (wiki) book._

## Day 1 (Tuesday) Introduction to ORM 
What/why is an ORM, install eclipselink+mysql dependencies, generate tables,
generate classes (reverse JPA), the persistence unit, the Entity class, the
EntityManager.



### Before this lesson you should
Read the following for day-1
* [:book: Wikipedia Article(5 min.)](https://en.wikipedia.org/wiki/Object-relational_mapping). Only read the first section, to get an overall idea about ORM. This is a concept you will find in almost all modern technologies (Java, .Net, JavaScipt, PHP etc..)
* 3.3 [:book: What is JPA (5 min.)](https://en.wikibooks.org/wiki/Java_Persistence/What_is_JPA%3F)
* 3.7 [:book: Why use JPA or ORM? (5 min.)](https://en.wikibooks.org/wiki/Java_Persistence/Why_use_JPA_or_ORM%3F)
* 4.0 [:book: Java Persistence/Persistence Products (3-5 min. Skim only)](https://en.wikibooks.org/wiki/Java_Persistence/Persistence_Products) (we will be using EclipseLink)
* 5.0 [:book: Mapping (5 min.)](https://en.wikibooks.org/wiki/Java_Persistence/Mapping) Read down to the Access Type Section.
* [:BOOK: 5.1, 5.2, 5.4, 5.6 (skim only)](https://en.wikibooks.org/wiki/Java_Persistence) SKIM these sections, so you know where to come back, when you start with the exercises
* 6.2  [Persisting (Inserting, Updating, Merging) (10-15 min.)](https://en.wikibooks.org/wiki/Java_Persistence/Persisting) Read until the section Advanced.

### Exercises
- [Day-1](https://docs.google.com/document/d/1e7Xyj_dCH6QkYIZ1zd2nE2XBffwCQ9LWxbMX7AGM-4U/edit?usp=sharing)

### Slides
[ORM Intro](https://docs.google.com/presentation/d/1IDeoEtchqX88Jo0JBSNOIhJkOWHl86BvFL9laGnW_MM/edit?usp=sharing)

## Day 2 (Wednesday) - Relationships 
Relationships, cardinality, directionality and Inheritance (only red students)

### Readings
**Important:** Make sure your have read the section "Important when you read the Wiki" earlier in this document

From this [chapter](https://en.wikibooks.org/wiki/Java_Persistence/Relationships#JPA_Relationship_Types) in the wikibook you should read:

[Relationships (skim only)](https://en.wikibooks.org/wiki/Java_Persistence/Relationships#JPA_Relationship_Types). Make sure to follow and skim these links in this section :
* [:book: OneToOne (5 min.)](https://en.wikibooks.org/wiki/Java_Persistence/OneToOne)
* [:book: ManyToOne (5 min.)](https://en.wikibooks.org/wiki/Java_Persistence/ManyToOne)
* [:book: OneToMany (5 min.)](https://en.wikibooks.org/wiki/Java_Persistence/OneToMany)
* [:book: ManyToMany (5 min.)](https://en.wikibooks.org/wiki/Java_Persistence/ManyToMany)
* RED ONLY :arrow_right: [:book: Java Persistence/Inheritance (5-10 min)](https://en.wikibooks.org/wiki/Java_Persistence/Inheritance) ONLY RED STUDENTS

### Exercises
- [Day-2](https://docs.google.com/document/d/1pJYALzFkZlGHKSN2PtvdJXL9UYg5oB0PEj2Sx6aZmkE/edit?usp=sharing)
- [Mapping Inheritance (RED ONLY)](https://docs.google.com/document/d/1qhIuA5MuIR-YYVUsvTsI6LGEOQxOPEopBrAkoHhopaI/edit?usp=sharing)

## Day 3 (Thuersday) - Quering with JPQL
JPQL-queries 
- [:book: Java Persistence/Querying 10 min. (Read until the section "Common Queries")](https://en.wikibooks.org/wiki/Java_Persistence/Querying#Common_Queries) 
- [Common Queries (Skim only)](https://en.wikibooks.org/wiki/Java_Persistence/Querying#Common_Queries) Skim all sections to see what you can do. You will need this for the exercises.
- For your reference [JPQL (Skim Only)](https://en.wikibooks.org/wiki/Java_Persistence/JPQL) This is an extra section in the wiki, which is kind of a complete referende to JPQL

### Exercises
- [Day-3](https://docs.google.com/document/d/1tbVNQe4rbiVf4uKQAiugeTwYRas0qLBvnrTxEhzxnf4/edit?usp=sharing)

## Day 4 (Friday) - Friday Exercises

[Friday](https://docs.google.com/document/d/1kIDFD49vfMOlL0lPjG_DOc4PP8Gj0NamNl2F5BX9Xmc/edit?usp=sharingg)

### Extra Material for this week

The following tutorial from netbeans, as well as a couple videos Christian made, may help you through the JPA setup process if you forget it after the lecture. These are not useful learning resources. I recommend only using them if you forget how to setup the persistence unit, and do table/class generation with JPA.
- [List of ALL JPA-annotations](https://www.objectdb.com/api/java/jpa/annotations)
- [netbeans persistence unit tutorial](http://wiki.netbeans.org/SimpleJPAApplicationWithNetbeans#Create_Persistence_Unit)
- [Video JPA setup](https://www.twitch.tv/videos/168683174)
- [Video JPA database table -> entityclass](https://www.twitch.tv/videos/168934609)
- [Video JPA relationships](https://www.twitch.tv/videos/168939780)




