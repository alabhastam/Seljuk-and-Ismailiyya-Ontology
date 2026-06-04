# Seljuk and Ismailiyya Ontology

This ontology is designed to model historical concepts related to the Seljuk period and the Ismailiyya movement. It represents historical figures, states, battles, cities, educational institutions, and religious groups in a structured and semantic way.

## Main Classes

The main classes of the ontology include concepts such as `HistoricalPerson`, `Sultan`, `GrandVizier`, `Fidai`, `Empire`, `Battle`, `City`, `CapitalCity`, `ReligiousOrder`, and `EducationalInstitution`. These classes are used to categorize the key historical entities in the domain.

## Object Properties

Object properties are defined to represent relationships between entities. Relations such as `assassinated`, `assassinatedBy`, `rulesOver`, `ruledBy`, `hasCapital`, `isCapitalOf`, `participatedIn`, `hadParticipant`, `isAtWarWith`, `hasVizier`, and `isVizierOf` allow the ontology to model political, military, administrative, and historical connections.

## Data Properties

Data properties are used to record descriptive and numerical values. Properties such as `birthYear`, `deathYear`, `reignStartYear`, `battleResult`, `religion`, `title`, `govRank`, `height`, and `weight` provide more detailed information about people, states, and events.

## Individuals

In the Individuals section, instances such as `AlpArslan`, `MalikShahI`, `NizamAlMulk`, `AbuTahirArrani`, `SeljukEmpire`, `ByzantineEmpire`, `BattleOfManzikert`, `Isfahan`, `IsmailiyyaOrder`, and `NizamiyaSchools` are added. These individuals represent real examples of the defined classes.

## Rules and Reasoning

Axioms and inference rules are used to improve the analytical power of the ontology. These rules enable automatic reasoning; for example, the ontology can infer that a person is deceased based on an assassination relation, or identify enemy states based on war relations.

## Application

This ontology can be used for organizing historical data, analyzing relationships between people and states, running semantic queries, and visualizing the historical network of the Seljuk and Ismailiyya period.
