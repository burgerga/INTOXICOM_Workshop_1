---
title: 'INTOXICOM Workshop Report: FAIRification of Toxicological Research Output: Leveraging ELIXIR Resources'
title_short: 'INTOXIOM #1: unknown chemical substances'
tags:
  - toxicology
  - ELIXIR Europe
authors:
  - name: Marvin Martens
    affiliation: 1
  - name: Egon Willighagen
    affiliation: 1
affiliations:
  - name: Dept of Translational Genomics, NUTRIM, FHML, Maastricht University, Maastricht, NL
    index: 1
date: 29 May 2024
cito-bibliography: paper.bib
event: INTOXICOM
biohackathon_name: "INTOXICOM Workshops"
biohackathon_url:   "[https://biohackathon-europe.org/](https://elixir-europe.org/internal-projects/commissioned-services/integrating-toxicology-community)"
biohackathon_location: "Utrecht, 28-29 May 2024"
group: Workshop 1
git_url: https://github.com/BiGCAT-UM/INTOXICOM_Workshop_1
authors_short: Martens \emph{et al.}
---

# Introduction

This document reports on the first workshop held by the ELIXIR
Toxicology Community [@citesAsRecommendedReading:Martens2023ELIXIR]
as part of the
INTOXICOM Implementation Study workshop series [@citesAsEvidence:INTOXICOM],
held in Utrecht on May 28 and 29 2024 [@citesAsEvidence:Aanmelder]. The topic of
the meeting was the FAIRification of toxicological research output, including how
ELIXIR resources may be able to help here. The meeting was organized by a team
of ten people from the ELIXIR Toxicology Community: Marvin Martens, Penny Nymark,
Iseult Lynch, Meike Bünger, Rob Stierum, Thomas Exner, Egon Willighagen, Ammar Ammar,
Dominik Martinát, and Karel Berka. The target audience of this first INTOXICOM
workshop was toxicologists with an interest in using FAIR data resources for their
research or in making their data (more) FAIR, as well as data managers/stewards
and researchers working with adverse outcome pathways (AOPs).

The workshop included presentations and working sessions around various topics.
The INTOXICOM described the first workshop as having two parts. The first part
of the workshop would focus on applying FAIR solutions to toxicology databases
and datasets. Part of this was describing the use of compact identifiers to link
to specific records in databases in narratives such as project deliverables, e.g.
in PARC [@citesForInformation:PARC].

The second part would focus on Adverse Outcome Pathways (AOPs) in the AOP-Wiki.
The workshop will explore the FAIRification of AOPs and AOP-Wiki, making AOPs
findable in more ways, and continues on the efforts of the CIAO project
([ciao-covid.net](https://ciao-covid.net/)) that assesses the FAIRness of
AOPs [@citesForInformation:CIAO2022]. The output of this part would be the FAIR
Implementation Profile for AOPs.

The planned delvierables for the workshop
include: 1. this report; 2. a FAIR Implementation Profile for AOPs; and, 3.
a proposed standard on how to use compact identifiers on project reports.

This report will describe the program of the actually held workshop, link to
presentations (where possible), and discuss the hands-on work done and results
from that.

# The workshop

The workshop was attended in person in Utrecht (The Netherlands) by 16 people on the first day,
with two people giving an online presentation, and X people on the second day.
Participants came from various universities (Karolinska Leiden, Maastricht, ...,
Leibniz, and Birmingham),
research institutes (TNO, EU-JRC, RIVM), regulators, and various ELIXIR Platforms.
Ongoing toxicology projects that people are involved in included VHP4Safety,
PARC, and PINK. Participants came from The Netherlands, Italy, UK, Germany,
Czechia, and Sweden.

## Presentations

To introduce ELIXIR, the ELIXIR Toxicology Community, the scope of the meeting,
and the various workshop sessions, several speakers presented their ongoing
work. Table 1 gives an overview of the presentations.

Table: Presentations at the workshop.

| Speaker | Talk Title  |
| -------- | -------- |
| David Lloyd | ELIXIR Introduction |
| Marvin Martens | ELIXIR Toxicology Community |
| Iseult Lynch | FAIR data to support Chemical Risk |
|              | Assessment & Regulation – the PARC |
|              | approach for toxicological data |
| Rob Stierum | Compact IDs - identified challenges |
| Egon Willighagen | Introduction to hands-on session data |
|                  | FAIRification |
| Penny Nymark | What is an Adverse Outcome Pathway? |
| Clemens Wittwehr | Why Adverse Outcome Pathways need |
|                  | to be FAIR |
| Marvin Martens | FAIR AOPs - identified challenges |
| Ulrike Wittig | ELIXIR Data Platform |
| Marvin Martens | FAIRsharing Toxicology Collection |
| Iseult Lynch | Welcome to FIP.27.W.1 |
| Penny Nymark | Data vs. metadata in an Adverse Outcome |
|              | Pathway |

The meeting covered a few topics on the interface between ELIXIR and the
toxicology community. The first topic was generally FAIRification of research
output (an guiding defintiion is found in [@citesForInformation:Houweling2023]).
A main aspect of this part of the workshop was around making
data FAIR, ambitions, and practical challenges. This part included a workshop
discussion and writing a guidance document on making project reports more
interoperable with compact identifiers.

This part was followed by a hands-on session around FAIRificiation recipes in
the ELIXIR FAIR Cookbook. To decide on the topics of the recipes, several
data challenges were identified. Partly, these challenges were collected before the
workshop in the preparatory webinar.

The first day ended with a third topic, around making adverse outcome pathways
(AOPs) more FAIR, continuing on earlier work by the CIAO project and feeding
into the continued development of the AOP-Wiki.

The second day started with session on the ELIXIR Data Platform and the
FAIRsharing Toxicology Collection. This collection has been an ongoing collaboration
between the ELIXIR Toxicology Community and the FAIRsharing project, recently
boosted by a FAIRsharing Community Champion project.

The main focus of the second day was around the topic second hands-on session,
FAIR Implementation Profiles (FIPs). These FIPs formalize a community partice
or even standard that guides members of those community, and possible even
outside that community, with minimal expectations and best practices.

# Results

This section gives an overview of the main outcomes of the sessions of this
workshop.

## FAIR standards and challenges

One of the outcomes of the workshop comes from the discussions. Where ELIXIR
already provides many solution for FAIR, adoption in projects and communities
is not trivial. PARC is adopting various solutions, invluding FIPs and FAIR
Data Points (FDPs) [@citesAsRecommendedReading:Silva2022FAIR]. Community
standards like IUCLID6 and the Toxicology Process Ontology (TXPO) were mentiond.
Other toxicology projects adopted solutions including repositories like the
EMBL-EBI BioStudies, OpenAIRE, and Zenodo. The role of global unique identifiers
comes up, including the Nano-InChI [XXXX] and the European Registry of Materials
(ERM) identifier [XXXX] as metadata for datasets to indicate what chemicals are
studied in those datasets.

Challenges the toxicology community faces include incomplete interoperabilty,
lack of adoption of unique identifers, and data that cannot be reused because
it does not meet community standards. Three specific challenges were identified
that need following up: the first is the BioStudies web interface is not
sufficiently interoperable, works with plain text, and does not provide an
easy (machine) interface for annotation with identifiers and ontologies.

The second challenge specifically listed is the adoption of identifiers in
toxicology datasets. Better metadata of datasets with those identifiers is
essential. It could be solved with compact identifiers in descriptions or
identifiers as keywords. The NanoCommons community made some progress with
this (), but work is mostly manual.

The third challenge is a general incompleteness of ontologies. Finding ontology
terms to be used for annotation of research output is non-trivial whle the
translation of ontology terms to identifiers are key to data consistency and 
interoperability. As examples of this challenge the ontological annotation of
biological assays and composite nanoamterials were discussed.

Regarding the community standards, reasons why data cannot be reused include
scientific aspect as lack of community-accepted standards for testing, which
should address experimental artifacts like batch affects and interlaboratory
effects.

## FAIR-ification recipes

...

## FAIR Implementation profiles

...




# Discussion

The workshop had a lively discussion and resulted in new output that feeds
back into ELIXIR Toxicology Community (e.g. via this report) and via the
FIPs, FAIR Cookbook recipes, and other outcomes back into the wider ELIXIR
and toxicology communities.

Remaining key challenges includes ...

## Acknowledgements

...

## Funding

This workshop was funded by the ELIXIR Europe INTOXICOM grant.

## References



<!-- 

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation

-->
