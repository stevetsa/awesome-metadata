# awesome-metadata
A list of resources for metadata tools, standards and development.  [Contributions](https://github.com/stevetsa/awesome-metadata/blob/master/CONTRIBUTE.md) welcome!

## Framework
(Sort alphabetically.)    
\[Resource](URL) - description.  


[caDSR](https://cbiit.cancer.gov/ncip/biomedical-informatics-resources/interoperability-and-semantics/metadata-and-models)- caDSR comprises a database, application programming interfaces (APIs), and web-based applications for creating, editing, controlling, deploying, monitoring, and finding reusable metadata. These metadata describe common data elements (CDEs), information models, and case-report forms (CRFs) that are used for data collection and analysis or for software development.  

[ISA-Tab](https://isa-tools.github.io/index.html) - The open source ISA framework and tools help to manage an increasingly diverse set of life science, environmental and biomedical experiments that employing one or a combination of technologies. Built around the 'Investigation' (the project context), 'Study' (a unit of research) and 'Assay' (analytical measurement) data model and serializations (tabular, JSON and RDF), the ISA framework helps you to provide rich description of the experimental metadata (i.e. sample characteristics, technology and measurement types, sample-to-data relationships) so that the resulting data and discoveries are reproducible and reusable.  


## Model
(Sort alphabetically.)    
\[Resource](URL) - description.   


[CDISC](https://www.cdisc.org/) - Clinical Data Interchange Standards Consortium, Inc. enables clinical research to work smarter by allowing data to speak the same language. Various clinical models.  

[Detailed Clinical Models](http://wiki.hl7.org/index.php?title=Detailed_Clinical_Models) - an information model of a discrete set of precise clinical knowledge which can be used in a variety of contexts.  

[ISA Abstract Model](http://isa-specs.readthedocs.io/en/latest/isamodel.html) - This ISA specification defines an Abstract Model of the metadata framework. The ISA Abstract Model has been implemented in two format specifications, ISA-Tab and ISA-JSON, both of which have supporting tools and services associated with them. The format specifications are also available for additional tooling to take advantage of ISA-formatted content.  

[NCI Metathesaurus](https://ncim.nci.nih.gov/ncimbrowser/) -(NCIm) is a wide-ranging biomedical terminology database that covers most terminologies used by NCI for clinical care, translational and basic research, and public information and administrative activities.   

[NCI Thesaurus](https://ncit.nci.nih.gov/ncitbrowser/) - (NCIt) provides reference terminology for many NCI and other systems. It covers vocabulary for clinical care, translational and basic research, and public information and administrative activities.   




## Tools
(Sort alphabetically.)    
\[Resource](URL) - description.    

[ISA-tools](https://isa-tools.github.io/software-suite.html) - A set of tools for ISA-Tab and model.

Gen3 -  
[GitHub](https://github.com/uc-cdis)  
[Website](https://cdis.uchicago.edu/gen3/)  

SHEEPDOG   
The Sheepdog service is responsible for herding user submissions of metadata into the graph database. The submissions are quality controlled against the data dictionary to ensure all required fields are present and have appropriate data values. The Sheepdog service is also responsible for supporting bulk export of the metadata into TSV or JSON formats. 

PEREGRINE  
Peregrine is the high speed metadata seeking service which responds to GraphQL search queries. The GraphQL service allows Commons operators and users to precisely query only the information they are most interested in from the metadata collections. The service translates the GraphQL search into the appropriate statements which are run against the PostgreSQL backend before being returned as friendly JSON. 

FENCE  
The Fence service controls access to the metadata, submission, indexing, and data itself. Fence is an authentication (AuthN) and authorization (AuthZ) service which utilizes OpenID Connect flow (an extension of OAuth2) to generate tokens for clients. It can also provide tokens directly to a user. Clients and users may then use those tokens (JWT) with other Gen3 Data Commons services to access protected endpoints that require specific permissions. Fence can be configured to support different Identity Providers (IDPs) for AuthN. At the moment, supported IDPs include Google, and Shibboleth supporting providers such as NIH iTrust.  

INDEXD  
The Indexd service provides permanent digital IDs for data objects. These IDs can be used to retrieve the data, or query the metadata associated with the object. The Indexd service tracks the locations and hash of every asset (file) in the data commons object store. It exports RESTful APIs for registering a new asset, and retrieving data for an existing asset. 

WINDMILL  
The Windmill service is an interactive website that allows users to explore, submit, and download data. The Windmill service utilizes the APIs offered by the data commons just as any other externally built app could.  

[MetaROOT](https://github.com/NCBI-Hackathons/MetaROOT) - Using MetaMapLite to standardize metadata terminology and make sequencing metadata machine readable.  


## Metadata/Data Standard Hackathons and Tool Development
(Sort by date, latest on top.)  
\[Event](URL) - City, State/Country - Date - Description.  

[IEEE Hackathon on Big Data Governance and Metadata and Management](https://bigdatawg.nist.gov/bdgmm_compsac2018.html) -  Tokyo, Japan - July 23, 2018 - develop interoperable data infrastructure for Big Data Governance and Metadata Management that is scalable and can enable the Findability, Accessibility, Interoperability, and Reusability between heterogeneous datasets from various domains without worrying about data source and structure. Keywords: cancer, genomics, precision medicine.

[Bio-IT World FAIR Data Hackathon](http://www.bio-itworldexpo.com/fair-data-hackathon/) - Boston, MA - May 14 - 15, 2018 - 
The second annual Bio-IT FAIR Data Hackathon will unite life science and IT teams to tackle actual genomic datasets with maximum impact potential. The hackathon will have an initial focus on evaluating the FAIRness of a range of different data sets. The second stage will involve teams, each working with a different data set, developing approaches to improve the FAIRness of that dataset through the use of unique identifiers, linking to additional data sets, collection of appropriate metadata, and other techniques that can be applied.  [Products](https://github.com/BioITHackathons/single_cell_portal_core)

[NIH Data Science Collaborative Hackathon](https://ncbi-hackathons.github.io/) - Bethesda, Maryland - April 16 – 18, 2018 - The hackathon will focus on tools for advanced analysis of biomedical datasets including text, images, next generation sequencing data, proteomics, and metadata. [Product - MetaROOT](https://github.com/NCBI-Hackathons/MetaROOT)   

[IEEE metadata hackathon and workshop](https://www.clarin.eu/event/2018/cancelled-ieee-metadata-hackathon-and-workshop-berlin) - Berlin, Germany - March 19, 2018 - CANCELLED This two-day event will consist of two parallel 24-hour hackathon tracks and a plenary workshop session on big data governance and metadata management. CLARIN organises one hackathon track, which revolves around the analysis, curation, processing, presentation and management of metadata for resources relevant to the social sciences and humanities.  [Product](https://github.com/clarin-eric/ieee-metadata-hackathon).  

## Publications
[Detailed Clinical Models: A Review](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3092133/)



## Other resources
[BioPortal](http://bioportal.bioontology.org/) - The goal of the National Center for Biomedical Ontology is to support biomedical researchers in their knowledge-intensive work, by providing online tools and a Web portal enabling them to access, review, and integrate disparate ontological resources in all aspects of biomedical investigation and clinical practice. A major focus of our work involves the use of biomedical ontologies to aid in the management and analysis of data derived from complex experiments.  

[Equator Netowrk](http://www.equator-network.org/) - The EQUATOR (Enhancing the QUAlity and Transparency Of health Research) Network is an international initiative that seeks to improve the reliability and value of published health research literature by promoting transparent and accurate reporting and wider use of robust reporting guidelines.  It is the first coordinated attempt to tackle the problems of inadequate reporting systematically and on a global scale; it advances the work done by individual groups over the last 15 years.  

[FairSharing.org](https://fairsharing.org/standards/) - The standards in FAIRsharing are manually curated from a variety of sources, including BioPortal, MIBBI and the Equator Network.  

[RDA Metadata Directory](http://rd-alliance.github.io/metadata-directory/) - The RDA Metadata Standards Directory Working Group is supported by individuals and organizations involved in the development, implementation, and use of metadata for scientific data. The overriding goal is to develop a collaborative, open directory of metadata standards applicable to scientific data can help address infrastructure challenges.  

