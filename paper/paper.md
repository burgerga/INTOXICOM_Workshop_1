---
title: 'INTOXICOM Workshop Report: FAIRification of Toxicological Research Output: Leveraging ELIXIR Resources'
title_short: 'INTOXICOM #1: FAIRification of Toxicological Research Output'
tags:
  - toxicology
  - ELIXIR Europe
  - FAIR
authors:
  - name: Marvin Martens
    orcid: 0000-0003-2230-0840
    affiliation: 1
  - name: Iseult Lynch
    orcid: 0000-0003-4250-4584
    affiliation: 2
  - name: Thomas Exner
    orcid: 0000-0002-1849-5246
    affiliation: 3
  - name: Rob Stierum
    orcid: 0000-0002-4409-1974
    affiliation: 4
  - name: Penny&nbsp;Nymark
    orcid: 0000-0002-3435-7775
    affiliation: 5
  - name: Dominik Martinát
    orcid: 0000-0001-6611-7883
    affiliation: 6
  - name: Javier Millán Acosta
    orcid: 0000-0002-4166-7093
    affiliation: 1
  - name: Ulrike&nbsp;Wittig
    orcid: 0000-0002-9077-5664
    affiliation: 7
  - name: Clemens Wittwehr
    orcid: 0000-0003-2760-7702
    affiliation: 8
  - name: Meike Bunger
    orcid: 0009-0002-7664-0058
    affiliation: 9
  - name: Gerhard Burger
    orcid: 0000-0003-1062-5576
    affiliation: 10
  - name: Tooba&nbsp;Abbassi-Daloii
    orcid: 0000-0002-4904-3269
    affiliation: 1
  - name: Uday Killi
    orcid: 0000-0001-6267-7541
    affiliation: 11, 12
  - name: Jente Houweling
    orcid: 0009-0005-3680-0645
    affiliation: 1, 13
  - name: Riju&nbsp;Roy&nbsp;Chowdhury
    orcid: 0009-0002-4110-241X
    affiliation: 14
  - name: Tamara Danilyuk
    orcid: 0000-0001-6125-6147
    affiliation: 10
  - name: Lucy Sinke
    orcid:
    affiliation: 
  - name: Egon&nbsp;Willighagen
    orcid: 0000-0001-7542-0286
    affiliation: 1
affiliations:
  - name: Dept of Translational Genomics, NUTRIM, FHML, Maastricht University, Maastricht, NL
    index: 1
  - name: University of Birmingham, Birmingham, UK
    index: 2
  - name: Seven Past Nine GmbH, Schopfheim, DE
    index: 3
  - name: The&nbsp;Netherlands&nbsp;Organisation for Applied Scientific Research. Risk Analysis for Prevention, Innovation & Development, Utrecht, NL
    index: 4
  - name: Institute of Environmental Medicine, Karolinska Institutet, Stockholm, SE
    index: 5
  - name: Department of Physical Chemistry, Palacký University Olomouc, CZ
    index: 6
  - name: Heidelberg Institute for Theoretical Studies, Heidelberg, Germany
    index: 7
  - name: European Commission, Joint Research Centre (JRC), Ispra, Italy
    index: 8
  - name: Stichting Health-RI, Utrecht, The Netherlands
    index: 9
  - name: Leiden Academic Centre for Drug Research (LACDR), Leiden University, Leiden, The Netherlands
    index: 10
  - name: University of Eastern Finland, Finland
    index: 11
  - name: University of South Bohemia, Czech Republic
    index: 12
  - name: RIVM, Bilthoven, Netherlands
    index: 13
  - name: IUF – Leibniz Research Institute for Environmental Medicine, Düsseldorf, Germany
    index: 14
date: 29 May 2024
cito-bibliography: paper.bib
event: INTOXICOM
biohackathon_name: "INTOXICOM Workshops"
biohackathon_url:   "https://elixir-europe.org/internal-projects/commissioned-services/integrating-toxicology-community"
biohackathon_location: "Utrecht, 28-29 May 2024"
group: Workshop 1
git_url: https://github.com/BiGCAT-UM/INTOXICOM_Workshop_1
authors_short: Martens \emph{et al.}
---

<!--

RS GENERAL REMARK: ADD SOME ILLUSTRATIONS? E.G. ON THE OUTCOME OF THE FAIR COOK BOOK, ON THE TOXICOLOGY REPOSITORY UNDER FAIRSHARING.ORG ?? ETC.

-->

# Introduction

This document reports on the first workshop held by the ELIXIR
Toxicology Community [@citesAsRecommendedReading:Martens2023ELIXIR]
as part of the INTOXICOM Implementation Study workshop series [@citesAsEvidence:INTOXICOM],
held in Utrecht on May 28 and 29 2024 [@citesAsEvidence:Aanmelder]. The topic of
the meeting was the FAIRification of toxicological research output, including the exploration of how
ELIXIR resources may facilitate this. The meeting was organized by a team
of ten people from the ELIXIR Toxicology Community: Marvin Martens, Penny Nymark,
Iseult Lynch, Meike Bünger, Rob Stierum, Thomas Exner, Egon Willighagen, Ammar Ammar,
Dominik Martinát, and Karel Berka. The target audience of this first INTOXICOM
workshop was toxicologists with an interest in using FAIR data resources for their
research or in making their data (more) FAIR, as well as data managers/stewards
and researchers working with adverse outcome pathways (AOPs).

The workshop included presentations and working sessions around various topics.
The first workshop within the INTOXICOM implementation study consisted of two parts. The first part
of the workshop focussed on the application of FAIR solutions to toxicology databases
and datasets. Part of this was describing the use of compact identifiers to link
to specific records in databases in narratives such as project deliverables, e.g.
in PARC [@citesForInformation:PARC].

The second part addressed Adverse Outcome Pathways (AOPs) in the AOP-Wiki.
The workshop explored the FAIRification of AOPs and AOP-Wiki, making AOPs
findable in more ways, and continues on the efforts of the CIAO project
([ciao-covid.net](https://ciao-covid.net/)) that assesses the FAIRness of
AOPs [@citesForInformation:Carusi2023]. The output of this part would be FAIR
Implementation Profile for AOPs.

The deliverables for the workshop include: 1. this report; 2. a FAIR Implementation Profile (FIP)
for AOPs; and 3. a proposed standard on how to use compact identifiers on project reports.
This report describes the outcome of the workshop, provides links to presentations (when
applicable), and discusses the hands-on work done including emerging results.

# The workshop

The workshop was attended in person in Utrecht (The Netherlands) by 16 people on the first day,
with two people giving an online presentation. <!-- [RS: HOW MANY PARTICIPATED ONLINE ??] -->
Participants came from various universities (Karolinska Institutet, Leiden,
Maastricht, Olomouc, Eastern Finland, and Birmingham),
research institutes (TNO, EU-JRC, RIVM), regulators, and various ELIXIR Platforms.
Furthermore, ongoing toxicology research projects in which attendees are involved, and from which also data problems/challenges were identified prior to the workshop for giving direction, included VHP4Safety (https://vhp4safety.nl) [@VHP4Safety2024],
PARC (https://www.eu-parc.eu/), and PINK (https://pink-project.eu/).
<!-- [RS: OTHER PROJECTS AS WELL I RECALL FOR EXAMPLE (https://www.risk-hunt3r.eu/)) HOWEVER I CANNOT RETRIEVE FROM THE GOOGLE THE ORIGINAL INVENTORY OF DATA PROBLEMS WE DID PRIOR TO THE WORKSHOP, -->
In terms of geographical distribution, participants came from The Netherlands,
Finland, Italy, UK, Germany, Czechia, and Sweden.

## Presentations

To introduce ELIXIR, the ELIXIR Toxicology Community, the scope of the meeting,
and the various workshop sessions, several speakers presented their ongoing
work. Table 1 gives an overview of the presentations.

Table: Presentations at the workshop.

| Speaker | Talk Title  |
| --- | -------- |
| David Lloyd | ELIXIR Introduction |
| Marvin Martens | ELIXIR Toxicology Community [@martens_2024_14005367]|
| Iseult Lynch | FAIR data to support Chemical Risk Assessment & Regulation – the PARC approach for toxicological data [@Lynch2024] |
| Rob Stierum | Compact IDs - identified challenges |
| Egon Willighagen | Introduction to hands-on session data FAIRification [@Willighagen_2024] |
| Penny Nymark | What is an Adverse Outcome Pathway? [@Nymark_2024] |
| Clemens Wittwehr | Why Adverse Outcome Pathways need to be FAIR [@Wittwehr2024] |
| Marvin Martens | FAIR AOPs - identified challenges [@martens_2024_14005454]|
| Ulrike Wittig | ELIXIR Data Platform |
| Marvin Martens | FAIRsharing Toxicology Collection [@martens_2024_14005493]|
| Iseult Lynch | Welcome to FIP.27.W.1 [@Lynch2024b] |
| Penny Nymark | Data vs. metadata in an Adverse Outcome Pathway |

To zoom in on the possible exploration of ELIXIR resources/tools/platforms as to the usefulness towards the toxicology research community, the first topic was the general FAIRification of research
output (a guiding definition is found in [@citesForInformation:Houweling2023]).
A main aspect of this part of the workshop was around making data FAIR, considering the ambitions, and practical challenges. This part included a workshop
discussion and writing a guidance document on making project reports more interoperable using compact identifiers.

This part was followed by a hands-on session around FAIRificiation recipes in
the ELIXIR FAIR Cookbook [@RoccaSerra2023]. The selection of data challenges/topics for this session was based upon topics identified from the Research Projects mentioned above, as well as during the preparatory webinar series.

The first day ended with a third topic, around making adverse outcome pathways
(AOPs) more FAIR, continuing on earlier work by the CIAO project 
([https://www.ciao-covid.net/](https://www.ciao-covid.net/))
and feeding into the continued development of the AOP-Wiki.

The second day started with a session on the ELIXIR Data Platform and the
FAIRsharing Toxicology Collection. This collection has been an ongoing collaboration
between the ELIXIR Toxicology Community and the FAIRsharing project, recently
boosted by a FAIRsharing Community Champion project.

The main focus of the second day was on the topic second hands-on session,
FAIR Implementation Profiles (FIPs). These FIPs formalize a community practice
or even standard that guides members of those communities, and possibly even
outside that community, with minimal expectations and best practices. There is
a DSWizard-based tool to create FIPs which has been used by the WorldFAIR
project for ready-for-modelling datasets for nanoinformatics [@citesForInformation:WFFIP1] and
for datasets [@citesForInformation:WFFIP2].

# Results

This section gives an overview of the main outcomes of the sessions of this
workshop.

## Guidance for compact identifier use

One of the goals of the workshop was to promote the use of compact identifiers
in project reporting. Compact identifiers are short but meaningful references
to identifiers for entities like proteins, genes, metabolites, and nanomaterials.
A draft guidance document has been under development and is available at
[https://github.com/egonw/compact-ids-in-reports](https://github.com/egonw/compact-ids-in-reports).

## FAIR standards and challenges

With regards to FAIR standards and associated challenges, the participants discussed various aspects
on how to make research output more reused. Whereas ELIXIR
already provides many solutions for FAIR, adoption in projects and communities
is not trivial. PARC is adopting various solutions, including FIPs and FAIR
Data Points (FDPs) [@citesAsRecommendedReading:Silva2022FAIR]. Community
standards like IUCLID6 and the Toxic Process Ontology (TXPO) were mentioned <!-- [RS: THAT IS CORRECT, HOWEVER THESE ARE THEMSELVES NO FAIR STANDARDS YET AND AS SUCH ARE NO IMMEDIATE SOLUTIONS FOR FAIRIFICATION (OR ARE THEY?), IN THE END THESE RESOURCES MAY CONTRIBUTE TO FAIRNESS, AS IUCLID6 DEMANDS A STRUCTURED RECORING OF (META)DATA ACCORDING TO OECD HARMONZIED TEMPLATES) AND ONTOLOGIES ARE ALWAYS HELPFULL....] -->
Other toxicology projects adopted solutions including repositories like the
EMBL-EBI BioStudies, OpenAIRE, and Zenodo <!-- [RS: IS IT POSSIBLE TO BE MORE SPECIFIC WHICH TOX PROJECTS HAVE ADOPTED WHICH TOOLS?] -->. The role of global unique identifiers
was raised, including the Nano-InChI [@citesAsPotentialSolution:Lynch2020] and the European Registry of Materials
(ERM) identifier [@citesAsPotentialSolution:VanRijn2022] as metadata for datasets to unequivocally indicate which chemicals are
studied within these toxicology projects.

Challenges the toxicology community faces include (1) incomplete interoperability,
(2) lack of adoption of unique identifiers, and (3) data that cannot be reused because
it does not meet community standards. 

<!-- 
[RS NOT CLEAR HOW THE TEXT ABOVE RELATES TO BELOW. ABOVE YOU MENTION 3 CHALLENGES (1) INCOMPLETE INTEROPERABILITY; (2) LACK OF ADOPTION OF UNIQUE IDENTIFIERS; (2) DATA NOT MEETING COMMUNITY STANDARDS. BELOW YOU MENTION AGAIN 3 DATA CHALLENGES, FOR WHICH THE FIRST TWO ARE THE SAME AS ABOVE, I UNDERSTAND THIS. HOWEVER, THE THIRD CHALLENGE MENTIONED BELOW IS ABOUT ONTOLOGIES WHICH IS NOT NECESSARILY THE SAME AS MEETING COMMUNITY STANDARDS, OR IS THIS WHAT YOU MEAN: E.G. IUCLID IS AN ECHA STANDARD BUT NOT AN ONTOLOGY PER SE, CAN YOU CLARIFY?] 
-->

Below, three specific identified challenges, for which follow up is to be relevant for the toxicology community, are explained in more detail.


The first is the fact that the BioStudies web interface <!-- [RS THIS IS A VERY SPECIFIC CHALLENGE SPECIFICALLY FOR AN ELIXIR INFRASTRUCTURE COMPONENT, WHICH FITS THE WORKSHOP IDEA. IT FALLS UNDER THE MORE GENERIC CHALLENGE OF "INCOMPLETE INTEROPERABILITY" BUT SOMEHWERE WE NEED TO MENTION THE TRANSITION IN THE TEXT FROM THE  OBSERVATION THAT INTEROPERABILITY IS AN ISSUE IN GENERAL, TO THIS SPECIFIC ELIXIR EXAMPLE. OR AM I WRONG AND WAS THIS (BIOSTUDIES) IN FACT THE VERY SPECIFIC DATA CHALLENGE IDENTIFIED FROM ONE OF THE TOXICOLOGY PROJECTS?] -->
sufficiently interoperable. The website allows to work with plain text (e.g. to enable the querying of the biostudies within the "Search BioStudies" field, but does not provide an
easy (machine) interface for annotation with identifiers and ontologies. <!-- [RS POST MEETING REMARK: IF I LOOK AT https://www.ebi.ac.uk/biostudies/help#, THERE ARE SOME OPTIONS TO QUERY THE DATA IN MORE DETAIL USING AN API] -->


The second challenge specifically listed is the adoption of identifiers in
toxicology datasets. Better metadata of datasets with supporting unique identifiers is
essential. It could be solved with compact identifiers in descriptions or
identifiers as keywords. The NanoCommons community made some progress with
this ([https://nanocommons.github.io/datasets/](https://nanocommons.github.io/datasets/)),
but annotating the data still needs to be done manually.

Regarding the community standards, reasons why data cannot be reused include
scientific aspect as lack of community-accepted standards for testing, which
should address experimental artifacts like batch effects and interlaboratory
effects.

The third challenge is a general incompleteness of ontologies. <!-- [RS: OR IS IT A BIT WIDER COMPARED TO ONTOLOGIES ONLY, THAT IS "DATA NOT MEETING COMMUNITY STANDARDS?" SEE ALSO MY REMARK ABOVE] -->
Finding ontology
terms to be used for annotation of research output is non-trivial while the
translation of ontology terms to identifiers is key to data consistency and 
interoperability. As examples of this challenge some challenges around ontological annotation of
biological assays and composite nanomaterials were discussed. 

The discussion also covered the tradeoff between comprehensive ontological modeling, which allows reasoning to infer new links in data and achieve a more complete knowledge representation, and the complexity that setting up an ontology (or deciding on which ontologies to use) can introduce for certain projects. In many application-specific or short-term research efforts, representing knowledge in an ontology format can add unnecessary hurdles for researchers as opposed to simpler solutions like taxonomies or controlled vocabularies, especially if the reasoning capabilities of OWL ontologies can't be fully utilized within the project's scope and timeline. 

This problem statement led to a recap of some instances of spreadsheet template-based workflows for ontology reuse and expansion within past and present projects in the INTOXICOM environment<!-- PARC iirc -->. Leveraging tools like the OBO foundry's ontology toolkit, ROBOT [@citesAsRecommendedReading:Jackson_2019], allows for workflows that use adaptable templates to accommodate new data needs while building upon and remaining compatible with established ontolgies. These workflows, with their emphasis on iterative refinement and community involvement, can help include technical and non-technical researchers, leading to more applicable ontologies and allowing ontology developers to focus on the technical aspects of ontology engineering and development.

<!-- based on my (Javier) understanding of Thomas's point about ontologies and what I can remember from our conversation-->For ontologies to become the cornerstone of FAIR metadata, there is a need to align perspectives between database-oriented thinking, which favors simpler relational models; metadata producers, who may find a lack of granularity in available terms if the ontology is too high-level; and ontology engineers, who must strike a balance between the precision of their logical models and their practical usability for metadata producers and consummers.


## FAIRification recipes

After an introduction to the concepts of the FAIR Cookbook, the workshop
participants started three FAIR Cookbook recipes, of which one is currently
private: "Adding KE Component annotations in AOP-Wiki",
"Metadata for cell-based assays using BAO", and "Setting up imaging based confocal screening".


<!-- [RS CAN THE OWNERS OF THE RECEPIES PERHAPS PROVIDE SOME MORE DETAILS HERE, WITH SUGGESTION: TOGETHER WITH A REFLECTION ON HOW EASY IT WAS TO ADOPT THE FAIR COOKBOOK PRINCIPLE IN THEIR WORK?] -->

<!-- EW: one is currently private and could maybe be made public. Second, we need
         Tooba and the rest of the FAIR Cookbook team to help the authors move
         forward. 
     TAD: I would be happy to help and onboard other people from the FAIR cookbook side    -->

### Adding KE Component annotations in AOP-Wiki

In a breakout session covering FAIR Cookbook recipes, one group drafted the initial <!-- [names of breakout session members here?]  -->
version of a recipe for AOP developers to aid in complying with the guidelines outlined on p. 28 of [@OECD2018],
under the heading "KE Components and Biological Context"
([https://hackmd.io/\@WBu-yMi5R62T6i7YA3RGVA/BJtnqIQVR](https://hackmd.io/\@WBu-yMi5R62T6i7YA3RGVA/BJtnqIQVR)).
This involves the proper annotation of Key Event
Components with appropriate ontology terms. Current experience indicates that AOP developers often avoid this
task due to its perceived complexity. The recipe aims to mitigate this challenge by providing step-by-step
guidance. Once AOP developers realize the simplicity of adding ontology terms, they will also recognize the
enhanced visibility of their AOPs when searched by these terms. Additionally, the broader adoption of
ontologies in the AOP domain could facilitate the semi-automatic formation of AOP networks and the
identification of overlapping or redundant Key Event Entries. The next step involves incorporating the
recipe into the FAIR Cookbook and referencing it in the AOP-Wiki guidance and help system.

### Metadata for cell-based assays

This recipe, though still a draft, provides a starting point for the consistent and FAIR-compliant metadata annotation of cell-based bioassay types ([https://hackmd.io/\@lusinke/rkXlvLXE0](https://hackmd.io/\@lusinke/rkXlvLXE0)). The starting point is a review of biomedical ontologies and controlled vocabularies and the metadata areas they cover, from the biological aspects of assay samples to assay specifications and analysis-level metadata. The different metadata fields to be annotated with these semantic resources are then divided into required and recommended depending on whether they occur at least in two of the metadata standards enumerated in the recipe.

### Setting up imaging based confocal screening

The third recipe is about standardized protocols for reproducible imaging of eGFP-tagged hiPSC reporter lines
([https://hackmd.io/MBKglLL3Ri6uiodo46VbJg?both](https://hackmd.io/MBKglLL3Ri6uiodo46VbJg?both)).
This recipe outlines the essential components required to create a **minimal imaging dataset** that enables
validation of functional reproducibility of fluorescent eGFP hiPSC reporter lines using confocal imaging
**across collaborative project partners**. It covers nine points, including a reference compound
set, metadata, imaging settings, raw data deposition, quality control, and more.

## FAIR Implementation profiles

For the FAIR Implementation profiles, we look at the FIP Wizard
([https://fip-wizard.ds-wizard.org/](https://fip-wizard.ds-wizard.org/), [@Magagna2022]),
following the choice made by WorldFAIR. During the workshop [@RAa-SA1rYr], two FIPs were
started. The first FIP was developed for AOPs and the second FIP was developed for 
toxiconomics. Generally, filling out the FIP template was not found to be easy
and both FIPs left a lot of questions open.

### Adverse Outcome Pathways FIP

The AOP FIP is based on the work done by AOP-Wiki. For example, metadata used
by the AOP-Wiki include an identifier, a title, a contact point, and a license.
For the interoperability, ontologies like PROV-O [@Sahoo2013], Cell Ontology [@Diehl2016],
and UBERION ([https://uberon.github.io/](https://uberon.github.io/)) were discussed.

### Toxicogenomics FIP

The toxicogenomics FIP derived from experience from the participants. Some projects
have previously already used resources like BioStudies [@Sarkans2018], ArrayExpress, and 
the European Nucleotide Archive [@Burgin2023] and matching identifier like
the BioStudies Accession number, DOI, and ORCID. ISA-Tab [@RoccaSerra2009] is mentioned as
format, along with the more general CSV, TSV, and JSON. Ddatasets have already been
indexed by Google Dataset Search and Wikidata. Ontologies that were mentioned
include the Chemical Entities of Biological Interest [@deMatos2010], Gene Ontology, and 
Experimental Factor Ontology (EFO) [@Malone2010].

<!--
  https://docs.google.com/spreadsheets/d/1Bc7sCERl7FIJxm8wp7wz3vzZdnNaf-6N_8pn_xFMQyM/edit?usp=drive_link
  
    -> moved to https://docs.google.com/spreadsheets/d/1nNxdR8cWhcQq-9xWnA1QRo9gWcTxqz8W/edit?gid=1113123974#gid=1113123974
  
  https://docs.google.com/spreadsheets/d/1yNEYzJRbx10RkuqJmLcO7RPOq-nrimUKQLQW6uWzfho/edit?usp=sharing
--> 

<!-- [RS: SOME ADDITIONAL TEXT NEEDED INCLUDING USER EXPERIENCES HOW TO USE THE CONCEPT OF ESTABLISHING A FIP] -->

# Discussion

The workshop had a lively discussion and resulted in new output that feeds
back into the ELIXIR Toxicology Community (e.g. via this report) and via the
two FIPs, three FAIR Cookbook recipes, and other outcomes back into the wider ELIXIR
and toxicology communities. Both the recipes and the cookbook need further work,
and, more importantly, adoption by toxicologists.
Of course, the workshop was relatively short to complete output as it set out to
do. This is reflected in by the nature of the cited results, and for the FIPs
there are not even tangible results that can be linked to, at the time of writing.

This limitation was anticipated and results will be picked up by the participants and
followed up in the second INTOXICOM workshop. This report will allow follow up
work to acknowledge the input from this workshop by citing this paper.

<!-- 

[RS SOME THOUGHTS FOR DISCUSSION, WITH THE NOTITION THAT IT HAS BEEN SOME TIME SINCE THE WORKSHOP AND MY MEMORY IS FADING HERE. 

DIFFICULT TO BALANCE BETWEEN DETAILED (META)DATA ANNOTATION OF STUDIES VERSUS PRACTICAL FEASABILITY WITHIN TOXICOLOGY PROJECTS. TOXICOLOGY IS AN INTERDISCIPLINARY BROAD FIELD, COMBINING CHEMISTRY, BIOLOGY, MOLECULAR SCIENCES (E.G. OMICS), RISK ASSESSMENT, AND ENVIRONMENTAL SCIENCES IF YOU WILL. WHICH MAY MAKE THIS EVEN MORE CHALLENGING. AS AN END USER (NON-ACADEMIC TOXICOLOGIST) I DO NOT KNOW BEFOREHAND WHICH DATATYPES I NEED TO INTEGRATE FOR A PARTICULAR TOXICOLOGICAL QUESTION: THEREFORE HOW TO PRIORITIZE THE FAIRIFICATION OF THE DIFFERENT DATA SUBDOMAINS.
THEREFORE, THE DEVELOPMENT OF/USE OF FAIR COOKBOOK AND/OR FIP CAN GO MANY WAYS, AS WE DID I THINK EVIDENCED DURING THE WORKSHOP: AND EVEN THOUGH THESE RESOURCES ARE A STEP FORWARD TO ULTIMATE FAIRIFICATION ONE SOLUTION (A FIP, A RECEPY) CREATED BY RESEARCHER X DOES NOT NECESSARILY ACCOMODATES THE NEED FOR RESEARCHER Z, HOW TO DEAL WITH THIS

IDEALLY WE WOULD LIKE TO HAVE ONE LARGE OVERARCHING FIP TO COVER THE WIDEST POSSIBLE DATA DOMAIN NEEDED (OR NEEDED IN FUTURE) FOR TOXICOLOGY. BUT IS THIS REALISTIC AND FEASIBLE?. WE WILL AT LEAST TRY THIS NOW WITHIN THE TOXICOLOGY COMMUNITY WITHIN PARC: TO BUILD A TOXICOLOGY REFERENCE FIP, SUPPORTIVE TO THE PARC TOXICOLOGY PROJECTS.

CAN WE LEARN FROM OTHER INTERDISCIPLINARY DISCIPLINES (TECHNOLOGY) IN WHICH STANDARDISATION HAS BEEN MORE ADVANCED,  ETC ETC? HOW WAS THIS, OR WAS THIS AT ALL, ULTIMATELY ENFORCED WITHIN LARGER COMMUNITIES? 
CAN WE ENFORCE FAIRIFICATION WITHIN THE TOX COMMUNITY, OR IS THIS OT THE WAY TO GO?

NON-ACADEMIC TOXICOLOGY/RISK ASSESSMENT IS CONSERVATIVE AND MATTERS WILL ONLY CHANGE SLOWLY: FOR TOXICOLOGY OBVIOUSLY OECD/ECHA ETC COULD PLAY A ROLE HERE. FROM RECENT WORK (STIERUM ET AL. 2024 IN PREP. )WE DID IN PARC (FREQUENCY ANALYSIS OF TERMS RELEVANT TO THE PARC FAIR DATA POLICY (E.G. "DATA SHARING AND COLLABORATION" AND "ETHICS AND FAIRNESS", ACCROSS DIFFERENT STAKEHOLDER DOCUMENTS A.O. FROM DECENTRALIZED RISK ASSESSMENT AGENCIES) IT WAS DEMONSTRATED THAT THE "PENETRATION" OF FAIR CONCEPTS WITHIN THESE REGULATORY COMMUNITIES IS MINIMAL. PROBABLY WITH A REASON AS CHEMICAL DOSIERS OFTEN CONTAIN WELL-DEFINED DATA SPACES, THAT ARE OFTEN (PARTIALLY) CONFIDENTIAL, WITH LESS NEED FOR INTEGRATION. THIS MAY CHANGE HOWEVER AS INCREASINGLY RESEARCH DATA MAY BE USED IN DOSIERS IN WEIGHT OF EVIDENCE APPROACHES, SUPPORTING GROUPING/READ ACCROSS BASED UPON NGRA (IN FACT ONE OF THE GOALS OF PARC!) 

-->

<!-- ## Acknowledgements

... -->

## Funding

This workshop was funded by the ELIXIR Europe INTOXICOM grant (Grant No. NL-2023-INTOXICOM).
Participants acknowledge funding from PARC (Grant agreement No. 101057014 and UKRI Grant No. 1752317),
WorldFAIR (Grant agreement No. 101058393 and UKRI Grant No. 1831977 ) and
PINK (Grant agreement No. 101137809) and UKRI Grant No. 10097944).
The VHP4Safety project is funded by the Netherlands Research Council (NWO) (Grant No. NWA-ORC 1292.19.272).

## References
