# Norms for Data Use and Publication

The text below describes the [Canadensys](http://www.canadensys.net) norms for data publication and use. This is NOT a legal document or contract. This IS a well-considered code of conduct that anyone who publishes data to or uses data downloaded from Canadensys are expected to uphold. When you adopt these norms, you will both model a much needed set of ethical behaviours and help us to build a vibrant community intended to support efforts to make biodiversity data as complete, discoverable, and accessible as possible.

## What We Believe

* Biodiversity data should be as complete, discoverable, and accessible as possible.
* Biodiversity data should be standardized so they can be aggregated, shared, and used as easily as possible.
* Factual data cannot be protected by copyright and should be committed to the Public Domain.
* Any licenses used to protect compilations or datasets (when applicable) should be licensed using standardized, machine-readable licenses, such as licenses from the Creative Commons. The ideal is for all datasets to be published under the designation of the [Creative Commons Zero (CC0)](https://creativecommons.org/publicdomain/zero/1.0/) waiver to affirm clearly that the data are in the public domain.
* Data publishers have the right to protect any creative content, including, but not limited to images, sound files, videos, and descriptive/speculative text, where applicable.
* The licensing and waiver process should be as simple as possible for data publishers and for users (results may vary from collection to collection).
* All data publishers should get the credit they deserve when the data they curate are used by others.
* It is worth the time and effort to achieve these goals to the greatest extent possible.

## Give Credit Where Credit is Due

As is common practice in scientific research, cite the data you are using. Canadensys data publishers have invested a lot of time and effort into collecting, digitizing, maintaining, and publishing the biodiversity information you are using. They deserve credit for their work. We have provided recommended formats at the end of this document.

## Be Responsible

Use the data responsibly. The data are published to Canadensys and other biodiversity portals to allow you and everyone else to better study and understand the world in which we live. It is your responsibility to use these data for the benefit of our collective health, knowledge, and self-improvement. Avoid using these data in any way that is unlawful, harmful or misleading. Please understand that these data are subject to change, errors and bias. When giving credit where credit is due, protect the reputation of the data publisher and indicate clearly any changes you may have made to the data.

## Share Knowledge

Let Canadensys data publishers and the broader community know if — and how — you have used data from the network. Sharing helps:
* Canadensys to understand value of this project to you and the community and to create better tools and services for your use.
* Data publishers to showcase their efforts and encourages them to continue to improve data quality and maintenance of collections.
* You and your work reach a wider audience through an expanded presence.
* Everyone - data publishers, biodiversity informatics projects, and researchers - to raise the money needed to keep the data, products, services, and research alive.

You can [contact us](http://www.canadensys.net/contact) or share your work via [our public forum](http://www.canadensys.net/forum).

Communicate with the data publisher(s) directly. Let them know if you have comments or questions, notice errors, or want more information about the data they publish. Their contact details are included in the dataset metadata and on [our repository](http://data.canadensys.net/ipt).

### Respect the Data License or Waiver

Understand and respect the data licence or waiver under which the data are published. Whenever possible, Canadensys places selected licenses and waivers in the *[rights](http://rs.tdwg.org/dwc/terms/index.htm#dcterms:rights)* field of every record and in the dataset metadata. To help you [make greater use of the data](http://www.canadensys.net/2012/why-we-should-publish-our-data-under-cc0), most of our data publishers have dedicated their data to the public domain using the [Creative Commons Zero waiver (CC0)](http://creativecommons.org/publicdomain/zero/1.0/). Do not remove the public domain mark or provide misleading information about the copyright status.

## Data Publication Conditions

In order to [publish your data](http://www.canadensys.net/publication) through the Canadensys network, you should meet the following criteria:

* You are associated with a Canadian collection or organization.
* You are publishing a specimen or observation dataset, a taxonomic checklist, or metadata about one of these (i.e., one of the 3 types of datasets supported by the [IPT](http://www.canadensys.net/ipt)).
* You hold the rights to publish the data.
* You are willing to maintain the dataset and improve its quality where possible.
* You are willing to provide sufficient metadata, so users can learn what the dataset is about.
* You are publishing the data under an open license, so others can really use them. We strongly recommend dedicating to the public domain using the [Creative Commons Zero waiver (CC0)](http://creativecommons.org/publicdomain/zero/1.0/) and [here is why](http://www.canadensys.net/2012/why-we-should-publish-our-data-under-cc0).

## <a id="citations"></a>Preferred citations

These are the preferred formats for citing data published through the Canadensys network. If other citation practices apply, feel free to use them. We do request however to always include a link.

### Aggregated data

#### Example

	Acadia University, Université de Montréal Biodiversity Centre, 
	University of Toronto Mississauga, University of British Columbia. 
	http://data.canadensys.net/explorer 
	(accessed on 2012-03-21)

#### Format

	[list of data publishers]. 
	http://data.canadensys.net/explorer 
	(accessed on [date])

### Single dataset

#### Example with DOI

	Green Plant Herbarium (TRT) 
	from Royal Ontario Museum. 
	http://dx.doi.org/10.5886/g7j6gct1 
	(accessed on 2012-03-21)

#### Format

	[dataset name] 
	from [data publisher]. 
	http://dx.doi.org/[DOI of dataset] 
	(accessed on [date])

#### Example without DOI

	University of British Columbia Herbarium (UBC) - Vascular Plant Collection 
	from University of British Columbia. 
	http://dataset.canadensys.net/ubc-vascular-specimens 
	(accessed on 2012-03-21)

#### Format

	[dataset name] 
	from [data publisher]. 
	[link to dataset] 
	(accessed on [date])

### Single specimen/observation record

#### Example

	MT00012345, 
	Marie-Victorin Herbarium (MT) 
	from Université de Montréal Biodiversity Centre. 
	http://dataset.canadensys.net/mt-specimens 
	(accessed on 2012-03-21)

#### Format

	[record id], 
	[dataset name] 
	from [data publisher]. 
	[link to dataset] 
	(accessed on [date])

### Where can I find the elements to create a citation?

All the elements can be found in the [Darwin Core](http://www.canadensys.net/darwin-core) fields for each record you download:

* [data publisher]: in [institutionCode](http://rs.tdwg.org/dwc/terms/index.htm#institutionCode) (and [rightsHolder](http://rs.tdwg.org/dwc/terms/index.htm#rightsHolder)). This is also the institution that has registered the dataset with [GBIF](http://www.gbif.org).

* [dataset name]: in [datasetName](http://rs.tdwg.org/dwc/terms/index.htm#datasetName). This is also the title of the dataset in its metadata and on its repository page.

* [link to dataset]: in [datasetID](http://rs.tdwg.org/dwc/terms/index.htm#datasetID). This link redirects to the human readable repository page of the dataset.

* [record id]: in [catalogNumber](http://rs.tdwg.org/dwc/terms/index.htm#catalogNumber). If no catalogNumber is available, use [occurrenceID](http://rs.tdwg.org/dwc/terms/index.htm#occurrenceID).

*These norms may be subject to minor revisions without notice; major revisions will be announced. The norms are based on those of the [Europeana Foundation](http://www.europeana.eu/portal/pd-usage-guide.html) and [Open Data Commons](http://opendatacommons.org/norms/odc-by-sa/).*
