# Data Product Canvas - Berlin LOR daycare centers

## Input Ports

**Input ports define the format and protocol in which data can be read (database, file, API, visualizations)**

This data product uses point-of-interest data from Open Street Maps (OSM) distributed
under [Open Data Commons Open Database License ](https://opendatacommons.org/licenses/odbl/) (ODbL) by
the [OpenStreetMap Foundation](https://osmfoundation.org/) (OSMF).

## Data Product Design

**Describe everything you need to design a data product on a conceptual level.**
**Ingestion, storage, transport, wrangling, cleaning, transformations, enrichment, augmentation, analytics, SQL
statements, or used data platform services.**

* [loads data from Open Street Maps via Overpass API](../lib/extract/overpass_data_extractor.py)
* [converts json data into csv](../lib/transform/data_csv_converter.py)

## Output Ports

**Output ports define the format and protocol in which data can be exposed (db, file, API, visualizations)**

The data of this data product is available under the following URLs

* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-art-galleries-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-art-galleries-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-bars-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-bars-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-beer-gardens-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-beer-gardens-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-bicycle-rentals-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-bicycle-rentals-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-bus-stops-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-bus-stops-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-cafes-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-cafes-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-car-sharing-stations-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-car-sharing-stations-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-childcare-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-childcare-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-cinemas-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-cinemas-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-clinics-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-clinics-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-community-centers-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-community-centers-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-convenience-stores-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-convenience-stores-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-coworking-spaces-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-coworking-spaces-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-doctors-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-doctors-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-fast-food-restaurants-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-fast-food-restaurants-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-fire-stations-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-fire-stations-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-fitness-centers-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-fitness-centers-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-food-courts-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-food-courts-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-grocery-stores-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-grocery-stores-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-hospitals-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-hospitals-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-ice-cream-parlours-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-ice-cream-parlours-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-kindergartens-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-kindergartens-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-libraries-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-libraries-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-marketplaces-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-marketplaces-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-museums-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-museums-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-nightclubs-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-nightclubs-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-offices-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-offices-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-parks-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-parks-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-pharmacies-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-pharmacies-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-places-of-worship-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-places-of-worship-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-playgrounds-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-playgrounds-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-police-stations-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-police-stations-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-post-offices-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-post-offices-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-pubs-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-pubs-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-restaurants-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-restaurants-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-sbahn-stops-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-sbahn-stops-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-schools-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-schools-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-sport-centers-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-sport-centers-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-supermarkets-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-supermarkets-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-theaters-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-theaters-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-tram-stops-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-tram-stops-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-ubahn-stops-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-ubahn-stops-2024-04-details.csv) 
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-universities-2024-04-details.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-universities-2024-04-details.csv) 

Additionally, non-countable places-of-interest can be found in

* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-forests-2024-04-details.json](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-forests-2024-04-details.json)
* [berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-parks-2024-04-details.json](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/main/data/berlin-lor-points-of-interest-2024-04/berlin-lor-points-of-interest-parks-2024-04-details.json)

Earlier versions of the data can be found in

* [berlin-lor-points-of-interest-2024-01](https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/tree/main/data/berlin-lor-points-of-interest-2024-01)
* [berlin-lor-points-of-interest-2024-02](https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/tree/main/data/berlin-lor-points-of-interest-2024-02)
* [berlin-lor-points-of-interest-2024-03](https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-points-of-interest-source-aligned/tree/main/data/berlin-lor-points-of-interest-2024-03)

## Metadata

### Ownership

**Domain, data product owner, organizational unit, license, version and expiration date**

* ownership: Open Lifeworlds
* domain: places
* license: CC-BY-4.0

### Schema

**Attributes, data types, constraints, and relationships to other elements**

### Semantics

**Description, logical model**

### Security

**Security rules applied to the data product usage e.g. public org, internal, personally identifiable information (PII)
attributes**

## Observability

### Quality metrics

**Requirements and metrics such as accuracy, completeness, integrity, or compliance to Data Governance policies**

### Operational metrics

**Interval of change, freshness, usage statistics, availability, number of users, data versioning, etc.**

### SLOs

**Thresholds for service level objectives to up alerting**

## Consumer

**Who is the consumer of the Data Product?**

## Use Case

**We believe that ...**
**We help achieving ...**
**We know, we are getting there based on ..., ..., ...**

We believe that this data product can be used to derive any kind of data based product.

## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

This data product is source-aligned since the contained csv files represent the source data.

## Ubiquitous Language

**Context-specific domain terminology (relevant for Data Product), Data Product polysemes which are used to create the
current Data Product**

---
This data product canvas uses the template
of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).
