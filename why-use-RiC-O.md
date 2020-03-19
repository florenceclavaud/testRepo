# Title

* [Home](index.html)
* [About RiC-O](about.html)
* **Why use RiC-O?**
* [Next steps](next-steps.html)
* [Diagrams](diagrams.html)
* [Examples](examples.html)
* [Events and presentations](events.html)
* [Projects and tools](projects-and-tools.html)

If you work as an archivist, or with archivists, **if you are interested in next generation archival description standards, and particularly in the way they can be expressed for producing high quality, useful,  interoperable Linked Data, you should certainly have a look at RiC-O, and probably do more**.

To be more accurate, **the following is a list of 'reasons why' you should consider understanding, testing, and using RiC-O**, and even, if you wish so, contributing to it.

* RiC-O is a domain or reference ontology. It provides a generic vocabulary and formal rules for creating RDF datasets (or generating them from existing archival metadata) that describe in a consistent way any kind of archival record resource.
    * **While some projects have built some specific ontologies for describing archives, no other generic, domain, ontology than RiC-O exists that addresses this need**.
    * RiC-O is **a complete representation of the new international archival description standard, Records in Contexts-Conceptual Model**. It is being developed by the same expert group, EGAD()link). EGAD is a group of about twenty persons, who work, either as archivists in archival institutions and libraries, or as teachers in archival science, or as ingeneers, each of these persons having expertise, both theoretical and practical, in archival description and current technologies. EGAD works on behalf of ICA, and has an official mandate from this organisation.
* By modeling archival description, **RiC-O (and RiC-CM) are not reinventing the wheel**.
    * The conceptual models of libraries (FRBR), museums (CIDOC-CRM) and archives (ISAD/ISAAR/ISDF and now RiC-CM) are vastly different. The semantic concepts for very basic things like "title" or "authorship"/"provenance" greatly differ between these communities. Therefore it would be dangerous to repurpose classes or properties of existing domain-ontologies to implement the conceptual model of the archival domain. 
    * Archival description and contextualization works through hierarchies. None of the existing ontologies (at least to my knowledge) can model this speciality with the necessary care. PROV and DC are not capable of doing so, RDA only in a limited and workaroundish way. 
    * RiC-CM and RiC-O clearly define their perimeter and only model what is necessary for the archival community -- and that's the archival description. They don't model eg. technical metadata since PREMIS functions already very well for this purpose. They only model the part of the world where there is no ontology, thus filling white parts on the map.
* As a domain ontology, RiC-O does not borrow any component from other existing ontologies. **It should therefore be easier, for an archival institution or archival project, to understand, implement and maintain RiC-O within its system**.
    * In particular, for the maintenance of the ontology the archival community should't be dependent upon the goodwill of other communities and groups who maintain ontologies that we later reuse. We as a community must be able to act and innovate in our own speed. Again, this concerns only the island of archival description, in all other domains like controlled vocabularies, technical metadata etc. archival institutions and projects of course collaborate with other domains.
    * RiC-O will rather, later on and as far as it can be done, be aligned with these models. This is of course essential for interconnecting RDF datasets conforming to RiC-O with other datasets, or for using parts of RiC-O in other contexts than an archival or record management context.
* **RiC-O sources are now available on GitHub (link), so that the development process is open**. Everybody can clone the repository, create issues, or even fork and submit pull requests.
* RiC-O is **fully documented** in English. The internal documentation includes the [design principles](https://www.ica.org/standards/RiC/ontology.html#design-principles) and [an overview] (https://www.ica.org/standards/RiC/ontology.html#understanding-RiCO). RiC-O also comes with [examples](examples.html) and [diagrams](diagrams.html). You can also access online some [recent presentations](events.html). In short, **you can already find a significant amount of material that should help you start a project**. EGAD will release more and more of these, and will of course improve the documentation. EGAD will also organize events and workshops. 
* **RiC-O is already used by several institutions or projects**, some tools already exist (see [this page](projects-and-tools.html). So, **if you start a project, you will not be alone**. Do not hesitate to contact us! use either ([egad at ica.org mailbox](mailto:egad@ica.org), or RiC-O users discussion list (if you want to subscribe to this list, simply email to Florence Clavaud (florence.clavaud@culture.gouv.fr).
