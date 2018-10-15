# Data Discovery Paradigms Interest Group

**Task force proposal**

## Research Schemas: Using schema.org for research data discoverability and accessibility

<p class="callout info">
**_Rafael C Jimenez_**: I think we should focus on improving discovery (findability) and IMHO also accessibility
**_Mingfang Wu_**: Yes, I totally agree. We are doing this ([schema.org](https://schema.org/) markup) for the purpose of making data more discoverable and accessible. We need to clarify what the "discoverable" means - to be indexed and searched by Google data search tool, to have improved search ranking from Google data search tool (or something equivalent), to achieve more interoperability with other data repositories, or something else...?
When we clarify about the discoverability (or findability), we can then come out methods to measure/compare improvement.
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>

The wide use of [schema.org](http://schema.org) vocabularies to add structured metadata in web pages for use by commercial search engines has attracted the attention of the data management community as a possible mechanism to leverage the robust commercial search engines like Google, Yahoo, Bing etc. to facilitate discovery and access to scientific data. Various projects have been exploring this approach, including the [US NSF EarthCube p418 project](http://geodex.org/), [Google's Dataset Recommendations](https://developers.google.com/search/docs/data-types/dataset), [BioSchemas](http://bioschemas.org), [Force11 DCIP](https://www.force11.org/group/dcip/eg4repository), [Research Data Australia](https://researchdata.ands.org.au/), [DataCite](https://blog.datacite.org/schema-org-register-dois/), [Harvard Dataverse](https://dataverse.org/blog/latest-dataverse-update-adds-support-schemaorg), NASA’s Distributed Active Archive Center (DAAC) Infrastructure, EOSCpilot,  *[add other projects here]*.  Since the origins of the schema.org vocabulary have largely been driven by commercial business use cases, and a loosely governed process for adding and defining vocabulary, there are gaps and deficiencies in the vocabulary that make its application for science data problematic.

<p class="callout info">
**_Andrea Perego_**: This statement does not completely apply to the data-related subset of [schema.org](http://schema.org), which is instead based on the W3C Data Catalog vocabulary (DCAT) - see the ack section at the end of [Schema Dataset](https://schema.org/Dataset).
**_Byron Cochrane_**: I agree with this statement as written. Working with the Open Geospatial Consortium on the Environmental Linked Features Interoperability Experiment, we have found Schema. org useful but only at the broad consumer level. It does not well support specialist. For that we had to turn to other ontologies
**_Andrea Perego_**: +bcochrane@linz.govt.nz , I also agree that [schema.org](http://schema.org) is very generic, and it does not cover (domain-)specific data aspects. My comment was more on the first sentence: "_Since the origins of the schema.org vocabulary have largely been driven by commercial business use cases_". As I said, this does not apply to the dataset-related subset of schema.org, because it is basically a schema.org porting of DCAT.
**_Lewis John Mcgibbney_**: Further, I would suggest that at least one example is given which identifies a shortcoming as applies to science data.
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>


The proposed RDA task group within the Data Discovery Paradigms Interest Group would bring together practitioners who are working with schema.org vocabularies to document scientific data.

<p class="callout info">
**_Rafael C Jimenez_**: I do not think this group should focus on documenting all scientific data types. We should focus on common and generic types across research disciplines (eg dataset, study, ...) and leave the specific scientific types (volcanoes, proteins, ...) to specific scientific domains (earth science, life sciences, ...).
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>

RDA provides an excellent forum for this work because of the wide variety of science domains participating in the RDA community.

<p class="callout info">
**_Rafael C Jimenez_**: I agree. I think RDA is in a good position to start and lead this initiative. However, in my opinion, this initiative should not live in the long term as a task within a group within RDA. I think an effort like this deserves to be an independent initiative similar to Bioschemas.
**_Mingfang Wu_**: Yes, the intention is to have a task force (say for half a year) working on a clearly defined scope and writing a case statement for a working group.
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>


The task group could identify problems with the use of schema.org vocabularies, and make recommendations for solutions, including both 'best practice' recommendations for use of existing vocabulary, as well as formulating and promoting recommendations for vocabulary extensions through the schema.org process.

<p class="callout info">
**_Rafael C Jimenez_**: I agree but I hope we can come up with a more concrete proposal. I think to succeed we should have a focused scope and set of well-defined priorities.
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>

Task group work could be organized via a [GitHub wiki and issue tracker](https://github.com/RDA-DDP/Schema.org-for-Research-Data) for online participation, with regular telecons for discussion.

<p class="callout info">
**_Rafael C Jimenez_**: I think this is a good start. But we should aim at something similar to what [Bioschemas](http://bioschemas.org) has.
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>

Some process for adopting recommendations to promote to the community would have to be developed; the goal would be to minimize the administrative overhead and focus on documented, demonstrably workable solutions.

[_The following was inserted into the DDPIG Session notes at P11_]

How can the research data community leverage schema.org to enhance data discovery?

For many researchers, web search engines are the first port of call for discovery. We need to ensure that they find research data and can rapidly identify relevance. In many domains, this is done by providing additional information in a structured form using schema.org. Schema.org is an open community-organized metadata schema that can be readily integrated into web pages.

Portions of the research data community are already using schema.org (eg bioschemas) to improve discovery.

RDA is well positioned to organize cross-disciplinary recommendations to ensure that schema.org is fit-for-purpose to discover research data, as well as to make recommendations and provide guidance to data providers.

Areas that a task force could provide benefits:

* Define use-cases for search engines and data providers
* Review and make recommendations for schema.org  (e.g. missing attribute, controlled values)

<p class="callout info">
**_Amanda Xu_**: If Date is used, a list of controlled values for dateType might be useful, e.g. Accepted, Copyrighted, Collected, Created, Issued, Submitted, Updated, Available, Valid, Other
**_Amanda Xu_**: Identifier type is important, e.g. DOI
**_Amanda Xu_**: relationType is important, e.g. isSupplementTo, isSupplementedBy, etc.
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>

* Recommend practices for better descriptions and metadata semantics (e.g. what is a 'modified date')

<p class="callout info">
**_Rafael C Jimenez_**: for this we should engage as well with other RDA groups like [RDA Metadata IG](https://rd-alliance.org/groups/metadata-ig.html)
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>

* Provide practical guidance for including / publishing schema.org (e.g., where should it go, how can repos support it, how can data centers reduce the effort required)
* Provide recommendations for more community-specific metadata.

<p class="callout info">
**_Rafael C Jimenez_**: I think this should be out of scope. We should support community-specific metadata efforts but not provide recommendations for community-specific metadata. This group should focus on what it is common across sciences not about what is specific.
**_Nick Juty_**: agree - there could be countless communities, which would make this impractical.
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>

* Engage with W3C DCAT, which is doing a revision cycle;  let's engage from the RDA community perspective

<p class="callout info">
**_Rafael C Jimenez_**: There are many standards describing many different data types. DCAT is just one of the many standards describing datasets and data catalogues. We should align with DCAT and other standards. We should also be open to other types beyond datasets. Cross-walks across existing standards and reusability of properties should be one of the goals of this effort.
**_Mingfang Wu_**: I think perhaps this could be first low hanging fruit activity - to have crosswalks from several representative standards (e.g. DCAT, Geonetwork, DDI, etc) to schema.org (or vice versa), find common gaps and also gaps specific to a discipline, engage with schema.org community and web search engine providers (e.g. Google) and discuss how common gaps and specific gaps should be handled.
**_Mingfang Wu_**: Those participating projects as listed in the first paragraph may already have a crosswalk. We can collect these crosswalks and analyse gaps.
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>


A list of goals and objectives on this group provided by Rafael Jimenez is the following:

* Improve findability and accessibility of research data via schema.org
* Create a community effort engaging existing research initiatives and people working on the discovery of research data
* Support and focus on common and generic types widely used across different scientific domains (dataset, data record, study, ...)
* Support common types for different research objects (data, software, training materials, ...)
* Support and delegate the description of domain specific data entities (eg. volcano, planet, protein, ...) to domain specific initiatives (eg. Bioschemas, ...)
* For each prioritized type create minimum information guidelines agreeing on a common set of properties important across different research fields
* Create (or adopt existing) specific guidelines of how to expose data for some common properties to improve consistency across scientific domains (eg. identifiers, policies, ...)
* Promote the useful adoption of schema.org in science by providing clear profiles, examples, use cases and training materials
* Engage with Schema.org as a community to make specific proposals about research data types
* Create tools that help user to use schema.org annotations (libraries, crawlers, validators, visualisations, ...)
* Provide schema.org cross-walks (mappings) to existing standards

In case it is useful, below the link to the RDA P11 about using Schema.org to improve dataset discoverability based on our experience with Bioschemas.
- https://drive.google.com/file/d/1b_nIVplzcynNmW6RjxJs-PuUFedY7SSv/view?usp=sharing

In Bioschemas and in EOSC we did also think about schema.org for research (science) and something we would like to support. Below links with presentations related to this topic ...
- https://drive.google.com/file/d/11YHRlOn0rxnKODbCKR8eIFwv9dLnOmhI/view?usp=sharing
- https://drive.google.com/file/d/1X8xJ6JmaadTZ4kkMgsj0RoAzKYJhdyWw/view?usp=sharing

### References

???


### Collaboration with other existing efforts / groups / communities**
_(please add title, a URL and ideally a contact name)_

- [https://w3c.github.io/dxwg/dcat/#dcat-sdo](https://w3c.github.io/dxwg/dcat/#dcat-sdo)

### Task Force calls

#### Call #1 (Europe/Asia/Australia) @ 08:00 UTC

Connection link [https://monash.zoom.us/j/418657328](https://monash.zoom.us/j/418657328)

See the time in your local zone [here](https://www.timeanddate.com/worldclock/fixedtime.html?msg=DDPIG_Schema_TF&iso=20181004T11&p1=1428&ah=1).

**Participants List**
  1. Fotis E. Psomopoulos -  [fpsom@issel.ee.auth.gr](mailto:fpsom@issel.ee.auth.gr)
  2. Mingfang Wu - [mingfang.wu@ardc.edu.au](mailto:mingfang.wu@ardc.edu.au)
  3. Rafael C Jimenez - [rafael.jimenez@elixir-europe.org](mailto:rafael.jimenez@elixir-europe.org)
  4. Kathleen Gregory - [kathleen.gregory@dans.knaw.nl](mailto:kathleen.gregory@dans.knaw.nl)
  5. Natalia Atkins - [Natalia.Atkins@utas.edu.au](mailto:Natalia.Atkins@utas.edu.au)
  6. Matt Lightfoot - [lightfoot@ccdc.cam.ac.uk](mailto:lightfoot@ccdc.cam.ac.uk)
  7. Eric Rogers - [erogers@ccdc.cam.ac.uk](mailto:erogers@ccdc.cam.ac.uk)
  8. Giorgos Papanikos - [gpapanikos@imis.athena-innovation.gr](mailto:gpapanikos@imis.athena-innovation.gr)
  9. Katerina Gkirtzou - [katerina.gkirtzou@ilsp.athena-innovation.gr](mailto:katerina.gkirtzou@ilsp.athena-innovation.gr)
  10. Jane Wyngaard - [jwyngaar@nd.edu](mailto:jwyngaar@nd.edu)
  11. Alasdair J G Gray - [A.J.G.Gray@hw.ac.uk](mailto:A.J.G.Gray@hw.ac.uk)

##### Minutes

**_Rafael C Jimenez_**: Scope / title is too long. The TF could have a shorter name. Schema.org has too generic attributes and characteristics. E.g. a dataset under schema.org has too many properties - a user will probably not address all of them.  We should focus on generic data

One of the scopes would be to identify for the generic entries (dataset, project, study, etc) what are the most necessary and appropriate properties.

We should access different aspects; in bioschemas we have several activities (training, platform, implementation/tools, community etc).

It is important to have community engagement, for example, have DataCite,

An important point is to identify and engage the community.

**_Fotis E. Psomopoulos_**: A single well-defined goal would be a list of generic discipline-agnostic entries from schema.org, and identify the properties that would be mandatory

**_Mingfang Wu_**: We already have different communities present here. We can try to identify the commonalities of the different "versions" of schemas used by the different communities.

Another point would be to identify current gaps in the schemas - either the common gaps between disciplines, or all gaps identified (i.e. intersection or union)

**_Rafael C Jimenez_**: Identify the points that are more important in science, and based on those, engage the community to find the minimum required properties of those.

**_Mingfang Wu_**: We can connect that to how users search for data, and then see how we match that up with

**_Alasdair J G Gray_**: There is already a dataset tool provided by Google. What would be the added value of this TF? We need to consider the wider context of the dataset (as Rafa said), e.g. DataCatalog, Publications, Projects.

**_Mingfang Wu_**: We have contributed data to the Google data search, but we don’t know how the metadata is actually used. Is one metadata type more important than another? Also, we can also investigate additional processes such as citations of dataset

**_Giorgos Papanikos_**: The Google data search is just a first step in data discovery. Additional metadata (and services) are going to be required (such as produced under a particular project or a particular funding agency). The TF should not be limited to identifying what is out there, but what can be done to be more focused

**_Rafael C Jimenez_**: Absolutely right. We need to find a way to federate different resources through the appropriate metadata.

**Alasdair J G Gray**: From BioSchemas we are getting a lot of push back on "why are we providing more than  Google requires" and we need schema.org?

**_Jane Wyngaard_**: There are also a lot of recommendations that we can connect with within RDA

**_Rafael C Jimenez_**: There are indeed a lot of WG/IG in RDA that we should liaison with (e.g. metadata working group). The best practices could be about control vocabularies or metadata.

**_Jane Wyngaard_**: We should also check the existing RDA recommendations against schema.org. So another point would be to investigate this for gaps.

**_Rafael C Jimenez_**: We need to recognize that there are other efforts there (e.g. dataset types) and try to link with them. Specification would be to assisting the existing standards. Look for the alignment with the existing standards. Accessibility is equally important to discoverability/findability.

First activity is to create a list of communities to engage.

#### Call #2 (US/Europe) @ 15:00 UTC

Connection link [https://cuboulder.zoom.us/j/726223625](https://cuboulder.zoom.us/j/726223625)

See the time in your local zone [here](https://www.timeanddate.com/worldclock/fixedtime.html?msg=DDPIG_Schema_TF&iso=20181004T18&p1=1428&ah=1).

**Participants List**
  1. Fotis E. Psomopoulos - [fpsom@issel.ee.auth.gr](mailto:fpsom@issel.ee.auth.gr)
  2. Nick Juty - [nick.juty@manchester.ac.uk](mailto:nick.juty@manchester.ac.uk) [Univ. Manchester]
  3. Leyla Garcia, [ljgarcia@ebi.ac.uk](mailto:ljgarcia@ebi.ac.uk) (EMBL-EBI, Elixir-Hub)
  4. Heinrich Widmann, [widmann@dkrz.de](mailto:widmann@dkrz.de) (DKRZ, Hamburg for EOSC-hub and EUDAT-B2FIND)
  5. Alessia Bardi - [alessia.bardi@isti.cnr.it](mailto:alessia.bardi@isti.cnr.it) (OpenAIRE)
  6. Miriam Baglioni - [miriam.baglioni@isti.cnr.it](mailto:miriam.baglioni@isti.cnr.it) (OpenAIRE)
  7. Jochen Schirrwagen - [jochen.schirrwagen@uni-bielefeld.de](mailto:jochen.schirrwagen@uni-bielefeld.de) (OpenAIRE)
  8. Lewis John McGibbney - [lewis.j.mcgibbney@jpl.nasa.gov](mailto:lewis.j.mcgibbney@jpl.nasa.gov) [NASA JPL]
  9. Rafael C Jimenez - [rafael.jimenez@elixir-europe.org](mailto:rafael.jimenez@elixir-europe.org) [ELIXIR, EOSCpilot, Bioschemas]
  10. Robert R. Downs - [rdowns@ciesin.columbia.edu](mailto:rdowns@ciesin.columbia.edu)
  11. Adam Shepherd - [ashepherd@whoi.edu](mailto:ashepherd@whoi.edu) ([BCO-DMO](https://www.bco-dmo.org), EarthCube, [Project 418](https://github.com/earthcubearchitecture-project418), [GeoDex](http://geodex.org/))
  12. Douglas Fils - [dfils@oceanleadership.org](mailto:dfils@oceanleadership.org)  (EarthCube, [Project 418](https://github.com/earthcubearchitecture-project418), [GeoDex](http://geodex.org/))
  13. Amanda Xu - [amanda.xu@ars.usda.gov](mailto:amanda.xu@ars.usda.gov)
  14. Jennie Larkin - [jennie.larkin@nih.gov](mailto:jennie.larkin@nih.gov) (NIH-NIDDK)
  15. Greta de Groat - [gdegroat@stanford.edu](mailto:gdegroat@stanford.edu)  Stanford University

##### Minutes

**_Fotis E. Psomopoulos_**: Overview of the morning session

_Discussion on Obj #1_

**_Jennie Larkin_**: How do you envision this connecting to other objects or identifier systems. E.G I can envision a situation where I have a dataset and i want to connect this dataset (through dataset) as well as with the respective projects/funders/publication etc.

**_Fotis E. Psomopoulos_**: Depends on how broad or specific the scope of the TF should be.

**_Nick Juty_**: In addition to "minimal" properties, we should also be considering recommended properties

**_Leyla Garcia_**: We need to define what "recommended" stands for. Sometimes “recommended” be “required if available”. So we need to define exactly what recommended stands for.

**_Douglas Fils_**: People may wish to look at Google's type dataset required a recommend info at [https://developers.google.com/search/docs/data-types/dataset](https://developers.google.com/search/docs/data-types/dataset) I'm suggesting they be reviewed, but they provide a starting point

Recommendation may change depending on the domain that they are applicable to. So recommendations may be biased as well.

**_Heinrich Widmann_**: Have a look also on recommendations from EUDAT ( [http://b2find.eudat.eu/guidelines/introduction.html](http://b2find.eudat.eu/guidelines/introduction.html) ), DataCite ( [https://schema.datacite.org/](https://schema.datacite.org/) ) , OpenAire Guidelines ([https://guidelines.openaire.eu/en/latest/](https://guidelines.openaire.eu/en/latest/) ) etc.

**_Douglas Fils_**: There is already a flow between DataCite and schema.org (DC created schema.org json files)

**_Alessia Bardi_**: It is important to start with the guidelines. However, from OpenAire and DataCite the recommendations are mostly focused on citations, and this may not be enough. So it’s possible that each discipline might need each own set of entries. So Obj#1 is a bit tricky.

**_Douglas Fils_**: Also of value is the work being done by DCAT with schema.org alignment htt

_Discussing Obj #2_

**_Rafael C Jimenez:_** Try to do a cross-walk between different standards, and see if there are gaps there (in addition to promoting these standards).

**_Heinrich Widmann_**: In EUDAT-B2FIND instead of cross-walk we do a connection / mapping  different schemas onto a common generic cross-discipline schema.

_Discussing Obj #3_

**_Adam Shepherd_**: This is an area I’m really interested in. There are several different extension so bringing them all together and see how we can build something from there.

**_Jennie Larkin_**: There are some projects in NIH (such as Data Commons) that are working in this area - using schema.org as well as the extensions that fit under bio-related data. We need to know how to extend it in different areas to find it more useful.

**_Adam Shepherd_**: We need to find a good balance;

### Summary notes / Actions

New TF title "Research Schemas: Using schema.org for research data discoverability and accessibility". The focus of the TF is “data” (and context around data),  not limited e.g.to “Google Dataset Search”

1. **Objective #1**

  Create / Identify a list of generic discipline-agnostic entries from schema.org, and identify the properties that would be minimally  suggested for users / data providers (minimal suggested properties could be provided by existing RDA recommendation taking into consideration the original context of those recommendations vs our interest in discoverability and accessibility).

<p class="callout info">
**_Rafael C Jimenez_**: Jennie Larkin made a good point about the connections among types. I think besides to identify (prioritise) the Research Schemas types, we should define and prioritise relationships among types. For instance for us in Bioschemas in data resources is important to define DataCatalog, DataSet and DataRecord but also make the connections among them. We could see something similar with other types like investigation, study, assay, ...
**_Mingfang Wu_**: Could this be an outcome of the objective #3? For example, when we map our repository schema (RIF-CS), we find many relations (e.g. between data and software, between data and data services, and between data and data creators/researchers, etc) could not be mapped to schema.org.
However, we need consider where the relationships (really a web of knowledge graph) would be best used for - for improving search ranking, browsability, sparksql like query, or others.
If take google data search as an example, would google treats relationships between types similar to links between web pages, and use PageRank link algorithm to improve search?
</p>
<p class="callout success">A success message</p>
<p class="callout warning">A warning message</p>
<p class="callout danger">A danger message</p>

    1. Adam Shepherd
    2. Alasdair J G Gray
    3. Amanda Xu
    4. Douglas Fils
    5. Giorgos Papanikos
    6. Heinrich Widmann
    7. Jane Wyngaard
    8. Jochen Schirrwagen
    9. Kathleen Gregory
    10. Leyla Garcia
    11. Lewis John McGibbney
    12. Mingfang Wu
    13. Miriam Baglioni
    14. Nick Juty
    15. Rafa C Jimenez
    16. Robert R. Downs


2. **Objective #2**

  Look for gaps between existing RDA recommendations / existing best practices / users’ practices in data searches against schema.org, and assess potential solutions. Do a cross-walk between the different standards, and identify the gaps through this process (in addition to promoting these standards). Compare between mapping / cross-walking.

    1. Alasdair J G Gray
    2. Amanda Xu
    3. Giorgos Papanikos
    4. Heinrich Widmann
    5. Kathleen Gregory
    6. Leyla Garcia
    7. Lewis John McGibbney
    8. Mingfang Wu
    9. Miriam Baglioni
    10. Nick Juty
    11. Rafa C Jimenez


3. **Objective #3**

  Identify the commonalities of the different "versions" of schemas used by the different communities, find current gaps in the schemas - either the common gaps independent of potential **extensions** to schema.org between disciplines, or all gaps identified (i.e. intersection or union)

    1. Adam Shepherd
    2. Amanda Xu
    3. Douglas Fils
    4. Giorgos Papanikos
    5. Heinrich Widmann
    6. Mingfang Wu
    7. Nick Juty
    8. Rafa C Jimenez


4. **Objective #4**

  Collaboration with other existing efforts / groups / communities

    1. Adam Shepherd
    2. Alasdair J G Gray
    3. Douglas Fils
    4. Giorgos Papanikos
    5. Heinrich Widmann
    6. Jane Wyngaard
    7. Jochen Schirrwagen
    8. Leyla Garcia
    9. Mingfang Wu
    10. Nick Juty
    11. Rafa C Jimenez
