---
# See project.yml for variables.
---
# About
_Building community around and gathering knowledge about the world’s stick and leaf insects_

## Overview
The _{{ app:project_name }}_ file offers a community-curated collection of richly-cited and annotated information on the taxonomy of Earth’s {{app:focal_taxon_common_name}}. Data found here come from a collaboratively compiled database originating in an instance of [TaxonWorks](https://taxonworks.org) managed by the [Species File Group](https://speciesfilegroup.org). See [Contribute](#contribute-or-get-help) for how you can participate. This site is built using TaxonPages, [learn more and get help](https://github.com/SpeciesFileGroup/taxonpages). For more on how this site is built please see the [Software](#software) section.

## Gaps as opportunity
The Earth's biodiversity is vast, the data captured to describe it are minimal in comparison, but still immense. All projects of this nature contain gaps, i.e. opportunities for collaboration on future work, grants, and research. Known gaps in this project include photographs of certain type material, particularly required for the Chinese fauna and more. [Contact us](#contribute-or-get-help) if you would like to help us address these, in particular we'd like to prioritize high quality photographs of type material not on Phasmida Species File.

## History
_Our old website is now a read-only resource available at [https://{{app:focal_taxon}}.archive.speciesfile.org](https://{{app:focal_taxon}}.archive.speciesfile.org)._

The original Phasmida species file data was transferred from a PDF catalog in 2005, and was the second taxonomic group after Orthoptera.  The database was built to be _a growing and evolving thing_ that continues past the careers of those who have responsibility for it from time to time. This database was inputted by David Eades and his team, from Daniel Otte and Paul Brock's 2003 CD entitled Phasmida Species File: A Catalog of the Stick and Leaf Insects of the World and by reference to changes made in the 2005 book of the same title by Otte & Brock.  It has been subsequently updated by Paul, who will continue to maintain it. Someday Paul Brock will relinquish the responsibility, and it will be up to a committee of the Orthopterists' Society to select a successor/s. In addition to the matter of continuity, it seems clear that the migration of the taxonomic data management to TaxonWorks will provide the opportunity for an eventual handoff.

Members of the Orthopterists' Society are invited to participate in making this website and database better. Participation can be at various levels:

As of August 2023 all data in the former Species File Websites were frozen and shortly thereafter migrated to TaxonWorks. As with all migrations of this nature the process is both lossy (e.g. some data could not be mapped with certainty) and improved (e.g. semantics of the new models have more precision and clarity). The old website remains an excellent resource for fact-checking this migration. If you spot something that needs attention, please see [Contribute or get help](#contribute-or-get-help).

### Support and funding
_This Species File functionality and content is serviced in part by the Species File Group._  
Through the generous support of various phasmid specialists, we add images and improve data.
## Contributors
|name|role|affiliation|
|----|----|-----------|
| Paul D. Brock | Author and Editor | The Natural History Museum, London | 
| Thies H. Büscher | Assistant Editor | Christian-Albrechts-Universität, Kiel, Germany |
| Ed Baker | Assistant Editor | The Natural History Museum, London, University of York |
| David C. Eades\* | Founder of Species File Group | Illinois Natural History Survey |
| Daniel Otte\* | Major contributor | Academy of Natural Sciences of Philadelphia |

### Expertise by Geographic Region  

| Continent | Country/ies | Person |  
|:----------|:----------|:----------|  
| Africa | Comores, Madagascar, Mauritius, Réunion, Rodrigues | Nicolas Cliquennois nicolascliquennois@yahoo.fr |  
| Africa | Southern | Paul D. Brock pauldbrock@btinternet.com |  
| America | northern | Frank Hennemann fhhennemann@hotmail.de & Oskar Conle o_conle@hotmail.com |  
| America | southern | Frank Hennemann fhhennemann@hotmail.de & Oskar Conle o_conle@hotmail.com |  
| Asia, temperate | temperate | TBA |  
|  | China | Ho Wai Chun georgehwc@hotmail.com |  
|  | Hong Kong |  Ho Wai Chun georgehwc@hotmail.com |  
|  | Taiwan | Yamai Shi-Fu Huang yamai63@yahoo.com.tw |  
| Asia, tropical | |  
| | Borneo & Sumatra | Francis Seow-Choen seowchoen@gmail.com |  
| | India | Tushar Mukherjee mukherjee.tushar@gmail.com |  
| | Indochinese region (Vietnam, Cambodia & Laos) | Joachim Bresseel |  
| | Peninsular Malaysia & Singapore | Paul D. Brock pauldbrock@btinternet.com |  
| | Philippines | Orlando Eusebio orleusebio@yahoo.com |  
| | Sri Lanka | Frank Hennemann fhhennemann@hotmail.de |  
| | Sulawesi  | Frank Hennemann fhhennemann@hotmail.de |  
| | Thailand & Myanmar | Thies Büscher thies.b@web.de |  
| Australasia ||  Paul D. Brock pauldbrock@btinternet.com |  
| Europe || Paul D. Brock pauldbrock@btinternet.com |  
| Pacific ||  TBA |  
| World Phylliidae || Royce Cumming phylliidae.walkingleaf@gmail.com |

_A \* denotes a past contributor, now inactive._

## Contribute or get help
_Projects of this nature require expertise in many different areas, not only on the taxa being treated. If you can imagine a way to contribute we'd love to hear about it._

- **<a href="mailto:{{app:contact_email}}">Email</a>** is the primary way to contact us, including enquiries about **joining** the researchers building this Species File. { ... or join a regular support meeting. } { See also [Governance](#governance). }
- **Provide new data or identify a problem with existing data** by contacting us (see above). { Alternate data manager email}, {Issue tracker option}.
- **Cite** this website via the citation at the bottom of the page. See also [Terms of use](#terms-of-use).
- **Something is broken** (i.e. with TaxonPages the software)? See [Software](#software), or use the [TaxonPages Issue Tracker](https://github.com/SpeciesFileGroup/taxonpages/issues).

### Extended data access
_A goal of these pages is to ensure that the underlying data behind them are accessible in their digital format. By diversifying the ways the data are accessible (e.g. on the web page, in JSON, in Darwin Core standard), we increase the opportunities to both spot errors and provide new services and portals._

- Researchers working on this project use their rich, multi-faceted access to the data via TaxonWorks' interfaces (e.g. filters, reporting, downloads). Access requires a project account, see [Contribute or get help](#contribute-or-get-help).
- Data behind individual panels per page can be seen via the _Sitemap_ functionality.
- Each page offers an option to download a _DarwinCore formatted table_ containing all data for this taxon and its children.
- Panel data (each section on a page) and other information not available on these pages are accessible via a [TaxonWorks API](https://api.taxonworks.org) at [https://sfg.taxonworks.org/api/v1](https://sfg.taxonworks.org/api/v1).
- Core taxonomic data are exported to and available at the [Catalogue of Life]({https://link_to_root_taxon_page}) and its [associated API]({https://link_to_api_for_pertinent_dataset}).

### Software
These pages are built with completely open-source software. [Read more](http://speciesfilegroup.org/docs/taxonworks_in_production_at_sfg.html) about what drives them, how they supported by the Species File Group and their many collaborators, or [join weekly support meetings](https://speciesfilegroup.org/events.html) and see how it all fits together, includes links to issue trackers.

### Governance
About our group structure, how the rules behind joining and participating are set.

## Related resources

### References
- [Abbreviations for Insect and Spider Collections of the World](https://hbs.bishopmuseum.org/codens/)
- [International Commission on Zoological Nomenclature (ICZN)](https://www.iczn.org/)
- [The Orthopterists' Society](https://www.orthsoc.org)

### Museums
- [Muséum national d’Histoire naturelle de Paris type images ](https://sciencepress.mnhn.fr/sites/default/files/documents/en/liste_phasmes_mnhn.pdf)
- [Natural History Museum, London ](https://www.nhm.ac.uk/our-science/collections/entomology-collections.html)
- [Naturhistorisches Museum Wien](https://www.nhm-wien.ac.at/en/research/2_zoology_insects/collections/neuropteroidea_and_appended_collections)
- [Oxford University Museum](https://www.oumnh.ox.ac.uk/insects#/)
- [Phasmatodea.com Museum collections](http://www.phasmatodea.com/museum-collections)

### Other
- [Order: Phasmida](stick and leaf insects) (http://www.biodiversityexplorer.info/insects/phasmida/index.htm)
- [Species 2000](http://www.sp2000.org/)
- [Stick and Leaf Insects — Order Phasmatodea](Australian stick insects) (http://brisbaneinsects.com/brisbane_hoppers/StickInsect.htm)
- [The Phasmid Study Group](http://phasmidstudygroup.org/)
- [The Stick Insects (Phasmida) of South Africa] (http://www.ru.ac.za/media/rhodesuniversity/resources/martin/phasmida.html)
- [The world of stick insects](http://www.phasmatodea.com/)
- [Tree of life, Phasmida](http://tolweb.org/tree?group=Euphasmida&contgroup=Phasmida)
-	[A la decouverte des Phasmes & Phyllies](http://dilawata.free.fr/site/index.html)
-	[Association for the Systematic of Stick insects and the Study of their Distribution (ASPER)](http://www.asper.org/menu/en_asper.html)

## Terms of use (Copyright guidance)

<div class="flex items-center gap-2">
  <a
    class="min-w-fit"
    href="{{ app:copyright_image_link }}"
  >
    <img 
      src="{{ app:copyright_image }}" 
      alt="copyright" 
      class="m-0"
    >
  </a>
  <span>{{ app:copyright_text }}</span>
</div>

