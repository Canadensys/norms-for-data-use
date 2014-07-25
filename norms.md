# Norms for data use and publication

The text below describes the [VertNet](http://www.vertnet.org) norms for data publication and use. These norms are not a legal document, but by adopting them, you help to build a vibrant community around the data and support future efforts to unlock biodiversity data.

## Give credit where credit is due

As is common practice in scientific research, cite the data you are using. Our participants have invested a lot of time and effort into collecting, digitizing, maintaining, and publishing the biodiversity information you are using, and they deserve credit for their work. [You can find the preferred formats for citation at the end of this document](#citations).

## Be responsible

Use the data responsibly. The data are published to allow anyone to better study and understand the world around us, so please do not use the data in any way that is unlawful, harmful or misleading. Understand that the data are subject to change, errors and sampling bias. Protect the reputation of the data publisher and clearly indicate any changes you may have made to the data.

## Share knowledge

Let us know if you have used the data. It helps our participants to showcase their efforts and it helps you reach a wider audience. You can [contact us](http://www.canadensys.net/contact) or share your work via [our public forum](http://www.canadensys.net/forum).

Inform the data publisher(s) if you have comments about the data, notice errors, or want more information. Their contact details are included in the dataset metadata and on [our repository](http://data.canadensys.net/ipt).

## Respect the data license

Understand and respect the data licence or waiver under which the data are published. It is indicated in the *[rights](http://rs.tdwg.org/dwc/terms/index.htm#dcterms:rights)* field of every record and in the dataset metadata. To help you [make greater use of the data](http://www.canadensys.net/2012/why-we-should-publish-our-data-under-cc0), most of our participants have dedicated their data to the [public domain (CC0)](http://creativecommons.org/publicdomain/zero/1.0/). Do not remove the public domain mark or provide misleading information about the copyright status.

## Data publication conditions

We care about data and we just want to make sure you do too. In order to [publish your data](http://www.vertnet.org/join/join.html) through VertNet, you should meet the following criteria:

* You are associated with a Canadian collection or organization.
* You are publishing a specimen or observation dataset.
* You hold the rights to publish the data.
* You are willing to maintain the dataset and improve its quality where possible.
* You are willing to provide sufficient metadata, so users can learn what the dataset is about.
* You are publishing the data under an open license, so others can really use them. We strongly recommend publishing under [CC0](http://creativecommons.org/publicdomain/zero/1.0/) ([here is why](http://www.canadensys.net/2012/why-we-should-publish-our-data-under-cc0)).

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
